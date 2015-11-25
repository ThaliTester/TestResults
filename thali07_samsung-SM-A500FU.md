#### Test 503880196dc97cd_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/TelephonyPermission( 2367): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2367): isDefault true
D/Mms/MmsApp( 2367): onCreate() com.android.mms
D/Mms/MmsApp( 2367): [start]    initCountryIso consume time = 358.133541
D/Mms/MmsApp( 2367): [end]    initCountryIso consume time = 15.381355
D/Mms/MmsConfig( 2367): [start]    MmsConfig.init() consume time = 0.072395
--------- beginning of system
D/CountryDetector( 1017): The first listener is added
D/Mms/MmsConfig( 2367): before partial update
D/Mms/MmsConfig( 2367): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2367): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2367): isAuth is false
D/Mms/MmsConfig( 2367): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/TP/MmsSmsProvider( 1455): query,matched:2117, calling pid = 2367
D/TP/MmsSmsProvider( 1455): match 2117:Elapsed time : 2.290 ms
D/EasySignUpManager_1.0.1( 2367): isAuth is false
D/EasySignUpManager_1.0.1( 2367): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2367): mps_code.dat does not exist
E/CscParser( 2367): customer_path =/system/csc/customer.xml
E/CscParser( 2367): fileName + /system/csc/customer.xml
E/CscParser( 2367): mps_code.dat does not exist
E/CscParser( 2367): customer_path =/system/csc/customer.xml
E/CscParser( 2367): fileName + /system/csc/customer.xml
D/CscParser( 2367): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2367):  enable multiwindow = true
E/Mms/MessageUtils( 2367): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2367): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2367): [end]    init() consume time = 78.815469
D/Mms/Contact( 2367): [start]    init() consume time = 1.906511
D/Mms/Contact( 2367): [end]    init consume time = 9.904583
D/TP/MmsSmsProvider( 1455): query,matched:13, calling pid = 2367
D/TP/MmsSmsProvider( 1455): match 13:Elapsed time : 1.667 ms
D/Mms/DraftCache( 2367): [start]    rebuildCache consume time = 6.858594
D/TP/MmsSmsProvider( 1455): query,matched:12, calling pid = 2367
D/TP/MmsSmsProvider( 1455): match 12:Elapsed time : 1.275 ms
D/Mms/DraftCache( 2367): [end]    rebuildCache consume time = 6.815989
D/Mms/MethodReflector( 2367): getSubId is called
D/Mms/TelephonyUtils( 2367): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2367): getTelephonyProperty is called
D/Mms/DownloadManager( 2367): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2367): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2367): auto download without roaming -> true
D/Mms/DownloadManager( 2367): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2367): getSubId is called
D/Mms/MethodReflector( 2367): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2367): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2367): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2367): getTelephonyProperty is called
D/Mms/DownloadManager( 2367): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2367): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2367): auto download without roaming -> true
D/Mms/DownloadManager( 2367): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2367): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2367): mAutoDownload ------> true
D/ComposerPerformance( 2367): 1448460663433 ms / [DONE] Composer constructor
D/Mms/Conversation( 2367): [start]    init() consume time = 25.598542
E/CII     ( 2367): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 2367): ReservationManager()
I/Mms/ReservationManager( 2367): resetAfterConnected()
D/TP/MmsSmsDatabaseHelper( 1455): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1455): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1455): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1455): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1455): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1455): query,matched:7, calling pid = 2367
D/TP/MmsSmsProvider( 1455): match 7:Elapsed time : 2.549 ms
D/TP/MmsSmsProvider( 1455): deleteConversation threadId: 9223372036854775807
I/Mms/ReservationManager( 2367): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1455): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
D/Mms/MmsApp( 2367): [end]    onCreate() consume time = 22.428802
D/Mms/SmsReceiver( 2367): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
V/TP/MmsSmsDatabaseHelper( 1455): updateThread(), thread_id = 9223372036854775807
D/Mms/ArtClassLoader( 2367): init [DONE] art
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/splitIntent( 1017): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/DownloadManager( 2367): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 2367): roaming ------> false, mSimSlot = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
V/TP/MmsSmsDatabaseHelper( 1455): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1455): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/Mms/Conversation( 2367): [end]    init consume time = 25.219635
D/Mms/MethodReflector( 2367): getSubId is called
D/Mms/TelephonyUtils( 2367): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2367): getTelephonyProperty is called
D/Mms/DownloadManager( 2367): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2367): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2367): auto download without roaming -> true
D/Mms/DownloadManager( 2367): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 2367): mAutoDownload ------> true
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/Mms/MessagingNotification( 2367): [start]    init() consume time = 6.148125
D/Mms/MessagingNotification( 2367): [end]    init consume time = 2.5525
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
D/Mms/SmsReceiverService( 2367): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
D/comsamsunglog( 1290): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1290): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1290): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1290): [MSC_Daemon]>>> ====================================================================================================================
D/TP/MmsSmsProvider( 1455): query,matched:0, calling pid = 2367
D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
V/TP/MmsSmsProvider( 1455): getSimpleConversations entered.
D/Mms/TelephonyPermission( 2367): isDefault true
D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
D/Mms/SmsReceiverService( 2367): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/TP/MmsSmsProvider( 1455): match 0:Elapsed time : 1.283 ms
D/Mms/SpamFilter( 2367): [start]    SpamFilter fill() begin consume time = 5.550365
D/Mms/SmsReceiverService( 2367): handleSIMStatus()
D/Mms/SmsReceiverService( 2367): handleSIMStatus(): SIM_STATUS = ABSENT
D/Mms/Synchronizer( 2367): [start]    doSync consume time = 3.408542
D/TP/MmsSmsProvider( 1455): update, matched:300, calling pid = 2367
V/TP/MmsSmsProvider( 1455): syncDBData start
D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/TP/MmsSmsProvider( 1455): query,matched:400, calling pid = 2367
V/TP/MmsSmsProvider( 1455): syncDBData sms end
V/TP/MmsSmsProvider( 1455): syncDBData mms end
D/Mms/SpamFilter( 2367): [end]    SpamFilter fill() finished consume time = 8.891614
V/TP/MmsSmsProvider( 1455): syncDBData end
D/Mms/Synchronizer( 2367): [end]    doSync consume time = 1.46
D/Mms/MessagingNotification( 2367): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1455): query,matched:26, calling pid = 2367
D/TP/SmsProvider( 1455): match 26:Elapsed time : 0.970 ms
D/TP/MmsSmsProvider( 1455): query,matched:6, calling pid = 2367
D/TP/MmsSmsProvider( 1455): match 6:Elapsed time : 2.114 ms
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2491): MountEmulatedStorage()
E/Zygote  ( 2491): v2
I/libpersona( 2491): KNOX_SDCARD checking this for 10020
I/libpersona( 2491): KNOX_SDCARD not a persona
I/SELinux ( 2491): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2491 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 2491): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2491): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
E/Zygote  ( 2502): MountEmulatedStorage()
E/Zygote  ( 2502): v2
I/libpersona( 2502): KNOX_SDCARD checking this for 10025
I/libpersona( 2502): KNOX_SDCARD not a persona
I/SELinux ( 2502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/SELinux ( 2502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2491): TimaSignature is unavailable
D/ActivityThread( 2491): Added TimaKeyStore provider
I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2502 uid=10025 gids={50025, 9997} abi=armeabi-v7a
D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/AlarmManagerService( 1017): Setting time of day to sec=1448460663
D/AlarmManagerService( 1017): Trying to open a file
D/AlarmManagerService( 1017): File Open Success
D/AlarmManagerService( 1017): File Close Success
I/AlarmManagerService( 1017): DRM_TIME_PATH CHMOD 666 for resetState done 
V/AlarmManager( 1017): waitForAlarm result :65536
W/AlarmManagerService( 1017): Unable to set rtc to 1448460663: Invalid argument
V/AlarmManager( 1017): No more alarm at this time.nowELAPSED=28006 batch.start=77856
D/OTPFW   ( 1017): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1448460663803
D/WifiStateMachine( 1017): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
D/TimaKeyStoreProvider( 2502): TimaSignature is unavailable
D/ActivityThread( 2502): Added TimaKeyStore provider
W/ResourcesManager( 2491): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2491): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2491): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
I/DowntimeConditions( 1017): android.intent.action.TIME_SET ignored because schedule turned off.
D/accuweather( 1618): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_SET
D/accuweather( 1618): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1618): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/accuweather( 1618): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1618): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/SecKeyguardClockView( 1174): HomeTimezone(): 1
D/accuweather( 1618): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1618): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
D/accuweather( 1618): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1618): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_SET
E/accuweather( 1618): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 11
D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/SettingsProvider( 1017): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
E/GpsLocationProvider( 1017): No APN found to select.
E/LocSvc_eng( 1017): E/void loc_eng_agps_ril_update_network_availability(loc_eng_data_s_type&, int, const char*): log_eng state error: instance not initialized
E/SMD     (  288): DCD OFF
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10054
W/ResourcesManager( 2502): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/KeyguardEffectViewUtil( 1174): isStrongPowerSavingMode() :false
E/USB_UICC(  297): Timeout! No signal received. Retry num = 22
D/KeyguardEffectViewController( 1174): isPreloadedWallpaper=true
I/GeometricMosaic_Keyguard( 1174): update
D/KeyguardEffectViewUtil( 1174): getCurrentWallpaper() mWallpaperPath :null
I/KeyguardEffectViewUtil( 1174): set current wallpaper info
D/SettingsProvider( 1017): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10054
D/SettingsProvider( 1017): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10054
D/SettingsProvider( 1017): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10054
V/VibratorService( 1017): hasVibrator - useVibetonz: true
D/TEST    ( 1174): run!!!
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
I/GeometricMosaic_Renderer( 1174): setBackgroundBitmap
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/EasySignUpManager_1.15.0305( 2491): serviceId : 0, features : -1
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/KeyguardEffectViewController( 1174): isPreloadedWallpaper=true
I/OMACP   ( 2502): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/Mms/Omacp( 2367): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/SecContentProvider2( 1017): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1017): mCursor = null
D/SecContentProvider2( 1017): isCopyContactToSimAllowed = true
I/splitIntent( 1017): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1017): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2527): MountEmulatedStorage()
E/Zygote  ( 2527): v2
I/libpersona( 2527): KNOX_SDCARD checking this for 10044
I/libpersona( 2527): KNOX_SDCARD not a persona
I/SELinux ( 2527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2527 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 2527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/libpersona( 2539): KNOX_SDCARD checking this for 10054
E/Zygote  ( 2539): MountEmulatedStorage()
I/libpersona( 2539): KNOX_SDCARD not a persona
E/Zygote  ( 2539): v2
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/SELinux ( 2539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/OMACP   ( 2502): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/TimaKeyStoreProvider( 2527): TimaSignature is unavailable
I/ActivityManager( 1017): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2539 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
D/ActivityThread( 2527): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
I/SELinux ( 2539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2539): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
E/Zygote  ( 2557): MountEmulatedStorage()
E/Zygote  ( 2557): v2
I/libpersona( 2557): KNOX_SDCARD checking this for 10142
I/libpersona( 2557): KNOX_SDCARD not a persona
I/SELinux ( 2557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 2539): TimaSignature is unavailable
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2557 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 2539): Added TimaKeyStore provider
I/SELinux ( 2557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2557): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2557): TimaSignature is unavailable
D/ActivityThread( 2557): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1486, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ResourcesManager( 2539): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
V/TaskCloserActivity( 2557): TaskCloserActivity enter()
V/TaskCloserActivity( 2557): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
W/art     ( 2491): Verification of void com.android.contacts.common.list.l.P() took 159.670ms
D/Recents_RecreateReceiver( 2539): onReceive by home
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2575 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/Zygote  ( 2575): MountEmulatedStorage()
E/Zygote  ( 2575): v2
I/libpersona( 2575): KNOX_SDCARD checking this for 10139
I/libpersona( 2575): KNOX_SDCARD not a persona
I/SELinux ( 2575): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2575): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2575): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2575): TimaSignature is unavailable
D/ActivityThread( 2575): Added TimaKeyStore provider
W/ResourcesManager( 2575): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2575): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2575): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2575): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2575): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/AndroidRuntime( 2573): 
D/AndroidRuntime( 2573): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2573): CheckJNI is OFF
D/AndroidRuntime( 2573): readGMSProperty: start
D/AndroidRuntime( 2573): readGMSProperty: already setted!!
D/AndroidRuntime( 2573): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2573): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2573): readGMSProperty: end
D/AndroidRuntime( 2573): addProductProperty: start
I/WifiNative-HAL( 1017): startHal
E/wifi    ( 1017): getStaticLongField sWifiHalHandle 0x9d25e8bc
I/WifiNative-HAL( 1017): Could not start hal
D/NearbySource( 2527): Nearby Source Create!
D/NearbyContext( 2527): Nearby Context Create!
D/AbsListView( 2491): Get MotionRecognitionManager
D/MotionRecognitionService( 1017):  ssp status : false
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2527): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 2527): Samsung link source created
E/AffinityControl( 2573): AffinityControl: registerfunction enter
D/AndroidRuntime( 2573): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1486): onPause
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
D/InputDispatcher( 1017): Focused application set to: xxxx
D/Launcher( 1486): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/InputDispatcher( 1017): Focus left window: 1486
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
D/AndroidRuntime( 2573): Shutting down VM
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2603): MountEmulatedStorage()
I/libpersona( 2603): KNOX_SDCARD checking this for 10174
E/Zygote  ( 2603): v2
I/libpersona( 2603): KNOX_SDCARD not a persona
I/SELinux ( 2603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2603): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2603 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 1486): updateVisibility : ActivityRecord{3db67d token=android.os.BinderProxy@bef2525 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 2603): TimaSignature is unavailable
D/ActivityThread( 2603): Added TimaKeyStore provider
D/ContactProvider( 2527): getAllContactInfoList Start
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1486): onStop
V/ActivityThread( 1486): updateVisibility : ActivityRecord{3db67d token=android.os.BinderProxy@bef2525 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/GalleryCacheReady( 2527): Receive : home resume
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
E/USB_UICC(  297): Timeout! No signal received. Retry num = 23
D/Launcher( 1486): onTrimMemory. Level: 20
D/Mms/UIEventReceiver( 2367): ui event
I/splitIntent( 1017): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 1227): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
D/ContactProvider( 2527): getAllContactInfoList End
I/syncContacts( 2527): thread: 253, sync time = 142
I/WebViewFactory( 2603): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 2603): Time to load native libraries: 1 ms (timestamps 9154-9155)
I/LibraryLoader( 2603): Expected native library version number "",actual native library version number ""
W/art     ( 2573): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
W/ResourcesManager( 1662): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1662): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
I/MultiDex( 1662): VM with version 2.1.0 has multidex support
I/MultiDex( 1662): install
I/MultiDex( 1662): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 1662): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromiumFactoryProvider( 2603): Binding Chromium to main looper Looper (main, tid 1) {249e74fe}
,I/LibraryLoader( 2603): Expected native library version number "",actual native library version number ""
,I/chromium( 2603): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2603): Initializing chromium process, singleProcess=true
,W/art     ( 2603): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2603): ApplicationContext is null in ApplicationStatus
,W/chromium( 2603): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/ActivityThread( 1662): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 1662): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10fab1a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1662): Installed default security provider GmsCore_OpenSSL
,E/libEGL  ( 2603): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 2603): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2603): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2603): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2603): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2603): Local Branch: 
I/Adreno-EGL( 2603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2603): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2603):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1732): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/BootupListener( 1455): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/PhoneUtilsCommon( 1455): isSupportVoLTE is false.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/StatusChecker( 2335): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2335): onReceive : net.mt.init : DONE
D/BluetoothAdapter( 2603): 407504369: getState() :  mService = null. Returning STATE_OFF
D/StatusChecker( 2335): Service state changed : 3 mSub-1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/art     ( 2603): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,D/GCM     ( 1662): COMPAT: Multi user not supported
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AwContents( 2603): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 2603): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2603): *FMB* installDecor flags : 8456448
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemWebViewEngine( 2603): CordovaWebView is running on device made by: samsung
,W/art     ( 2603): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2603): Attempt to remove local handle scope entry from IRT, ignoring
,E/SQLiteLog( 1662): (283) recovered 54 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
,I/Scheduler( 1662): Use PeriodicScheduler
,W/InstanceID/Rpc( 1662): Found 10012
,D/OpenGLRenderer( 2603): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 2603): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 2603): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2603): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1017): Focus entered window: 2603
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2603): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 2603): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2603): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 2603): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1174): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +766ms
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{2970446a u0 com.example.hello/.MainActivity t228} time:29737
,I/Timeline( 2603): Timeline: Activity_idle id: android.os.BinderProxy@3c0822ba time:29745
,I/SamsungIME( 1788): getCurrentCandidateView
,I/GCM     ( 1662): GCM config loaded
,D/AuthorizationBluetoothService( 1662): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1662): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/SamsungIME( 1788): Dismiss ExpandCandiate
,D/a       ( 1662): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1788): getDebugLevel  : 0x4f4c
,V/GmsCoreStatsServiceLauncher( 1905): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Mms/MmsApp( 2367):  start initViewCache mms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/Mms/ComposeMessageFragment( 2367): [start]    fillCache consume time = 1948.105051
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/ComposeMessageFragment( 2367): fillCache, easy = false
,I/SamsungIME( 1788): getDebugLevel  : 0x4f4c
,W/BindingManager( 2603): Cannot call determinedVisibility() - never saw a connection for the pid: 2603
,I/SamsungIME( 1788): KeybaordView init() : load resources
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,I/SamsungIME( 1788): getCurrentKeyboard
I/SamsungIME( 1788): getTextKeyboard
,I/chromium( 2603): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/SamsungIME( 1788): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 57315(3MB) AllocSpace objects, 5(194KB) LOS objects, 33% free, 25MB/38MB, paused 2.241ms total 161.175ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 2019): callingUid 10012, callindPid: 2019
,D/GCM     ( 1662): Connected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 24
,E/GmsWearableLS( 1732): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1732): [173] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 1662): Message class com.google.f.a.a.p
,D/JsMessageQueue( 2603): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/AndroidProtocolHandler( 2603): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/AbsListView( 2367): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 2367): [end]    fillCache consume time = 364.279739
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1455): query,matched:0, calling pid = 1905
,D/TP/SmsProvider( 1455): match 0:Elapsed time : 4.038 ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1455): Query uri=content://mms, match=0, calling pid = 1905
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 2291): wlan0: sending IPv6 Router Solicitation,
D/LocationInitializer( 1905): Restart initialization of location
,D/Mms/BubbleViewCache( 2367): fillCache bubble = 1
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1455): query,matched:0, calling pid = 1905
,D/TP/SmsProvider( 1455): match 0:Elapsed time : 2.165 ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,D/TP/MmsProvider( 1455): Query uri=content://mms, match=0, calling pid = 1905
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {274c6330}
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/jxcore_app_log( 2603): JniHelper::setJavaVM(0xb8397450), pthread_self() = -1198517120
D/JX-Cordova( 2603): jxcore cordova android initializing
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,I/art     ( 1662): Background sticky concurrent mark sweep GC freed 26087(1532KB) AllocSpace objects, 6(96KB) LOS objects, 12% free, 10MB/12MB, paused 5.145ms total 88.459ms
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1290): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1290): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1290): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1290): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,W/jxcore-log( 2603): Initializing JXcore engine
W/jxcore-log( 2603): JXcore engine is ready
,W/jxcore-log( 2603): Starting JXcore engine
,D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:750 [0:0] Cncl30MinRftAl
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:1056 [0:0] == cityListItem Size : 0
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:175 [0:0] ============== Start refreshType : 3
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:206 [0:0] checkCuL:0, mCityDataList : 0
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:904 [0:0] MR pcknme : Manual systemui
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:257 [0:0] == rCL 1448460666383
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1290): [MSC_Daemon]>>> RM:273 [0:0] EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:278 [0:0] checkCuL:0, getRefreshType():3
,D/daemonapp( 1290): [MSC_Daemon]>>> WMCL:455 [0:0] MCL pfGetCL@NP:false
D/daemonapp( 1290): [MSC_Daemon]>>> WMCL:461 [0:0] MCL pfL set:t
,D/daemonapp( 1290): [MSC_Daemon]>>> WMCL:1895 [0:0] MCL getLLoc@
D/daemonapp( 1290): [MSC_Daemon]>>> WMCL:244 [0:0] MCL getCPrvdr@
,D/daemonapp( 1290): [MSC_Daemon]>>> WMCL:1954 [0:0] PrvdrErr!!
,D/daemonapp( 1290): [MSC_Daemon]>>> WMCL:1956 [0:0] PrvdrErr getPerformLoc:true
D/daemonapp( 1290): [MSC_Daemon]>>> WMCL:1958 [0:0] MCL pfL set:f
,D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1448460666412
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1448482266410
D/daemonapp( 1290): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1448482260000
D/daemonapp( 1290): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448482260000
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1448482260000
D/daemonapp( 1290): [MSC_Daemon]>>> AWCLRH:43 [0:0] ==============rLH=====================
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:1314 [0:0] CL@AtRfr = 3
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/audit   ( 1859): type=1400 msg=audit(1448460666.417:205): avc:  denied  { ioctl } for  pid=2603 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1859):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1859): type=1300 msg=audit(1448460666.417:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=bed53d58 items=0 ppid=307 ppcomm=main pid=2603 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1859): type=1320 msg=audit(1448460666.417:205): 
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:1321 [0:0]  AR_lasttime: 1448482260000
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1615 [0:0] util getnext by widget 1448482260000
,D/daemonapp( 1290): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448482260000
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:1332 [0:0] NextTime       :1448482260000
D/daemonapp( 1290): [MSC_Daemon]>>> AWCLRH:242 [0:0] rLH /on rciclf
D/daemonapp( 1290): [MSC_Daemon]>>> RM:1480 [0:0]  retryCityIdCurrentlocationfail getRefreshType : 3
D/daemonapp( 1290): [MSC_Daemon]>>> RM:1491 [0:0] send broad cast error to clock
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/Zygote  ( 2684): MountEmulatedStorage()
I/libpersona( 2684): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2684): v2
I/libpersona( 2684): KNOX_SDCARD not a persona
I/SELinux ( 2684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2684 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2684): TimaSignature is unavailable
,D/ActivityThread( 2684): Added TimaKeyStore provider
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,D/AdaptiveEventManager( 1174): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
,D/AdaptiveEventManager( 1174): currentCityId is null
D/AdaptiveEventManager( 1174): NetWork disabled : Don't refresh weather info : 201
D/AdaptiveEventManager( 1174): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1174): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1174): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1174): mWeatherInfo is not reliable
,E/daemonapp( 1290): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1290): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,E/daemonapp( 1290): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2684):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 2684):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,E/Zygote  ( 2700): MountEmulatedStorage(),
E/Zygote  ( 2700): v2
I/libpersona( 2700): KNOX_SDCARD checking this for 10135,
I/libpersona( 2700): KNOX_SDCARD not a persona
,I/SELinux ( 2700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2700 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/daemonapp( 1290): [MSC_Daemon]>>> WDBH:4086 [0:0] ud SLS false
E/SELinux ( 2700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecurityLogAgent( 2684):  SeDenialReceiver : Start file Zipping Service 
W/ContextImpl( 2684): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
W/jxcore-log( 2603): Platform android
W/jxcore-log( 2603): 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
W/jxcore-log( 2603): Process ARCH arm
W/jxcore-log( 2603): 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
D/daemonapp( 1290): [MSC_Daemon]>>> RM:1344 [0:0] RhTy : 3, ResponseCount :1, Listsize : 0
D/daemonapp( 1290): [MSC_Daemon]>>> RM:1349 [0:0] =======RefreshType:1 End RetThd Current===========
D/daemonapp( 1290): [MSC_Daemon]>>> RM:1236 [0:0] resetRefreshThread : 0
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/art     (  307): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 21.711ms
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): start check captive portal 
,D/daemonapp( 1290): [MSC_Daemon]>>> RM:1441 [0:0] getBManualRefreshState : false, checkCurrentLocation : 0
D/daemonapp( 1290): [MSC_Daemon]>>> RM:1353 [0:0] send broad cast to clock Cur
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2684): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 2684): FileZippingService : file path =  /data/misc/audit/audit.old
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 17.574ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TimaKeyStoreProvider( 2700): TimaSignature is unavailable
D/ActivityThread( 2700): Added TimaKeyStore provider
,D/SecurityLogAgent( 2684): FileZippingService : onPremise disabled. Zipping..  
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 17.431ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2684): DenialLogFileZipCreator : createZip
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/jxcore-log( 2603): JXcore Cordova bridge is ready!
I/jxcore-log( 2603): 
W/jxcore-log( 2603): JXcore engine is started
,W/ResourcesManager( 2700): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2700): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/SecurityLogAgent( 2684): DenialLogFileZipCreator : Not empty 
W/ResourcesManager( 2700): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/SecurityLogAgent( 2684): DenialLogFileZipCreator File existence : true audit.old file size 631
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2717): MountEmulatedStorage(),
I/ActivityManager( 1017): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 2717): v2
I/libpersona( 2717): KNOX_SDCARD checking this for 1000
I/libpersona( 2717): KNOX_SDCARD not a persona,
I/SELinux ( 2717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/SecurityLogAgent( 2684): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,I/SELinux ( 2717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/SecurityLogAgent( 2684): FileZippingService : completed task. Returning wakelock . 
,E/SELinux ( 2717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/jxcore-log( 2603): >> samsung-SM-A500FU
E/jxcore-log( 2603): 
,I/jxcore-log( 2603): Total memory 1983787008
I/jxcore-log( 2603): 
,I/jxcore-log( 2603): Free memory 239345664
I/jxcore-log( 2603): 
,I/jxcore-log( 2603): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2603): 
I/jxcore-log( 2603): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2603): 
,D/TimaKeyStoreProvider( 2717): TimaSignature is unavailable
,D/ActivityThread( 2717): Added TimaKeyStore provider
,I/jxcore-log( 2603): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2603): 
,I/jxcore-log( 2603): Size 720 1280
I/jxcore-log( 2603): 
,I/jxcore-log( 2603): Screen Brightness 5
I/jxcore-log( 2603): 
,E/jxcore-log( 2603): Dummy Error Log.
E/jxcore-log( 2603): 
,W/ResourcesManager( 2717): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/FactoryTestApp( 2717): [FactoryTestBroadcastReceiver$onReceive](2717) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2717): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2717): [XMLDataStorage$parseXML](2717) is Live Demo : false
,D/FactoryTestApp( 2717): [XMLDataStorage$parseXML](2717) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2717): [XMLDataStorage$parseXML](2717) deviceXML=a5ulte.dat
D/FactoryTestApp( 2717): [XMLDataStorage$parseXML](2717) nameXML=a5ultexx.dat
D/FactoryTestApp( 2717): [XMLDataStorage$parseAsset](2717) parseAsset Is Started
,I/FactoryTestApp( 2717): [XMLDataStorage$parseAsset](2717) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2717): [XMLDataStorage$parseAsset](2717) Decode base file: factory.dat
,E/SMD     (  288): DCD OFF
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 25
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=FACTORY_TEST_APP
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=FAILHIST_VERSION
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=MODEL_NAME
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=MODEL_NUMBER
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=CHIPSET_NAME
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=DEVICE_TYPE
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=BATT_TYPE
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=PANEL_TYPE
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SPEAKER_COUNT
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=MIC_COUNT
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_LTE
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_DUAL_STANBY_ONE_CP
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_RCV
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=FACTORY_TEST_APO
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_EPEN
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_CAM_ISP
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_CAM_FRONT_NOT_ISP
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_SECOND_MIC_TEST
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=NEED_CAMDRIVER_OPEN
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=HW_VER_EFS
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_AUTO_WAKELOCK
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=FONT_SIZE
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=RAM_SIZE_IF
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=MULTI_TSK_THD
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_DISABLE_SCROLLING_CACHE
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_TEST_POWER
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_TEST_HOME
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_TEST_BACK
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=AT_GPSSTEST
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=PA0_TEMP_ADC
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=PA1_TEMP_ADC
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=HALL_IC_TEST,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=READ_TARGET_GEOMAGNETIC,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SYS_INFO_FONT_SIZE,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SYS_INFO_MEMORY_SIZE,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SYS_INFO_MODEL_NAME,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_NODE_COUNT_WIDTH,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_NODE_COUNT_HEIGHT,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_SELFTEST_MIN_MELFAS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_SELFTEST_MAX_MELFAS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TOUCH_KEY_SPEC_MIN,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TOUCH_KEY_SPEC_MAX,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=BOOTLOADER_VERSION,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=BATTERY_TEST_MODE,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=BATTERY_VOLT_AVER,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=BATTERY_VF_OCV,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=SEC_EXT_THERMISTER_TEMP,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=PA0_THERMISTER_ADC,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=PA1_THERMISTER_ADC,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_COMMAND_CMD,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_COMMAND_STATUS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=TSP_COMMAND_RESULT,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=PATH_HALLIC_STATE,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=KEY_PRESSED_POWER,
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=APCHIP_TEMP_ADC
D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=HUMITEMP_THERMISTER_BATT,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=HUMITEMP_THERMISTER_BATT_CELCIUS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=HUMITEMP_THERMISTER_S_HUB_BATT,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=LPA_MODE_SET,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=GEOMAGNETIC_SENSOR_ADC,
,D/FactoryTestApp( 2717): [XMLDataStorage$redefinitionById](2717) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2717): [XMLDataStorage$parseAsset](2717) SemiFunctionMenu
,D/FactoryTestApp( 2717): [XMLDataStorage$parseAsset](2717) parseAsset Is Completed
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2717): [ModuleCommon$ModuleCommon](2717) Create ModuleCommon
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2717): [Support$Kernel.read](2717) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2717): [ModuleCommon$readFactoryMode](2717) mode: ON
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2717): [FactoryTestBroadcastReceiver$onReceive](2717) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2717): [Support$Values.getBoolean](2717) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 2717): [Support$Properties.get](2717) property=ro.factory.factory_binary
D/FactoryTestApp( 2717): [FactoryTestBroadcastReceiver$onReceive](2717) Boot completed, IS_FACTORY_BINARY = USER MODE
,D/SensorService( 1017): [SO] 0.172 0.096 10.228
,I/FactoryTestApp( 2717): [ModuleCommon$getFtClientEnableState](2717) result : false
I/FactoryTestApp( 2717): [ModuleCommon$connectedJIG](2717) ...
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2717): [ModuleCommon$connectedJIG](2717) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2717): [Support$Kernel.read](2717) path=/sys/class/sec/switch/adc, value=1f
,I/FactoryTestApp( 2717): [ModuleCommon$connectedJIG](2717) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2717): [ModuleCommon$isConnectionModeNone](2717) mConnectionMode = gsm
I/FactoryTestApp( 2717): [ModuleCommon$isRunningFtClient](2717) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2717): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2717) start DummyFtClient service for APO
,W/ContextImpl( 2717): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2717): User mode
,I/FactoryTestApp( 2717): [ModuleCommon$disableFtClient](2717) ...
,D/FactoryTestApp( 2717): [DummyFtClient$onCreate](2717) Create DummyFtClient service
I/FactoryTestApp( 2717): [XMLDataStorage$parsingXML](2717) FtClient => data parsing was completed.
D/FactoryTestApp( 2717): [DummyFtClient$onReceive](2717) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2717): [ModuleCommon$isConnectionModeNone](2717) mConnectionMode = gsm
,D/FactoryTestApp( 2717): [Support$Values.getBoolean](2717) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2717): [DummyFtClient$onStartCommand](2717) ...
,I/WifiService( 1017): android.intent.action.BOOT_COMPLETED
,E/DevicePolicyManagerService( 1017): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1017): getAllowBluetoothMode - value retunrs : 2
,I/jxcore-log( 2603): getBuffer is called!!!!
I/jxcore-log( 2603): 
,D/UsbDeviceManager( 1017): boot completed
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
D/UsbDeviceManager( 1017): handleMessage -> MSG_BOOT_COMPLETED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2739): MountEmulatedStorage()
E/Zygote  ( 2739): v2
,I/libpersona( 2739): KNOX_SDCARD checking this for 1002
I/libpersona( 2739): KNOX_SDCARD not a persona
I/SELinux ( 2739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2739 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
I/SELinux ( 2739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2739): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbDeviceManager( 1017): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1017): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
I/KeyguardEffectViewUtil( 1174): set resource id
D/SettingsProvider( 1017): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1174): handleBootCompleted()
,D/KeyguardUpdateMonitor( 1174): handleBootCompleted()
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/PalmMotion( 1017): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
I/PalmMotion( 1017): [PALM] SURFACE_PALM_SWIPE: 1
D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/PalmMotion( 1017): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/PalmMotion( 1017): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SamsungIME( 1788): showDlgMsgBox : false true true
D/UsbDeviceManager( 1017): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,D/NfcService( 1440): call the applyRouting
,D/TimaKeyStoreProvider( 2739): TimaSignature is unavailable
,D/ActivityThread( 2739): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 2739): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 2739): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2757): MountEmulatedStorage(),
E/Zygote  ( 2757): v2
I/libpersona( 2757): KNOX_SDCARD checking this for 1000
I/libpersona( 2757): KNOX_SDCARD not a persona
I/SELinux ( 2757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2757 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/RecoverySystem( 1017): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1017): No recovery log file
,I/BluetoothA2dpSinkServiceJni( 2739): register_com_android_bluetooth_a2dp_sink
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/TimaKeyStoreProvider( 2757): TimaSignature is unavailable
,D/ActivityThread( 2757): Added TimaKeyStore provider
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,D/Reset_Reason( 1017): resetString = NPON
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/BootReceiver( 1017): Copying audit failures to DropBox
,I/BootReceiver( 1017): Checking for fsck errors
,V/OtaStartupReceiver( 1455): onOtaspChanged: mOtaspMode=1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/BtSettings.ProfileConfig( 2739): Adding GattService
,D/BtSettings.ProfileConfig( 2739): Adding HeadsetService
,D/BtSettings.ProfileConfig( 2739): Adding A2dpService
D/BtSettings.ProfileConfig( 2739): Adding HidService
D/BtSettings.ProfileConfig( 2739): Adding HealthService
,D/BtSettings.ProfileConfig( 2739): Adding PanService
D/BtSettings.ProfileConfig( 2739): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 2739): Adding SapService
D/BtSettings.ProfileConfig( 2739): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 2739): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 2739): Adding SapClientService
D/BtSettings.ProfileConfig( 2739): Adding HidDevService
I/BtSettings.ProfileConfig( 2739): *********Initializing Bluetooth Profile Settings*******
,E/Zygote  ( 2778): MountEmulatedStorage()
I/libpersona( 2778): KNOX_SDCARD checking this for 1001
E/Zygote  ( 2778): v2
I/libpersona( 2778): KNOX_SDCARD not a persona
I/SELinux ( 2778): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2778): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2778 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
E/SELinux ( 2778): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/TimaKeyStoreProvider( 2778): TimaSignature is unavailable
,D/ActivityThread( 2778): Added TimaKeyStore provider
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,E/File    ( 2757): fail readDirectory() errno=2
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hid.HidService
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
W/ResourcesManager( 2778): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,D/SettingsProvider( 1017): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/FactoryTestApp( 2717): [ProtectedFactoryTestBroadcastReceiver$onReceive](2717) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2717): [ProtectedFactoryTestBroadcastReceiver$onReceive](2717) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2717): User mode
,D/Mms/NotificationReceiver( 2367): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,D/Mms/NotificationReceiver( 2367): handleBootCompleted()
,D/Mms/RcsOwnCapsManager( 2367): queue Uri = content://im/queue-messages?box=pending
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/TP/ImProvider( 1455): im query match24
,D/TP/ImProvider( 1455): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1455): ftSesstionId must be a long.
D/TP/ImProvider( 1455): getQueuedImMessages
,D/TP/ImProvider( 1455): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
D/Mms/NotificationReceiver( 2367):  getPendingMessageIds: no pending messages.
D/Mms/ActionsFactory( 2367): Call to GET_LAST_MESSAGES_SENT
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/SettingsProvider( 1017): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
I/art     ( 1905): Background partial concurrent mark sweep GC freed 5564(684KB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 10MB/17MB, paused 6.568ms total 94.647ms
D/SettingsProvider( 1017): name = db_smartlock_supported
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/AccessibilityManagerService( 1017): setmDNIeNegative (false)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2799): MountEmulatedStorage()
,E/Zygote  ( 2799): v2
I/libpersona( 2799): KNOX_SDCARD checking this for 10075
I/libpersona( 2799): KNOX_SDCARD not a persona
,I/SELinux ( 2799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/BluetoothAdapterState( 2739): make
I/ActivityManager( 1017): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=2799 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/bluedroid( 2739): init
,I/SELinux ( 2799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2799): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/BluetoothAdapterState( 2739): Entering OffState
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/bte_conf( 2739): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2739): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2739): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2739): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 2739): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 2739): get_profile_interface socket
I/bluedroid( 2739): get_profile_interface map_client
,D/BluetoothAdapterService( 2739): checkAddrForIOP: Loading from conf
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GKI_LINUX( 2739): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 2739): Address is:7C:F9:0E:51:18:22
E/BluetoothServiceJni( 2739): populateRssiValuesNative
I/bluedroid( 2739): getModelRssiValues
E/BluetoothServiceJni( 2739): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2739): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothA2dp( 2739): doBind(): CallingUid(myUserHandle) = 0
,D/BluetoothAdapterProperties( 2739): Name is: Thali Test (Galaxy A5)
,D/TimaKeyStoreProvider( 2799): TimaSignature is unavailable
,D/ActivityThread( 2799): Added TimaKeyStore provider
D/SettingsProvider( 1017): name = bluetooth_name
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/Settings( 1319): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/bluedroid( 2739): config_hci_snoop_log
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService( 1017): Ble is always on enable gatt
,I/BluetoothManagerService( 1017): enableGattForLeMode, doBind called
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,E/DevicePolicyManagerService( 1017): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1017): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1017): uri = 3 selection = isBluetoothEnabled
,D/SettingsProvider( 1017): name = block_emergency_message
,D/BluetoothAdapterState( 2739): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 2739): Setting state to 11
I/BluetoothAdapterState( 2739): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 2739): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2739): updateAdapterState state is 11
,D/BluetoothAdapterService( 2739): Autoconnection is available 
D/BluetoothAdapterService( 2739): updateAdapterState prevState = 10newState = 11
I/BtGatt.JNI( 2739): classInitNative(L900): classInitNative: Success!
D/BluetoothSecureManager( 2739): getInstant: null
D/BluetoothSecureManager( 2739): calling getMethod for getService
D/BluetoothSecureManager( 2739): calling getService
,D/BluetoothSecureManager( 2739): getService return binder: android.os.BinderProxy@16645744
,D/BluetoothSecureManagerService( 1017): isSecureModeEnabled
D/BluetoothSecureManagerService( 1017): getSecureModeSetting, name: secure_mode_enable
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1017): [BT Setting State] State =11
D/BtConfig.SecureMode( 2739): isSecureModeOn:false
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2739): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 2739): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2739): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2739): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2739): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2739): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2739): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2739): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2739): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2739): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1174):  getBluetoothState : 11
,W/BluetoothAdapterService( 2739): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2739): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 2739): make
D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/SamsungIME( 1788): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.gatt.GattService
D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
I/BluetoothBondStateMachine( 2739): StableState(): Entering Off State
,D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 1174): onStateChanged: Bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.hid.HidService
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
E/USB_UICC(  297): Timeout! No signal received. Retry num = 26
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.hdp.HealthService
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.map.BluetoothMapService
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2739): Not skipping com.broadcom.bt.service.sap.SapService
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2739): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2739): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2739): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2739): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2739): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 2739): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,W/DriveInitializer( 1905): Background init thread started
,D/BtGatt.DebugUtils( 2739): handleDebugAction() action=null
D/SettingsProvider( 1017): name = safetycare_geolookout_registering
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BtGatt.GattService( 2739): Received start request. Starting profile...
D/BtGatt.GattService( 2739): start()
D/BtGatt.GattService( 2739): start()
I/bluedroid( 2739): get_profile_interface gatt
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
D/BtGatt.AdvertiseManager( 2739): advertise manager created
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/CursorWrapperInner( 2367): Cursor finalized without prior close()
,D/BtGatt.GattService( 2739): mStartError = false
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,D/HeadsetService( 2739): Received start request. Starting profile...
D/HeadsetService( 2739): start()
,I/BluetoothHeadsetServiceJni( 2739): classInitNative: succeeds
,D/HeadsetStateMachine( 2739): make
,E/HeadsetStateMachine( 2739): # of Max HF connection is 2,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
I/bluedroid( 2739): get_profile_interface handsfree
,W/ContextImpl( 1905): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/DriveInitializer( 1905): Awaiting to be initialized
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 37088(2043KB) AllocSpace objects, 10(569KB) LOS objects, 33% free, 25MB/38MB, paused 2.055ms total 155.767ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DualScoManager( 2739): Instantiating Dual Sco Manager
I/DualScoManager( 2739): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 2739): createCMTIContentObservers
,D/SettingsProvider( 1017): name = bluetooth_hfp_allowed_bvra
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 2739): Enter Disconnected: -2
,D/HeadsetService( 2739): mStartError = false
,D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,D/A2dpService( 2739): Received start request. Starting profile...
D/A2dpService( 2739): start()
,I/BluetoothAvrcpServiceJni( 2739): classInitNative: succeeds
,I/bluedroid( 2739): get_profile_interface avrcp
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,E/RemoteController( 2739): Cannot set synchronization mode on an unregistered RemoteController
,D/HeadsetStateMachine( 2739): Clear mHeadsetBrsf
D/HeadsetStateMachine( 2739): map size, before remove : 0
D/HeadsetStateMachine( 2739): map size, after remove: 0
,I/GLSActivity( 1662): [ac] getting account id
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/Avrcp   ( 2739):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 2739):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/BluetoothA2dpServiceJni( 2739): classInitNative: succeeds
D/A2dpStateMachine( 2739): make
,I/bluedroid( 2739): get_profile_interface a2dp
,I/GKI_LINUX( 2739): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 2739): warning : media task started media_task_refcnt 1 
,D/BluetoothMediaBrowser( 2739): no now playing list
D/BluetoothMediaBrowser( 2739):  getNowPlayingId now playing id : -1
D/A2dpService( 2739): mStartError = false
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
D/A2dpStateMachine( 2739): Enter Disconnected: -2
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/BluetoothHidServiceJni( 2739): classInitNative: succeeds
,D/HidService( 2739): Received start request. Starting profile...
D/HidService( 2739): start()
I/bluedroid( 2739): get_profile_interface hidhost
D/HidService( 2739): setHidService(): set to: null
D/HidService( 2739): mStartError = false
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,I/BluetoothHealthServiceJni( 2739): classInitNative: succeeds
,D/HealthService( 2739): Received start request. Starting profile...
D/HealthService( 2739): start()
,I/bluedroid( 2739): get_profile_interface health
,D/HealthService( 2739): mStartError = false
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,I/GLSUser ( 1662): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1662): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,W/DriveInitializer( 1905): Background init thread ended
,W/GAV2    ( 2799): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BluetoothPanServiceJni( 2739): classInitNative(L105): succeeds
,D/PanService( 2739): Received start request. Starting profile...
,D/PanService( 2739): start()
D/BluetoothPanServiceJni( 2739): initializeNative(L110): pan
I/bluedroid( 2739): get_profile_interface pan
,D/PanService( 2739): mStartError = false
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,I/GLSUser ( 1662): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/BooksApp( 2799): Created application version: 3.6.9 (30609)
,D/BluetoothMapService( 2739): Received start request. Starting profile...
,D/BluetoothMapService( 2739): start()
,D/BluetoothMapService( 2739): mStartError = false
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
E/Auth.Api.Credentials( 1905): [CredentialSyncAdapter] Unknown sync event.
,I/BluetoothSAPServiceJni( 2739): classInitNative(L204): succeeds
,D/SapService( 2739): Received start request. Starting profile...
D/SapService( 2739): start()
D/BluetoothSAPServiceJni( 2739): initializeNative(L209): sap
I/bluedroid( 2739): get_profile_interface sap
D/SapService( 2739): mStartError = false
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/HeadsetStateMachine( 2739): Try to query the phonestate on bind
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/Telecom ( 1428): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1428): BluetoothPhoneService: handleMessage(7) / param 0
,I/Telecom ( 1428): BluetoothPhoneService: updateHeadsetWithCallState
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Telecom ( 1428): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1,
,I/Telecom ( 1428): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,E/SmartFaceService( 1017): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1017): no icon
,E/SmartFaceService( 1017): mActiveServiceType: 0
D/BluetoothA2dp( 1017): Proxy object connected
E/SmartFaceService( 1017): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1017): updateClientsDone. def. do nothing.
E/SmartFaceService( 1017): Service Type to Worker: 0
E/SmartFaceService( 1017): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1017): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/BluetoothPan( 1017): BluetoothPAN Proxy object connected
,V/AlarmManagerEXT( 1017): mGmsLocationBundling: false
,D/RCPManagerService( 1017): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1017):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/RCPManagerService( 1017): BootReceiver.onReceive(): Starting RCP Proxy for user = null
,E/RCPManagerService( 1017):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,I/Telecom ( 1428): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1428): Proxy not attached to service
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,I/Telecom ( 1428): BluetoothPhoneService: Result of Message : true
D/HeadsetStateMachine( 2739): Proxy object connected
,D/HeadsetPhoneState( 2739): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 2739): sendDeviceDataStateChanged
D/HeadsetPhoneState( 2739): Signal level : previous=0 curr=0
V/HeadsetService( 2739): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothA2dp( 2739): Proxy object connected
D/BluetoothAdapterService( 2739): Bluetooth A2dp source service connected
D/HeadsetStateMachine( 2739): Disconnected process message: 11
D/HeadsetStateMachine( 2739): Disconnected process message: 18
D/HeadsetStateMachine( 2739): Disconnected process message: 10
D/HeadsetPhoneState( 2739): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2739): Disconnected process message: 11
,E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1017): [SO] activate (ident=0xb8b645a8, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
,D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb8b645a8, enabled=1)
D/SensorService( 1017): [SO] AR_init
,I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/Icing   ( 1905): Storage manager: low false usage 2.00MB avail 7.89GB capacity 9.93GB
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/EnterpriseDeviceManagerService( 1017): android.intent.action.BOOT_COMPLETED,
,D/EnterpriseDeviceManagerService( 1017): runAdminUpdate
,D/EnterpriseUtils( 1017): File Not Found : /data/system/selfUpdateAdmin.conf
,D/EnterpriseDeviceManagerService( 1017): nothing to selfUpdate
V/ApplicationPolicy( 1017): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1017): refresh widget status for user 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/,ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
W/Icing   ( 1905): Received bad json for section weights override -- ignoring.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/Icing   ( 1905): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 1905): Received bad json for section weights override -- ignoring.
W/Icing   ( 1905): Received bad json for corpus context scoring override -- ignoring.
D/PicasaService( 2527): start picasa sync
D/PicasaService( 2527): end picasa sync
E/Zygote  ( 2868): MountEmulatedStorage()
E/Zygote  ( 2868): v2
I/libpersona( 2868): KNOX_SDCARD checking this for 10145
I/libpersona( 2868): KNOX_SDCARD not a persona
I/SELinux ( 2868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=2868 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 2868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2868): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/PhoneRestrictionPolicy( 1017): Message received - msg { when=-3ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
D/KnoxMUMContainerPolicy( 1017): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
I/KnoxMUMContainerPolicy( 1017): MSG_REMOVE_ORPHANED_CONTAINERS received
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/PhoneRestrictionPolicy( 1017):  >>>> deliveryBlockedMsgs
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/PhoneRestrictionPolicy( 1017): cvList size 0
W/PhoneRestrictionPolicy( 1017):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1017): cvList size 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/WifiP2pService( 1017): InactiveState{ what=143415 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143415 }
D/WifiP2pService( 1017): DefaultState{ what=143415 }
,D/ConnectivityService( 1017): Got NetworkFactory Messenger for WIFI_P2P
,D/WIFI_P2P( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/Tethering( 1017): Boot complete.
,D/ConnectivityService( 1017): Got NetworkFactory Messenger for WIFI
,V/EnterpriseBillingEngine( 1017): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1017): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1017): getCurrentActiveProfiles - start - 
D/TimaKeyStoreProvider( 2868): TimaSignature is unavailable
V/EnterpriseBillingPolicyStorage( 1017): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1017): handleAllprofiles - end
D/ActivityThread( 2868): Added TimaKeyStore provider
,E/WifiStateMachine( 1017): Blacklist file delete
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
D/UsbHostNotification( 1017): boot completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,D/UsbHostRestrictor( 1017): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1017): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1017): SIM was never inserted
,D/UsbHostRestrictor( 1017): writableHostSysNode[false]
D/UsbHostRestrictor( 1017): Can NOT Write Disable Sys Node to [ON]
,W/ResourcesManager( 2868): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/WIFI    ( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,W/ResourcesManager( 2868): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PersonaManagerService( 1017): ACTION_BOOT_COMPLETED
,W/ResourcesManager( 2868): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2868): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2868): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/UsbStorageNotification( 1017): boot completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,E/PersonaManagerServiceHandler( 1017):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/KnoxKeyguardUpdateMonitor( 1017): onBootComplete
,I/KnoxKeyguardUpdateMonitor( 1017): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1017): onTrustChanged user:0, enable:false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,D/KeyguardViewMediator( 1174): onTrustChanged( Showing = false , userId = 0 )
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1017): set_capabilities_callback: 55u
,I/libmdmdetect( 1017): ESOC framework not supported
,I/libmdmdetect( 1017): Found internal modem: modem
E/PerMgrLib( 1017): Peripheral manager is not supported on this device
,E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_cleanup 
,D/qmi_secgps_clnt( 1017): qmi_secgps_client_init()
,D/StorageNotification( 1174): boot completed
,W/ProcessCpuTracker( 1017): Skipping unknown process pid 2887
W/ProcessCpuTracker( 1017): Skipping unknown process pid 2888
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,I/i       ( 1017): No model
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/StatusBarManagerService( 1017): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/FactoryTest( 1017): Not factory mode
D/FactoryTest( 1017): Not factory mode. isFactoryMode() returend false
D/w       ( 1017): isUserBuild = true
D/PhoneStatusBar( 1174): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2895): MountEmulatedStorage()
I/libpersona( 2895): KNOX_SDCARD checking this for 10099
E/Zygote  ( 2895): v2
I/libpersona( 2895): KNOX_SDCARD not a persona
,I/SELinux ( 2895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2895): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2895 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/BooksSync( 2799): Starting books sync for 61035162, extras: ade
,D/TimaKeyStoreProvider( 2895): TimaSignature is unavailable
,D/ActivityThread( 2895): Added TimaKeyStore provider
,D/SSRM:n  ( 1017): SIOP:: AP = 410
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1017): [SO] activate (ident=0xb8b645a8, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb8b645a8, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/LocSvc_utils_cfg( 1017): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1017): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 27,
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1017): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1017): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1017): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SensorService( 1017): [SO] currT = 33111013000, prevT = 32651374000, diff = 459639000, [0.172 0.115 10.228],
D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1017): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,D/SensorService( 1017): [SO] currT = 33181051000, prevT = 32651374000, diff = 529677000, [0.172 0.115 10.228],
D/SensorService( 1017): [SO] 0.172 0.115 10.228
D/SensorService( 1017): [SO] [100 -> 255]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityThread( 2895): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2895): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1017): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
,I/splitIntent( 1017): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1017): DrmEventReceiver : beginStartingService
I/System.out( 1017): start Service
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/DownloadManager( 1227): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2922): MountEmulatedStorage(),
E/Zygote  ( 2922): v2
,I/libpersona( 2922): KNOX_SDCARD checking this for 10085
I/libpersona( 2922): KNOX_SDCARD not a persona
,I/SELinux ( 2922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2922 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 2922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2922): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 2932): MountEmulatedStorage(),
I/libpersona( 2932): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2932): v2
I/libpersona( 2932): KNOX_SDCARD not a persona,
I/SELinux ( 2932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2932): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media,
,D/TimaKeyStoreProvider( 2922): TimaSignature is unavailable
D/ActivityThread( 2922): Added TimaKeyStore provider
,E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/WVMDrmPlugIn(  282): WVMDrmPlugin::onInitialize : 2253
D/WVMDrmPlugIn(  282): WVMDrmPlugin::onSetOnInfoListener : add 2253
,D/BluetoothAdapterState( 2739): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2739): enable
,I/bt_hci_bdroid( 2739): init
,I/GKI_LINUX( 2739): gki_task_entry task_id=0 [BTU] starting
,I/DrmEventService( 1017): action event :android.intent.action.BOOT_COMPLETED
,I/TimaServiceEventReceiver( 1017): TimaServiceEventReceiver : onReceive
,I/bt_vendor( 2739): bt-vendor : init
I/bt_vendor( 2739): bt-vendor : get_bt_soc_type
E/bt_vendor( 2739): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 2739): init: Local BD Address : 22:18:51:0e:f9:7c
D/bt_userial_mct( 2739): userial_init
,I/bt_vendor( 2739): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2739): Starting hciattach daemon
I/bt_vendor( 2739): try to set false
,I/bt_vendor( 2739): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 2739): Starting hciattach daemon
I/bt_vendor( 2739): try to set true
,I/ANDROID_DRM_FRWORKS_DrmManager(  282): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,D/TimaKeyStoreProvider( 2932): TimaSignature is unavailable
,D/ActivityThread( 2932): Added TimaKeyStore provider
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState,
D/SecContentProvider2( 1017): mCursor = null
,D/MediaScannerReceiver( 1227): action: android.intent.action.BOOT_COMPLETED
,I/qcom-bluetooth( 2963): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,E/CscReceiver( 1455): onReceive android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 2922): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2922): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2922): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ResourcesManager( 2922): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 2922): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ResourcesManager( 2922): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/SQLiteLog( 2799): (284) automatic index on view_volumes(volume_id)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,D/BadgeProvider( 1578): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 1455): onStart
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/CscUpdateService( 1455): costomer file is exists : it has been preconfiged.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/CscUpdateService( 1455): set_CSC_version
E/CscParser( 1455): update(): xml file exist
,I/qcom-bluetooth( 2969): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 2971): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/Zygote  ( 2973): MountEmulatedStorage()
,E/Zygote  ( 2973): v2
I/libpersona( 2973): KNOX_SDCARD checking this for 10003
I/libpersona( 2973): KNOX_SDCARD not a persona
,I/SELinux ( 2973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 2973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2973): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2973 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/qcom-bluetooth( 2975): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 2982): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/CscUtil ( 1455): isWifiOnly = false
,I/System.out( 1455): HandDataNode = null
,I/qcom-bluetooth( 2986): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/CscUpdateService( 1455): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1455): This is normal boot : CSC not updated,
D/TimaKeyStoreProvider( 2973): TimaSignature is unavailable
D/ActivityThread( 2973): Added TimaKeyStore provider
,E/CscParser( 1455): update(): xml file exist
E/Zygote  ( 2996): MountEmulatedStorage(),
I/qcom-bluetooth( 2993): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2996 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,E/Zygote  ( 2996): v2
I/libpersona( 2996): KNOX_SDCARD checking this for 10160
I/SELinux ( 2996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/libpersona( 2996): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Killing 1190:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/MediaScannerService( 1227): !@start scanning volume internal: [/system/media, /oem/media]
I/SELinux ( 2996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CscGPS  ( 1455): CSCGPS.updateParameters
D/CscGPS  ( 1455): supl host : null
D/CscGPS  ( 1455): SUPL Host is null or invalid
D/CscGPS  ( 1455): supl_ver : null
D/CscGPS  ( 1455): SUPL Ver is null or invalid
D/CscGPS  ( 1455): supl port : null
D/CscGPS  ( 1455): SUPL PORT is null or invalid
D/CscGPS  ( 1455): LPP : null
D/CscGPS  ( 1455): LPP is null or invalid
D/CscGPS  ( 1455): CSC don't have any AGPS value.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/art     (  307): Explicit concurrent mark sweep GC freed 8761(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 906us total 26.437ms
,D/BadgeProvider( 1578): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 1578): sendNotify, [notify] : null
D/BadgeProvider( 1578): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1578): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1578): update, [UpdateCount] : 1
,D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
,D/TimaKeyStoreProvider( 2996): TimaSignature is unavailable
,D/ActivityThread( 2996): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 19.700ms
D/Launcher.Model( 1486): reloadBadges entered.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1190/cgroup.procs: No such file or directory
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 22.313ms
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,I/BooksConfig( 2799): GmsCore Version = 7.8.99 (2134222-436),
,W/ResourcesManager( 2996): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/CscUpdateService( 1455): same CSC Version
,D/CscUtil ( 1455): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,I/SecureStorage( 2973): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3018): MountEmulatedStorage(),
E/Zygote  ( 3018): v2
I/libpersona( 3018): KNOX_SDCARD checking this for 1000,
I/libpersona( 3018): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3018 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3018): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3018): TimaSignature is unavailable
,D/ActivityThread( 3018): Added TimaKeyStore provider
,D/TP/MmsProvider( 1455): Update uri=content://mms, match=0,
,D/TP/MmsProvider( 1455): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
,I/Mms:transaction( 2367): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2367): [start]    nonBlockingUpdateMessageIndicator() consume time = 3729.537342
I/Mms/ReservationManager( 2367): resetAfterConnected()
,I/SecureStorage( 2973): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/TP/MmsSmsProvider( 1455): query,matched:7, calling pid = 2367
,I/SecureStorage(  372): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2973,
,I/SecureStorage(  372): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C,
,I/SecureStorage( 2973): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2973): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  372): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2973
I/SecureStorage(  372): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
D/TP/MmsSmsProvider( 1455): match 7:Elapsed time : 3.522 ms
,E/SQLiteLog( 1227): (283) recovered 280 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,D/Mms/MessagingNotification( 2367): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2367): isDefault true,
,I/Mms/ReservationManager( 2367): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsProvider( 1455): Query uri=content://mms, match=0, calling pid = 2367
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/[0]UMC:UMCContentProvider( 2996): @onCreate,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/qcom-bluetooth( 3037): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:51:18:22 
,E/Zygote  ( 3040): MountEmulatedStorage()
,E/Zygote  ( 3040): v2
I/libpersona( 3040): KNOX_SDCARD checking this for 10048
I/libpersona( 3040): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3040 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 3040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/qcom-bluetooth( 3039): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,D/Mms/SmsReceiverService( 2367): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
I/SELinux ( 3040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/TelephonyPermission( 2367): isDefault true
,D/Mms/SmsReceiverService( 2367): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2367): [start]    handleBootCompleted() consume time = 53.667188
,I/bt_vendor( 2739): bluetooth satus is on
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
D/bt_userial_mct( 2739): userial_open(port:0),
I/bt_vendor( 2739): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 2739): Done intiailizing UART
,I/bt_vendor( 2739): Done intiailizing UART
I/bt_userial_mct( 2739): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2739): Bluetooth Firmware and transport layer are initialized
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/bt_userial_mct( 2739): Entering userial_read_thread()
,D/TP/MmsSmsProvider( 1455): query,matched:200, calling pid = 2367
,D/TP/MmsSmsProvider( 1455): match 200:Elapsed time : 2.708 ms
D/TimaKeyStoreProvider( 3040): TimaSignature is unavailable
,D/ActivityThread( 3040): Added TimaKeyStore provider
,D/[0]UMC:Core( 2996): onCreate(): 
D/[0]UMC:Core( 2996): @isManagedProfileUser
,D/[0]UMC:Core( 2996): userId: 0
,D/TP/SmsProvider( 1455): query,matched:0, calling pid = 2367
,D/[0]UMC:Core( 2996): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2996): userInfo.isManagedProfile() : false
,D/TP/SmsProvider( 1455): match 0:Elapsed time : 2.026 ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3040): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ResourcesManager( 3040): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourcesManager( 3040): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1455): query,matched:51, calling pid = 2367
,D/TP/SmsProvider( 1455): match 51:Elapsed time : 1.390 ms
,E/SMD     (  288): DCD OFF
,E/SQLiteLog( 3018): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 28
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,D/SettingsProvider( 1017): name = next_alarm_formatted
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10085
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
,I/art     ( 1455): Explicit concurrent mark sweep GC freed 38367(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/12MB, paused 971us total 53.271ms
,I/        ( 2739): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2739): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2739): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2739): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2739): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2739): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2739): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2739): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2739): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2739): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2739): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2739): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2739): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2739): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2739): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2739): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2739): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/[0]UMC:DeviceInfo( 2996): USA==US==
,D/DSM     ( 3018): [Lines:107] Normal booted
,D/DSM     ( 3018): [Lines:114] Boot completed
,D/Mms/MessagingNotification( 2367): isBlockingModeEnabled() = false, Zen mode = 0
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/BadgeProvider( 1578): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3060): MountEmulatedStorage()
E/Zygote  ( 3060): v2
I/libpersona( 3060): KNOX_SDCARD checking this for 1000
I/libpersona( 3060): KNOX_SDCARD not a persona
I/SELinux ( 3060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3060): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 43234(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 26MB/39MB, paused 3.881ms total 233.286ms
,D/SettingsProvider( 1017): name = block_emergency_message
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10048
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/bt-l2cap( 2739): l2c_link_processs_ble_num_bufs 16
,W/ActivityManager( 1017): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,E/bt-btm  ( 2739): BTM_SecRegister:p_cb_info->p_le_callback == 0xa439f6e9 
E/bt-btm  ( 2739): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa439f6e9 
,D/BadgeProvider( 1578): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1578): sendNotify, [notify] : null
D/BadgeProvider( 1578): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1578): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1578): update, [UpdateCount] : 1
,D/Launcher.Model( 1486): reloadBadges entered.
,D/Mms/MessagingNotification( 2367): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2367): remove alarm
,D/TimaKeyStoreProvider( 3060): TimaSignature is unavailable
,D/BluetoothAdapterProperties( 2739): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,D/ActivityThread( 3060): Added TimaKeyStore provider
,E/bt-btif ( 2739):                : sec
E/bt-btif ( 2739): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 2739): Address is:7C:F9:0E:51:18:22
E/BluetoothServiceJni( 2739): populateRssiValuesNative
I/bluedroid( 2739): getModelRssiValues
E/BluetoothServiceJni( 2739): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2739): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/USER_AGENT( 2996): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,D/TP/MmsSmsProvider( 1455): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1455): deleteConversation threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1455): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1455): updateThread(), thread_id = 9223372036854775806
,D/[0]UMC:AdminManager( 2996): init - start
,V/TP/MmsSmsDatabaseHelper( 1455): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,D/[0]UMC:AdminManager( 2996): loadAdmins
,D/BluetoothAdapterProperties( 2739): Name is: Thali Test (Galaxy A5)
,D/[0]UMC:AdminManager( 2996): init - end
,D/GSLBManager( 2996): migrateStoredUrlFromOldPref
,D/SettingsProvider( 1017): name = bluetooth_name
,D/Mms/MessagingNotification( 2367): updateAllHistoryAsRead()
,D/TP/SmsProvider( 1455): query,matched:0, calling pid = 2367
,D/TP/SmsProvider( 1455): match 0:Elapsed time : 4.136 ms
,D/TP/MmsSmsProvider( 1455): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
,I/ActivityManager( 1017): Killing 1399:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,D/BluetoothUtils( 2739): getBtEnabledContainers(): btContainers = []
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/BluetoothAdapterProperties( 2739): Scan Mode:20
,D/BluetoothAdapterProperties( 2739): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 2739): LE Address is:FC:F3:1C:A2:30:44
,E/bt-btif ( 2739): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,D/MediaScanner( 1227): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,E/bt_mct  ( 2739): hci lib postload completed
,I/NotificationStore( 1662): System rebooted after Notification storage file was last written
,I/dhcpcd  ( 2291): wlan0: sending IPv6 Router Solicitation
I/NotificationStore( 1662): Deleting the file
,I/WifiCredService( 1319): onCreate
,E/bt-btif ( 2739): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 2739): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 2739): btif_sock_init: !vhci_init
D/IOP_DB_BT( 2739): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 2739): db_open: db_open : handle 3027902480l, read 13894 bytes onto local cache
D/IOP_DB_BT( 2739): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 2739): db_query: result 1
I/        ( 2739): iop_db_open: iop_db_open status 0
,W/ResourcesManager( 3060): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/bte_conf( 2739): Device ID record 1 : primary
D/bte_conf( 2739):   vendorId            = 0075
D/bte_conf( 2739):   vendorIdSource      = 0001
D/bte_conf( 2739):   product             = 0100
D/bte_conf( 2739):   version             = 0200
D/bte_conf( 2739):   clientExecutableURL = 
D/bte_conf( 2739):   serviceDescription  = 
D/bte_conf( 2739):   documentationURL    = 
D/bte_conf( 2739): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 2739): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 2739): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2739): ScanMode =  20
D/BluetoothAdapterProperties( 2739): State =  11
,D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 2739): Setting state to 12
,I/BluetoothAdapterState( 2739): Bluetooth adapter state changed: 11-> 12
,D/Mms/Conversation( 2367): deleteTempConversation(),deleted=0
,D/Mms/MessagingNotification( 2367): [end]    nonBlockingUpdateMessageIndicator() consume time = 396.824843
,D/BluetoothUtils( 2739): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2739): Scan Mode:21
D/BluetoothAdapterProperties( 2739): Discoverable Timeout:120
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_mode
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 2739): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 2739): updateAdapterState state is 12
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/art     ( 2922): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 228.385ms
,D/WifiTimerReceiver( 1319): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1319): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1319): Action boot completed received
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,D/WifiCredService( 1319): Action received :android.net.wifi.WIFI_STATE_CHANGED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/WifiStateMachine( 1017): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1017): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1017): invaild command id : 215
D/SmsProvider( 1455): Update uri=content://sms/outbox, match=8
,D/GSLBManager( 2996):  key : segd-api
D/GSLBManager( 2996):  value : https://eu-segd-api.secb2b.com:443/v2
,D/BluetoothAdapter( 1174): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1174): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 1017): onBluetoothStateChange: up=true
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
D/BluetoothAdapterService( 2739): Autoconnection is available 
D/BluetoothAdapterService( 2739): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 2739): starting service from this receiver
,D/BluetoothAdapter( 1428): onBluetoothStateChange: up=true,
D/BluetoothAdapter( 1428): onBluetoothStateChange: Bluetooth is on
,D/WindowManager( 1017): showStatusBarByNotification() mOpenByNotification=false
,W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_1399/cgroup.procs: No such file or directory
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/BluetoothAdapter( 2603): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 2603): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 2739): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1440): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1440): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1017): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1017): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1455): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1455): onBluetoothStateChange: Bluetooth is on,
D/GSLBManager( 2996):  key : umc-cdn
D/GSLBManager( 2996):  value : ,
,D/BluetoothAdapter( 2114): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2114): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1732): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1732): onBluetoothStateChange: Bluetooth is on
,I/BluetoothPbapService( 2739): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/BluetoothPbapService( 2739): Handler(): got msg=1
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapter( 2739): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2739): onBluetoothStateChange: Bluetooth is on
,D/GSLBManager( 2996):  key : segp-api
,D/GSLBManager( 2996):  value : 
W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/BluetoothAdapterState( 2739): Entering On State from state = 11
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1017): [BT Setting State] State =12
,V/MediaScanner( 1227): processDirectory :  /system/media
I/InputMethodManagerService( 1017): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothHeadset( 1428): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1be1f637, true
,D/BluetoothHeadset( 1428): registerMessageListener
,D/BluetoothTile( 1174):  onBluetoothStateChange:
,I/SamsungIME( 1788): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothPbapService( 2739): PBAP Service initSocket try: 0,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1174):  getBluetoothState : 12
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,W/ResourcesManager( 1174): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1174): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=true
D/GSLBManager( 2996):  key : myknoxapi
,D/GSLBManager( 2996):  value : 
,D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,W/ActivityThread( 3060): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/HeadsetService( 2739): registerMessageListener
,D/HeadsetService( 2739): registerMessageListener
,D/HeadsetStateMachine( 2739): Disconnected process message: 70
,D/HeadsetStateMachine( 2739): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@133752f
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,I/Telecom ( 1428): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1428): BluetoothPhoneService: updateHeadsetWithCallState
,D/Mms/SmsReceiverService( 2367): moveOutboxMessagesToFailedBox messageCount: 0
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/Mms/SmsReceiverService( 2367): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2367): [SIM-1]sendFirstQueuedMessage()
D/BluetoothSocket( 2739): bindListen(): myUserId = 0
W/BluetoothAdapter( 2739): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 2739): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 2739): bindListen(), new LocalSocket 
D/BluetoothSocket( 2739): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2739): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@267861a
I/Telecom ( 1428): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1428): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1428): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothSocket( 2739): channel: 19
D/BluetoothPbapService( 2739): PBAP Socket is BluetoothServerSocket
,D/HeadsetStateMachine( 2739): Disconnected process message: 9
,D/HeadsetStateMachine( 2739): mNumActive: 0 mNumHeld: 0 mCallState: 6
,V/MediaScanner( 1227):  prescan time: 712ms (DB items: 141)
V/MediaScanner( 1227):     scan time: 71ms (Caching mode: true), (makeEntry time: 42ms ~59%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 783ms
V/MediaScanner( 1227): checked files: 133  directories : 6  (I: 0, U: 0)
,D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,I/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,D/TP/SmsProvider( 1455): query,matched:26, calling pid = 2367
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1174): ----- inflateViews : modified publicViewLocal -----
,D/TP/SmsProvider( 1455): match 26:Elapsed time : 23.250 ms
,D/GSLBManager( 2996): migrateStoredUrlFromOldPref : Finished Migrating
,D/[0]UMC:UMCAdmin( 2996): deactivateUMCAdminIfNotRequired : -1
,D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,E/[0]UMC:Utils( 2996): Admin not found in package com.samsung.knoxpb.mdm
,D/MediaScanner( 1227): checkDefaultSounds
E/[0]UMC:Utils( 2996): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2996): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2996): isContainer : 0
,D/audio_hw_primary(  283): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  283): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,D/KnoxNotification( 1174): ----- inflateViews : modified KnoxViewLocal -----
,D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
,E/HeadsetStateMachine( 2739): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/NearbySettings( 1319): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1319): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1319): MountReceiver.onReceive - Create mPrefHandler
,D/PersonaManager( 1174): PersonaID is invalid or persona doesn't exists. : 0
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2996): No active admin owned by uid 10160
,D/[0]UMC:UMCAdmin( 2996): isContainer : 0
D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PanelView( 1174): There is/are notification(s) ,
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
D/[0]UMC:UMCAdmin( 2996): deactivateUMCAdmin - UMC App Admin deactivated
,D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
,D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION,
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK,
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
V/NearbySettings( 1319): MountReceiver.mPrefHandler - 7002
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2,
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,D/SettingsProvider( 1017): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 3060): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,I/LcdtestApp( 3060): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2996): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
D/[0]UMC:CoreReceiver( 2996): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2996):  check PreETag 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/Mms/SmsReceiver( 2367): unregisterForServiceStateChanges, already unregistered
,D/BluetoothMapMasInstance( 2739): set MAP SDP message type : 1
,I/NearbySettings( 1319): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1319): MountReceiver.onReceive - Internal Path
,E/Zygote  ( 3094): MountEmulatedStorage()
,E/Zygote  ( 3094): v2
I/libpersona( 3094): KNOX_SDCARD checking this for 1000
I/libpersona( 3094): KNOX_SDCARD not a persona
D/Mms/MessagingNotification( 2367): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2367): isDefault true
,D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3094 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Killing 1520:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,I/SELinux ( 3094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothSocket( 2739): bindListen(): myUserId = 0
W/BluetoothAdapter( 2739): getBluetoothService() called with no BluetoothManagerCallback
I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/BluetoothSocket( 2739): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 2739): bindListen(), new LocalSocket 
D/BluetoothSocket( 2739): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2739): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3266db27
D/BluetoothSocket( 2739): channel: 5
,D/[0]UMC:CoreReceiver( 2996): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2996): Enter loadList
D/TP/MmsProvider( 1455): Query uri=content://mms, match=0, calling pid = 2367
D/[0]UMC:CoreReceiver( 2996): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2996): deactivateUMCAdminIfNotRequired : -1
,D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/[0]UMC:Utils( 2996): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2996): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2996): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2996): isContainer : 0
,D/TimaKeyStoreProvider( 3094): TimaSignature is unavailable
,D/ActivityThread( 3094): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2996): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2996): isContainer : 0
,D/SettingsProvider( 1017): name = personal_mode_enabled
,D/MediaScannerService( 1227): !@done scanning volume internal
,D/[0]UMC:UMCAdmin( 2996): deactivateUMCAdmin - UMC App Admin deactivated
,D/FactoryTestApp( 2717): [DummyFtClient$mBroadcastReceiver](2717) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2717): [DummyFtClient$mBroadcastReceiver](2717) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2717): [DummyFtClient$mBroadcastReceiver](2717) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,E/BooksAccountManager( 2799): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,D/[0]UMC:ByodSetupStarter( 2996): Container ID : 0
,V/[0]UMC:Utils( 2996): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2996): shutdown
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2996): @GuardService - stopService Result = true
,I/art     ( 2996): System.exit called, status: 0
I/AndroidRuntime( 2996): VM exiting with result code 0, cleanup skipped.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ResourcesManager( 1455): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourcesManager( 1455): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 1455): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1455): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1455): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1455): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/BooksSync( 2799): Soft error
E/BooksSync( 2799): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 2799): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 2799): Sync error
E/BooksSync( 2799): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 2799): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 2799): Finished books sync
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/TP/MmsSmsProvider( 1455): query,matched:200, calling pid = 2367
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/TP/MmsSmsProvider( 1455): match 200:Elapsed time : 5.980 ms
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1520/cgroup.procs: No such file or directory
,I/SmartcardBootCompleteReceiver( 1319): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1319): Received intent with action - android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 1017): Killing 1578:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23266, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/TP/SmsProvider( 1455): query,matched:0, calling pid = 2367
,D/TP/SmsProvider( 1455): match 0:Elapsed time : 1.612 ms
,D/TP/SmsProvider( 1455): query,matched:51, calling pid = 2367
,D/TP/SmsProvider( 1455): match 51:Elapsed time : 2.143 ms
,I/DIAGMON_AGENT( 3094): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
I/ActivityManager( 1017): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2996)(adj 0) has died(66,1069)
,W/ContextImpl( 1319): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/Mms/MessagingNotification( 2367): isBlockingModeEnabled() = false, Zen mode = 0
,I/SmartcardBootCompleteReceiver( 1319): Broadcast sent with current lockscreen type
D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1017): ProcessRecord{36c5b1ab 1578:com.sec.android.provider.badge/u0a72} is already killed
E/lowmemorykiller(  254): Error writing /proc/1578/oom_score_adj; errno=22
E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager( 1017): Existing provider com.sec.android.provider.badge/.BadgeProvider is crashing; detaching ProcessRecord{2390f008 2367:com.android.mms/u0a46}
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/comsamsunglog( 1290): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1290): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1290): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1290): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1290): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished,
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
,E/Zygote  ( 3113): MountEmulatedStorage()
,I/libpersona( 3113): KNOX_SDCARD checking this for 10072
E/Zygote  ( 3113): v2
I/libpersona( 3113): KNOX_SDCARD not a persona
I/SELinux ( 3113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3113 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/SELinux ( 3113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3113): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1017): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10162
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/MediaScanner( 1227): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,I/SecureStorage(  372): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
D/daemonapp( 1290): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
D/daemonapp( 1290): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1290): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3113): TimaSignature is unavailable
,E/daemonapp( 1290): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityThread( 3113): Added TimaKeyStore provider
,D/[SBeam] ( 1319): SBeamEnabler.initPreferenceForSbeam : 0
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1448460670715
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1448482260000
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1290): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,E/Zygote  ( 3129): MountEmulatedStorage()
E/Zygote  ( 3129): v2
I/libpersona( 3129): KNOX_SDCARD checking this for 1000
I/libpersona( 3129): KNOX_SDCARD not a persona
,I/SELinux ( 3129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3129 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Killing 1756:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31,
,E/SELinux ( 3129): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
,D/daemonapp( 1290): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448482260000
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
D/daemonapp( 1290): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1448482260000
,D/comdaemonstockapp( 1290): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1290): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/Icing   ( 1905): updateResources: need to parse f{com.google.android.gms}
,D/TimaKeyStoreProvider( 3129): TimaSignature is unavailable
,D/ActivityThread( 3129): Added TimaKeyStore provider
,I/SecureStorage( 2973): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 2973): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
,I/SettingSearch/SearchIntentReceiver( 1319): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1319): search setting db init!!
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1578/cgroup.procs: No such file or directory
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,W/ContextImpl( 1865): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
W/ContextImpl( 1319): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,W/ResourcesManager( 3129): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/SettingSearch/SearchIntentReceiver( 1319): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/SecUISvc( 1865): Service started flags 0 startId 1
,D/SecUISvc( 1865): Thread created.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 29
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BadgeProvider( 3113): onCreate
D/BadgeProvider( 3113): DatabaseHelper
,E/Zygote  ( 3150): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3150 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3150): v2
I/libpersona( 3150): KNOX_SDCARD checking this for 10028
I/SELinux ( 3150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3150): KNOX_SDCARD not a persona
,I/SELinux ( 3150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 3150): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DIAGMON_AGENT( 3094): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
,I/DIAGMON_AGENT( 3094): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,V/MediaScanner( 1227):  prescan time: 118ms (DB items: 27)
V/MediaScanner( 1227):     scan time: 176ms (Caching mode: true), (makeEntry time: 70ms ~39%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 12ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 306ms
V/MediaScanner( 1227): checked files: 10  directories : 17  (I: 0, U: 0)
,I/DIAGMON_AGENT( 3094): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3150): TimaSignature is unavailable
,I/DIAGMON_AGENT( 3094): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,I/DIAGMON_AGENT( 3094): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
E/Zygote  ( 3165): MountEmulatedStorage()
I/libpersona( 3165): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3165): v2
I/libpersona( 3165): KNOX_SDCARD not a persona
,I/DIAGMON_AGENT( 3094): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/SELinux ( 3165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityThread( 3150): Added TimaKeyStore provider
,I/SELinux ( 3165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3179): MountEmulatedStorage()
E/Zygote  ( 3179): v2
I/libpersona( 3179): KNOX_SDCARD checking this for 10150
I/libpersona( 3179): KNOX_SDCARD not a persona
,I/SELinux ( 3179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3179 uid=10150 gids={50150, 9997} abi=armeabi-v7a
I/SELinux ( 3179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3179): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/iu.UploadsManager( 1905): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/FactoryTestApp( 2717): [DummyFtClient$mBroadcastReceiver](2717) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2717): [DummyFtClient$mBroadcastReceiver](2717) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2717): [DummyFtClient$sendBootCompletedAndFinish](2717) ...
D/FactoryTestApp( 2717): [Support$Values.getString](2717) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2717): [ModuleCommon$isConnectionModeNone](2717) mConnectionMode = gsm
D/FactoryTestApp( 2717): [IPCWriterToSecPhoneService$ResponseWriter](2717) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2717): [IPCWriterToSecPhoneService$connectToSecPhoneService](2717)  
,W/libprocessgroup( 1017): failed to open /acct/uid_10138/pid_1756/cgroup.procs: No such file or directory
,D/MediaScannerService( 1227): !@done scanning volume external
,D/TimaKeyStoreProvider( 3165): TimaSignature is unavailable
,D/ActivityThread( 3165): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 1562:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/BluetoothMediaBrowser( 2739):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 2717): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,D/TimaKeyStoreProvider( 3179): TimaSignature is unavailable
D/ActivityThread( 3179): Added TimaKeyStore provider
,E/Zygote  ( 3198): MountEmulatedStorage()
E/Zygote  ( 3198): v2
,I/libpersona( 3198): KNOX_SDCARD checking this for 10086
I/libpersona( 3198): KNOX_SDCARD not a persona
,I/SELinux ( 3198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3198 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3198): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 3113): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/ActivityManager( 1017): Killing 2114:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3198): TimaSignature is unavailable
,D/ActivityThread( 3198): Added TimaKeyStore provider
,W/ResourcesManager( 3165): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 3217): MountEmulatedStorage(),
E/Zygote  ( 3217): v2
I/libpersona( 3217): KNOX_SDCARD checking this for 1000
I/libpersona( 3217): KNOX_SDCARD not a persona,
I/SELinux ( 3217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3217 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/BluetoothHeadset( 2973): BTStateChangeCB is registed
,D/BluetoothHeadset( 2973): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,I/FactoryTestApp( 2717): [IPCWriterToSecPhoneService$onServiceConnected](2717) connected done
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 2973): BluetoothHeadset service is binded
I/art     (  307): Explicit concurrent mark sweep GC freed 8772(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.019ms total 30.927ms
,D/BluetoothA2dp( 2973): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,D/FactoryTestApp( 2717): [IPCWriterToSecPhoneService$write](2717) Send Response Message to SecPhone,
D/FactoryTestApp( 2717): [IPCWriterToSecPhoneService$write](2717) Response ��
,D/BluetoothMediaBrowser( 2739): no now playing list
D/BluetoothMediaBrowser( 2739):  getNowPlayingId now playing id : -1
,D/TimaKeyStoreProvider( 3217): TimaSignature is unavailable
D/ActivityThread( 3217): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 732us total 18.260ms
,D/AT_Distributor(  311): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,D/FactoryTestApp( 2717): [IPCWriterToSecPhoneService$handleMessage](2717) Send BOOTING COMPLETED done
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 655us total 18.022ms
,W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_1562/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10031/pid_2114/cgroup.procs: No such file or directory
,I/iu.UploadsManager( 1905): End new media; added: 0, uploading: 0, time: 213 ms
,D/Launcher.Model( 1486): reloadBadges entered.
D/BadgeProvider( 3113): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 3113): sendNotify, [notify] : null
D/BadgeProvider( 3113): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 3113): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3113): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 2367): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2367): remove alarm
,D/TP/SmsProvider( 1455): query,matched:0, calling pid = 2367
,D/TP/SmsProvider( 1455): match 0:Elapsed time : 2.723 ms
,D/AT_Distributor(  311): SetAtdStatus(), 1_1_0
D/AT_Distributor(  311): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/Mms/MessagingNotification( 2367): updateAllHistoryAsRead()
,D/Mms/SmsReceiverService( 2367): [end]    handleBootCompleted() consume time = 1125.720208
,D/BluetoothA2dp( 2973): Proxy object connected
,I/ActivityManager( 1017): Killing 2163:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 16140(825KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 2.302ms total 143.617ms
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4118, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1174): Cable  true --> true mBootCompleted : true
,D/PowerUI ( 1174): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/HeadsetService( 2739): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2739): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/Icing   ( 1905): Internal init done: storage state 0
,E/UpdateRequestReceiver( 3198): ignoring update request
,E/UpdateRequestReceiver( 3198): ignoring update request
,W/libprocessgroup( 1017): failed to open /acct/uid_10050/pid_2163/cgroup.procs: No such file or directory
,I/FOTA    ( 3165): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/UpdateRequestReceiver( 3198): ignoring update request
,E/UpdateRequestReceiver( 3198): ignoring update request
,I/art     ( 1662): Explicit concurrent mark sweep GC freed 27739(1650KB) AllocSpace objects, 7(172KB) LOS objects, 25% free, 10MB/13MB, paused 1.092ms total 142.829ms
,E/UpdateRequestReceiver( 3198): ignoring update request
,W/SQLiteConnectionPool( 1662): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 1905): Post-init done
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/UpdateRequestReceiver( 3198): ignoring update request
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3256): MountEmulatedStorage()
,E/Zygote  ( 3256): v2
I/libpersona( 3256): KNOX_SDCARD checking this for 10094
I/libpersona( 3256): KNOX_SDCARD not a persona
,I/SELinux ( 3256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3256 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2180:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
I/DBG_POLICYDM( 3217): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
E/SELinux ( 3256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3217): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/Zygote  ( 3271): MountEmulatedStorage()
I/libpersona( 3271): KNOX_SDCARD checking this for 10009
E/Zygote  ( 3271): v2
I/libpersona( 3271): KNOX_SDCARD not a persona
,I/SELinux ( 3271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3271 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3271): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3217): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,D/TimaKeyStoreProvider( 3256): TimaSignature is unavailable
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,D/ActivityThread( 3256): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3217): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3165): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_DM  ( 3165): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_DM  ( 3165): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,D/TimaKeyStoreProvider( 3271): TimaSignature is unavailable
,D/ActivityThread( 3271): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,W/libprocessgroup( 1017): failed to open /acct/uid_10113/pid_2180/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3217): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/DBG_POLICYDM( 3217): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3217): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3217): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,D/BluetoothAdapter( 2603): disable()
,D/SettingsProvider( 1017): name = bluetooth_on
,D/elm:15183( 3256): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3256): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3256): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 3256): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.,
,D/elm:15183( 3256): ElmAgentService : onCreate()
,D/elm:15183( 3256): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 3256): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
V/EmergencyMode( 1416): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
D/elm:15183( 3256): BootCompletedState : startBootCompleted() call
,D/elm:15183( 3256): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3256): Get License : 0
D/elm:15183( 3256): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 1503:com.android.printspooler/u0a136 (adj 15): empty #31
,D/Finsky  ( 3150): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/EmergencyMode( 1416): [EmergencyBase] setBootTime
,V/EmergencyMode( 1416): [EmergencyFactory] No Recovery State, kill my self.
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 30
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: false pid=2603, uid=10174
D/SettingsProvider( 1017): name = wifi_on
,E/Zygote  ( 3308): MountEmulatedStorage()
,E/Zygote  ( 3308): v2
I/libpersona( 3308): KNOX_SDCARD checking this for 1000
I/libpersona( 3308): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3308 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/DBG_DM  ( 3165): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220,
I/SELinux ( 3308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3308): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
D/BluetoothAdapterState( 2739): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2739): Setting state to 13
,I/BluetoothAdapterState( 2739): Bluetooth adapter state changed: 12-> 13
W/ContextImpl( 3165): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
D/BluetoothAdapterService( 2739): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 2739): updateAdapterState state is 13
,I/jxcore-log( 2603): ****TEST TOOK:  5225  ms ****
I/jxcore-log( 2603): 
,I/jxcore-log( 2603): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2603): 
E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2131): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2131): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2131): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2131): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1017): failed to open /acct/uid_10136/pid_1503/cgroup.procs: No such file or directory
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
I/ServiceManager(  318): Waiting for service AtCmdFwd...
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
D/BluetoothAdapterService( 2739): Autoconnection is available 
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/BluetoothAdapterService( 2739): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2739): terminating service from this receiver
,I/BluetoothPbapService( 2739): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothSocket( 2739): close() in, this: android.bluetooth.BluetoothSocket@33bb61d4, channel: 19, state: LISTENING
D/BluetoothSocket( 2739): close() this: android.bluetooth.BluetoothSocket@33bb61d4, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@267861a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c8f6f7dmSocket: android.net.LocalSocket@14b8be72 impl:android.net.LocalSocketImpl@1adc02c3 fd:FileDescriptor[74]
D/BluetoothSocket( 2739): Closing mSocket: android.net.LocalSocket@14b8be72 impl:android.net.LocalSocketImpl@1adc02c3 fd:FileDescriptor[74]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3308): TimaSignature is unavailable
,D/ActivityThread( 3308): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,D/BluetoothAdapterProperties( 2739): onBluetoothDisable()
D/BluetoothAdapterProperties( 2739): mDiscovering is false
,D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
I/BluetoothAdapterState( 2739): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1662): Read error: ssl=0xb8939f30: I/O error during system call, Connection timed out
I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,V/NativeCrypto( 1662): SSL shutdown failed: ssl=0xb8939f30: I/O error during system call, Broken pipe
,I/DBG_POLICYDM( 3217): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-5ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
I/InputMethodManagerService( 1017): [BT Setting State] State =13
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 343 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
E/USB_UICC(  297): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  297): usb_uicc_init_qmi failed ! 
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
I/USB_UICC(  297): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  297): usb_uicc_cleanup, Issuing QMI deinit ... 
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/qtaguid ( 1017): Untagging socket 343
D/BluetoothUtils( 2739): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2739): Scan Mode:20
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false,
I/DBG_POLICYDM( 3217): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,D/BluetoothTile( 1174):  onBluetoothStateChange:
,I/DBG_POLICYDM( 3217): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,D/BluetoothTile( 1174): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1174):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1174):  getBluetoothState : 13
,D/BluetoothTile( 1174):  handleUpdatestate:false name:null,
I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0,
,I/DBG_DM  ( 3165): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/DBG_DM  ( 3165): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true,
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
E/DBG_POLICYDM( 3217): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524292
,D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/BluetoothTile( 1174):  handleUpdatestate:false name:null
,I/SamsungIME( 1788): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1174): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
D/TelephonyNetworkFactory( 1455): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/STATUSBAR-QSTileView( 1174): onStateChanged: Bluetooth
D/TelephonyNetworkFactory( 1455): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType(),
,D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
I/DBG_DM  ( 3165): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,D/OverheatReceiver( 1174): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1174): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1174): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1174): isSafeMode = false
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit,
V/NetworkStats( 1017): updateIfacesLocked()
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
I/DBG_DM  ( 3165): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 3ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BluetoothAdapterState( 2739): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2739): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2739): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/bt-btif ( 2739): cmd socket is not created
E/bt-btm  ( 2739): btm_ble_start_auto_conn start : 0, 0
D/btif_config_util( 2739): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 2739): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2739): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x001b not found for deregistration
,I/DBG_DM  ( 3165): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3165): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,I/DBG_DM  ( 3165): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
I/DBG_POLICYDM( 3217): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/WifiP2pService( 1017): InactiveState{ what=131204 }
D/WifiP2pService( 1017): P2pEnabledState{ what=131204 }
,I/DBG_DM  ( 3165): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,D/WifiP2pService( 1017): sending p2p connection changed broadcast: FAILED
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/Tethering( 1017): No numeric data
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/WifiScanningService( 1017): SCAN_AVAILABLE : 1
,D/WifiScanningService( 1017): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 1017): SCAN_AVAILABLE : 1
,I/CameraApp( 3308): CameraApp.onCreate()... mFeature : null
,D/RttService( 1017): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/testFeature( 3308): Feature.Feature(context)
,I/testFeature( 3308): Feature.readInternalDefaultXml()
E/Tethering( 1017): No numeric data
I/testFeature( 3308): ResetFeatureValue
I/ActivityManager( 1017): Killing 1682:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
,I/CameraFirmware_broadcast( 3308): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3308): CameraApp.getAppFeature()...
,D/WifiP2pService( 1017): sending p2p connection changed broadcast: DISCONNECTED
,E/ConnectivityService( 1017): updateNetworkInfo()
,E/WifiStateMachine( 1017): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
W/ContextImpl( 3165): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,E/Tethering( 1017): No numeric data
I/DBG_DM  ( 3165): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,D/WifiDisplayController( 1017): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1017): disconnect
D/WifiDisplayController( 1017): updateConnection
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/DBG_DM  ( 3165): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,E/Tethering( 1017): No numeric data
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,D/WifiP2pService( 1017): P2pDisablingState
D/WifiP2pService( 1017): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1017): p2p socket connection lost
I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
D/WifiP2pService( 1017): P2pDisabledState
,I/DBG_POLICYDM( 3217): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3217): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 1017): P2pDisabledState{ what=143375 }
,D/WifiP2pService( 1017): DefaultState{ what=143375 }
,D/Finsky  ( 3150): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,E/Zygote  ( 3349): MountEmulatedStorage()
E/Zygote  ( 3349): v2
I/libpersona( 3349): KNOX_SDCARD checking this for 10100
I/libpersona( 3349): KNOX_SDCARD not a persona
,I/SELinux ( 3349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3349 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2344:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
I/SELinux ( 3349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothSocket( 2739): close() in, this: android.bluetooth.BluetoothSocket@37288679, channel: 5, state: LISTENING
D/BluetoothSocket( 2739): close() this: android.bluetooth.BluetoothSocket@37288679, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3266db27, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@fd04fbemSocket: android.net.LocalSocket@1ef2081f impl:android.net.LocalSocketImpl@1281176c fd:FileDescriptor[76]
D/BluetoothSocket( 2739): Closing mSocket: android.net.LocalSocket@1ef2081f impl:android.net.LocalSocketImpl@1281176c fd:FileDescriptor[76]
,D/AllShareCastTile( 1174): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1174): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
,D/CommandListener(  278): Clearing all IP addresses on wlan0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,I/wpa_supplicant( 2131): p2p0: State: DISCONNECTED -> DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/TimaKeyStoreProvider( 3349): TimaSignature is unavailable
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityThread( 3349): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1174): Wifi onReceive(0)
D/STATUSBAR-QSTileView( 1174): onStateChanged: Wi-Fi
,D/HotspotTile( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1174): onReceive : 0, 0,
,D/WifiCredService( 1319): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2344/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_1682/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3329): 
D/AndroidRuntime( 3329): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,D/AndroidRuntime( 3329): CheckJNI is OFF
I/ActivityManager( 1017): Killing 2392:com.sec.android.omc/1000 (adj 15): empty #31
D/AndroidRuntime( 3329): readGMSProperty: start
D/AndroidRuntime( 3329): readGMSProperty: already setted!!
D/AndroidRuntime( 3329): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3329): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3329): readGMSProperty: end
D/AndroidRuntime( 3329): addProductProperty: start
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 2131): Blacklist: Clear (all) 
,I/bt_userial_mct( 2739): exiting userial_read_thread
D/bt_userial_mct( 2739): Leaving userial_evt_read_thread()
W/bt-l2cap( 2739): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2739): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2739): ag scb idx 1 not allocated
W/bt-btif ( 2739): ag scb idx 2 not allocated
E/bt-btif ( 2739): BTA AG is already disabled, ignoring ...
D/bt_userial_mct( 2739): userial_close_reader Joined userial reader thread: 0
,I/bt_vendor( 2739): hw_epilog_process
D/bt_userial_mct( 2739): userial_close
I/bt_vendor( 2739): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/[SBeam] ( 1319): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1319): SBeamEnabler.isSBeamSupported : EXIST
D/PackageIntentReceiver( 3349): ACTION_BOOT_COMPLETED
,E/Zygote  ( 3365): MountEmulatedStorage(),
E/Zygote  ( 3365): v2
I/libpersona( 3365): KNOX_SDCARD checking this for 1000
I/libpersona( 3365): KNOX_SDCARD not a persona
,I/SELinux ( 3365): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,D/PackageIntentReceiver( 3349): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,I/SELinux ( 3365): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3365): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/DBG_DM  ( 3165): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
I/ActivityManager( 1017): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3365 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2447:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
I/ActivityManager( 1017): Killing 2436:com.sec.tcpdumpservice/1000 (adj 15): empty #32
I/ActivityManager( 1017): Killing 2414:com.sec.modem.settings/1000 (adj 15): empty #33
,I/wpa_supplicant( 2131): p2p0: CTRL-EVENT-TERMINATING 
,I/Nat464Xlat( 1017): interfaceLinkStateChanged p2p0, false,
D/Tethering( 1017): interfaceLinkStateChanged p2p0, false
D/Tethering( 1017): interfaceStatusChanged p2p0, false
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2392/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Killing 2502:com.wsomacp/u0a25 (adj 15): empty #31
,I/DBG_DM  ( 3165): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,I/GoogleHttpClient( 1662): GMS http client unavailable, use old client
,E/Tethering( 1017): No numeric data
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Tethering( 1017): No numeric data
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3365): TimaSignature is unavailable
E/Tethering( 1017): No numeric data
,D/ActivityThread( 3365): Added TimaKeyStore provider
,E/Tethering( 1017): No numeric data,
I/wpa_supplicant( 2131): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 2131): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2131): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2131): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2131): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
E/Zygote  ( 3390): MountEmulatedStorage()
E/Zygote  ( 3390): v2
I/libpersona( 3390): KNOX_SDCARD checking this for 1000
I/libpersona( 3390): KNOX_SDCARD not a persona
I/SELinux ( 3390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/Tethering( 1017): InitialState.processMessage what=4
I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3390 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,E/Tethering( 1017): No numeric data
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/DBG_DM  ( 3165): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3165): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/AffinityControl( 3329): AffinityControl: registerfunction enter
,D/TimaKeyStoreProvider( 3390): TimaSignature is unavailable
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3165): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,E/Zygote  ( 3403): MountEmulatedStorage()
V/VibratorService( 1017): hasVibrator - useVibetonz: true
E/Zygote  ( 3403): v2
I/libpersona( 3403): KNOX_SDCARD checking this for 10012
I/SELinux ( 3403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3403): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3403 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 3403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3403): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityThread( 3390): Added TimaKeyStore provider,
,D/AndroidRuntime( 3329): Calling main entry com.android.commands.pm.Pm
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,W/NotificationAccessSettings( 1319): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
V/NetworkStats( 1017): performPollLocked() took 4ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{422482223}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/TimaKeyStoreProvider( 3403): TimaSignature is unavailable
,D/ActivityThread( 3403): Added TimaKeyStore provider
V/VibratorService( 1017): hasVibrator - useVibetonz: true
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/PackageManager( 1017): !@killApplicatoin: 10174, uninstall pkg
,I/bt_vendor( 2739): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2739): bluetooth satus is on
I/bt_vendor( 2739): bt-vendor : resetting BT status
I/bt_vendor( 2739): Starting hciattach daemon
I/bt_vendor( 2739): try to set false
,I/bt_vendor( 2739): Starting hciattach daemon
,I/bt_vendor( 2739): try to set false
,I/bt_vendor( 2739): cleanup
I/GKI_LINUX( 2739): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2739): GKI_exit_task 0 done
I/GKI_LINUX( 2739): GKI_shutdown(): task [BTU] terminated
,W/Settings( 3150): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3150): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2436/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2414/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_2447/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2131): Blacklist: Clear (all) 
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/PackageSettings( 1017): Skipping PackageSetting{334941a2 com.test.thalitest/10175} due to missing metadata
,V/AlarmManager( 1017): waitForAlarm result :4
,I/wpa_supplicant( 2131): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_2502/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 2603:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1017): Force removing ActivityRecord{2970446a u0 com.example.hello/.MainActivity t228}: app died, no saved state
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 2603
,W/ResourcesManager( 1319): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,I/DBG_FMMDM( 3365): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
W/ResourcesManager( 3403): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3403): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,I/DBG_FMMDM( 3365): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups,
,I/DBG_FMMDM( 3365): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,D/BluetoothAdapterState( 2739): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2739): isSecureModeOn:false
D/BluetoothAdapterService( 2739): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,I/DBG_FMMDM( 3365): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.gatt.GattService
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=0: pkg removed
,D/Launcher( 1486): onRestart, Launcher: 508115352
,I/MultiDex( 3403): VM with version 2.1.0 has multidex support
I/MultiDex( 3403): install
I/MultiDex( 3403): VM has multidex support, MultiDex support library is disabled.
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,D/ScoverManager( 1319): serviceVersion : 16908288
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BtGatt.DebugUtils( 2739): handleDebugAction() action=null
W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 2739): Received stop request...Stopping profile...
D/BtGatt.GattService( 2739): stop()
D/BtGatt.AdvertiseManager( 2739): advertise clients cleared
W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.hfp.HeadsetService
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3426): MountEmulatedStorage()
,E/Zygote  ( 3426): v2
I/libpersona( 3426): KNOX_SDCARD checking this for 1000
I/libpersona( 3426): KNOX_SDCARD not a persona
,I/SELinux ( 3426): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3426 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3426): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/Launcher( 1486): onStart, Launcher: 508115352
D/Launcher.HomeView( 1486): onStart
,D/Launcher( 1486): onResume, Launcher: 508115352,
E/SELinux ( 3426): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1017): name = kids_home_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/Launcher.HomeView( 1486): onResume
,D/Launcher( 1486): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/TimaKeyStoreProvider( 3426): TimaSignature is unavailable
,D/ActivityThread( 3426): Added TimaKeyStore provider
,E/SamsungIME( 1788): mOCRHelper is null
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3165): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/WifiStateMachine( 1017): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [21]
,D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,D/MenuAppsGridFragment( 1486): onResume
,D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1174): Wifi onReceive(1)
D/STATUSBAR-QSTileView( 1174): onStateChanged: Wi-Fi
,D/HotspotTile( 1174): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1174): onReceive : 1, 0
W/Settings( 1732): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiCredService( 1319): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1440): isKioskContainerExistOnDevice,
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1017): handle home activity for 0
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.hid.HidService
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,E/SMD     (  288): DCD OFF,
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 1486
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1486): log_dcs ThreadedRenderer::initialize entered! 
,I/ActivityManager( 1017): Killing 2557:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Launcher( 1486): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3445): MountEmulatedStorage(),
,I/libpersona( 3445): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3445): v2
,I/libpersona( 3445): KNOX_SDCARD not a persona
I/SELinux ( 3445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3445 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3445): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.hdp.HealthService
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.pan.PanService
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/RCPManagerService( 1017): PackageReceiver onReceive()
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
I/art     ( 1017): Explicit concurrent mark sweep GC freed 43405(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 26MB/40MB, paused 4.725ms total 268.927ms
,W/BluetoothAdapterService( 2739): Not skipping com.android.bluetooth.map.BluetoothMapService
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 2603 uid 10174
,D/BootupListener( 1455): intent.getAction() = android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/PhoneUtilsCommon( 1455): isSupportVoLTE is false.
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,W/BluetoothAdapterService( 2739): Not skipping com.broadcom.bt.service.sap.SapService
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/Volley  ( 3150): [383] DiskBasedCache.clear: Cache cleared.
I/PCWCLIENTTRACE_LOG( 3426): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3426): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3426): new DMDBOpenHelper instance
,D/TimaKeyStoreProvider( 3445): TimaSignature is unavailable
,D/ActivityThread( 3445): Added TimaKeyStore provider
I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,D/Volley  ( 3150): [376] DiskBasedCache.clear: Cache cleared.
,D/PackageManager( 1017): delete codoeFile: 
,V/JNIHelp ( 3403): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/AASA_removePackage( 1017): UID=10174 Target=com.example.hello
D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
,D/PackageManager( 1017): result of delete: 1{422482223}
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=228_task.xml
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
,D/RegisteredServicesCache( 1440): empty dynamic service
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1017): [SO] activate (ident=0xb8b645a8, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SamsungIME( 1788): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb8ca77a0, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/BluetoothAdapterService( 2739): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/AndroidRuntime( 3329): Shutting down VM
,W/BluetoothAdapterService( 2739): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/BluetoothAdapterService( 2739): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2739): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2739): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,D/PCWCLIENTTRACE_DMContentProvider( 3426): [URIMatcher] - result : 2
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,W/BluetoothAdapterService( 2739): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,D/BluetoothAdapterState( 2739): Stopping profile services that were post enabled
E/BluetoothAdapterService(804708012)( 2739): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/HeadsetService( 2739): Received stop request...Stopping profile...
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1017): Displayed Component not be shown by security: +468ms
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityThread( 3403): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3403): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37288679: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3403): Installed default security provider GmsCore_OpenSSL
,D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,I/ActivityManager( 1017): Killing 2575:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/ApplicationPolicy( 1017): updateDataUsageMap
,D/PanelView( 1174): There is/are notification(s) 
,W/ResourcesManager( 1455): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/A2dpService( 2739): Received stop request...Stopping profile...
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/A2dpStateMachine( 2739): Exit Disconnected: -1
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_FMMDM( 3365): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,I/DBG_FMMDM( 3365): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
I/DBG_FMMDM( 3365): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/KnoxSetupWizardDbHelper( 3445): dbMigrationFlag : false
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/HidService( 2739): Received stop request...Stopping profile...
D/HidService( 2739): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2739): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2739): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2739): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothA2dp( 2973): Proxy object disconnected
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3482): MountEmulatedStorage()
E/Zygote  ( 3482): v2
I/libpersona( 3482): KNOX_SDCARD checking this for 1000
I/libpersona( 3482): KNOX_SDCARD not a persona
,I/SELinux ( 3482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ShortcutReceiver( 3445):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/SELinux ( 3482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3482): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3482 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/KnoxShortcutUtil( 3445): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3445):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3445):  shortcut migration not required 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/HealthService( 2739): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,D/Finsky  ( 3150): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3150): [1] 2.run: Finished loading 1 libraries.
,I/Telecom ( 1428): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/TimaKeyStoreProvider( 3482): TimaSignature is unavailable
,D/ActivityThread( 3482): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,D/PanService( 2739): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2739): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff6deac,
D/Tethering( 1017): interfaceRemoved wlan0
,W/art     ( 3329): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/Tethering( 1017): attempting to remove unknown iface (wlan0), ignoring
,I/Telecom ( 1428): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3503): MountEmulatedStorage()
E/Zygote  ( 3503): v2,
I/libpersona( 3503): KNOX_SDCARD checking this for 1000
I/libpersona( 3503): KNOX_SDCARD not a persona
I/SELinux ( 3503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3503 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 8803(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 732us total 22.014ms
,D/Tethering( 1017): interfaceRemoved p2p0
,E/Tethering( 1017): attempting to remove unknown iface (p2p0), ignoring
,D/TimaKeyStoreProvider( 3503): TimaSignature is unavailable
,D/ActivityThread( 3503): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 20.023ms
,I/ActivityManager( 1017): Killing 2335:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 19.114ms
,D/BluetoothMapService( 2739): Received stop request...Stopping profile...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1662): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1662): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,D/SensorService( 1017): [SO] currT = 37631098000, prevT = 37181080000, diff = 450018000, [0.192 0.115 10.247]
D/SensorService( 1017): [SO] 0.192 0.115 10.247
D/SensorService( 1017): [SO] [100 -> 255]
,E/ClearcutLoggerIntentService( 1662): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1662): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1662): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1662): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearcutLoggerIntentService( 1662): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1662): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearcutLoggerIntentService( 1662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/ClearcutLoggerIntentService( 1662): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1662): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1662): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1662): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1662): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1662): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1662): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/Telecom ( 1428): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/Telecom ( 1428): InCallController: Unbinding from InCallService unbind
,D/Finsky  ( 3150): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/LockPatternUtils( 1319): isSmartCardAuthenticationAvailable: false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/DBG_DM  ( 3165): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/GAV2    ( 2799): Thread[GAThread,5,main]: No campaign data found.
,D/Settings_Utils( 1319): isSupportVNFestival SM-A500FU XEO
,I/DBG_FMMDS( 3482): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3482): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/Finsky  ( 3150): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSUser ( 1662): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,E/SQLiteLog( 3482): (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3482): Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
E/SQLiteDatabase( 3482): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3482): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3482): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 3482): 	at com.fmm.ds.db.XDBHelper.<init>(XDBHelper.java:32)
E/SQLiteDatabase( 3482): 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:254)
E/SQLiteDatabase( 3482): 	at com.fmm.ds.XDSApplication.xdsMakeDbHelper(XDSApplication.java:320)
E/SQLiteDatabase( 3482): 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:59)
E/SQLiteDatabase( 3482): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3482): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 3482): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 3482): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 3482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3482): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3482): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 3482): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3482): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3482): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 3482): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothA2dp( 1017): Proxy object disconnected
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 2

```
