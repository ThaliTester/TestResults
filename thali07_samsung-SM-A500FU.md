#### Test 50242285576d0b0_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/MmsConfig( 2324): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2324): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2324): isAuth is false
D/Mms/MmsConfig( 2324): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/TP/MmsSmsProvider( 1463): query,matched:2117, calling pid = 2324
D/TP/MmsSmsProvider( 1463): match 2117:Elapsed time : 2.077 ms
D/EasySignUpManager_1.0.1( 2324): isAuth is false
D/EasySignUpManager_1.0.1( 2324): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2324): mps_code.dat does not exist
E/CscParser( 2324): customer_path =/system/csc/customer.xml
E/CscParser( 2324): fileName + /system/csc/customer.xml
E/CscParser( 2324): mps_code.dat does not exist
E/CscParser( 2324): customer_path =/system/csc/customer.xml
E/CscParser( 2324): fileName + /system/csc/customer.xml
D/CscParser( 2324): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2324):  enable multiwindow = true
E/Mms/MessageUtils( 2324): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2324): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2324): [end]    init() consume time = 93.032761
D/Mms/Contact( 2324): [start]    init() consume time = 2.808021
D/Mms/Contact( 2324): [end]    init consume time = 7.978489
D/TP/MmsSmsProvider( 1463): query,matched:13, calling pid = 2324
D/TP/MmsSmsProvider( 1463): match 13:Elapsed time : 1.867 ms
D/Mms/DraftCache( 2324): [start]    rebuildCache consume time = 6.59625
D/Mms/MethodReflector( 2324): getSubId is called
D/Mms/TelephonyUtils( 2324): getLongSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 1463): query,matched:12, calling pid = 2324
D/TP/MmsSmsProvider( 1463): match 12:Elapsed time : 1.921 ms
D/Mms/MethodReflector( 2324): getTelephonyProperty is called
D/Mms/DownloadManager( 2324): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2324): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2324): auto download without roaming -> true
D/Mms/DownloadManager( 2324): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2324): getSubId is called
D/Mms/DraftCache( 2324): [end]    rebuildCache consume time = 12.492136
D/Mms/MethodReflector( 2324): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2324): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2324): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2324): getTelephonyProperty is called
D/Mms/DownloadManager( 2324): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2324): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2324): auto download without roaming -> true
D/Mms/DownloadManager( 2324): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2324): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2324): mAutoDownload ------> true
D/ComposerPerformance( 2324): 1449410946741 ms / [DONE] Composer constructor
D/Mms/Conversation( 2324): [start]    init() consume time = 19.43302
E/CII     ( 2324): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 2324): ReservationManager()
I/Mms/ReservationManager( 2324): resetAfterConnected()
D/Mms/ArtClassLoader( 2324): init [DONE] art
D/TP/MmsSmsDatabaseHelper( 1463): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1463): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1463): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1463): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1463): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1463): query,matched:7, calling pid = 2324
D/TP/MmsSmsProvider( 1463): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1463): match 7:Elapsed time : 2.710 ms
I/Mms/ReservationManager( 2324): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1463): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
D/Mms/MmsApp( 2324): [end]    onCreate() consume time = 19.472657
V/TP/MmsSmsDatabaseHelper( 1463): updateThread(), thread_id = 9223372036854775807
D/Mms/SmsReceiver( 2324): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
--------- beginning of system
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
V/TP/MmsSmsDatabaseHelper( 1463): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
I/splitIntent( 1019): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
D/Mms/DownloadManager( 2324): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 2324): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 2324): getSubId is called
D/Mms/TelephonyUtils( 2324): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2324): getTelephonyProperty is called
D/Mms/DownloadManager( 2324): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2324): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2324): auto download without roaming -> true
D/Mms/DownloadManager( 2324): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 2324): mAutoDownload ------> true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/TP/MmsSmsProvider( 1463): delete threadId: 9223372036854775807
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
D/TP/MmsSmsProvider( 1463): need read changed broadcast:false
D/Mms/Conversation( 2324): [end]    init consume time = 15.420416
D/Mms/MessagingNotification( 2324): [start]    init() consume time = 5.868907
D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/Mms/SmsReceiverService( 2324): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
D/Mms/TelephonyPermission( 2324): isDefault true
D/Mms/SmsReceiverService( 2324): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2324): handleSIMStatus()
D/Mms/SmsReceiverService( 2324): handleSIMStatus(): SIM_STATUS = ABSENT
D/Mms/MessagingNotification( 2324): [end]    init consume time = 4.007239
D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/Mms/SpamFilter( 2324): [start]    SpamFilter fill() begin consume time = 3.324896
D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/TP/MmsSmsProvider( 1463): query,matched:0, calling pid = 2324
V/TP/MmsSmsProvider( 1463): getSimpleConversations entered.
D/Mms/Synchronizer( 2324): [start]    doSync consume time = 1.905365
D/TP/MmsSmsProvider( 1463): match 0:Elapsed time : 1.872 ms
D/TP/MmsSmsProvider( 1463): query,matched:400, calling pid = 2324
D/TP/MmsSmsProvider( 1463): update, matched:300, calling pid = 2324
V/TP/MmsSmsProvider( 1463): syncDBData start
D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
V/TP/MmsSmsProvider( 1463): syncDBData sms end
V/TP/MmsSmsProvider( 1463): syncDBData mms end
D/Mms/SpamFilter( 2324): [end]    SpamFilter fill() finished consume time = 8.277395
V/TP/MmsSmsProvider( 1463): syncDBData end
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
D/Mms/Synchronizer( 2324): [end]    doSync consume time = 2.306407
D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1284): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1284): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/Mms/MessagingNotification( 2324): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1463): query,matched:26, calling pid = 2324
D/TP/SmsProvider( 1463): match 26:Elapsed time : 1.488 ms
D/TP/MmsSmsProvider( 1463): query,matched:6, calling pid = 2324
D/TP/MmsSmsProvider( 1463): match 6:Elapsed time : 1.995 ms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2424): MountEmulatedStorage()
I/libpersona( 2424): KNOX_SDCARD checking this for 10025
E/Zygote  ( 2424): v2
I/libpersona( 2424): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2424 uid=10025 gids={50025, 9997} abi=armeabi-v7a
D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/SELinux ( 2424): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
I/SELinux ( 2424): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
E/SELinux ( 2424): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2436): MountEmulatedStorage()
E/Zygote  ( 2436): v2
I/libpersona( 2436): KNOX_SDCARD checking this for 10020
I/libpersona( 2436): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2436 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 2436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2436): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2424): TimaSignature is unavailable
D/ActivityThread( 2424): Added TimaKeyStore provider
W/ResourcesManager( 2424): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2436): TimaSignature is unavailable
D/ActivityThread( 2436): Added TimaKeyStore provider
W/ResourcesManager( 2436): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2436): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2436): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/OMACP   ( 2424): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/Mms/Omacp( 2324): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 2424): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
V/VibratorService( 1019): hasVibrator - useVibetonz: true
D/EasySignUpManager_1.15.0305( 2436): serviceId : 0, features : -1
I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 1019): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1019): mCursor = null
D/SecContentProvider2( 1019): isCopyContactToSimAllowed = true
E/Zygote  ( 2459): MountEmulatedStorage()
E/Zygote  ( 2459): v2
I/libpersona( 2459): KNOX_SDCARD checking this for 10044
I/libpersona( 2459): KNOX_SDCARD not a persona
I/SELinux ( 2459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2459 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 2459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2459): TimaSignature is unavailable
D/ActivityThread( 2459): Added TimaKeyStore provider
E/Zygote  ( 2472): MountEmulatedStorage()
E/Zygote  ( 2472): v2
I/libpersona( 2472): KNOX_SDCARD checking this for 10054
I/libpersona( 2472): KNOX_SDCARD not a persona
I/SELinux ( 2472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2472 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
I/SELinux ( 2472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2472): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/SMD     (  288): DCD OFF
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2488): MountEmulatedStorage()
I/libpersona( 2488): KNOX_SDCARD checking this for 10142
E/Zygote  ( 2488): v2
I/libpersona( 2488): KNOX_SDCARD not a persona
W/ResourcesManager( 2459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2488 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 2459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SELinux ( 2488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ResourcesManager( 2459): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2459): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2459): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2459): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SELinux ( 2488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1491, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
E/SELinux ( 2488): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/USB_UICC(  296): Timeout! No signal received. Retry num = 22
D/TimaKeyStoreProvider( 2472): TimaSignature is unavailable
D/ActivityThread( 2472): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 2488): TimaSignature is unavailable
D/ActivityThread( 2488): Added TimaKeyStore provider
W/ResourcesManager( 2472): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
V/TaskCloserActivity( 2488): TaskCloserActivity enter()
W/art     ( 2436): Verification of void com.android.contacts.common.list.l.P() took 119.639ms
V/TaskCloserActivity( 2488): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/Recents_RecreateReceiver( 2472): onReceive by home
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2505): MountEmulatedStorage()
E/Zygote  ( 2505): v2
I/libpersona( 2505): KNOX_SDCARD checking this for 10139
I/libpersona( 2505): KNOX_SDCARD not a persona
I/SELinux ( 2505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2505 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/SELinux ( 2505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2505): TimaSignature is unavailable
,D/ActivityThread( 2505): Added TimaKeyStore provider
W/ResourcesManager( 2505): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2505): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2505): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2505): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2505): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/AbsListView( 2436): Get MotionRecognitionManager
D/MotionRecognitionService( 1019):  ssp status : false
D/NearbySource( 2459): Nearby Source Create!
D/NearbyContext( 2459): Nearby Context Create!
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2459): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 2459): Samsung link source created
D/AndroidRuntime( 2520): 
D/AndroidRuntime( 2520): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2520): CheckJNI is OFF
D/AndroidRuntime( 2520): readGMSProperty: start
D/AndroidRuntime( 2520): readGMSProperty: already setted!!
D/AndroidRuntime( 2520): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2520): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2520): readGMSProperty: end
D/AndroidRuntime( 2520): addProductProperty: start
D/ContactProvider( 2459): getAllContactInfoList Start
E/SQLiteLog( 1230): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider( 2459): getAllContactInfoList End
I/syncContacts( 2459): thread: 253, sync time = 43
D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/GalleryCacheReady( 2459): Receive : home resume
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 2324): ui event
I/splitIntent( 1019): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/BootupListener( 1463): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1019): name = internet_call_settings_visibility
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1001
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/PhoneUtilsCommon( 1463): isSupportVoLTE is false.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/StatusChecker( 2294): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2294): onReceive : net.mt.init : DONE
D/StatusChecker( 2294): Service state changed : 3 mSub-1
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
E/AffinityControl( 2520): AffinityControl: registerfunction enter
W/ResourcesManager( 1660): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1660): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 1660): VM with version 2.1.0 has multidex support
I/MultiDex( 1660): install
I/MultiDex( 1660): VM has multidex support, MultiDex support library is disabled.
D/AndroidRuntime( 2520): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/JNIHelp ( 1660): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/Launcher.HomeView( 1491): onPause
W/ActivityManager( 1019): mDVFSHelper.acquire()
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/FocusedStackFrame( 1019): Set to : 0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1491
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
D/AndroidRuntime( 2520): Shutting down VM
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, iello
E/Zygote  ( 2537): MountEmulatedStorage()
E/Zygote  ( 2537): v2
I/libpersona( 2537): KNOX_SDCARD checking this for 10174
I/libpersona( 2537): KNOX_SDCARD not a persona
I/SELinux ( 2537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2537 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2537): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1491): updateVisibility : ActivityRecord{ec4b873 token=android.os.BinderProxy@20e03ed1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityThread( 1660): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 1660): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2820b351: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1660): Installed default security provider GmsCore_OpenSSL
D/TimaKeyStoreProvider( 2537): TimaSignature is unavailable
D/ActivityThread( 2537): Added TimaKeyStore provider
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1491): onStop
V/ActivityThread( 1491): updateVisibility : ActivityRecord{ec4b873 token=android.os.BinderProxy@20e03ed1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/Launcher( 1491): onTrimMemory. Level: 20
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
W/SQLiteConnectionPool( 1660): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
V/UserPresentBroadcastReceiver( 1748): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
I/WebViewFactory( 2537): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/LibraryLoader( 2537): Time to load native libraries: 1 ms (timestamps 9077-9078)
I/LibraryLoader( 2537): Expected native library version number "",actual native library version number ""
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/art     ( 2520): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/WebViewChromiumFactoryProvider( 2537): Binding Chromium to main looper Looper (main, tid 1) {967347a}
,I/LibraryLoader( 2537): Expected native library version number "",actual native library version number ""
,I/chromium( 2537): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/BrowserStartupController( 2537): Initializing chromium process, singleProcess=true
,W/art     ( 2537): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SysUtils( 2537): ApplicationContext is null in ApplicationStatus
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1660): COMPAT: Multi user not supported
W/chromium( 2537): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/USB_UICC(  296): Timeout! No signal received. Retry num = 23
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/chromium( 2537): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2537): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2537): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2537): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2537): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2537): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2537): Local Branch: 
I/Adreno-EGL( 2537): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2537): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2537):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothAdapter( 2537): 270802502: getState() :  mService = null. Returning STATE_OFF
,I/GCM     ( 1660): GCM config loaded
,D/GCM     ( 1660): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/8)
D/AuthorizationBluetoothService( 1660): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/8)
,W/art     ( 2537): Attempt to remove local handle scope entry from IRT, ignoring
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10012
,W/AwContents( 2537): onDetachedFromWindow called when already detached. Ignoring
,D/a       ( 1660): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PhoneWindow( 2537): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 2537): *FMB* installDecor flags : 8456448
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1660): (283) recovered 36 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
,V/GmsCoreStatsServiceLauncher( 1929): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/SystemWebViewEngine( 2537): CordovaWebView is running on device made by: samsung
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Scheduler( 1660): Use PeriodicScheduler
,W/art     ( 2537): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2537): Attempt to remove local handle scope entry from IRT, ignoring
,W/InstanceID/Rpc( 1660): Found 10012
,D/OpenGLRenderer( 2537): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/chromium( 2537): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 2537): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2537): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/InputDispatcher( 1019): Focus entered window: 2537
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2537): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2537): Initialized EGL, version 1.4
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/OpenGLRenderer( 2537): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2537): Enabling debug mode 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 2048): callingUid 10012, callindPid: 2048
,I/Mms/MmsApp( 2324):  start initViewCache mms
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/Mms/ComposeMessageFragment( 2324): [start]    fillCache consume time = 1970.998853
D/Mms/ComposeMessageFragment( 2324): fillCache, easy = false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1180): There is/are notification(s) 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Displayed Component not be shown by security: +843ms
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{3c8606a5 u0 com.example.hello/.MainActivity t228} time:29730
W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 2537): Timeline: Activity_idle id: android.os.BinderProxy@756a4f6 time:29735
,I/SamsungIME( 1780): getCurrentCandidateView
,E/GmsWearableLS( 1748): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1748): [184] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/SamsungIME( 1780): Dismiss ExpandCandiate
,I/SamsungIME( 1780): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1780): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1780): KeybaordView init() : load resources
,W/BindingManager( 2537): Cannot call determinedVisibility() - never saw a connection for the pid: 2537
,I/SamsungIME( 1780): getCurrentKeyboard
I/SamsungIME( 1780): getTextKeyboard
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 39500(2MB) AllocSpace objects, 3(162KB) LOS objects, 33% free, 25MB/38MB, paused 2.380ms total 171.347ms
,D/SamsungIME( 1780): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/chromium( 2537): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  256): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  256): id=10 Removed iello (-2/8)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 1929
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1463): match 0:Elapsed time : 11.368 ms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1463): Query uri=content://mms, match=0, calling pid = 1929
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1929): Restart initialization of location
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 1929
,D/TP/SmsProvider( 1463): match 0:Elapsed time : 1.515 ms
,D/TP/MmsProvider( 1463): Query uri=content://mms, match=0, calling pid = 1929
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/JsMessageQueue( 2537): Set native->JS mode to OnlineEventsBridgeMode
,D/AbsListView( 2324): Get MotionRecognitionManager
,D/MotionRecognitionService( 1019):  ssp status : false
,D/Mms/ComposeMessageFragment( 2324): [end]    fillCache consume time = 426.033542
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,E/AndroidProtocolHandler( 2537): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 24
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/BubbleViewCache( 2324): fillCache bubble = 1
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1284): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1284): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/jxcore_app_log( 2537): JniHelper::setJavaVM(0xb7e0f450), pthread_self() = -1204382472
D/JX-Cordova( 2537): jxcore cordova android initializing
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
D/daemonapp( 1284): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
E/daemonapp( 1284): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
D/daemonapp( 1284): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
W/ActivityManager( 1019): userId = 0, bbcId = -10000
E/daemonapp( 1284): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
D/daemonapp( 1284): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/AdaptiveEventManager( 1180): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/AdaptiveEventManager( 1180): currentCityId is null
D/AdaptiveEventManager( 1180): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1180): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1180): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1180): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1180): mWeatherInfo is not reliable
,E/Zygote  ( 2613): MountEmulatedStorage()
E/Zygote  ( 2613): v2
I/libpersona( 2613): KNOX_SDCARD checking this for 10135
I/libpersona( 2613): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2613 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 2613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
I/SELinux ( 2613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2613): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1449410949485
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1449432549482
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1449432540000
D/daemonapp( 1284): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449432540000
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
W/jxcore-log( 2537): Initializing JXcore engine
W/jxcore-log( 2537): JXcore engine is ready
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1449432540000
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/jxcore-log( 2537): Starting JXcore engine
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2613): TimaSignature is unavailable,
D/ActivityThread( 2613): Added TimaKeyStore provider
,E/Zygote  ( 2628): MountEmulatedStorage()
,E/Zygote  ( 2628): v2,
I/libpersona( 2628): KNOX_SDCARD checking this for 1000
I/libpersona( 2628): KNOX_SDCARD not a persona
,I/SELinux ( 2628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2628): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2628 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ResourcesManager( 2613): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/art     (  306): Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 21.917ms
,W/ResourcesManager( 2613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 2613): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/audit   ( 1848): type=1400 msg=audit(1449410949.563:203): avc:  denied  { ioctl } for  pid=2537 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1848):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1848): type=1300 msg=audit(1449410949.563:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=bea5bd58 items=0 ppid=306 ppcomm=main pid=2537 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1848): type=1320 msg=audit(1449410949.563:203): 
,D/TimaKeyStoreProvider( 2628): TimaSignature is unavailable
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.178ms
,D/ActivityThread( 2628): Added TimaKeyStore provider
,V/AlarmManager( 1019): waitForAlarm result :4
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 17.890ms
,D/SecurityLogAgent( 2628):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2628):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2628):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2628): FileZippingService : onHandleIntent 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2628): FileZippingService : file path =  /data/misc/audit/audit.old
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SecurityLogAgent( 2628): FileZippingService : onPremise disabled. Zipping..  
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : createZip
,W/jxcore-log( 2537): Platform android
W/jxcore-log( 2537): 
,W/jxcore-log( 2537): Process ARCH arm
W/jxcore-log( 2537): 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : Not empty 
,E/Zygote  ( 2647): MountEmulatedStorage()
,I/libpersona( 2647): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2647): v2
I/libpersona( 2647): KNOX_SDCARD not a persona
,I/SELinux ( 2647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
D/SecurityLogAgent( 2628): DenialLogFileZipCreator : Files exceeded the max limit 
,E/SELinux ( 2647): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2647 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/SecurityLogAgent( 2628): DenialLogFileZipCreator File existence : true audit.old file size 631
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,D/SecurityLogAgent( 2628): FileZippingService : completed task. Returning wakelock . 
,D/TimaKeyStoreProvider( 2647): TimaSignature is unavailable
,D/ActivityThread( 2647): Added TimaKeyStore provider
,I/jxcore-log( 2537): JXcore Cordova bridge is ready!
I/jxcore-log( 2537): 
,W/jxcore-log( 2537): JXcore engine is started
,W/ResourcesManager( 2647): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/jxcore-log( 2537): >> samsung-SM-A500FU,
E/jxcore-log( 2537): 
I/jxcore-log( 2537): Total memory 1983787008
I/jxcore-log( 2537): 
,I/jxcore-log( 2537): Free memory 255197184
I/jxcore-log( 2537): 
I/jxcore-log( 2537): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2537): 
I/jxcore-log( 2537): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2537): 
,I/jxcore-log( 2537): userPath [ 'rList-com.example.hello.MainActivity', 'www' ],
I/jxcore-log( 2537): 
,I/jxcore-log( 2537): Size 720 1280
I/jxcore-log( 2537): 
I/jxcore-log( 2537): Screen Brightness 5
I/jxcore-log( 2537): 
,E/jxcore-log( 2537): Dummy Error Log.
E/jxcore-log( 2537): 
,D/FactoryTestApp( 2647): [FactoryTestBroadcastReceiver$onReceive](2647) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2647): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2647): [XMLDataStorage$parseXML](2647) is Live Demo : false
,D/FactoryTestApp( 2647): [XMLDataStorage$parseXML](2647) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2647): [XMLDataStorage$parseXML](2647) deviceXML=a5ulte.dat
,D/FactoryTestApp( 2647): [XMLDataStorage$parseXML](2647) nameXML=a5ultexx.dat
,D/FactoryTestApp( 2647): [XMLDataStorage$parseAsset](2647) parseAsset Is Started
,I/FactoryTestApp( 2647): [XMLDataStorage$parseAsset](2647) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2647): [XMLDataStorage$parseAsset](2647) Decode base file: factory.dat
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=FACTORY_TEST_APP
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=FAILHIST_VERSION
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=MODEL_NAME
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=MODEL_NUMBER
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=CHIPSET_MANUFACTURE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=CHIPSET_NAME
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=DEVICE_TYPE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=BATT_TYPE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=PANEL_TYPE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SENSOR_NAME_MAGNETIC,
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SPEAKER_COUNT,
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=MIC_COUNT
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TORCH_MODE_FLASH_ON_CURRENT
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_LTE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_DUAL_STANBY_ONE_CP
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_RCV
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=FACTORY_TEST_APO
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_EPEN
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_CAM_ISP
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_CAM_FRONT_NOT_ISP
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_SECOND_MIC_TEST
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=NEED_CAMDRIVER_OPEN
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=HW_VER_EFS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_AUTO_WAKELOCK
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_DSDS_MSIMM_CHECK
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=FONT_SIZE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=RAM_SIZE_IF
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=MULTI_TSK_THD
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SEMI_FUNCTION_FONT_SIZE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_FM_RADIO
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_DISABLE_SCROLLING_CACHE
D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_TEST_POWER
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_TEST_HOME
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_TEST_BACK
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_GEOMAGNETIC_ALPS_CAL,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=GEOMAGNETIC_IC_POINT,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=AT_GPSSTEST
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=AT_BATTEST_RESET_WHEN_READ,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SUPPORT_CHARGE_COUNT,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=PA0_TEMP_ADC,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=PA1_TEMP_ADC,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=NEED_ACK_FOR_CAMERA_STOP,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=HALL_IC_TEST
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=READ_TARGET_GEOMAGNETIC
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_SELFTEST_MIN_MELFAS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_SELFTEST_MAX_MELFAS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=BOOTLOADER_VERSION
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=BATTERY_TEST_MODE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=BATTERY_VF_OCV
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_COMMAND_CMD,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=TSP_COMMAND_RESULT,
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=KEY_PRESSED_POWER
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=LPA_MODE_SET
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2647): [XMLDataStorage$redefinitionById](2647) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2647): [XMLDataStorage$parseAsset](2647) SemiFunctionMenu
,D/FactoryTestApp( 2647): [XMLDataStorage$parseAsset](2647) parseAsset Is Completed
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2647): [ModuleCommon$ModuleCommon](2647) Create ModuleCommon
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2647): [Support$Kernel.read](2647) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2647): [ModuleCommon$readFactoryMode](2647) mode: ON
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2647): [FactoryTestBroadcastReceiver$onReceive](2647) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2647): [Support$Values.getBoolean](2647) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 2647): [Support$Properties.get](2647) property=ro.factory.factory_binary
D/FactoryTestApp( 2647): [FactoryTestBroadcastReceiver$onReceive](2647) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2647): [ModuleCommon$getFtClientEnableState](2647) result : false
,I/FactoryTestApp( 2647): [ModuleCommon$connectedJIG](2647) ...
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2647): [ModuleCommon$connectedJIG](2647) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2647): [Support$Kernel.read](2647) path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 2647): [ModuleCommon$connectedJIG](2647) value = 1f, JIG_ON = 1C
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2647): [ModuleCommon$isConnectionModeNone](2647) mConnectionMode = gsm
I/FactoryTestApp( 2647): [ModuleCommon$isRunningFtClient](2647) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2647): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2647) start DummyFtClient service for APO
,W/ContextImpl( 2647): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2647): User mode
,I/FactoryTestApp( 2647): [ModuleCommon$disableFtClient](2647) ...
,D/FactoryTestApp( 2647): [DummyFtClient$onCreate](2647) Create DummyFtClient service
,I/FactoryTestApp( 2647): [XMLDataStorage$parsingXML](2647) FtClient => data parsing was completed.
D/FactoryTestApp( 2647): [DummyFtClient$onReceive](2647) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2647): [ModuleCommon$isConnectionModeNone](2647) mConnectionMode = gsm
,D/FactoryTestApp( 2647): [Support$Values.getBoolean](2647) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2647): [DummyFtClient$onStartCommand](2647) ...
,I/WifiService( 1019): android.intent.action.BOOT_COMPLETED
,E/SMD     (  288): DCD OFF
,D/UsbDeviceManager( 1019): boot completed
,D/UsbDeviceManager( 1019): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1019): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1019): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/UsbDeviceManager( 1019): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,I/KeyguardEffectViewUtil( 1180): set resource id
,D/SettingsProvider( 1019): name = keyguard_default_wallpaper_res_id,
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed,
D/SettingsProvider( 1019): selectionArgs: false,
D/SettingsProvider( 1019): selectionArgs: 10054
E/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
D/SettingsProvider( 1019): ret = -1
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BOOT_COMPLETED
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
,D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
I/PalmMotion( 1019): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1019): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1019): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1019): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH,
,D/SamsungIME( 1780): showDlgMsgBox : false true true
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,D/NfcService( 1445): call the applyRouting
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 25
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 2670): MountEmulatedStorage()
E/Zygote  ( 2670): v2
I/libpersona( 2670): KNOX_SDCARD checking this for 1000
I/libpersona( 2670): KNOX_SDCARD not a persona
,I/SELinux ( 2670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1019): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2670 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/RecoverySystem( 1019): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1019): No recovery log file
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 2537): getBuffer is called!!!!
I/jxcore-log( 2537): 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,V/OtaStartupReceiver( 1463): onOtaspChanged: mOtaspMode=1
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2670): TimaSignature is unavailable
,D/ActivityThread( 2670): Added TimaKeyStore provider
,E/RecoverySystem( 1019): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1019): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1019): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,E/Zygote  ( 2688): MountEmulatedStorage(),
E/Zygote  ( 2688): v2
I/libpersona( 2688): KNOX_SDCARD checking this for 1001
,I/ActivityManager( 1019): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2688 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 2688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 2688): KNOX_SDCARD not a persona
D/Reset_Reason( 1019): resetString = NPON
,I/SELinux ( 2688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BootReceiver( 1019): Copying audit failures to DropBox
I/BootReceiver( 1019): Checking for fsck errors
,D/TimaKeyStoreProvider( 2688): TimaSignature is unavailable
,D/ActivityThread( 2688): Added TimaKeyStore provider
,E/File    ( 2670): fail readDirectory() errno=2
,W/ResourcesManager( 2688): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,D/FactoryTestApp( 2647): [ProtectedFactoryTestBroadcastReceiver$onReceive](2647) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2647): [ProtectedFactoryTestBroadcastReceiver$onReceive](2647) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2647): User mode
D/Mms/NotificationReceiver( 2324): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
D/Mms/NotificationReceiver( 2324): handleBootCompleted()
,D/Mms/RcsOwnCapsManager( 2324): queue Uri = content://im/queue-messages?box=pending
,D/TP/ImProvider( 1463): im query match24
,D/TP/ImProvider( 1463): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1463): ftSesstionId must be a long.
D/TP/ImProvider( 1463): getQueuedImMessages
,D/TP/ImProvider( 1463): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/NotificationReceiver( 2324):  getPendingMessageIds: no pending messages.
,D/Mms/ActionsFactory( 2324): Call to GET_LAST_MESSAGES_SENT
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SettingsProvider( 1019): name = db_smartlock_supported
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/AccessibilityManagerService( 1019): setmDNIeNegative (false)
,D/SensorService( 1019): [SO] 0.153 0.115 10.190
,W/Settings( 1307): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1019): name = block_emergency_message
,D/SettingsProvider( 1019): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/SmartFaceService( 1019): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1019): no icon
E/SmartFaceService( 1019): mActiveServiceType: 0
E/SmartFaceService( 1019): mLightIntensityEnough: true mLux: 0.0
,D/Stay/Rotation Worker( 1019): updateClientsDone. def. do nothing.
E/SmartFaceService( 1019): Service Type to Worker: 0
E/SmartFaceService( 1019): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1019): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/RCPManagerService( 1019): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1019):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
D/RCPManagerService( 1019): BootReceiver.onReceive(): Starting RCP Proxy for user = null
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
E/RCPManagerService( 1019):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,V/AlarmManagerEXT( 1019): mGmsLocationBundling: false
,D/SensorService( 1019): [SO] activate (ident=0xb8664160, enabled=0),
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1019): [SO] changed settle time [0]
,D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb87555c8, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/EnterpriseDeviceManagerService( 1019): android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1019): runAdminUpdate
,D/EnterpriseUtils( 1019): File Not Found : /data/system/selfUpdateAdmin.conf
,V/ApplicationPolicy( 1019): boot completed - refreshWidgetStatus
,V/ApplicationPolicy( 1019): refresh widget status for user 0
D/EnterpriseDeviceManagerService( 1019): nothing to selfUpdate
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.email
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.vending
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,W/PhoneRestrictionPolicy( 1019): Message received - msg { when=0 what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1019): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,W/PhoneRestrictionPolicy( 1019):  >>>> deliveryBlockedMsgs
,I/KnoxMUMContainerPolicy( 1019): MSG_REMOVE_ORPHANED_CONTAINERS received
,D/WifiP2pService( 1019): P2pDisabledState{ what=143415 }
,D/WifiP2pService( 1019): DefaultState{ what=143415 }
,D/ConnectivityService( 1019): Got NetworkFactory Messenger for WIFI_P2P
,W/PhoneRestrictionPolicy( 1019): cvList size 0
W/PhoneRestrictionPolicy( 1019):  >>>> deliveryBlockedMsgs
D/WIFI_P2P( 1019): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/ConnectivityService( 1019): Got NetworkFactory Messenger for WIFI
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/WifiStateMachine( 1019): Blacklist file delete
,W/PhoneRestrictionPolicy( 1019): cvList size 0
,D/Tethering( 1019): Boot complete.
,V/EnterpriseBillingEngine( 1019): ACTION_BOOT_COMPLETED
,V/EnterpriseBillingEngine( 1019): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1019): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1019): getCurrentActiveProfiles - end - null
,V/EnterpriseBillingEngine( 1019): handleAllprofiles - end
,D/UsbHostNotification( 1019): boot completed
,D/UsbHostRestrictor( 1019): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1019): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1019): SIM was never inserted
,D/UsbHostRestrictor( 1019): writableHostSysNode[false]
,D/UsbHostRestrictor( 1019): Can NOT Write Disable Sys Node to [ON]
,D/PersonaManagerService( 1019): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1019):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/KnoxKeyguardUpdateMonitor( 1019): onBootComplete
,D/UsbStorageNotification( 1019): boot completed
,I/KnoxKeyguardUpdateMonitor( 1019): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1019): onTrustChanged user:0, enable:false
,D/KeyguardViewMediator( 1180): onTrustChanged( Showing = false , userId = 0 )
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,D/GpsLocationProvider_ex( 1019): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1019): set_capabilities_callback: 55u
,D/qmi_secgps_clnt( 1019): qmi_secgps_client_init()
,I/libmdmdetect( 1019): ESOC framework not supported
,I/libmdmdetect( 1019): Found internal modem: modem
E/PerMgrLib( 1019): Peripheral manager is not supported on this device
,E/Geofence_Adapter( 1019): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,E/Geofence_Adapter( 1019): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1019): BOOT_COMPLETED native_cleanup 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,D/StorageNotification( 1180): boot completed
,D/WIFI    ( 1019): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,D/qmi_secgps_clnt( 1019): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,D/qmi_secgps_clnt( 1019): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2,
,D/StatusBarManagerService( 1019): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ),
D/qmi_secgps_clnt( 1019): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,D/PhoneStatusBar( 1180): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2726): MountEmulatedStorage(),
I/libpersona( 2726): KNOX_SDCARD checking this for 10099
E/Zygote  ( 2726): v2
I/libpersona( 2726): KNOX_SDCARD not a persona,
I/SELinux ( 2726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2726 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 2726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2726): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/i       ( 1019): No model
,D/FactoryTest( 1019): Not factory mode,
D/w       ( 1019): isUserBuild = true
D/FactoryTest( 1019): Not factory mode. isFactoryMode() returend false
,D/TimaKeyStoreProvider( 2726): TimaSignature is unavailable
,D/ActivityThread( 2726): Added TimaKeyStore provider
,D/SSRM:n  ( 1019): SIOP:: AP = 370
,E/LocSvc_utils_cfg( 1019): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,D/SSRM:a  ( 1019): DeviceInfo:: 000000000000
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
D/SSRM:a  ( 1019): SettingsAirViewInfo:: 000000000
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1019): SECGPS: Set AGPS Mode : 7
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/qmi_secgps_clnt( 1019): SECGPS: send a qmi message to secgps_server OK
,D/SensorService( 1019): [SO] activate (ident=0xb87555c8, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1019): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1019): [SO] changed settle time [1]
,D/SensorService( 1019): [SO] setDelay [66000000]
,D/SensorService( 1019): [SO] activate (ident=0xb87555c8, enabled=1)
,D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1019): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
I/qmi_secgps_clnt( 1019): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1019): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1019): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1019): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1019): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1019): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1019): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1019): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1019): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
D/SensorService( 1019): [SO] currT = 32101092000, prevT = 31711033000, diff = 390059000, [0.153 0.096 10.209]
D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,E/LocSvc_ApiV02( 1019): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,E/ActivityThread( 2726): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2726): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1019): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
,I/splitIntent( 1019): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/DrmEventReceiver( 1019): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1019): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1019): DrmEventReceiver : beginStartingService
I/System.out( 1019): start Service
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1019): [SO] currT = 32176665000, prevT = 31711033000, diff = 465632000, [0.172 0.077 10.190]
,D/SensorService( 1019): [SO] 0.172 0.077 10.190
D/SensorService( 1019): [SO] [100 -> 255]
,W/CursorWrapperInner( 2324): Cursor finalized without prior close()
,V/DownloadManager( 1230): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2746): MountEmulatedStorage(),
E/Zygote  ( 2746): v2
,I/libpersona( 2746): KNOX_SDCARD checking this for 10085
I/libpersona( 2746): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2746 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 2746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 2753): MountEmulatedStorage()
I/libpersona( 2753): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2753): v2
I/libpersona( 2753): KNOX_SDCARD not a persona
I/SELinux ( 2753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2753 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/USB_UICC(  296): Timeout! No signal received. Retry num = 26
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/SELinux ( 2753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2753): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2746): TimaSignature is unavailable
,D/ActivityThread( 2746): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2753): TimaSignature is unavailable
,D/ActivityThread( 2753): Added TimaKeyStore provider
D/SecContentProvider2( 1019): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1019): mCursor = null
,D/MediaScannerReceiver( 1230): action: android.intent.action.BOOT_COMPLETED
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onInitialize : 2015
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onSetOnInfoListener : add 2015
,W/art     ( 2389): Suspending all threads took: 11.922ms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,I/DrmEventService( 1019): action event :android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/TimaServiceEventReceiver( 1019): TimaServiceEventReceiver : onReceive
,I/ANDROID_DRM_FRWORKS_DrmManager(  281): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,W/ResourcesManager( 2746): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 2746): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2746): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2746): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2746): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/CscReceiver( 1463): onReceive android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2781): MountEmulatedStorage(),
,E/Zygote  ( 2781): v2
,I/libpersona( 2781): KNOX_SDCARD checking this for 10160
I/libpersona( 2781): KNOX_SDCARD not a persona
,I/SELinux ( 2781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2781 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
I/SELinux ( 2781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/SELinux ( 2781): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2793): MountEmulatedStorage()
,E/Zygote  ( 2793): v2
I/libpersona( 2793): KNOX_SDCARD checking this for 10003
I/libpersona( 2793): KNOX_SDCARD not a persona
,I/SELinux ( 2793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2793 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/SELinux ( 2793): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2781): TimaSignature is unavailable,
,D/ActivityThread( 2781): Added TimaKeyStore provider
,D/CscUpdateService( 1463): onStart
E/CscUpdateService( 1463): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1463): set_CSC_version
,E/CscParser( 1463): update(): xml file exist
,I/CscUtil ( 1463): isWifiOnly = false
,I/System.out( 1463): HandDataNode = null
I/CscUpdateService( 1463): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1463): This is normal boot : CSC not updated
,W/ResourcesManager( 2781): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2793): TimaSignature is unavailable
,D/ActivityThread( 2793): Added TimaKeyStore provider
,E/CscParser( 1463): update(): xml file exist
D/MediaScannerService( 1230): !@start scanning volume internal: [/system/media, /oem/media]
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/CscGPS  ( 1463): CSCGPS.updateParameters
D/CscGPS  ( 1463): supl host : null
D/CscGPS  ( 1463): SUPL Host is null or invalid
D/CscGPS  ( 1463): supl_ver : null
D/CscGPS  ( 1463): SUPL Ver is null or invalid
D/CscGPS  ( 1463): supl port : null
D/CscGPS  ( 1463): SUPL PORT is null or invalid
D/CscGPS  ( 1463): LPP : null
D/CscGPS  ( 1463): LPP is null or invalid
D/CscGPS  ( 1463): CSC don't have any AGPS value.
,D/MtpService( 1230): updating state; isCurrentUser=true, mMtpLocked=false
,D/[0]UMC:UMCContentProvider( 2781): @onCreate
,D/TP/MmsProvider( 1463): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1463): update , handleReadChangedBroadcast
,D/TP/MmsSmsProvider( 1463): need read changed broadcast:false
,I/Mms:transaction( 2324): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2324): [start]    nonBlockingUpdateMessageIndicator() consume time = 2392.039009
,I/Mms/ReservationManager( 2324): resetAfterConnected()
,D/TP/MmsSmsProvider( 1463): query,matched:7, calling pid = 2324
,D/Mms/MessagingNotification( 2324): sDisableVibrateForCamera = false
,D/TP/MmsSmsProvider( 1463): match 7:Elapsed time : 3.309 ms
,D/Mms/TelephonyPermission( 2324): isDefault true
,I/CscUpdateService( 1463): same CSC Version
,D/CscUtil ( 1463): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
D/TP/MmsProvider( 1463): Query uri=content://mms, match=0, calling pid = 2324
,I/Mms/ReservationManager( 2324): getReservedSendMessageCount(): retMessageCount=0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/[0]UMC:Core( 2781): onCreate(): 
,D/[0]UMC:Core( 2781): @isManagedProfileUser
D/[0]UMC:Core( 2781): userId: 0
,D/[0]UMC:Core( 2781): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2781): userInfo.isManagedProfile() : false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2793): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
E/Zygote  ( 2818): MountEmulatedStorage(),
E/Zygote  ( 2818): v2
I/libpersona( 2818): KNOX_SDCARD checking this for 10048
I/libpersona( 2818): KNOX_SDCARD not a persona
,I/SELinux ( 2818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2818 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,I/SELinux ( 2818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,E/SELinux ( 2818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,D/[0]UMC:DeviceInfo( 2781): USA==US==
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/TP/MmsSmsProvider( 1463): query,matched:200, calling pid = 2324
,D/TP/MmsSmsProvider( 1463): match 200:Elapsed time : 1.512 ms
D/Mms/SmsReceiverService( 2324): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,D/Mms/TelephonyPermission( 2324): isDefault true
,D/Mms/SmsReceiverService( 2324): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2324): [start]    handleBootCompleted() consume time = 63.466354
,D/TimaKeyStoreProvider( 2818): TimaSignature is unavailable
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 2818): Added TimaKeyStore provider
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2793): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  341): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2793
I/SecureStorage(  341): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
,I/SecureStorage( 2793): [INFO]: SPID(0x00000000)SS Daemon is running
I/libpersona( 2835): KNOX_SDCARD checking this for 1000
I/SecureStorage( 2793): [INFO]: SPID(0x00000000)Processing data
I/libpersona( 2835): KNOX_SDCARD not a persona
E/Zygote  ( 2835): MountEmulatedStorage()
E/Zygote  ( 2835): v2
,I/SecureStorage(  341): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2793
I/SecureStorage(  341): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
I/SELinux ( 2835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2835 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SQLiteLog( 1230): (283) recovered 332 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,E/SELinux ( 2835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1463): getThreadUnReadCount unreadCount=0 imUnreadCount=0
,D/TP/MmsSmsProvider( 1463): deleteConversation threadId: 9223372036854775806
,D/TimaKeyStoreProvider( 2835): TimaSignature is unavailable
,D/ActivityThread( 2835): Added TimaKeyStore provider
,D/SettingsProvider( 1019): name = next_alarm_formatted
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10085
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/TP/MmsSmsProvider( 1463): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1463): updateThread(), thread_id = 9223372036854775806
W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,W/ResourcesManager( 2818): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 2818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2818): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,V/TP/MmsSmsDatabaseHelper( 1463): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1463): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1463): need read changed broadcast:false
,D/USER_AGENT( 2781): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,D/Mms/Conversation( 2324): deleteTempConversation(),deleted=0
,D/[0]UMC:AdminManager( 2781): init - start
,D/[0]UMC:AdminManager( 2781): loadAdmins
,D/SettingsProvider( 1019): name = block_emergency_message
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10048
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/ActivityManager( 1019): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/MediaScanner( 1230): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/SSRM:a  ( 1019): DeviceInfo:: 000000000000
D/SSRM:a  ( 1019): SettingsAirViewInfo:: 000000000
,D/[0]UMC:AdminManager( 2781): init - end
,D/GSLBManager( 2781): migrateStoredUrlFromOldPref
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,I/WifiCredService( 1307): onCreate
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 44434(2MB) AllocSpace objects, 34(954KB) LOS objects, 33% free, 26MB/39MB, paused 2.501ms total 163.191ms
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 2324
,D/TP/SmsProvider( 1463): match 0:Elapsed time : 3.131 ms
,V/MediaScanner( 1230): processDirectory :  /system/media
,D/WifiTimerReceiver( 1307): action: android.intent.action.BOOT_COMPLETED
,D/WifiTimerReceiver( 1307): extra: Bundle[mParcelledData.dataSize=84]
,D/TP/SmsProvider( 1463): query,matched:51, calling pid = 2324
,D/TP/SmsProvider( 1463): match 51:Elapsed time : 1.481 ms
,D/MY_TAG  ( 1307): Action boot completed received
,D/SmsProvider( 1463): Update uri=content://sms/outbox, match=8
,D/Mms/MessagingNotification( 2324): isBlockingModeEnabled() = false, Zen mode = 0
,E/SQLiteLog( 2835): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,D/TP/MmsSmsProvider( 1463): need read changed broadcast:false
,D/BadgeProvider( 1566): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/Mms/SmsReceiverService( 2324): moveOutboxMessagesToFailedBox messageCount: 0
,D/NearbySettings( 1307): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1307): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 1307): MountReceiver.onReceive - Create mPrefHandler
,D/Mms/SmsReceiverService( 2324): handle boot completed, sendFirstQueuedMessage()
,D/Mms/SmsReceiverService( 2324): [SIM-1]sendFirstQueuedMessage()
,D/DSM     ( 2835): [Lines:107] Normal booted
D/DSM     ( 2835): [Lines:114] Boot completed
,D/GSLBManager( 2781):  key : segd-api
D/GSLBManager( 2781):  value : https://eu-segd-api.secb2b.com:443/v2
,W/art     ( 2746): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 138.879ms
,D/BadgeProvider( 1566): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 1566): sendNotify, [notify] : null
D/BadgeProvider( 1566): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1566): update, [BadgeCount] : badgecount=0
V/MediaScanner( 1230):  prescan time: 318ms (DB items: 141)
V/MediaScanner( 1230):     scan time: 116ms (Caching mode: true), (makeEntry time: 60ms ~51%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1230): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1230):    total time: 434ms
V/MediaScanner( 1230): checked files: 133  directories : 6  (I: 0, U: 0)
,D/BadgeProvider( 1566): update, [UpdateCount] : 1
,D/MediaScanner( 1230): checkDefaultSounds
D/MediaScanner( 1230): system alarm_alert  : Vwiurug_etwofi5wgg
,D/Launcher.Model( 1491): reloadBadges entered.
,D/GSLBManager( 2781):  key : umc-cdn
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1019): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,D/Mms/MessagingNotification( 2324): setBadgeCount(), count=0
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,D/Mms/MessagingNotification( 2324): remove alarm
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/GSLBManager( 2781):  value : 
,E/Zygote  ( 2860): MountEmulatedStorage()
E/Zygote  ( 2860): v2
I/libpersona( 2860): KNOX_SDCARD checking this for 1000
I/libpersona( 2860): KNOX_SDCARD not a persona,
I/SELinux ( 2860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/NearbySettings( 1307): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1307): MountReceiver.onReceive - Internal Path
E/SELinux ( 2860): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MediaScanner( 1230): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 1230): system notification_sound  : K_Oprkltf5wgg
,D/TP/SmsProvider( 1463): query,matched:26, calling pid = 2324
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/ActivityManager( 1019): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2860 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TP/SmsProvider( 1463): match 26:Elapsed time : 14.481 ms
,D/GSLBManager( 2781):  key : segp-api
D/GSLBManager( 2781):  value : 
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 2324
,D/MediaScanner( 1230): OK. notification_sound is already exist in setting DB.
,D/TP/SmsProvider( 1463): match 0:Elapsed time : 4.687 ms
D/MediaScanner( 1230): system ringtone  : Wmfi_lpf_pwirywu5wgg
,I/art     (  306): Explicit concurrent mark sweep GC freed 8775(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 656us total 32.692ms
,D/MediaScanner( 1230): OK. ringtone is already exist in setting DB.
,D/TimaKeyStoreProvider( 2860): TimaSignature is unavailable
,D/ActivityThread( 2860): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 2324): updateAllHistoryAsRead()
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.015ms
D/SettingsProvider( 1019): name = personal_mode_enabled
,D/GSLBManager( 2781):  key : myknoxapi
D/GSLBManager( 2781):  value : 
,D/MediaScannerService( 1230): !@done scanning volume internal
,W/ResourcesManager( 2860): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2647): [DummyFtClient$mBroadcastReceiver](2647) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2647): [DummyFtClient$mBroadcastReceiver](2647) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2647): [DummyFtClient$mBroadcastReceiver](2647) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 18.651ms
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 38900(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/12MB, paused 952us total 48.501ms
D/GSLBManager( 2781): migrateStoredUrlFromOldPref : Finished Migrating
D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2781): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2781): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2781): isContainer : 0
D/MediaScannerService( 1230): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/Mms/SmsReceiver( 2324): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2324): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2324): isDefault true
,D/Mms/MessagingNotification( 2324): [end]    nonBlockingUpdateMessageIndicator() consume time = 434.565052
,D/EnterpriseDeviceManagerService( 1019): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2781): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2781): isContainer : 0
,D/TP/MmsProvider( 1463): Query uri=content://mms, match=0, calling pid = 2324
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
W/ActivityThread( 2860): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdmin - UMC App Admin deactivated
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter finished
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/MediaScanner( 1230): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/[0]UMC:GuardService( 2781): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,D/[0]UMC:CoreReceiver( 2781): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2781):  check PreETag 
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat,
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
D/TP/MmsSmsProvider( 1463): query,matched:200, calling pid = 2324
I/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat,
,D/TP/MmsSmsProvider( 1463): match 200:Elapsed time : 7.093 ms
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,V/MediaScanner( 1230): processDirectory :  /storage/emulated/0
W/ResourcesManager( 1463): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/MediaScanner( 1230): Skipping:
D/MediaScanner( 1230): 7klwibgf7fvntblfd7(75ebcf7
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 2324
,D/MediaScanner( 1230): Skipping:
D/MediaScanner( 1230): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/[0]UMC:CoreReceiver( 2781): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2781): Enter loadList
,D/[0]UMC:CoreReceiver( 2781): handleAutoEnrollmentAndUMCAdminDeactivation
,D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2781): Admin not found in package com.samsung.knoxpb.mdm
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
E/[0]UMC:Utils( 2781): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2781): isContainer : 0
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,V/MediaScanner( 1230): processDirectory :  /storage/extSdCard
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
W/MediaScanner( 1230): Error opening directory, reason : Permission denied.
W/MediaScanner( 1230): 7klwibgf7fxlKdCbid7
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/TP/SmsProvider( 1463): match 0:Elapsed time : 34.129 ms
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 2860): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,D/EnterpriseDeviceManagerService( 1019): isManagedProfileUser(): userId = 0
V/MediaScanner( 1230):  prescan time: 37ms (DB items: 27)
I/SmartcardBootCompleteReceiver( 1307): SmartcardBootCompleteReceiver - onReceive() 
V/MediaScanner( 1230):     scan time: 31ms (Caching mode: true), (makeEntry time: 22ms ~70%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
I/SmartcardBootCompleteReceiver( 1307): Received intent with action - android.intent.action.BOOT_COMPLETED
V/MediaScanner( 1230): postscan time: 25ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1230):    total time: 93ms
I/LcdtestApp( 2860): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
V/MediaScanner( 1230): checked files: 10  directories : 17  (I: 0, U: 0)
,E/[0]UMC:UMCAdmin( 2781): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2781): isContainer : 0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdmin - UMC App Admin deactivated
,D/TP/SmsProvider( 1463): query,matched:51, calling pid = 2324
D/[0]UMC:ByodSetupStarter( 2781): Container ID : 0
,E/Zygote  ( 2883): MountEmulatedStorage()
E/Zygote  ( 2883): v2
I/libpersona( 2883): KNOX_SDCARD checking this for 1000
I/libpersona( 2883): KNOX_SDCARD not a persona
,I/SELinux ( 2883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/TP/SmsProvider( 1463): match 51:Elapsed time : 8.816 ms
E/SELinux ( 2883): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2883 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 1191:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,V/[0]UMC:Utils( 2781): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2781): shutdown
D/MediaScannerService( 1230): !@done scanning volume external
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 27
,E/Zygote  ( 2898): MountEmulatedStorage()
E/Zygote  ( 2898): v2
I/libpersona( 2898): KNOX_SDCARD checking this for 1000
I/libpersona( 2898): KNOX_SDCARD not a persona
,I/SELinux ( 2898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2898 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/TimaKeyStoreProvider( 2883): TimaSignature is unavailable
D/ActivityThread( 2883): Added TimaKeyStore provider
I/ActivityManager( 1019): Killing 1404:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,E/SELinux ( 2898): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2781): @GuardService - stopService Result = true
,D/FactoryTestApp( 2647): [DummyFtClient$mBroadcastReceiver](2647) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,D/FactoryTestApp( 2647): [DummyFtClient$mBroadcastReceiver](2647) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,D/FactoryTestApp( 2647): [DummyFtClient$sendBootCompletedAndFinish](2647) ...
D/FactoryTestApp( 2647): [Support$Values.getString](2647) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2647): [ModuleCommon$isConnectionModeNone](2647) mConnectionMode = gsm
D/FactoryTestApp( 2647): [IPCWriterToSecPhoneService$ResponseWriter](2647) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2647): [IPCWriterToSecPhoneService$connectToSecPhoneService](2647)  
,W/ContextImpl( 2647): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
I/art     ( 2781): System.exit called, status: 0
I/AndroidRuntime( 2781): VM exiting with result code 0, cleanup skipped.
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/iu.UploadsManager( 1929): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400,
,D/TimaKeyStoreProvider( 2898): TimaSignature is unavailable
I/SmartcardBootCompleteReceiver( 1307): Broadcast sent with current lockscreen type
D/ActivityThread( 2898): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 2324): isBlockingModeEnabled() = false, Zen mode = 0
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_1191/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_1404/cgroup.procs: No such file or directory
,I/FactoryTestApp( 2647): [IPCWriterToSecPhoneService$onServiceConnected](2647) connected done
D/FactoryTestApp( 2647): [IPCWriterToSecPhoneService$write](2647) Send Response Message to SecPhone
D/FactoryTestApp( 2647): [IPCWriterToSecPhoneService$write](2647) Response ��
,D/AT_Distributor(  310): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
W/ResourcesManager( 2898): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2647): [IPCWriterToSecPhoneService$handleMessage](2647) Send BOOTING COMPLETED done
,D/[SBeam] ( 1307): SBeamEnabler.initPreferenceForSbeam : 0
,D/BadgeProvider( 1566): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/SettingSearch/SearchIntentReceiver( 1307): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1307): search setting db init!!
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,I/SettingSearch/SearchIntentReceiver( 1307): BOOT_COMPLETED call InitSerachDBThread thread start!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2920): MountEmulatedStorage()
I/libpersona( 2920): KNOX_SDCARD checking this for 10086
E/Zygote  ( 2920): v2
I/libpersona( 2920): KNOX_SDCARD not a persona
I/SELinux ( 2920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2920 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 2920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2920): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/SecureStorage(  341): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,E/Zygote  ( 2933): MountEmulatedStorage()
E/Zygote  ( 2933): v2
I/libpersona( 2933): KNOX_SDCARD checking this for 1000
I/libpersona( 2933): KNOX_SDCARD not a persona
,I/SELinux ( 2933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/AT_Distributor(  310): SetAtdStatus(), 1_1_0,
D/AT_Distributor(  310): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/TimaKeyStoreProvider( 2920): TimaSignature is unavailable
,I/SELinux ( 2933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityThread( 2920): Added TimaKeyStore provider
,E/SELinux ( 2933): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1019): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2933 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2781)(adj 0) has died(154,1021)
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 1566): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1566): sendNotify, [notify] : null
D/BadgeProvider( 1566): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1566): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1566): update, [UpdateCount] : 1
D/Launcher.Model( 1491): reloadBadges entered.
,E/Zygote  ( 2950): MountEmulatedStorage()
I/libpersona( 2950): KNOX_SDCARD checking this for 10150
,E/Zygote  ( 2950): v2
I/libpersona( 2950): KNOX_SDCARD not a persona
,I/SecureStorage( 2793): [INFO]: SPID(0x00000001)Processing data has been completed
I/SELinux ( 2950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SecureStorage( 2793): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
I/ActivityManager( 1019): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2950 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 2933): TimaSignature is unavailable
,D/ActivityThread( 2933): Added TimaKeyStore provider
I/SELinux ( 2950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2950): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/MessagingNotification( 2324): setBadgeCount(), count=0
,I/iu.UploadsManager( 1929): End new media; added: 0, uploading: 0, time: 207 ms
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/DIAGMON_AGENT( 2883): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/Mms/MessagingNotification( 2324): remove alarm
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1284): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1284): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/Mms/MessagingNotification( 2324): updateAllHistoryAsRead()
,D/SettingsProvider( 1019): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10162
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,D/TimaKeyStoreProvider( 2950): TimaSignature is unavailable
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/ActivityThread( 2950): Added TimaKeyStore provider
,W/ResourcesManager( 2933): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 2324
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/TP/SmsProvider( 1463): match 0:Elapsed time : 5.985 ms
,E/daemonapp( 1284): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/SmsReceiverService( 2324): [end]    handleBootCompleted() consume time = 571.797396
,I/ActivityManager( 1019): Killing 1390:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1449410952657
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1449432540000
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/daemonapp( 1284): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449432540000
,E/UpdateRequestReceiver( 2920): ignoring update request
,E/UpdateRequestReceiver( 2920): ignoring update request
,E/UpdateRequestReceiver( 2920): ignoring update request
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 69
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1449432540000
,W/libprocessgroup( 1019): failed to open /acct/uid_10096/pid_1390/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 2920): ignoring update request
,E/UpdateRequestReceiver( 2920): ignoring update request
,D/comdaemonstockapp( 1284): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1284): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/FOTA    ( 2933): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,E/UpdateRequestReceiver( 2920): ignoring update request
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2980): MountEmulatedStorage(),
E/Zygote  ( 2980): v2
I/libpersona( 2980): KNOX_SDCARD checking this for 10094
I/libpersona( 2980): KNOX_SDCARD not a persona
,I/SELinux ( 2980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=2980 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,W/ContextImpl( 1856): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
E/SELinux ( 2980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 1566:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1856): Service started flags 0 startId 1
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/SecUISvc( 1856): Thread created.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2933): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true,
,E/Zygote  ( 2996): MountEmulatedStorage()
I/libpersona( 2996): KNOX_SDCARD checking this for 10028
E/Zygote  ( 2996): v2
I/libpersona( 2996): KNOX_SDCARD not a persona
I/SELinux ( 2996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2996 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 2933): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/SELinux ( 2996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2996): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2933): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,D/TimaKeyStoreProvider( 2980): TimaSignature is unavailable
,D/ActivityThread( 2980): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2996): TimaSignature is unavailable
D/ActivityThread( 2996): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 2883): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 2883): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 2883): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,I/DIAGMON_AGENT( 2883): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2883): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 2883): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup( 1019): failed to open /acct/uid_10072/pid_1566/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2933): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 2933): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED,
D/elm:15183( 2980): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 2980): ELMEngine.ELMEngine( context ).
,D/elm:15183( 2980): MDMBridge.setEnterpriseBridge()
I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 2980): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,V/EmergencyMode( 1421): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/OverheatReceiver( 1180): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1180): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1180): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1180): isSafeMode = false
,D/BootupListener( 1463): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/elm:15183( 2980): ElmAgentService : onCreate()
D/SettingsProvider( 1019): name = internet_call_settings_visibility
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1001
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/PhoneUtilsCommon( 1463): isSupportVoLTE is false.
D/elm:15183( 2980): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 2980): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 2980): BootCompletedState : startBootCompleted() call
,D/elm:15183( 2980): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 2980): Get License : 0
D/elm:15183( 2980): ElmAgentService : onDestroy().
,I/Telecom ( 1436): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/ActivityManager( 1019): Killing 1716:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,I/DBG_DM  ( 2933): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,I/DBG_DM  ( 2933): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 2933): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 2933): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,I/DBG_DM  ( 2933): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2933): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/Telecom ( 1436): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 2933): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2933): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 2933): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
E/Zygote  ( 3017): MountEmulatedStorage()
E/Zygote  ( 3017): v2
I/libpersona( 3017): KNOX_SDCARD checking this for 10012
I/libpersona( 3017): KNOX_SDCARD not a persona
,I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,I/SELinux ( 3017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3017): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3017 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
V/EmergencyMode( 1421): [EmergencyBase] setBootTime
V/EmergencyMode( 1421): [EmergencyFactory] No Recovery State, kill my self.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3017): TimaSignature is unavailable
,D/ActivityThread( 3017): Added TimaKeyStore provider
E/Zygote  ( 3028): MountEmulatedStorage()
I/libpersona( 3028): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3028): v2
I/libpersona( 3028): KNOX_SDCARD not a persona
,I/SELinux ( 3028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3028): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 2933): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
I/ActivityManager( 1019): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3028 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ContextImpl( 2933): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/Telecom ( 1436): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,I/Telecom ( 1436): InCallController: Unbinding from InCallService unbind
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3017): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3017): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3028): TimaSignature is unavailable
I/libpersona( 3047): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3047): MountEmulatedStorage()
I/libpersona( 3047): KNOX_SDCARD not a persona
E/Zygote  ( 3047): v2
I/SELinux ( 3047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityThread( 3028): Added TimaKeyStore provider
,I/SELinux ( 3047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3047): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3047 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/MultiDex( 3017): VM with version 2.1.0 has multidex support
I/MultiDex( 3017): install
I/MultiDex( 3017): VM has multidex support, MultiDex support library is disabled.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2933): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,E/Zygote  ( 3061): MountEmulatedStorage()
E/Zygote  ( 3061): v2
I/libpersona( 3061): KNOX_SDCARD checking this for 10003
I/libpersona( 3061): KNOX_SDCARD not a persona
,I/SELinux ( 3061): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3061): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3061): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3061 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3047): TimaSignature is unavailable
D/ActivityThread( 3047): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10138/pid_1716/cgroup.procs: No such file or directory
,D/PackageManager( 1019): [MSG] MCS_UNBIND
,I/ActivityManager( 1019): Killing 1549:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/art     (  306): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 720us total 28.323ms
,V/JNIHelp ( 3017): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/audio_hw_primary(  283): adev_get_parameters: enter: keys - call_forwarding
,D/audio_hw_extn(  283): audio_extn_get_parameters: returns 
V/msm8974_platform(  283): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  283): adev_get_parameters: exit: returns - call_forwarding=false
,I/str_params(  283): key: 'call_forwarding' value: ''
,V/InCall  ( 1866): ProximitySensor -  - screenonImmediately: false
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 771us total 19.040ms
V/InCall  ( 1866): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1866): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/TimaKeyStoreProvider( 3061): TimaSignature is unavailable
,D/ActivityThread( 3061): Added TimaKeyStore provider
D/ScoverManager( 1866): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1866): InCallUtils - isCoverClosed false
,I/Telecom ( 1436): ProximitySensorManager: Proximity wake lock already released
D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1866): InCallUtils - isCoverClosed false
,I/InCall  ( 1866): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1866): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1866): InCallPresenter -  - dismissCoverDialog()...
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 19.312ms
,I/ActivityManager( 1019): Killing 2115:com.vlingo.midas/u0a31 (adj 15): empty #31
,E/SMD     (  288): DCD OFF
,I/InCall  ( 1866): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1866): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,W/ActivityThread( 3017): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3017): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2016b265: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3017): Installed default security provider GmsCore_OpenSSL
,D/PhoneStatusBarView( 1180): setCallBackground:0
,D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1866): InCallUtils - isCoverClosed false
,E/BluetoothHeadset( 2793): BTStateChangeCB is registed
,D/BluetoothHeadset( 2793): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 2793): BluetoothHeadset service is binded
,I/CameraApp( 3047): CameraApp.onCreate()... mFeature : null
I/testFeature( 3047): Feature.Feature(context)
I/testFeature( 3047): Feature.readInternalDefaultXml()
I/testFeature( 3047): ResetFeatureValue
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 28
,I/CameraFirmware_broadcast( 3047): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3047): CameraApp.getAppFeature()...
,D/BluetoothA2dp( 2793): doBind(): CallingUid(myUserHandle) = 0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1019): failed to open /acct/uid_10031/pid_2115/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10057/pid_1549/cgroup.procs: No such file or directory
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/Zygote  ( 3081): MountEmulatedStorage()
I/libpersona( 3081): KNOX_SDCARD checking this for 10100
E/Zygote  ( 3081): v2
I/libpersona( 3081): KNOX_SDCARD not a persona
I/SELinux ( 3081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3081 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2142:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 2157:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,I/DBG_DM  ( 2933): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,D/TimaKeyStoreProvider( 3081): TimaSignature is unavailable
D/ActivityThread( 3081): Added TimaKeyStore provider
,D/VideoCallManager( 1866): Instantiating VideoCallManager
,E/        ( 1866): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1866): took 2.407604ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1866): took 5.359218ms for 0*0 texture 0
,I/GFX raster( 1866): took 11.685103ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1866): Bitmap=0xb81b4380 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb81b3c50 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1866): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,D/PackageIntentReceiver( 3081): ACTION_BOOT_COMPLETED
,I/Adreno-EGL( 1866): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1866): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1866): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1866): Local Branch: 
I/Adreno-EGL( 1866): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1866): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1866):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/PackageIntentReceiver( 3081): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,I/GFX GPU raster( 1866): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1866): took 0.267343ms for 320*61440 texture 37809
,I/draw setup( 1866): took 10.255625ms for 320*240 texture 37809
E/GFX GPU raster( 1866): drawn
,I/GFX GPU raster ASTC( 1866): took 39.595313ms for 320*240 texture 12
I/GFX raster( 1866): took 39.670106ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1866): Bitmap=0xb81b4300 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb81b3e68 counterpartCT=4 counterpartW=320 counterparth=240
,E/        ( 1866): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1866): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1866): took 0.310729ms for 480*122880 texture 37813
I/draw setup( 1866): took 0.628906ms for 480*640 texture 37813
E/GFX GPU raster( 1866): drawn
,D/UserAnalysis.PlaceProvider( 3061): PlaceProvider onCreate()
,I/GFX GPU raster ASTC( 1866): took 6.723593ms for 480*640 texture 12
I/GFX raster( 1866): took 6.804687ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1866): Bitmap=0xb81b3e68 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb83e1518 counterpartCT=4 counterpartW=480 counterparth=640
,E/        ( 1866): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1866): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1866): took 0.463073ms for 440*116864 texture 37809
I/draw setup( 1866): took 0.946927ms for 440*330 texture 37809
E/GFX GPU raster( 1866): drawn
,W/libprocessgroup( 1019): failed to open /acct/uid_10050/pid_2142/cgroup.procs: No such file or directory
,I/GFX GPU raster ASTC( 1866): took 5.395208ms for 440*330 texture 12
I/GFX raster( 1866): took 5.473907ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1866): Bitmap=0xb83e5770 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb83e5b30 counterpartCT=4 counterpartW=440 counterparth=330
,W/libprocessgroup( 1019): failed to open /acct/uid_10113/pid_2157/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2933): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 14070(752KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.825ms total 147.571ms
,E/Tethering( 1019): No numeric data
,I/ActivityManager( 1019): Killing 1506:com.android.printspooler/u0a136 (adj 15): empty #31
,I/DBG_DM  ( 2933): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/UserAnalysis.SecureDbManager( 3061): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3061): SecurePlaceDbHelper() 
D/UserAnalysis( 3061): Create SecureDbHelper
,E/        ( 1866): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1866): eglCreateImageKHR: EGL_SUCCESS
,D/BluetoothAdapter( 2793): 716613376: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2793): 716613376: getState() :  mService = null. Returning STATE_OFF
I/glCompressedTexImage2D( 1866): took 0.434531ms for 480*163840 texture 37811
,D/BluetoothAdapter( 2793): 716613376: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2793): 716613376: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2793): 716613376: getState() :  mService = null. Returning STATE_OFF
I/draw setup( 1866): took 0.738072ms for 480*640 texture 37811
E/GFX GPU raster( 1866): drawn
I/DBG_DM  ( 2933): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2933): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/GFX GPU raster ASTC( 1866): took 5.818071ms for 480*640 texture 12
I/GFX raster( 1866): took 5.902916ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1866): Bitmap=0xb8425140 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb83e12d0 counterpartCT=4 counterpartW=480 counterparth=640
,E/Tethering( 1019): No numeric data
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,E/Tethering( 1019): No numeric data
,E/Tethering( 1019): No numeric data
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3104): MountEmulatedStorage(),
I/libpersona( 3104): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3104): v2
I/libpersona( 3104): KNOX_SDCARD not a persona
I/SELinux ( 3104): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/GoogleHttpClient( 1660): GMS http client unavailable, use old client
,I/SELinux ( 3104): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/Tethering( 1019): No numeric data
,E/Tethering( 1019): No numeric data
,E/SELinux ( 3104): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/        ( 1866): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1866): took 2.117968ms for 0*0 texture 0
,E/Zygote  ( 3114): MountEmulatedStorage()
E/Zygote  ( 3114): v2
I/libpersona( 3114): KNOX_SDCARD checking this for 10009
I/libpersona( 3114): KNOX_SDCARD not a persona
,I/SELinux ( 3114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/GFX generate_partition_tables( 1866): took 7.514009ms for 0*0 texture 0
,I/SELinux ( 3114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/GFX raster( 1866): took 11.653072ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1866): Bitmap=0xb83e56f0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb83ded30 counterpartCT=4 counterpartW=176 counterparth=144
E/SELinux ( 3114): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1019): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3114 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/IntelligenceServiceApplication( 3061): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3061): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3104): TimaSignature is unavailable
D/ActivityThread( 3104): Added TimaKeyStore provider
,E/Zygote  ( 3138): MountEmulatedStorage(),
I/libpersona( 3138): KNOX_SDCARD checking this for 10060
E/Zygote  ( 3138): v2
I/libpersona( 3138): KNOX_SDCARD not a persona
I/SELinux ( 3138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 3114): TimaSignature is unavailable
,D/ActivityThread( 3114): Added TimaKeyStore provider
,I/SELinux ( 3138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3138): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3138 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 1683:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,W/libprocessgroup( 1019): failed to open /acct/uid_10136/pid_1506/cgroup.procs: No such file or directory
,E/        ( 1866): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1866): took 2.397083ms for 0*0 texture 0
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/GFX generate_partition_tables( 1866): took 6.303855ms for 0*0 texture 0
,I/GFX raster( 1866): took 10.835104ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1866): Bitmap=0xb83ded98 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb83def20 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1866): registerListener
,D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1019): registerListenerCallback : binder = android.os.BinderProxy@252e67f2, pid : 1866, uid : 1001, type : 1
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3028): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,D/IntelligenceServiceApplication( 3061): no applications having user consent for prediction
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
D/InCall  ( 1866): InCallPresenter -  - Finished InCallPresenter.setUp
I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,D/TimaKeyStoreProvider( 3138): TimaSignature is unavailable
I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,D/ActivityThread( 3138): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 3028): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,W/libprocessgroup( 1019): failed to open /acct/uid_10015/pid_1683/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3028): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 3061): [PlaceDetection::stopService] Service stopped.
,I/ActivityManager( 1019): Killing 2307:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/sCloudBackupApp( 3138): sCloudBackupApp Version Info : 4.04.8.KK_APP
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3159): MountEmulatedStorage()
E/Zygote  ( 3159): v2
I/libpersona( 3159): KNOX_SDCARD checking this for 10062
I/libpersona( 3159): KNOX_SDCARD not a persona
,D/[SBeam] ( 1307): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1307): SBeamEnabler.isSBeamSupported : EXIST
I/SELinux ( 3159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3159): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3159 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 2341:com.sec.android.omc/1000 (adj 15): empty #31
,V/PlaceDetection v1.0.19 ( 3061): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3061): Constructor Preference
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3159): TimaSignature is unavailable
,D/ActivityThread( 3159): Added TimaKeyStore provider
E/Tethering( 1019): No numeric data
,E/Tethering( 1019): No numeric data
,E/Tethering( 1019): No numeric data
,D/Finsky  ( 2996): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/Zygote  ( 3182): MountEmulatedStorage()
E/Zygote  ( 3182): v2
I/libpersona( 3182): KNOX_SDCARD checking this for 1000
I/libpersona( 3182): KNOX_SDCARD not a persona
I/SELinux ( 3182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/Tethering( 1019): No numeric data
,E/SELinux ( 3182): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3182 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 2356:com.sec.modem.settings/1000 (adj 15): empty #31
,I/DBG_POLICYDM( 3028): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/TimaKeyStoreProvider( 3182): TimaSignature is unavailable
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,D/ActivityThread( 3182): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3028): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,V/VibratorService( 1019): hasVibrator - useVibetonz: true
,W/NotificationAccessSettings( 1307): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1019): hasVibrator - useVibetonz: true
,V/VibratorService( 1019): hasVibrator - useVibetonz: true
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3028): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/ResourcesManager( 1307): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 3028): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2307/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2341/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2356/cgroup.procs: No such file or directory
,D/KnoxSetupWizardDbHelper( 3182): dbMigrationFlag : false
,I/ExternalOEMControlProvider( 3159): onCreate
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/ShortcutReceiver( 3182):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 3203): MountEmulatedStorage()
E/Zygote  ( 3203): v2
I/libpersona( 3203): KNOX_SDCARD checking this for 1000
I/libpersona( 3203): KNOX_SDCARD not a persona
,I/SELinux ( 3203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ScoverManager( 1307): serviceVersion : 16908288
,I/SELinux ( 3203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3203 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 2424:com.wsomacp/u0a25 (adj 15): empty #31,
I/ActivityManager( 1019): Killing 2389:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #32
I/ActivityManager( 1019): Killing 2374:com.sec.tcpdumpservice/1000 (adj 15): empty #33
,D/KnoxShortcutUtil( 3182): getIsShortcutMigrationFor_2_3_0_Done true
D/ShortcutReceiver( 3182):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3182):  shortcut migration not required 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/art     ( 2996): Verification of android.content.Intent com.google.android.finsky.utils.NotificationManager.createDefaultClickIntent(android.content.Context, java.lang.String, java.lang.String, java.lang.String, java.lang.String) took 132.958ms
,E/Zygote  ( 3219): MountEmulatedStorage()
E/Zygote  ( 3219): v2
I/libpersona( 3219): KNOX_SDCARD checking this for 1000
I/libpersona( 3219): KNOX_SDCARD not a persona
,I/SELinux ( 3219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 3203): TimaSignature is unavailable,
D/ActivityThread( 3203): Added TimaKeyStore provider
I/SELinux ( 3219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3219 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2459:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3234): MountEmulatedStorage()
E/Zygote  ( 3234): v2
I/libpersona( 3234): KNOX_SDCARD checking this for 1000
I/libpersona( 3234): KNOX_SDCARD not a persona,
I/SELinux ( 3234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3234): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3219): TimaSignature is unavailable
D/ActivityThread( 3219): Added TimaKeyStore provider
I/ActivityManager( 1019): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3234 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 2488:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/SettingsProvider( 1019): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10062
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1019): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10062
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/TimaKeyStoreProvider( 3234): TimaSignature is unavailable
D/ActivityThread( 3234): Added TimaKeyStore provider
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/ResourcesManager( 3234): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2374/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10025/pid_2424/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10131/pid_2389/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10044/pid_2459/cgroup.procs: No such file or directory
,I/LockPatternUtils( 1307): isSmartCardAuthenticationAvailable: false
W/libprocessgroup( 1019): failed to open /acct/uid_10142/pid_2488/cgroup.procs: No such file or directory
,I/ServiceMode( 3234): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3234): setReferenceIsDumpState : 0
,E/KnoxSetupWizardClient( 3219): isShipMode : 1
,I/KnoxSetupWizardClient( 3219): onReceive : android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Settings_Utils( 1307): isSupportVNFestival SM-A500FU XEO
,E/Zygote  ( 3262): MountEmulatedStorage()
E/Zygote  ( 3262): v2
I/libpersona( 3262): KNOX_SDCARD checking this for 1000
I/libpersona( 3262): KNOX_SDCARD not a persona
,I/SELinux ( 3262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 29
,D/Finsky  ( 2996): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager( 1019): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3262 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1019): Killing 2505:com.sec.android.app.camera/u0a139 (adj 15): empty #31
E/SELinux ( 3262): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusChecker( 2294): onReceive : android.intent.action.BOOT_COMPLETED
I/StatusChecker( 2294): onReceive : net.mt.init : DONE
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/DBG_FMMDM( 3203): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3278): MountEmulatedStorage()
,I/DBG_FMMDM( 3203): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
E/Zygote  ( 3278): v2
I/libpersona( 3278): KNOX_SDCARD checking this for 10116
I/DBG_FMMDM( 3203): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41,
I/DBG_FMMDM( 3203): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
I/libpersona( 3278): KNOX_SDCARD not a persona
,I/SELinux ( 3278): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3278 uid=10116 gids={50116, 9997} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2628:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3262): TimaSignature is unavailable
D/ActivityThread( 3262): Added TimaKeyStore provider
,I/SELinux ( 3278): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3278): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/System.err( 3219): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3219): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3219): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3219): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
,W/System.err( 3219): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3219): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3219): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/art     (  306): Explicit concurrent mark sweep GC freed 8755(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 24.180ms
,D/TimaKeyStoreProvider( 3278): TimaSignature is unavailable
D/ActivityThread( 3278): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 17.666ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.267ms
,E/Zygote  ( 3293): MountEmulatedStorage()
I/libpersona( 3293): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3293): v2
I/libpersona( 3293): KNOX_SDCARD not a persona
,I/SELinux ( 3293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3293 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3293): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1019): failed to open /acct/uid_10139/pid_2505/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2628/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3293): TimaSignature is unavailable
,D/ActivityThread( 3293): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 3278): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3278): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 3278): onCreate mCpBitFlag=0,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/Settings( 2996): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2996): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Zygote  ( 3311): MountEmulatedStorage()
,E/Zygote  ( 3311): v2
I/libpersona( 3311): KNOX_SDCARD checking this for 10125
I/libpersona( 3311): KNOX_SDCARD not a persona
,I/SELinux ( 3311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3311 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3311): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PCWCLIENTTRACE_LOG( 3293): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3293): DEFAULT_LOGLEVEL : 3
,V/VibratorService( 1019): hasVibrator - useVibetonz: true
D/TimaKeyStoreProvider( 3311): TimaSignature is unavailable
D/ActivityThread( 3311): Added TimaKeyStore provider
,D/NPS_WSSNPS( 3262): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3262): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3262): [] Service onCreate!!
,W/ResourcesManager( 3311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3311): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3311): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3293): new DMDBOpenHelper instance
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2933): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,E/Zygote  ( 3328): MountEmulatedStorage()
I/libpersona( 3328): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3328): v2
I/libpersona( 3328): KNOX_SDCARD not a persona
I/SELinux ( 3328): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3328): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3328): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3328 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/PCWCLIENTTRACE_DMContentProvider( 3293): [URIMatcher] - result : 2
,I/DBG_FMMDM( 3203): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3203): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3203): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 1019): Killing 2670:com.android.keychain/1000 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 2613:com.android.calendar/u0a135 (adj 15): empty #32
,D/NPS_WSSNPS( 3262): [50.150321] smlDBHelper
,D/TimaKeyStoreProvider( 3328): TimaSignature is unavailable
,D/ActivityThread( 3328): Added TimaKeyStore provider
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3262): [50.150321] NpsServiceTask Start
,I/NPS_WSSNPS( 3262): [50.150321] AsyncBulkFlagCheck
,E/Zygote  ( 3346): MountEmulatedStorage()
E/Zygote  ( 3346): v2
I/libpersona( 3346): KNOX_SDCARD checking this for 1000
I/libpersona( 3346): KNOX_SDCARD not a persona
,I/SELinux ( 3346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3346 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/TimaKeyStoreProvider( 3346): TimaSignature is unavailable
,D/ActivityThread( 3346): Added TimaKeyStore provider
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,I/NPS_WSSNPS( 3262): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3262): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3262): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/PowerUI ( 1180): Cable  true --> true mBootCompleted : true
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/PowerUI ( 1180): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/QuickConnect( 3311): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
D/QuickConnect( 3311): Util.setSCRunningSetting - [value]0
,D/Volley  ( 2996): [383] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 2996): [376] DiskBasedCache.clear: Cache cleared.
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2670/cgroup.procs: No such file or directory
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3262): [50.150321] Service onDestroy
,W/libprocessgroup( 1019): failed to open /acct/uid_10135/pid_2613/cgroup.procs: No such file or directory
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/NPS_WSSNPS( 3262): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3262): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3262): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3262): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3262): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3262): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3262): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3262): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3262): [50.150321] cpuBooster release : false
,D/SettingsProvider( 1019): name = scon_is_running
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10125
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/ActivityManager( 1019): Killing 2726:flipboard.boxer.app/u0a99 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/NPS_WSSNPS( 3262): [50.150321] dsServerSocket close
,I/QuickConnect( 3311): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/QuickConnect( 3311): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1019): name = access_control_enabled
,E/Zygote  ( 3364): MountEmulatedStorage()
,I/libpersona( 3364): KNOX_SDCARD checking this for 10131
E/Zygote  ( 3364): v2
I/libpersona( 3364): KNOX_SDCARD not a persona
,I/SELinux ( 3364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3364 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 2213:flipboard.app/u0a98 (adj 15): empty #31
I/SELinux ( 3364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3364): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Finsky  ( 2996): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 2996): [1] 2.run: Finished loading 1 libraries.
,I/DBG_FMMDS( 3346): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3346): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,E/Zygote  ( 3377): MountEmulatedStorage(),
I/libpersona( 3377): KNOX_SDCARD checking this for 10069
E/Zygote  ( 3377): v2
I/libpersona( 3377): KNOX_SDCARD not a persona
I/SELinux ( 3377): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,V/GLSUser ( 1660): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,I/SELinux ( 3377): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
D/BluetoothAdapter( 2537): disable(),
E/SELinux ( 3377): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3377 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 2753:com.sec.usbsettings/1000 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3364): TimaSignature is unavailable
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3364): Added TimaKeyStore provider
,D/Finsky  ( 2996): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/BluetoothManagerService( 1019): Bluetooth is already disabled. DO NOT disable again.
,D/TimaKeyStoreProvider( 3377): TimaSignature is unavailable
,D/ActivityThread( 3377): Added TimaKeyStore provider
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled,
D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1019): mCursor = null
,D/SettingsProvider( 1019): name = wifi_on
D/WifiService( 1019): setWifiEnabled: false pid=2537, uid=10174
,I/jxcore-log( 2537): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 2537): 
I/jxcore-log( 2537): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2537): 
,D/PCWCLIENTTRACE_DMContentProvider( 3293): [URIMatcher] - result : 2
W/ResourcesManager( 3364): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3364): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3364): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3364): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/DBG_FMMDS( 3346): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,V/GmsCoreStatsServiceLauncher( 1929): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NotificationStore( 1660): System rebooted after Notification storage file was last written
I/NotificationStore( 1660): Deleting the file
,I/LockPatternUtils( 1307): isSmartCardAuthenticationAvailable: false
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDS( 3346): [50.18.150420][Line:43][xdbDBInit] 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/FileShare-Server( 3377): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/libprocessgroup( 1019): failed to open /acct/uid_10099/pid_2726/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10098/pid_2213/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2753/cgroup.procs: No such file or directory
,D/PersistentNotificationBroadcastReceiver( 1660): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/Finsky  ( 2996): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/SBrowserFeatureFlag( 3364): initialized in static block : loadCscFeatureValue() succeed! 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ManifestProvider( 3364): onCreate()
,E/NetworkSettingsReceiver( 3364): onReceive: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDS( 3346): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,E/SBrowserFeatureFlag( 3364): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@212e9d34
,D/SBrowserFeatureFlag( 3364): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3364): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/DBG_FMMDS( 3346): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_FMMDS( 3346): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3346): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3346): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3346): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3346): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,E/Zygote  ( 3418): MountEmulatedStorage()
E/Zygote  ( 3418): v2
I/libpersona( 3418): KNOX_SDCARD checking this for 10135
I/libpersona( 3418): KNOX_SDCARD not a persona
,I/SELinux ( 3418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3418 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 3418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3418): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 3400): 
D/AndroidRuntime( 3400): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3400): CheckJNI is OFF
D/AndroidRuntime( 3400): readGMSProperty: start
D/AndroidRuntime( 3400): readGMSProperty: already setted!!
D/AndroidRuntime( 3400): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3400): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3400): readGMSProperty: end
D/AndroidRuntime( 3400): addProductProperty: start
,D/TimaKeyStoreProvider( 3418): TimaSignature is unavailable
D/ActivityThread( 3418): Added TimaKeyStore provider
,I/FOTA_Client( 3114): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/InstanceID/Rpc( 1929): Found 10012
,W/ResourcesManager( 3418): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3418): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3418): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1019): Killing 2324:com.android.mms/u0a46 (adj 15): empty #31
,W/FOTA_Client( 3114): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3442): MountEmulatedStorage(),
E/Zygote  ( 3442): v2
I/libpersona( 3442): KNOX_SDCARD checking this for 10014
I/libpersona( 3442): KNOX_SDCARD not a persona
,I/SELinux ( 3442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3442): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3442 uid=10014 gids={50014, 9997} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2818:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,D/CountryDetector( 1019): No listener is left
,D/TimaKeyStoreProvider( 3442): TimaSignature is unavailable
,D/ActivityThread( 3442): Added TimaKeyStore provider
,V/Finsky  ( 2996): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 30
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/AffinityControl( 3400): AffinityControl: registerfunction enter
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,I/ActivityManager( 1019): Killing 2835:com.sec.dsm.system/1000 (adj 15): empty #31
W/libprocessgroup( 1019): failed to open /acct/uid_10046/pid_2324/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10048/pid_2818/cgroup.procs: No such file or directory
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1307): InitSerachDBThread thread end!
,D/AndroidRuntime( 3400): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 1019): START PACKAGE DELETE: observer{603018062}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1019): !@killApplicatoin: 10174, uninstall pkg
I/ActivityManager( 1019): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 2537:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,V/OneTimeInitializerReceiver( 3442): OneTimeInitializerReceiver.onReceive
,E/USB_UICC(  296): Timeout! No signal received. Reach maximum retries!,
E/USB_UICC(  296): usb_uicc_init_qmi failed ! 
I/USB_UICC(  296): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  296): usb_uicc_cleanup, Issuing QMI deinit ... 
,I/FactoryTestApp( 2647): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2917)  ,
,I/WindowState( 1019): WIN DEATH: Window{ec442a9 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (-2/7)
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (-2/7)
,D/InputDispatcher( 1019): Focus left window: 2537
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,W/PackageSettings( 1019): Skipping PackageSetting{14487936 com.test.thalitest/10175} due to missing metadata
,W/ActivityManager( 1019): Force removing ActivityRecord{3c8606a5 u0 com.example.hello/.MainActivity t228}: app died, no saved state
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1019): Focused application set to: xxxx
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1,
V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2835/cgroup.procs: No such file or directory
,D/Launcher( 1491): onRestart, Launcher: 556703028
,V/OneTimeService( 3442): OneTimeService.onHandleIntent
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/FileApkUtils( 1929): Spent 27ms computing apk sha1.,
D/FileApkUtils( 1929): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1929): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
E/Zygote  ( 3477): MountEmulatedStorage()
E/Zygote  ( 3477): v2
I/libpersona( 3477): KNOX_SDCARD checking this for 10042
I/libpersona( 3477): KNOX_SDCARD not a persona
,I/SELinux ( 3477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3477 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1019): Spurious death for ProcessRecord{11502d7c 2537:com.example.hello/u0a174}, curProc for 2537: null
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10174 user=0: pkg removed
E/SELinux ( 3477): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/DexOptUtils( 1929): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1929): Lollipop platform, using <isa> directory.
D/DexOptUtils( 1929): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1929): Primary ABI of odexing process is armeabi-v7a
,D/TimaKeyStoreProvider( 3477): TimaSignature is unavailable
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
D/ActivityThread( 3477): Added TimaKeyStore provider
,I/DBG_DM  ( 2933): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1780): mOCRHelper is null
,W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Launcher( 1491): onStart, Launcher: 556703028
,D/Launcher.HomeView( 1491): onStart
D/Launcher( 1491): onResume, Launcher: 556703028
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/SettingsProvider( 1019): name = kids_home_mode
I/dex2oat ( 3491): ----------------------------------------------------
I/dex2oat ( 3491): <SS>: S T A R T I N G . . .
I/dex2oat ( 3491): <SS>: Zip is absent. Canceled.
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/dex2oat ( 3491): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10007
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
D/Launcher.HomeView( 1491): onResume
,D/RegisteredComponentCache( 1445): Collect Tech packages for Knox
,D/PersonaManager( 1445): isKioskContainerExistOnDevice
,D/PersonaManager( 1445): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1445): empty dynamic service
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/OTPFW   ( 1019): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1019): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1019): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1019): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1019): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1019): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10174
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
I/art     ( 1019): Explicit concurrent mark sweep GC freed 33899(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/40MB, paused 2.811ms total 196.345ms
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
I/art     ( 1019): WaitForGcToComplete blocked for 172.941ms for cause Explicit
,W/GeofencerStateMachine( 1748): Ignoring removeGeofence because network location is disabled.
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
I/ActivityManager( 1019): Killing 2860:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,W/TextServicesManagerService( 1019): no available spell checker services found
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1019): [SO] activate (ident=0xb87555c8, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
,W/ResourcesManager( 3477): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1019): [SO] changed settle time [0]
D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb872cb20, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10174
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 3501): MountEmulatedStorage()
I/libpersona( 3501): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3501): v2
I/libpersona( 3501): KNOX_SDCARD not a persona
,I/SELinux ( 3501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1019): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3501 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
D/TaskPersister( 1019): removeObsoleteFile: deleting file=228_task.xml
I/SELinux ( 3501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3501): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 2746:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 2883:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/MenuAppsGridFragment( 1491): onResume
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2( 3477): CalendarProvider2.onCreate() called
,D/TimaKeyStoreProvider( 3501): TimaSignature is unavailable
,D/ActivityThread( 3501): Added TimaKeyStore provider
,E/Zygote  ( 3517): MountEmulatedStorage()
,E/Zygote  ( 3517): v2
,I/libpersona( 3517): KNOX_SDCARD checking this for 10139
I/libpersona( 3517): KNOX_SDCARD not a persona
,I/SELinux ( 3517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3517 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/SELinux ( 3517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  306): Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 22.021ms
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/TimaKeyStoreProvider( 3517): TimaSignature is unavailable
,D/ActivityThread( 3517): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 19.333ms
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1019): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 18.594ms
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3517): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3517): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3517): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3517): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 3517): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3535 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3535): MountEmulatedStorage()
E/Zygote  ( 3535): v2
I/libpersona( 3535): KNOX_SDCARD checking this for 1000
I/libpersona( 3535): KNOX_SDCARD not a persona
I/SELinux ( 3535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,I/SELinux ( 3535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 3535): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1019): handle home activity for 0
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
I/Choreographer( 1491): Skipped 33 frames!  The application may be doing too much work on its main thread.
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
I/SurfaceFlinger(  256): id=12 createSurf (720x1280),1 flag=4, Mauncher
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1019): Focus entered window: 1491
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 1491): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 10011(662KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/39MB, paused 3.229ms total 269.705ms
D/TimaKeyStoreProvider( 3535): TimaSignature is unavailable
,D/ActivityThread( 3535): Added TimaKeyStore provider
,D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 2537 uid 10174
,D/PanelView( 1180): There is/are notification(s) 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,D/SamsungIME( 1780): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,I/ActivityManager( 1019): Killing 2898:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,D/SensorService( 1019): [SO] currT = 37181091000, prevT = 36721084000, diff = 460007000, [0.172 0.115 10.228]
,D/SensorService( 1019): [SO] 0.172 0.115 10.228
D/SensorService( 1019): [SO] [100 -> 255]
,I/ActivityManager( 1019): Displayed Component not be shown by security: +743ms
,E/SMD     (  288): DCD OFF
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3557): MountEmulatedStorage(),
E/Zygote  ( 3557): v2,
,I/libpersona( 3557): KNOX_SDCARD checking this for 10145,
I/ActivityManager( 1019): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3557 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/libpersona( 3557): KNOX_SDCARD not a persona
,I/SELinux ( 3557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 3557): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/GCM     ( 1929): COMPAT: Multi user not supported
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 3535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 3557): TimaSignature is unavailable
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 3557): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1660): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3584 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3584): MountEmulatedStorage()
I/libpersona( 3584): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3584): v2
I/libpersona( 3584): KNOX_SDCARD not a persona
,I/SELinux ( 3584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3584): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3557): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3557): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3557): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3557): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3557): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PackageManager( 1019): delete codoeFile: 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3584): TimaSignature is unavailable
,D/ActivityThread( 3584): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
,I/AASA_removePackage( 1019): UID=10174 Target=com.example.hello
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,D/PackageManager( 1019): result of delete: 1{603018062}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/AndroidRuntime( 3400): Shutting down VM
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/GCoreUlr( 1929): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3584): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,E/Zygote  ( 3605): MountEmulatedStorage()
E/Zygote  ( 3605): v2
I/libpersona( 3605): KNOX_SDCARD checking this for 1000
I/libpersona( 3605): KNOX_SDCARD not a persona
,I/SELinux ( 3605): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3605): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3605): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1019): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3605 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0,
,I/DBG_DM  ( 2933): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3605): TimaSignature is unavailable
,D/ActivityThread( 3605): Added TimaKeyStore provider
,I/CheckinService( 1929): Disabling old GoogleServicesFramework version
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,I/art     ( 1660): Explicit concurrent mark sweep GC freed 11493(910KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 10MB/17MB, paused 977us total 59.302ms
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/art     ( 3400): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{3106f4b2 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t227} time:37719
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/SystemUpdateService( 1929): onCreate
,I/Hs20UtilService( 3605): onCreate
,D/TimaService( 1019): TIMA: in getTimaVersion
,D/TimaService( 1019): TIMA3: KeyStore3_init
E/TLC_TZ_KEYSTORE: ( 1019): Inside TZ_KEYSTORE_initialize()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/TLC_TZ_KEYSTORE: ( 1019): creating new keystore context...
D/TimaService( 1019): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1019): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1019): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1019): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/GCoreUlr( 1748): DispatchingService.onCreate()
,E/Zygote  ( 3631): MountEmulatedStorage()
E/Zygote  ( 3631): v2
I/libpersona( 3631): KNOX_SDCARD checking this for 10019
I/libpersona( 3631): KNOX_SDCARD not a persona
,I/SELinux ( 3631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 3631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3631 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/UsbSettingsManager( 1019): clearDefaults: com.example.hello
I/CrashAnrDetector( 1019): onPackageRemoved : com.example.hello
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Hs20UtilService( 3605): Starting #1
,I/Hs20UtilService( 3605): Message received 5003
W/libprocessgroup( 1019): failed to open /acct/uid_10085/pid_2746/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2860/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2883/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2898/cgroup.procs: No such file or directory
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3631): TimaSignature is unavailable
,D/ActivityThread( 3631): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,D/SystemUpdateService( 1929): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1019): ctx = 0xb86a0c38, comm = 0xb86ea0a0, sendmsg = 0xa0810000, recvmsg = 0xa0810440
I/TZ_init: ( 1019): TZ_init: sending initialization request...
,E/TZ_init: ( 1019): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1019): trustlet initialization failed
I/TZ_init: ( 1019): TZ_init_START...
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/TZ_init: ( 1019): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1019): TZ_init: successful initialization
D/QSEECOMAPI: ( 1019): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1019): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1019): Count : 1, Ret : 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1660): onCreate
,I/ConfigFetchService( 1929): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1660): (28) failed to open "/data/data/com.google.android.gms/databases/config.db" with flag (131138) and mode_t (0) due to error (30)
,I/ActivityManager( 1019): Killing 2950:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,V/AuthZen ( 1929): Handling intent: android.intent.action.BOOT_COMPLETED
,E/SQLiteDatabase( 1660): Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
E/SQLiteDatabase( 1660): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 1660): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 1660): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1660): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1660): 	at com.google.android.gms.config.ConfigService.a(SourceFile:47)
E/SQLiteDatabase( 1660): 	at com.google.android.gms.config.j.run(SourceFile:163)
E/SQLiteDatabase( 1660): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1660): Couldn't open config.db for writing (will try read-only):
E/SQLiteOpenHelper( 1660): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 1660): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 1660): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1660): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1660): 	at com.google.android.gms.config.ConfigService.a(SourceFile:47)
E/SQLiteOpenHelper( 1660): 	at com.google.android.gms.config.j.run(SourceFile:163)
E/SQLiteOpenHelper( 1660): 	at java.lang.Thread.run(Thread.java:818)
,D/AuthZenEventHandler( 1929): Handling event: android.intent.action.BOOT_COMPLETED
I/CheckinService( 1929): Checking schedule, now: 1449410957059 next: 1449407374401
I/CheckinService( 1929): active receiver: enabled
W/SQLiteOpenHelper( 1660): Opened config.db in read-only mode
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1019): failed to open /acct/uid_10150/pid_2950/cgroup.procs: No such file or directory
,I/RlzPingService( 3501): Setting next ping for 1450015757095

```
