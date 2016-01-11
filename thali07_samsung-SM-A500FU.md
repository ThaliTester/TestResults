#### Test 50242285feafdeb_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/ArtClassLoader( 2334): init before art
D/Mms/TelephonyPermission( 2334): start operation mode monitor
--------- beginning of system
W/ResourcesManager( 2334): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2334): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2334): isDefault true
D/Mms/MmsApp( 2334): onCreate() com.android.mms
D/Mms/MmsApp( 2334): [start]    initCountryIso consume time = 314.488594
D/CountryDetector( 1018): The first listener is added
D/Mms/MmsApp( 2334): [end]    initCountryIso consume time = 14.362656
D/Mms/MmsConfig( 2334): [start]    MmsConfig.init() consume time = 0.116041
D/Mms/MmsConfig( 2334): before partial update
D/Mms/MmsConfig( 2334): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2334): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2334): isAuth is false
D/Mms/MmsConfig( 2334): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/TP/MmsSmsProvider( 1468): query,matched:2117, calling pid = 2334
D/TP/MmsSmsProvider( 1468): match 2117:Elapsed time : 3.575 ms
D/EasySignUpManager_1.0.1( 2334): isAuth is false
D/EasySignUpManager_1.0.1( 2334): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2334): mps_code.dat does not exist
E/CscParser( 2334): customer_path =/system/csc/customer.xml
E/CscParser( 2334): fileName + /system/csc/customer.xml
E/CscParser( 2334): mps_code.dat does not exist
E/CscParser( 2334): customer_path =/system/csc/customer.xml
E/CscParser( 2334): fileName + /system/csc/customer.xml
D/CscParser( 2334): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2334):  enable multiwindow = true
E/Mms/MessageUtils( 2334): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2334): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2334): [end]    init() consume time = 81.142188
D/Mms/Contact( 2334): [start]    init() consume time = 2.863385
D/Mms/Contact( 2334): [end]    init consume time = 8.535677
D/TP/MmsSmsProvider( 1468): query,matched:13, calling pid = 2334
D/TP/MmsSmsProvider( 1468): match 13:Elapsed time : 1.191 ms
D/Mms/DraftCache( 2334): [start]    rebuildCache consume time = 6.651407
D/TP/MmsSmsProvider( 1468): query,matched:12, calling pid = 2334
D/TP/MmsSmsProvider( 1468): match 12:Elapsed time : 1.551 ms
D/Mms/MethodReflector( 2334): getSubId is called
D/Mms/TelephonyUtils( 2334): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2334): getTelephonyProperty is called
D/Mms/DownloadManager( 2334): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2334): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2334): auto download without roaming -> true
D/Mms/DownloadManager( 2334): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2334): getSubId is called
D/Mms/MethodReflector( 2334): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2334): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2334): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2334): getTelephonyProperty is called
D/Mms/DownloadManager( 2334): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2334): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2334): auto download without roaming -> true
D/Mms/DownloadManager( 2334): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2334): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2334): mAutoDownload ------> true
D/Mms/DraftCache( 2334): [end]    rebuildCache consume time = 10.474427
D/ComposerPerformance( 2334): 1452552465692 ms / [DONE] Composer constructor
D/Mms/Conversation( 2334): [start]    init() consume time = 18.429219
E/CII     ( 2334): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 2334): ReservationManager()
I/Mms/ReservationManager( 2334): resetAfterConnected()
D/TP/MmsSmsDatabaseHelper( 1468): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1468): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1468): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1468): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1468): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1468): query,matched:7, calling pid = 2334
D/TP/MmsSmsProvider( 1468): match 7:Elapsed time : 2.077 ms
D/TP/MmsSmsProvider( 1468): deleteConversation threadId: 9223372036854775807
I/Mms/ReservationManager( 2334): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1468): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1468): updateThread(), thread_id = 9223372036854775807
D/Mms/ArtClassLoader( 2334): init [DONE] art
D/Mms/MmsApp( 2334): [end]    onCreate() consume time = 21.314739
D/Mms/SmsReceiver( 2334): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
V/TP/MmsSmsDatabaseHelper( 1468): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TP/MmsSmsProvider( 1468): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
D/Mms/Conversation( 2334): [end]    init consume time = 11.725521
I/splitIntent( 1018): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/Mms/DownloadManager( 2334): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 2334): roaming ------> false, mSimSlot = 0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Mms/MessagingNotification( 2334): [start]    init() consume time = 8.491875
D/Mms/MethodReflector( 2334): getSubId is called
D/Mms/TelephonyUtils( 2334): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2334): getTelephonyProperty is called
D/Mms/DownloadManager( 2334): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2334): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2334): auto download without roaming -> true
D/Mms/DownloadManager( 2334): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 2334): mAutoDownload ------> true
E/Zygote  ( 2432): MountEmulatedStorage()
E/Zygote  ( 2432): v2
I/libpersona( 2432): KNOX_SDCARD checking this for 10020
I/libpersona( 2432): KNOX_SDCARD not a persona
I/SELinux ( 2432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2432 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
D/Mms/MessagingNotification( 2334): [end]    init consume time = 17.139583
I/SELinux ( 2432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2432): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/Mms/SmsReceiverService( 2334): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
D/Mms/TelephonyPermission( 2334): isDefault true
D/Mms/SmsReceiverService( 2334): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2334): handleSIMStatus()
D/Mms/SmsReceiverService( 2334): handleSIMStatus(): SIM_STATUS = ABSENT
D/Mms/SpamFilter( 2334): [start]    SpamFilter fill() begin consume time = 17.860209
D/TimaKeyStoreProvider( 2432): TimaSignature is unavailable
D/TP/MmsSmsProvider( 1468): query,matched:0, calling pid = 2334
V/TP/MmsSmsProvider( 1468): getSimpleConversations entered.
D/ActivityThread( 2432): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1468): match 0:Elapsed time : 1.114 ms
D/TP/MmsSmsProvider( 1468): query,matched:400, calling pid = 2334
D/Mms/Synchronizer( 2334): [start]    doSync consume time = 5.83427
D/TP/MmsSmsProvider( 1468): update, matched:300, calling pid = 2334
V/TP/MmsSmsProvider( 1468): syncDBData start
V/TP/MmsSmsProvider( 1468): syncDBData sms end
V/TP/MmsSmsProvider( 1468): syncDBData mms end
D/Mms/SpamFilter( 2334): [end]    SpamFilter fill() finished consume time = 5.841198
V/TP/MmsSmsProvider( 1468): syncDBData end
D/Mms/Synchronizer( 2334): [end]    doSync consume time = 1.760417
W/ResourcesManager( 2432): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2432): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2432): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/Mms/MessagingNotification( 2334): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1468): query,matched:26, calling pid = 2334
D/TP/SmsProvider( 1468): match 26:Elapsed time : 1.906 ms
D/TP/MmsSmsProvider( 1468): query,matched:6, calling pid = 2334
D/TP/MmsSmsProvider( 1468): match 6:Elapsed time : 2.290 ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2449 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/Zygote  ( 2449): MountEmulatedStorage()
E/Zygote  ( 2449): v2
I/libpersona( 2449): KNOX_SDCARD checking this for 10025
I/libpersona( 2449): KNOX_SDCARD not a persona
I/SELinux ( 2449): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2449): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2449): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2449): TimaSignature is unavailable
D/ActivityThread( 2449): Added TimaKeyStore provider
W/ResourcesManager( 2449): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/VibratorService( 1018): hasVibrator - useVibetonz: true
I/OMACP   ( 2449): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/EasySignUpManager_1.15.0305( 2432): serviceId : 0, features : -1
I/splitIntent( 1018): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1018): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
D/SecContentProvider2( 1018): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1018): mCursor = null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/SecContentProvider2( 1018): isCopyContactToSimAllowed = true
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2467): MountEmulatedStorage()
E/Zygote  ( 2467): v2
I/libpersona( 2467): KNOX_SDCARD checking this for 10044
I/SELinux ( 2467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 2467): KNOX_SDCARD not a persona
D/Mms/Omacp( 2334): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2467 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 2467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
E/SELinux ( 2467): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2479): MountEmulatedStorage()
E/Zygote  ( 2479): v2
I/libpersona( 2479): KNOX_SDCARD checking this for 10054
I/libpersona( 2479): KNOX_SDCARD not a persona
I/SELinux ( 2479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/ActivityManager( 1018): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2479 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/SELinux ( 2479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/SELinux ( 2479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
D/TimaKeyStoreProvider( 2467): TimaSignature is unavailable
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
D/ActivityThread( 2467): Added TimaKeyStore provider
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
E/Zygote  ( 2497): MountEmulatedStorage()
E/Zygote  ( 2497): v2
I/libpersona( 2497): KNOX_SDCARD checking this for 10142
I/libpersona( 2497): KNOX_SDCARD not a persona
I/SELinux ( 2497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/TimaKeyStoreProvider( 2479): TimaSignature is unavailable
D/ActivityThread( 2479): Added TimaKeyStore provider
E/SELinux ( 2497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2497 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1492, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ResourcesManager( 2479): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2497): TimaSignature is unavailable
D/ActivityThread( 2497): Added TimaKeyStore provider
W/ResourcesManager( 2467): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2467): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2467): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2467): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2467): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2467): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
V/TaskCloserActivity( 2497): TaskCloserActivity enter()
V/TaskCloserActivity( 2497): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/Recents_RecreateReceiver( 2479): onReceive by home
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SMD     (  291): DCD OFF
E/Zygote  ( 2514): MountEmulatedStorage()
E/Zygote  ( 2514): v2
I/libpersona( 2514): KNOX_SDCARD checking this for 10139
I/libpersona( 2514): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2514 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/SELinux ( 2514): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2514): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2514): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
D/TimaKeyStoreProvider( 2514): TimaSignature is unavailable
D/ActivityThread( 2514): Added TimaKeyStore provider
E/USB_UICC(  299): Timeout! No signal received. Retry num = 22
W/ResourcesManager( 2514): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2514): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2514): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2514): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2514): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/art     ( 2432): Verification of void com.android.contacts.common.list.l.P() took 123.255ms
D/NearbySource( 2467): Nearby Source Create!
D/NearbyContext( 2467): Nearby Context Create!
D/AbsListView( 2432): Get MotionRecognitionManager
D/MotionRecognitionService( 1018):  ssp status : false
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2467): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/AndroidRuntime( 2529): 
D/AndroidRuntime( 2529): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/SLinkSource( 2467): Samsung link source created
D/AndroidRuntime( 2529): CheckJNI is OFF
D/AndroidRuntime( 2529): readGMSProperty: start
D/AndroidRuntime( 2529): readGMSProperty: already setted!!
D/AndroidRuntime( 2529): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2529): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2529): readGMSProperty: end
D/AndroidRuntime( 2529): addProductProperty: start
D/ContactProvider( 2467): getAllContactInfoList Start
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/GalleryCacheReady( 2467): Receive : home resume
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 2334): ui event
I/splitIntent( 1018): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/SQLiteLog( 1225): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
D/BootupListener( 1468): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1018): name = internet_call_settings_visibility
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1001
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/PhoneUtilsCommon( 1468): isSupportVoLTE is false.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/StatusChecker( 2306): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2306): onReceive : net.mt.init : DONE
D/StatusChecker( 2306): Service state changed : 3 mSub-1
D/ContactProvider( 2467): getAllContactInfoList End
I/syncContacts( 2467): thread: 253, sync time = 68
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/AffinityControl( 2529): AffinityControl: registerfunction enter
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1700): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 2529): Calling main entry com.android.commands.am.Am
D/AuthorizationBluetoothService( 1700): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/a       ( 1700): Opening database auth.proximity.permit_store...
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1492): onPause
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1018): Focused application set to: xxxx
D/Launcher( 1492): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/InputDispatcher( 1018): Focus left window: 1492
D/AndroidRuntime( 2529): Shutting down VM
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
E/Zygote  ( 2547): MountEmulatedStorage()
E/Zygote  ( 2547): v2
I/libpersona( 2547): KNOX_SDCARD checking this for 10176
I/libpersona( 2547): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2547 uid=10176 gids={50176, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2547): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
V/ActivityThread( 1492): updateVisibility : ActivityRecord{3241c9d2 token=android.os.BinderProxy@30ecfd6f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 2547): TimaSignature is unavailable
D/ActivityThread( 2547): Added TimaKeyStore provider
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Launcher.HomeView( 1492): onStop
V/ActivityThread( 1492): updateVisibility : ActivityRecord{3241c9d2 token=android.os.BinderProxy@30ecfd6f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Launcher( 1492): onTrimMemory. Level: 20
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/WearableService( 2028): callingUid 10012, callindPid: 2028
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/WebViewFactory( 2547): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/art     ( 2529): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/GmsWearableLS( 1643): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/LibraryLoader( 2547): Time to load native libraries: 3 ms (timestamps 9082-9085)
I/LibraryLoader( 2547): Expected native library version number "",actual native library version number ""
,E/MDM     ( 1643): [163] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/WebViewChromiumFactoryProvider( 2547): Binding Chromium to main looper Looper (main, tid 1) {10c23955}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/LibraryLoader( 2547): Expected native library version number "",actual native library version number ""
I/chromium( 2547): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2547): Initializing chromium process, singleProcess=true
,W/art     ( 2547): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2547): ApplicationContext is null in ApplicationStatus
,W/chromium( 2547): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2547): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2547): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2547): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2547): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2547): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2547): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2547): Local Branch: 
I/Adreno-EGL( 2547): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2547): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2547):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/TP/SmsProvider( 1468): query,matched:0, calling pid = 1854
D/TP/SmsProvider( 1468): match 0:Elapsed time : 1.620 ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1468): Query uri=content://mms, match=0, calling pid = 1854
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1468): query,matched:0, calling pid = 1854
,D/TP/SmsProvider( 1468): match 0:Elapsed time : 2.234 ms
,D/BluetoothAdapter( 2547): 25634870: getState() :  mService = null. Returning STATE_OFF
,D/TP/MmsProvider( 1468): Query uri=content://mms, match=0, calling pid = 1854
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
E/USB_UICC(  299): Timeout! No signal received. Retry num = 23
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/art     ( 2547): Attempt to remove local handle scope entry from IRT, ignoring
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/AwContents( 2547): onDetachedFromWindow called when already detached. Ignoring,
,D/PhoneWindow( 2547): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 2547): *FMB* installDecor flags : 8456448
,V/UserPresentBroadcastReceiver( 1643): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/SystemWebViewEngine( 2547): CordovaWebView is running on device made by: samsung
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 38729(2MB) AllocSpace objects, 3(162KB) LOS objects, 33% free, 25MB/37MB, paused 8.007ms total 165.988ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 2547): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2547): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/OpenGLRenderer( 2547): Render dirty regions requested: true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,W/chromium( 2547): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/PhoneWindow( 2547): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2547): *FMB* isFloatingMenuEnabled return false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/InputDispatcher( 1018): Focus entered window: 2547
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SRIB_DCS( 2547): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2547): Initialized EGL, version 1.4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/OpenGLRenderer( 2547): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2547): Enabling debug mode 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1278): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1278): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1278): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1278): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1278): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1278): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1278): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
D/daemonapp( 1278): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1278): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1176): There is/are notification(s) 
I/Timeline( 2547): Timeline: Activity_idle id: android.os.BinderProxy@301b1541 time:29662
,I/SamsungIME( 1786): getCurrentCandidateView
,I/ActivityManager( 1018): Displayed Component not be shown by security: +822ms
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3ac4be0e u0 com.example.hello/.MainActivity t228} time:29671
,D/SamsungIME( 1786): Dismiss ExpandCandiate
,I/SamsungIME( 1786): getDebugLevel  : 0x4f4c
,E/SQLiteLog( 1700): (283) recovered 64 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
,I/Mms/MmsApp( 2334):  start initViewCache mms,
,D/Mms/ComposeMessageFragment( 2334): [start]    fillCache consume time = 1947.88927
D/Mms/ComposeMessageFragment( 2334): fillCache, easy = false
,I/Scheduler( 1700): Use PeriodicScheduler
,W/BindingManager( 2547): Cannot call determinedVisibility() - never saw a connection for the pid: 2547
,I/SamsungIME( 1786): getDebugLevel  : 0x4f4c
,D/daemonapp( 1278): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,I/SamsungIME( 1786): KeybaordView init() : load resources
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/chromium( 2547): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/art     ( 1700): Background sticky concurrent mark sweep GC freed 26999(1583KB) AllocSpace objects, 6(96KB) LOS objects, 13% free, 10MB/12MB, paused 2.249ms total 100.401ms
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/SamsungIME( 1786): getCurrentKeyboard
I/SamsungIME( 1786): getTextKeyboard
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SamsungIME( 1786): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/AbsListView( 2334): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/AdaptiveEventManager( 1176): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/AdaptiveEventManager( 1176): currentCityId is null
D/AdaptiveEventManager( 1176): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1176): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1176): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1176): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1176): mWeatherInfo is not reliable
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,E/daemonapp( 1278): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1278): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
D/Mms/ComposeMessageFragment( 2334): [end]    fillCache consume time = 173.130833
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/daemonapp( 1278): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,E/Zygote  ( 2615): MountEmulatedStorage(),
I/libpersona( 2615): KNOX_SDCARD checking this for 10135
E/Zygote  ( 2615): v2
I/libpersona( 2615): KNOX_SDCARD not a persona
I/SELinux ( 2615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2615 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux ( 2615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1278): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1452552467945
D/daemonapp( 1278): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1452574067942
D/daemonapp( 1278): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1278): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1452574020000
,D/daemonapp( 1278): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1452574020000
,D/JsMessageQueue( 2547): Set native->JS mode to OnlineEventsBridgeMode
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1452574020000
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TimaKeyStoreProvider( 2615): TimaSignature is unavailable
D/ActivityThread( 2615): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/AndroidProtocolHandler( 2547): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ResourcesManager( 2615): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2615): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2615): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2632): MountEmulatedStorage()
I/libpersona( 2632): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2632): v2
I/libpersona( 2632): KNOX_SDCARD not a persona
,I/SELinux ( 2632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2632 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  309): Explicit concurrent mark sweep GC freed 8751(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 761us total 22.453ms
,D/TimaKeyStoreProvider( 2632): TimaSignature is unavailable
,D/ActivityThread( 2632): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.230ms total 23.427ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 18.216ms
,D/SecurityLogAgent( 2632):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2632):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2632):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2632): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/SecurityLogAgent( 2632): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 2632): FileZippingService : file path =  /data/misc/audit/audit.old
,D/Mms/BubbleViewCache( 2334): fillCache bubble = 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2632): FileZippingService : onPremise disabled. Zipping..  
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/SecurityLogAgent( 2632): DenialLogFileZipCreator : createZip
D/SecurityLogAgent( 2632): DenialLogFileZipCreator : Not empty 
,D/SecurityLogAgent( 2632): DenialLogFileZipCreator : Files exceeded the max limit 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SIP     ( 1468): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,D/SecurityLogAgent( 2632): DenialLogFileZipCreator File existence : true audit.old file size 631
,D/SecurityLogAgent( 2632): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . ,
,E/File    ( 1468): fail readDirectory() errno=2
D/SecurityLogAgent( 2632): FileZippingService : completed task. Returning wakelock . 
,E/Zygote  ( 2653): MountEmulatedStorage(),
,I/libpersona( 2653): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2653): v2
I/libpersona( 2653): KNOX_SDCARD not a persona,
I/SELinux ( 2653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2653 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2653): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2653): TimaSignature is unavailable
,D/ActivityThread( 2653): Added TimaKeyStore provider
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 24
,W/ResourcesManager( 2653): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/jxcore_app_log( 2547): JniHelper::setJavaVM(0xb8c7b450), pthread_self() = -1189276800
,D/FactoryTestApp( 2653): [FactoryTestBroadcastReceiver$onReceive](2653) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2653): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/jxcore-log( 2547): Initializing JXcore engine
W/jxcore-log( 2547): JXcore engine is ready
,D/FactoryTestApp( 2653): [XMLDataStorage$parseXML](2653) is Live Demo : false
,D/FactoryTestApp( 2653): [XMLDataStorage$parseXML](2653) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2653): [XMLDataStorage$parseXML](2653) deviceXML=a5ulte.dat
,D/FactoryTestApp( 2653): [XMLDataStorage$parseXML](2653) nameXML=a5ultexx.dat
D/FactoryTestApp( 2653): [XMLDataStorage$parseAsset](2653) parseAsset Is Started
,I/FactoryTestApp( 2653): [XMLDataStorage$parseAsset](2653) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2653): [XMLDataStorage$parseAsset](2653) Decode base file: factory.dat
,E/audit   ( 1869): type=1400 msg=audit(1452552468.408:203): avc:  denied  { ioctl } for  pid=2668 comm="Thread-291" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1869):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1869): type=1300 msg=audit(1452552468.408:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=5 a3=9d07f8f8 items=0 ppid=309 ppcomm=main pid=2668 auid=4294967295 uid=10176 gid=10176 euid=10176 suid=10176 fsuid=10176 egid=10176 sgid=10176 fsgid=10176 ses=4294967295 tty=(none) comm="Thread-291" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1869): type=1320 msg=audit(1452552468.408:203): 
,W/jxcore-log( 2547): Starting JXcore engine
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=FACTORY_TEST_APP
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=FAILHIST_VERSION
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=MODEL_NAME
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=MODEL_NUMBER
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=CHIPSET_NAME
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=DEVICE_TYPE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=BATT_TYPE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=PANEL_TYPE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SENSOR_NAME_MAGNETIC
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SPEAKER_COUNT
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=MIC_COUNT
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_LTE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_DUAL_STANBY_ONE_CP
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_RCV
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=FACTORY_TEST_APO
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_BOOST_MEDIASCAN
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_NVBACKUP_CMD
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_EPEN
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_SENSORHUB
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=NEED_CAMDRIVER_OPEN
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=HW_VER_EFS
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_HOVER_HIGHTLIGHT
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_AP_EX_THERM_ADC
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=FONT_SIZE
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=RAM_SIZE_IF
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=MULTI_TSK_THD
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_FM_RADIO
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_DISABLE_SCROLLING_CACHE
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_TEST_POWER
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_TEST_HOME
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_TEST_BACK
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SEMI_KEY_TEST_HOME,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=IS_KEY_TEST_THRESHOLD,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=IS_TSP_STANDARD_CHANNEL,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=IS_SENSOR_TEST_ACC_REVERSE
,W/jxcore-log( 2547): Platform android
W/jxcore-log( 2547): 
W/jxcore-log( 2547): Process ARCH arm
W/jxcore-log( 2547): 
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_GEOMAGNETIC_ALPS_CAL,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=GEOMAGNETIC_IC_POINT,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SENSOR_TEST_ACC_BIT,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=G_VECTOR_SUM_ACC_BIT,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=AT_GPSSTEST,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=AT_BATTEST_RESET_WHEN_READ,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=PA0_TEMP_ADC,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=PA1_TEMP_ADC,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=HALL_IC_TEST,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=IS_NEW_TSP_SELFTEST_SYNAPTICS,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK,
,I/jxcore-log( 2547): JXcore Cordova bridge is ready!,
I/jxcore-log( 2547): 
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=READ_TARGET_GEOMAGNETIC
W/jxcore-log( 2547): JXcore engine is started
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_SELFTEST_MIN_MELFAS
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_SELFTEST_MAX_MELFAS
,E/jxcore  ( 2547): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 2547): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=BOOTLOADER_VERSION
,D/PhoneWindow( 2547): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 2547): *FMB* installDecor flags : 8388610
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=BATTERY_TEST_MODE
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=BATTERY_VF_OCV
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=PA0_THERMISTER_ADC
,D/InputDispatcher( 1018): Focus left window: 2547
D/InputDispatcher( 1018): Focus entered window: 2547
D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=PA1_THERMISTER_ADC
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/PhoneWindow( 2547): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
D/PhoneWindow( 2547): *FMB* isFloatingMenuEnabled return false
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_COMMAND_CMD
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=KEY_PRESSED_POWER
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=4, NainActivit,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/SRIB_DCS( 2547): log_dcs ThreadedRenderer::initialize entered! 
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=LPA_MODE_SET
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=GEOMAGNETIC_SENSOR_ADC,
,D/FactoryTestApp( 2653): [XMLDataStorage$redefinitionById](2653) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2653): [XMLDataStorage$parseAsset](2653) SemiFunctionMenu
,D/FactoryTestApp( 2653): [XMLDataStorage$parseAsset](2653) parseAsset Is Completed
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2653): [ModuleCommon$ModuleCommon](2653) Create ModuleCommon
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2653): [Support$Kernel.read](2653) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2653): [ModuleCommon$readFactoryMode](2653) mode: ON
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2653): [FactoryTestBroadcastReceiver$onReceive](2653) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2653): [Support$Values.getBoolean](2653) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 2653): [Support$Properties.get](2653) property=ro.factory.factory_binary
D/FactoryTestApp( 2653): [FactoryTestBroadcastReceiver$onReceive](2653) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2653): [ModuleCommon$getFtClientEnableState](2653) result : false
,I/FactoryTestApp( 2653): [ModuleCommon$connectedJIG](2653) ...
D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2653): [ModuleCommon$connectedJIG](2653) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2653): [Support$Kernel.read](2653) path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 2653): [ModuleCommon$connectedJIG](2653) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2653): [ModuleCommon$isConnectionModeNone](2653) mConnectionMode = gsm
I/FactoryTestApp( 2653): [ModuleCommon$isRunningFtClient](2653) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2653): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2653) start DummyFtClient service for APO
,W/ContextImpl( 2653): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2653): User mode
I/FactoryTestApp( 2653): [ModuleCommon$disableFtClient](2653) ...
,D/FactoryTestApp( 2653): [DummyFtClient$onCreate](2653) Create DummyFtClient service
I/FactoryTestApp( 2653): [XMLDataStorage$parsingXML](2653) FtClient => data parsing was completed.
D/FactoryTestApp( 2653): [DummyFtClient$onReceive](2653) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2653): [ModuleCommon$isConnectionModeNone](2653) mConnectionMode = gsm
,D/FactoryTestApp( 2653): [Support$Values.getBoolean](2653) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2653): [DummyFtClient$onStartCommand](2653) ...
,I/WifiService( 1018): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager( 1018): boot completed
,D/UsbDeviceManager( 1018): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1018): sending intent : ACTION_USB_CABLE_STATE : connected = true
,D/UsbDeviceManager( 1018): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/UsbDeviceManager( 1018): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,I/KeyguardEffectViewUtil( 1176): set resource id
,D/SettingsProvider( 1018): name = keyguard_default_wallpaper_res_id
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10054
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1176): handleBootCompleted()
D/KeyguardUpdateMonitor( 1176): handleBootCompleted()
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1018): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1018): [PALM] SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1018): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1018): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SamsungIME( 1786): showDlgMsgBox : false true true
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NfcService( 1454): call the applyRouting
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,I/RecoverySystem( 1018): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1018): No recovery log file
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2680): MountEmulatedStorage(),
I/libpersona( 2680): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2680): v2
I/libpersona( 2680): KNOX_SDCARD not a persona,
I/SELinux ( 2680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2680 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/Reset_Reason( 1018): resetString = NPON
,I/BootReceiver( 1018): Copying audit failures to DropBox
,I/BootReceiver( 1018): Checking for fsck errors
,V/OtaStartupReceiver( 1468): onOtaspChanged: mOtaspMode=1
,I/BootReceiver( 1018): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/TimaKeyStoreProvider( 2680): TimaSignature is unavailable
,D/ActivityThread( 2680): Added TimaKeyStore provider
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,E/Zygote  ( 2699): MountEmulatedStorage(),
E/Zygote  ( 2699): v2
I/libpersona( 2699): KNOX_SDCARD checking this for 1001,
,I/SELinux ( 2699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 2699): KNOX_SDCARD not a persona
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 2699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2699): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1018): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2699 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 2699): TimaSignature is unavailable
,D/ActivityThread( 2699): Added TimaKeyStore provider
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/File    ( 2680): fail readDirectory() errno=2
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 2699): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/BootReceiver( 1018): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,D/CrashAnrDetector( 1018): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
D/CrashAnrDetector( 1018): Hardware: MSM8916
D/CrashAnrDetector( 1018): Revision: 2
D/CrashAnrDetector( 1018): Bootloader: A500FUXXU1BOE6
D/CrashAnrDetector( 1018): Radio: unknown
D/CrashAnrDetector( 1018): Kernel: Linux version 3.10.49-4944491 (dpi@SWDD5811) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Thu May 21 16:42:57 KST 2015
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1018): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1018): Revision: '2'
D/CrashAnrDetector( 1018): ABI: 'arm'
D/CrashAnrDetector( 1018): pid: 6207, tid: 6945, name: Thread-1092  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1018): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9affbff0
D/CrashAnrDetector( 1018):     r0 6f37d4a8  r1 71893998  r2 12d11400  r3 13491040
D/CrashAnrDetector( 1018):     r4 000000c2  r5 6f37d4a8  r6 71893998  r7 13491040
D/CrashAnrDetector( 1018):     r8 71893940  r9 b9815788  sl 12d11400  fp 9b0fd8a8
D/CrashAnrDetector( 1018):     ip 9affbff0  sp 9affdff0  lr 7447e389  pc 7447e30c  cpsr a00f0030
D/CrashAnrDetector( 1018):     d0  12d1140071893940  d1  0073002000650010
D/CrashAnrDetector( 1018):     d2  c0c0c0c0c0c0c049  d3  0000000000000113
D/CrashAnrDetector( 1018):     d4  4040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1018):     d6  ffffffffff000000  d7  0000000000000003
D/CrashAnrDetector( 1018):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1018):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1018):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1018):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1018):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1018):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1018):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1018):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1018):     d24 4040404000404040  d25 4040404040404000
D/CrashAnrDetector( 1018):     d26 0303030303030303  d27 0303030303030303
D/CrashAnrDetector( 1018):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1018):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1018):     scr 20000013
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): backtrace:
D/CrashAnrDetector( 1018):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): stack:
D/CrashAnrDetector( 1018):          9affdf70  00000000  
D/CrashAnrDetector( 1018):          9affdf74  00000000  
D/CrashAnrDetector( 1018):          9affdf78  00000000  
D/CrashAnrDetector( 1018):          9affdf7c  00000000  
D/CrashAnrDetector( 1018):          9affdf80  00000000  
D/CrashAnrDetector( 1018):          9affdf84  00000000  
D/CrashAnrDetector( 1018):          9affdf88  00000000  
D/CrashAnrDetector( 1018):          9affdf8c  00000000  
D/CrashAnrDetector( 1018):          9affdf90  00000000  
D/CrashAnrDetector( 1018):          9affdf94  00000000  
D/CrashAnrDetector( 1018):          9affdf98  00000000  
D/CrashAnrDetector( 1018):          9affdf9c  00000000  
D/CrashAnrDetector( 1018):          9affdfa0  00000000  
D/CrashAnrDetector( 1018):          9affdfa4  00000000  
D/CrashAnrDetector( 1018):          9affdfa8  00000000  
D/CrashAnrDetector( 1018):          9affdfac  00000000  
D/CrashAnrDetector( 1018):          9affdfb0  00000000  
D/CrashAnrDetector( 1018):          9affdfb4  00000000  
D/CrashAnrDetector( 1018):          9affdfb8  00000000  
D/CrashAnrDetector( 1018):          9affdfbc  00000000  
D/CrashAnrDetector( 1018):          9affdfc0  00000000  
D/CrashAnrDetector( 1018):          9affdfc4 , 00000000  
D/CrashAnrDetector( 1018):          9affdfc8  00000000  
D/CrashAnrDetector( 1018):          9affdfcc  00000000  
D/CrashAnrDetector( 1018):          9affdfd0  6f36ac38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affdfd4  00000000  
D/CrashAnrDetector( 1018):          9affdfd8  00000000  
D/CrashAnrDetector( 1018):          9affdfdc  00000000  
D/CrashAnrDetector( 1018):          9affdfe0  00000000  
D/CrashAnrDetector( 1018):          9affdfe4  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affdfe8  e3a070ad  
D/CrashAnrDetector( 1018):          9affdfec  ef9000ad  
D/CrashAnrDetector( 1018):     #00  9affdff0  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          ........  ........
D/CrashAnrDetector( 1018):     #01  9affdff0  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affdff4  00000000  
D/CrashAnrDetector( 1018):          9affdff8  00000000  
D/CrashAnrDetector( 1018):          9affdffc  00000000  
D/CrashAnrDetector( 1018):          9affe000  00000000  
D/CrashAnrDetector( 1018):          9affe004  00000000  
D/CrashAnrDetector( 1018):          9affe008  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affe00c  71893940  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affe010  13491040  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9affe014  71893998  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affe018  12d11400  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9affe01c  7447e33d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):          9affe020  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affe024  00000000  
D/CrashAnrDetector( 1018):          9affe028  00000000  
D/CrashAnrDetector( 1018):          9affe02c  00000000  
D/CrashAnrDetector( 1018):          9affe030  6f36ac38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affe034  00000000  
D/CrashAnrDetector( 1018):          9affe038  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affe03c  71893998  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9affe040  13491040  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9affe044  71
D/CrashAnrDetector( 1018): processName:com.test.thalitest
D/CrashAnrDetector( 1018): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/FactoryTestApp( 2653): [ProtectedFactoryTestBroadcastReceiver$onReceive](2653) onReceive action=com.samsung.intent.action.SECPHONE_READY
,I/FactoryTestApp( 2653): [ProtectedFactoryTestBroadcastReceiver$onReceive](2653) com.samsung.intent.action.SECPHONE_READY
D/FactoryTest( 2653): User mode
,D/Mms/NotificationReceiver( 2334): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
D/Mms/NotificationReceiver( 2334): handleBootCompleted()
,D/Mms/RcsOwnCapsManager( 2334): queue Uri = content://im/queue-messages?box=pending
,D/TP/ImProvider( 1468): im query match24
,D/TP/ImProvider( 1468): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1468): ftSesstionId must be a long.
,D/TP/ImProvider( 1468): getQueuedImMessages
,D/TP/ImProvider( 1468): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/NotificationReceiver( 2334):  getPendingMessageIds: no pending messages.
,D/Mms/ActionsFactory( 2334): Call to GET_LAST_MESSAGES_SENT
,I/BootReceiver( 1018): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
,D/CrashAnrDetector( 1018): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
D/CrashAnrDetector( 1018): Hardware: MSM8916
D/CrashAnrDetector( 1018): Revision: 2
D/CrashAnrDetector( 1018): Bootloader: A500FUXXU1BOE6
D/CrashAnrDetector( 1018): Radio: unknown
D/CrashAnrDetector( 1018): Kernel: Linux version 3.10.49-4944491 (dpi@SWDD5811) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Thu May 21 16:42:57 KST 2015
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1018): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1018): Revision: '2'
D/CrashAnrDetector( 1018): ABI: 'arm'
D/CrashAnrDetector( 1018): pid: 6229, tid: 7053, name: Thread-1102  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1018): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9b907ff0
D/CrashAnrDetector( 1018):     r0 6f37d4a8  r1 71893998  r2 12c0bac0  r3 13350dc0
D/CrashAnrDetector( 1018):     r4 000000c2  r5 6f37d4a8  r6 71893998  r7 13350dc0
D/CrashAnrDetector( 1018):     r8 71893940  r9 ba1f25b8  sl 12c0bac0  fp 9ba098a8
D/CrashAnrDetector( 1018):     ip 9b907ff0  sp 9b909ff0  lr 7447e389  pc 7447e30c  cpsr a00f0030
D/CrashAnrDetector( 1018):     d0  12c0bac0718939c0  d1  007300200065000d
D/CrashAnrDetector( 1018):     d2  c0c0c0c0c0c0c035  d3  0000000000000113
D/CrashAnrDetector( 1018):     d4  4040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1018):     d6  ffffffffff000000  d7  0000000000000003
D/CrashAnrDetector( 1018):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1018):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1018):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1018):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1018):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1018):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1018):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1018):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1018):     d24 4040404000404040  d25 4040404040404000
D/CrashAnrDetector( 1018):     d26 0303030303030303  d27 0303030303030303
D/CrashAnrDetector( 1018):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1018):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1018):     scr 20000013
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): backtrace:
D/CrashAnrDetector( 1018):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): stack:
D/CrashAnrDetector( 1018):          9b909f70  00000000  
D/CrashAnrDetector( 1018):          9b909f74  00000000  
D/CrashAnrDetector( 1018):          9b909f78  00000000  
D/CrashAnrDetector( 1018):          9b909f7c  00000000  
D/CrashAnrDetector( 1018):          9b909f80  00000000  
D/CrashAnrDetector( 1018):          9b909f84  00000000  
D/CrashAnrDetector( 1018):          9b909f88  00000000  
D/CrashAnrDetector( 1018):          9b909f8c  00000000  
D/CrashAnrDetector( 1018):          9b909f90  00000000  
D/CrashAnrDetector( 1018):          9b909f94  00000000  
D/CrashAnrDetector( 1018):          9b909f98  00000000  
D/CrashAnrDetector( 1018):          9b909f9c  00000000  
D/CrashAnrDetector( 1018):          9b909fa0  00000000  
D/CrashAnrDetector( 1018):          9b909fa4  00000000  
D/CrashAnrDetector( 1018):          9b909fa8  00000000  
D/CrashAnrDetector( 1018):          9b909fac  00000000  
D/CrashAnrDetector( 1018):          9b909fb0  00000000  
D/CrashAnrDetector( 1018):          9b909fb4  00000000  
D/CrashAnrDetector( 1018):          9b909fb8  00000000  
D/CrashAnrDetector( 1018):          9b909fbc  00000000  
D/CrashAnrDetector( 1018):          9b909fc0  00000000  
D/CrashAnrDetector( 1018):          9b909fc4 , 00000000  
D/CrashAnrDetector( 1018):          9b909fc8  00000000  
D/CrashAnrDetector( 1018):          9b909fcc  00000000  
D/CrashAnrDetector( 1018):          9b909fd0  6f36ac38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b909fd4  00000000  
D/CrashAnrDetector( 1018):          9b909fd8  00000000  
D/CrashAnrDetector( 1018):          9b909fdc  00000000  
D/CrashAnrDetector( 1018):          9b909fe0  00000000  
D/CrashAnrDetector( 1018):          9b909fe4  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b909fe8  e3a070ad  
D/CrashAnrDetector( 1018):          9b909fec  ef9000ad  
D/CrashAnrDetector( 1018):     #00  9b909ff0  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          ........  ........
D/CrashAnrDetector( 1018):     #01  9b909ff0  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b909ff4  00000000  
D/CrashAnrDetector( 1018):          9b909ff8  00000000  
D/CrashAnrDetector( 1018):          9b909ffc  00000000  
D/CrashAnrDetector( 1018):          9b90a000  00000000  
D/CrashAnrDetector( 1018):          9b90a004  00000000  
D/CrashAnrDetector( 1018):          9b90a008  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b90a00c  71893940  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b90a010  13350dc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9b90a014  71893998  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b90a018  12c0bac0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9b90a01c  7447e33d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):          9b90a020  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b90a024  00000000  
D/CrashAnrDetector( 1018):          9b90a028  00000000  
D/CrashAnrDetector( 1018):          9b90a02c  00000000  
D/CrashAnrDetector( 1018):          9b90a030  6f36ac38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b90a034  00000000  
D/CrashAnrDetector( 1018):          9b90a038  6f37d4a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b90a03c  71893998  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9b90a040  13350dc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9b90a044  71
D/CrashAnrDetector( 1018): processName:com.test.thalitest
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1018): broadcastEvent : null SYSTEM_TOMBSTONE
D/SettingsProvider( 1018): name = db_smartlock_supported
D/CrashAnrDetector( 1018): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
D/CrashAnrDetector( 1018): Hardware: MSM8916
D/CrashAnrDetector( 1018): Revision: 2
D/CrashAnrDetector( 1018): Bootloader: A500FUXXU1BOE6
D/CrashAnrDetector( 1018): Radio: unknown
D/CrashAnrDetector( 1018): Kernel: Linux version 3.10.49-4944491 (dpi@SWDD5811) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Thu May 21 16:42:57 KST 2015
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1018): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1018): Revision: '2'
D/CrashAnrDetector( 1018): ABI: 'arm'
D/CrashAnrDetector( 1018): pid: 2846, tid: 3250, name: Thread-332  >>> com.example.hello <<<
D/CrashAnrDetector( 1018): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 1018):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector( 1018):     r4 9d33ae78  r5 9d33ae38  r6 b93f4900  r7 9d33ae38
D/CrashAnrDetector( 1018):     r8 00000000  r9 9d33ae74  sl 9d33c3d0  fp 9d33ae1c
D/CrashAnrDetector( 1018):     ip 9cbf5ba0  sp 9d33ae00  lr 9c8fc308  pc b6e9a468  cpsr 600d0030
D/CrashAnrDetector( 1018):     d0  513802003a373ed5  d1  0000b80c03000001
D/CrashAnrDetector( 1018):     d2  88000000560a109c  d3  0000003502000060
D/CrashAnrDetector( 1018):     d4  0000008849000000  d5  0a0e000000b80c0c
D/CrashAnrDetector( 1018):     d6  01003a0f0000003d  d7  0000885103000057
D/CrashAnrDetector( 1018):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1018):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1018):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1018):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1018):     d16 0000000000000000  d17 ffffffffffffffff
D/CrashAnrDetector( 1018):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1018):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1018):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1018):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1018):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1018):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1018):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1018):     scr 20000012
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): backtrace:
D/CrashAnrDetector( 1018):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector( 1018):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): stack:
D/CrashAnrDetector( 1018):          9d33ad80  00000000  
D/CrashAnrDetector( 1018):          9d33ad84  00000000  
D/CrashAnrDetector( 1018):          9d33ad88  9bf2b820  [anon:js-gc-heap]
D/CrashAnrDetector( 1018):          9d33ad8c  fb60be01  
D/CrashAnrDetector( 1018):          9d33ad90  9d33adbc  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ad94  9d33ae64  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ad98  b93f4900  [heap]
D/CrashAnrDetector( 1018):          9d33ad9c  00000003  
D/CrashAnrDetector( 1018):          9d33ada0  9d33addc  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ada4  b9531238  [heap]
D/CrashAnrDetector( 1018):          9d33ada8  9bf53b00  [anon:js-gc-heap]
D/CrashAnrDetector( 1018):          9d33adac  9c011b30  [anon:js-gc-heap]
D/CrashAnrDetector( 1018):          9d33adb0  00000000  
D/CrashAnrDetector( 1018):          9d33adb4  ffffff82  
D/CrashAnrDetector( 1018):          9d33adb8  00000000  
D/CrashAnrDetector( 1018):          9d33adbc  ffffff82  
D/CrashAnrDetector( 1018):          9d33adc0  9bf2b040  [anon:js-gc-heap]
D/CrashAnrDetector( 1018):          9d33adc4  b952e238  [heap]
D/CrashAnrDetector( 1018):,          9d33adc8  b95754f8  [heap]
D/CrashAnrDetector( 1018):          9d33adcc  00000001  
D/CrashAnrDetector( 1018):          9d33add0  9bf49160  [anon:js-gc-heap]
D/CrashAnrDetector( 1018):          9d33add4  b93f4900  [heap]
D/CrashAnrDetector( 1018):          9d33add8  9bf4f1c0  [anon:js-gc-heap]
D/CrashAnrDetector( 1018):          9d33addc  00000000  
D/CrashAnrDetector( 1018):          9d33ade0  00000000  
D/CrashAnrDetector( 1018):          9d33ade4  00000000  
D/CrashAnrDetector( 1018):          9d33ade8  00000003  
D/CrashAnrDetector( 1018):          9d33adec  000000aa  
D/CrashAnrDetector( 1018):          9d33adf0  0000006b  
D/CrashAnrDetector( 1018):          9d33adf4  0001416e  
D/CrashAnrDetector( 1018):          9d33adf8  00000000  
D/CrashAnrDetector( 1018):          9d33adfc  9d33ae30  [stack:3250]
D/CrashAnrDetector( 1018):     #00  9d33ae00  9d33ae78  [stack:3250]
D/CrashAnrDetector( 1018):          ........  ........
D/CrashAnrDetector( 1018):     #01  9d33ae00  9d33ae78  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ae04  00000000  
D/CrashAnrDetector( 1018):          9d33ae08  9d33ae78  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ae0c  9d33ae5c  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ae10  9d33ae48  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ae14  00000000  
D/CrashAnrDetector( 1018):          9d33ae18  9d33be94  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ae1c  9c8d33f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 1018):          9d33ae20  9d33ae50  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ae24  00000000  
D/CrashAnrDetector( 1018):          9d33ae28  9d33ae44  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ae2c  9c705184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector( 1018):          9d33ae30  00000000  
D/CrashAnrDetector( 1018):          9d33ae34  00000000  
D/CrashAnrDetector( 1018):          9d33ae38  b6ee0de4  
D/CrashAnrDetector( 1018):          9d33ae3c  00000000  
D/CrashAnrDetector( 1018):          9d33ae40  9d33b1cc  [stack:3250]
D/CrashAnrDetector( 1018):          9d33ae44  9c7e1b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
D/CrashAnrDetector( 1018):          9d33ae48  b93f4900  [heap]
D/CrashAnrDetector( 1018):          9d33ae4c  b93f4900  [heap]
D/CrashAnrDetector( 1018):          9d33ae50  b95754f8  [heap]
D/CrashAnrDetector( 1018):          9d33ae54  00000001  
D/CrashAnrDetector( 1018):          9d33ae58  9
D/CrashAnrDetector( 1018): processName:com.example.hello
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1018): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
I/AccessibilityManagerService( 1018): setmDNIeNegative (false)
E/SMD     (  291): DCD OFF
,W/Settings( 1307): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 25
,D/SettingsProvider( 1018): name = block_emergency_message
,D/SettingsProvider( 1018): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,E/SmartFaceService( 1018): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1018): no icon
E/SmartFaceService( 1018): mActiveServiceType: 0
E/SmartFaceService( 1018): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1018): updateClientsDone. def. do nothing.
E/SmartFaceService( 1018): Service Type to Worker: 0
E/SmartFaceService( 1018): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1018): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/RCPManagerService( 1018): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1018):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/RCPManagerService( 1018): BootReceiver.onReceive(): Starting RCP Proxy for user = null
,E/RCPManagerService( 1018):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,V/AlarmManagerEXT( 1018): mGmsLocationBundling: false
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/SensorService( 1018): [SO] activate (ident=0xb9453cc8, enabled=0),
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1018): [SO] changed settle time [0]
,D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb9453cc8, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/EnterpriseDeviceManagerService( 1018): android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1018): runAdminUpdate
,D/EnterpriseUtils( 1018): File Not Found : /data/system/selfUpdateAdmin.conf
,V/ApplicationPolicy( 1018): boot completed - refreshWidgetStatus
,V/ApplicationPolicy( 1018): refresh widget status for user 0
,D/EnterpriseDeviceManagerService( 1018): nothing to selfUpdate
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/,ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,W/PhoneRestrictionPolicy( 1018): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1018): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,I/KnoxMUMContainerPolicy( 1018): MSG_REMOVE_ORPHANED_CONTAINERS received
,W/PhoneRestrictionPolicy( 1018):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1018): cvList size 0
W/PhoneRestrictionPolicy( 1018):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1018): cvList size 0
,D/WifiP2pService( 1018): P2pDisabledState{ what=143415 }
D/WifiP2pService( 1018): DefaultState{ what=143415 }
,D/ConnectivityService( 1018): Got NetworkFactory Messenger for WIFI_P2P
,D/WIFI_P2P( 1018): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/WifiStateMachine( 1018): Blacklist file delete
,D/ConnectivityService( 1018): Got NetworkFactory Messenger for WIFI
,D/Tethering( 1018): Boot complete.
,V/EnterpriseBillingEngine( 1018): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1018): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1018): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1018): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1018): handleAllprofiles - end
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
D/UsbHostNotification( 1018): boot completed
,D/UsbHostRestrictor( 1018): mBootCompletedReceiver onReceive
,D/UsbHostRestrictor( 1018): initSetUsbBlock STARTED
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,D/UsbHostRestrictor( 1018): SIM was never inserted
,D/UsbHostRestrictor( 1018): writableHostSysNode[false]
,D/UsbHostRestrictor( 1018): Can NOT Write Disable Sys Node to [ON]
,D/PersonaManagerService( 1018): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1018):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/KnoxKeyguardUpdateMonitor( 1018): onBootComplete
,I/KnoxKeyguardUpdateMonitor( 1018): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1018): onTrustChanged user:0, enable:false
,D/KeyguardViewMediator( 1176): onTrustChanged( Showing = false , userId = 0 )
D/UsbStorageNotification( 1018): boot completed
,D/WIFI    ( 1018): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,D/GpsLocationProvider_ex( 1018): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1018): set_capabilities_callback: 55u
,I/libmdmdetect( 1018): ESOC framework not supported
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,D/qmi_secgps_clnt( 1018): qmi_secgps_client_init()
,I/libmdmdetect( 1018): Found internal modem: modem
E/PerMgrLib( 1018): Peripheral manager is not supported on this device
E/Geofence_Adapter( 1018): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1018): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
,D/GpsLocationProvider_ex( 1018): BOOT_COMPLETED native_cleanup 
,D/StorageNotification( 1176): boot completed
,D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2,
D/StatusBarManagerService( 1018): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ),
D/PhoneStatusBar( 1176): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
,D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2736): MountEmulatedStorage()
E/Zygote  ( 2736): v2
I/libpersona( 2736): KNOX_SDCARD checking this for 10099
I/libpersona( 2736): KNOX_SDCARD not a persona
,I/SELinux ( 2736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2736 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 2736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2736): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/i       ( 1018): No model
,D/FactoryTest( 1018): Not factory mode
D/FactoryTest( 1018): Not factory mode. isFactoryMode() returend false
D/w       ( 1018): isUserBuild = true
,D/TimaKeyStoreProvider( 2736): TimaSignature is unavailable
,D/ActivityThread( 2736): Added TimaKeyStore provider
,D/SSRM:n  ( 1018): SIOP:: AP = 360
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,D/SensorService( 1018): [SO] 0.172 0.134 10.209
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1018): [SO] activate (ident=0xb9453cc8, enabled=0)
,I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb9453cc8, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/LocSvc_utils_cfg( 1018): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  ,
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1018): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,I/qmi_secgps_clnt( 1018): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1018): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1018): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,D/SensorService( 1018): [SO] currT = 31801044000, prevT = 31451159000, diff = 349885000, [0.172 0.134 10.209]
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,E/ActivityThread( 2736): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2736): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1018): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
,I/splitIntent( 1018): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/DrmEventReceiver( 1018): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1018): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1018): DrmEventReceiver : beginStartingService
I/System.out( 1018): start Service
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1018): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/DownloadManager( 1225): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2755): MountEmulatedStorage(),
E/Zygote  ( 2755): v2
I/libpersona( 2755): KNOX_SDCARD checking this for 10085
I/libpersona( 2755): KNOX_SDCARD not a persona
,I/SELinux ( 2755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2755 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 2755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 2767): MountEmulatedStorage()
E/Zygote  ( 2767): v2
I/libpersona( 2767): KNOX_SDCARD checking this for 1000
I/libpersona( 2767): KNOX_SDCARD not a persona
,D/SensorService( 1018): [SO] currT = 31871136000, prevT = 31451159000, diff = 419977000, [0.172 0.134 10.209]
I/SELinux ( 2767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/SensorService( 1018): [SO] 0.172 0.134 10.209
D/SensorService( 1018): [SO] [100 -> 255]
,I/SELinux ( 2767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2755): TimaSignature is unavailable
I/ActivityManager( 1018): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 2755): Added TimaKeyStore provider
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/TimaKeyStoreProvider( 2767): TimaSignature is unavailable
,D/ActivityThread( 2767): Added TimaKeyStore provider
D/WVMDrmPlugIn(  282): WVMDrmPlugin::onInitialize : 1156
,D/WVMDrmPlugIn(  282): WVMDrmPlugin::onSetOnInfoListener : add 1156
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,I/TimaServiceEventReceiver( 1018): TimaServiceEventReceiver : onReceive
,I/DrmEventService( 1018): action event :android.intent.action.BOOT_COMPLETED
,D/MediaScannerReceiver( 1225): action: android.intent.action.BOOT_COMPLETED
,I/ANDROID_DRM_FRWORKS_DrmManager(  282): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,W/ResourcesManager( 2755): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 2755): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2755): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2755): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 2755): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2755): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/CscReceiver( 1468): onReceive android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1468): onStart
E/CscUpdateService( 1468): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1468): set_CSC_version
E/CscParser( 1468): update(): xml file exist
,E/Zygote  ( 2789): MountEmulatedStorage()
I/libpersona( 2789): KNOX_SDCARD checking this for 10160
E/Zygote  ( 2789): v2
I/libpersona( 2789): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2789 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/SELinux ( 2789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2789): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CscUtil ( 1468): isWifiOnly = false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/System.out( 1468): HandDataNode = null
I/CscUpdateService( 1468): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1468): This is normal boot : CSC not updated
,E/CscParser( 1468): update(): xml file exist
,E/Zygote  ( 2799): MountEmulatedStorage()
,E/Zygote  ( 2799): v2,
,I/libpersona( 2799): KNOX_SDCARD checking this for 10003
I/libpersona( 2799): KNOX_SDCARD not a persona
,I/SELinux ( 2799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2799 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
I/SELinux ( 2799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,D/CscGPS  ( 1468): CSCGPS.updateParameters
D/CscGPS  ( 1468): supl host : null
D/CscGPS  ( 1468): SUPL Host is null or invalid
D/CscGPS  ( 1468): supl_ver : null
D/CscGPS  ( 1468): SUPL Ver is null or invalid
D/CscGPS  ( 1468): supl port : null
D/CscGPS  ( 1468): SUPL PORT is null or invalid
D/CscGPS  ( 1468): LPP : null
D/CscGPS  ( 1468): LPP is null or invalid
D/CscGPS  ( 1468): CSC don't have any AGPS value.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/TimaKeyStoreProvider( 2789): TimaSignature is unavailable
,D/ActivityThread( 2789): Added TimaKeyStore provider
,I/CscUpdateService( 1468): same CSC Version
D/CscUtil ( 1468): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
,D/TimaKeyStoreProvider( 2799): TimaSignature is unavailable
,D/ActivityThread( 2799): Added TimaKeyStore provider
,W/ResourcesManager( 2789): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/MediaScannerService( 1225): !@start scanning volume internal: [/system/media, /oem/media]
,D/SettingsProvider( 1018): name = next_alarm_formatted
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10085
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1225): updating state; isCurrentUser=true, mMtpLocked=false,
,W/CursorWrapperInner( 2334): Cursor finalized without prior close()
,E/SQLiteLog( 1225): (283) recovered 569 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
D/TP/MmsProvider( 1468): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1468): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
,I/Mms:transaction( 2334): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,D/Mms/MessagingNotification( 2334): [start]    nonBlockingUpdateMessageIndicator() consume time = 2319.077812
,I/Mms/ReservationManager( 2334): resetAfterConnected()
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/TP/MmsSmsProvider( 1468): query,matched:7, calling pid = 2334
,D/Mms/MessagingNotification( 2334): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2334): isDefault true
,D/TP/MmsProvider( 1468): Query uri=content://mms, match=0, calling pid = 2334
,D/TP/MmsSmsProvider( 1468): match 7:Elapsed time : 5.685 ms
,I/Mms/ReservationManager( 2334): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1468): query,matched:200, calling pid = 2334
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1468): match 200:Elapsed time : 2.393 ms
E/USB_UICC(  299): Timeout! No signal received. Retry num = 26
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2799): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,E/Zygote  ( 2827): MountEmulatedStorage()
,E/Zygote  ( 2827): v2
I/libpersona( 2827): KNOX_SDCARD checking this for 10048
I/libpersona( 2827): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2827 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 2827): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,I/SELinux ( 2827): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2827): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/SmsProvider( 1468): query,matched:0, calling pid = 2334
,D/TP/SmsProvider( 1468): match 0:Elapsed time : 1.319 ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:UMCContentProvider( 2789): @onCreate
,D/TimaKeyStoreProvider( 2827): TimaSignature is unavailable
D/ActivityThread( 2827): Added TimaKeyStore provider
,E/Zygote  ( 2844): MountEmulatedStorage(),
,I/ActivityManager( 1018): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2844 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 2844): v2,
D/TP/SmsProvider( 1468): query,matched:51, calling pid = 2334
I/libpersona( 2844): KNOX_SDCARD checking this for 1000
I/libpersona( 2844): KNOX_SDCARD not a persona
I/SELinux ( 2844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TP/SmsProvider( 1468): match 51:Elapsed time : 2.055 ms
,D/Mms/SmsReceiverService( 2334): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
I/SELinux ( 2844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/Mms/TelephonyPermission( 2334): isDefault true
D/Mms/SmsReceiverService( 2334): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
E/SELinux ( 2844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[0]UMC:Core( 2789): onCreate(): 
D/[0]UMC:Core( 2789): @isManagedProfileUser
D/[0]UMC:Core( 2789): userId: 0
D/Mms/SmsReceiverService( 2334): [start]    handleBootCompleted() consume time = 145.445208
,D/[0]UMC:Core( 2789): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2789): userInfo.isManagedProfile() : false
,W/ResourcesManager( 2827): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2827): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2827): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2844): TimaSignature is unavailable
,D/ActivityThread( 2844): Added TimaKeyStore provider
,I/SecureStorage( 2799): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  401): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2799
I/SecureStorage(  401): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
,I/SecureStorage( 2799): [INFO]: SPID(0x00000000)SS Daemon is running
,I/SecureStorage( 2799): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  401): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2799
I/SecureStorage(  401): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,D/[0]UMC:DeviceInfo( 2789): USA==US==
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,D/USER_AGENT( 2789): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,W/art     ( 2755): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 160.881ms
,D/[0]UMC:AdminManager( 2789): init - start
,D/[0]UMC:AdminManager( 2789): loadAdmins
,D/[0]UMC:AdminManager( 2789): init - end
,D/GSLBManager( 2789): migrateStoredUrlFromOldPref
,D/GSLBManager( 2789):  key : segd-api
,D/GSLBManager( 2789):  value : https://eu-segd-api.secb2b.com:443/v2
,D/GSLBManager( 2789):  key : umc-cdn
,D/GSLBManager( 2789):  value : 
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 56907(3MB) AllocSpace objects, 68(4MB) LOS objects, 33% free, 26MB/39MB, paused 2.150ms total 165.188ms
,D/Mms/MessagingNotification( 2334): isBlockingModeEnabled() = false, Zen mode = 0
,D/GSLBManager( 2789):  key : segp-api
D/GSLBManager( 2789):  value : 
,D/MediaScanner( 1225): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/TP/MmsSmsProvider( 1468): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1468): deleteConversation threadId: 9223372036854775806
,D/BadgeProvider( 1586): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/GSLBManager( 2789):  key : myknoxapi
D/GSLBManager( 2789):  value : 
,D/SettingsProvider( 1018): name = block_emergency_message
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10048
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/ActivityManager( 1018): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/TP/MmsSmsProvider( 1468): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1468): updateThread(), thread_id = 9223372036854775806
,D/GSLBManager( 2789): migrateStoredUrlFromOldPref : Finished Migrating
,D/[0]UMC:UMCAdmin( 2789): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2789): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2789): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,V/TP/MmsSmsDatabaseHelper( 1468): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
D/[0]UMC:UMCAdmin( 2789): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2789): isContainer : 0
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
,D/BadgeProvider( 1586): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1586): sendNotify, [notify] : null
D/BadgeProvider( 1586): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1586): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1586): update, [UpdateCount] : 1
,D/Launcher.Model( 1492): reloadBadges entered.
D/Mms/MessagingNotification( 2334): setBadgeCount(), count=0
,D/TP/MmsSmsProvider( 1468): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
,D/Mms/MessagingNotification( 2334): remove alarm
,D/Mms/Conversation( 2334): deleteTempConversation(),deleted=0
,D/EnterpriseDeviceManagerService( 1018): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2789): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2789): isContainer : 0
,D/[0]UMC:UMCAdmin( 2789): deactivateUMCAdmin - UMC App Admin deactivated
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,I/WifiCredService( 1307): onCreate
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2789): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
D/[0]UMC:CoreReceiver( 2789): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2789):  check PreETag 
,D/SmsProvider( 1468): Update uri=content://sms/outbox, match=8
,D/TP/SmsProvider( 1468): query,matched:0, calling pid = 2334,
,D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
,D/TP/SmsProvider( 1468): match 0:Elapsed time : 8.214 ms
,D/Mms/SmsReceiverService( 2334): moveOutboxMessagesToFailedBox messageCount: 0
,D/Mms/SmsReceiverService( 2334): handle boot completed, sendFirstQueuedMessage()
,D/WifiTimerReceiver( 1307): action: android.intent.action.BOOT_COMPLETED
D/Mms/MessagingNotification( 2334): updateAllHistoryAsRead()
D/WifiTimerReceiver( 1307): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1307): Action boot completed received
,D/Mms/SmsReceiverService( 2334): [SIM-1]sendFirstQueuedMessage()
,D/TP/SmsProvider( 1468): query,matched:26, calling pid = 2334
,D/Mms/MessagingNotification( 2334): [end]    nonBlockingUpdateMessageIndicator() consume time = 283.375261
D/TP/SmsProvider( 1468): match 26:Elapsed time : 1.118 ms
,D/NearbySettings( 1307): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1307): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1307): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1018): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,D/[0]UMC:CoreReceiver( 2789): bulk enrolled package: null
V/[0]UMC:ProfileStorage( 2789): Enter loadList
,D/[0]UMC:CoreReceiver( 2789): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2789): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2789): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2789): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2789): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2789): isContainer : 0
D/EnterpriseDeviceManagerService( 1018): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2789): No active admin owned by uid 10160
,D/[0]UMC:UMCAdmin( 2789): isContainer : 0
,D/[0]UMC:UMCAdmin( 2789): deactivateUMCAdmin - UMC App Admin deactivated
,D/[0]UMC:ByodSetupStarter( 2789): Container ID : 0
,V/[0]UMC:Utils( 2789): checkAppScreen() : com.example.hello
,I/[0]UMC:Core( 2789): shutdown
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/MediaScanner( 1225): processDirectory :  /system/media
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2789): @GuardService - stopService Result = true
I/art     ( 2789): System.exit called, status: 0
I/AndroidRuntime( 2789): VM exiting with result code 0, cleanup skipped.
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/NearbySettings( 1307): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 1307): MountReceiver.onReceive - Internal Path
,D/SettingsProvider( 1018): name = personal_mode_enabled
,I/ActivityManager( 1018): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2789)(adj 0) has died(161,1015)
,I/art     ( 1468): Explicit concurrent mark sweep GC freed 39239(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 8MB/13MB, paused 954us total 69.941ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1278): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1278): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ResourcesManager( 1468): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 1468): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1278): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
V/MediaScanner( 1225):  prescan time: 496ms (DB items: 141)
V/MediaScanner( 1225):     scan time: 110ms (Caching mode: true), (makeEntry time: 45ms ~40%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 606ms
V/MediaScanner( 1225): checked files: 133  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1225): checkDefaultSounds,
D/MediaScanner( 1225): system alarm_alert  : Vwiurug_etwofi5wgg
I/ActivityManager( 1018): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2875 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 2875): MountEmulatedStorage()
E/Zygote  ( 2875): v2
I/libpersona( 2875): KNOX_SDCARD checking this for 1000
I/libpersona( 2875): KNOX_SDCARD not a persona
,I/SELinux ( 2875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/comsamsunglog( 1278): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1278): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1278): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1278): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1278): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1278): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,I/SELinux ( 2875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2875): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/ResourcesManager( 1468): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/MediaScanner( 1225): OK. alarm_alert is already exist in setting DB.
D/SettingsProvider( 1018): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10162
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/MediaScanner( 1225): system notification_sound  : K_Oprkltf5wgg
E/SQLiteLog( 2844): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 1468): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 8772(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.187ms total 27.143ms,
D/MediaScanner( 1225): OK. notification_sound is already exist in setting DB.
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
D/TimaKeyStoreProvider( 2875): TimaSignature is unavailable
D/ActivityThread( 2875): Added TimaKeyStore provider
,D/MediaScanner( 1225): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 1225): OK. ringtone is already exist in setting DB.
,W/ProcessCpuTracker( 1018): Skipping unknown process pid 2789
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 25.621ms
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/FactoryTestApp( 2653): [DummyFtClient$mBroadcastReceiver](2653) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2653): [DummyFtClient$mBroadcastReceiver](2653) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2653): [DummyFtClient$mBroadcastReceiver](2653) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 592us total 20.832ms
D/daemonapp( 1278): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1278): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/MediaScannerService( 1225): !@done scanning volume internal
D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SmartcardBootCompleteReceiver( 1307): SmartcardBootCompleteReceiver - onReceive() 
D/MediaScannerService( 1225): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
I/SmartcardBootCompleteReceiver( 1307): Received intent with action - android.intent.action.BOOT_COMPLETED
,D/Mms/SmsReceiver( 2334): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2334): sDisableVibrateForCamera = false
,D/Mms/TelephonyPermission( 2334): isDefault true
,E/daemonapp( 1278): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/DSM     ( 2844): [Lines:107] Normal booted
D/DSM     ( 2844): [Lines:114] Boot completed
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1278): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1452552470845
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/daemonapp( 1278): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1452574020000
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
D/daemonapp( 1278): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/daemonapp( 1278): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/TP/MmsProvider( 1468): Query uri=content://mms, match=0, calling pid = 2334
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
,W/ResourcesManager( 2875): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,E/Zygote  ( 2890): MountEmulatedStorage()
I/libpersona( 2890): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2890): v2
I/libpersona( 2890): KNOX_SDCARD not a persona
,I/SELinux ( 2890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2890 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 1191:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/MediaScanner( 1225): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/SmartcardBootCompleteReceiver( 1307): Broadcast sent with current lockscreen type
,D/daemonapp( 1278): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1452574020000
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 13
D/daemonapp( 1278): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1452574020000
,D/TimaKeyStoreProvider( 2890): TimaSignature is unavailable
,D/ActivityThread( 2890): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1468): query,matched:200, calling pid = 2334
,D/comdaemonstockapp( 1278): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1278): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/TP/MmsSmsProvider( 1468): match 200:Elapsed time : 3.588 ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/MediaScanner( 1225): processDirectory :  /storage/emulated/0
,W/ResourcesManager( 2890): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/Zygote  ( 2907): MountEmulatedStorage(),
,E/Zygote  ( 2907): v2
,I/libpersona( 2907): KNOX_SDCARD checking this for 10086
I/SELinux ( 2907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 2907): KNOX_SDCARD not a persona
D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(75ebcf7
D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
I/SELinux ( 2907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2907 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 2907): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 1389:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,V/MediaScanner( 1225): processDirectory :  /storage/extSdCard
W/MediaScanner( 1225): Error opening directory, reason : Permission denied.
W/MediaScanner( 1225): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1225):  prescan time: 86ms (DB items: 27)
V/MediaScanner( 1225):     scan time: 33ms (Caching mode: true), (makeEntry time: 26ms ~78%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 121ms
V/MediaScanner( 1225): checked files: 10  directories : 17  (I: 0, U: 0)
,D/MediaScannerService( 1225): !@done scanning volume external
,D/FactoryTestApp( 2653): [DummyFtClient$mBroadcastReceiver](2653) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2653): [DummyFtClient$mBroadcastReceiver](2653) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,D/FactoryTestApp( 2653): [DummyFtClient$sendBootCompletedAndFinish](2653) ...
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2653): [ModuleCommon$isConnectionModeNone](2653) mConnectionMode = gsm
,D/FactoryTestApp( 2653): [IPCWriterToSecPhoneService$ResponseWriter](2653) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2653): [IPCWriterToSecPhoneService$connectToSecPhoneService](2653)  
W/ContextImpl( 1883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ContextImpl( 2653): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/TimaKeyStoreProvider( 2907): TimaSignature is unavailable
D/ActivityThread( 2907): Added TimaKeyStore provider
,D/SecUISvc( 1883): Service started flags 0 startId 1
,D/SecUISvc( 1883): Thread created.,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/[SBeam] ( 1307): SBeamEnabler.initPreferenceForSbeam : 0
,D/TP/SmsProvider( 1468): query,matched:0, calling pid = 2334
,D/TP/SmsProvider( 1468): match 0:Elapsed time : 1.510 ms
,E/Zygote  ( 2926): MountEmulatedStorage()
I/libpersona( 2926): KNOX_SDCARD checking this for 10028
E/Zygote  ( 2926): v2
I/libpersona( 2926): KNOX_SDCARD not a persona
,I/SELinux ( 2926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ActivityThread( 2890): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/SELinux ( 2926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2926): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2926 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,I/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1191/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1389/cgroup.procs: No such file or directory
,I/FactoryTestApp( 2653): [IPCWriterToSecPhoneService$onServiceConnected](2653) connected done
D/FactoryTestApp( 2653): [IPCWriterToSecPhoneService$write](2653) Send Response Message to SecPhone
D/FactoryTestApp( 2653): [IPCWriterToSecPhoneService$write](2653) Response ��
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/TimaKeyStoreProvider( 2926): TimaSignature is unavailable
D/ActivityThread( 2926): Added TimaKeyStore provider
,D/TP/SmsProvider( 1468): query,matched:51, calling pid = 2334
,D/TP/SmsProvider( 1468): match 51:Elapsed time : 2.716 ms
,I/iu.UploadsManager( 1854): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/SettingSearch/SearchIntentReceiver( 1307): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1307): search setting db init!!
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/AT_Distributor(  313): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/Mms/MessagingNotification( 2334): isBlockingModeEnabled() = false, Zen mode = 0
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
I/SecureStorage(  401): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,I/SettingSearch/SearchIntentReceiver( 1307): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 2890): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,D/FactoryTestApp( 2653): [IPCWriterToSecPhoneService$handleMessage](2653) Send BOOTING COMPLETED done
,I/LcdtestApp( 2890): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/BadgeProvider( 1586): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2947): MountEmulatedStorage(),
E/Zygote  ( 2947): v2
I/libpersona( 2947): KNOX_SDCARD checking this for 1000
I/libpersona( 2947): KNOX_SDCARD not a persona,
I/SELinux ( 2947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
D/AT_Distributor(  313): SetAtdStatus(), 1_1_0
D/AT_Distributor(  313): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 27
I/ServiceManager(  317): Waiting for service AtCmdFwd...
E/SELinux ( 2947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2947 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2960): MountEmulatedStorage(),
E/Zygote  ( 2960): v2
I/libpersona( 2960): KNOX_SDCARD checking this for 10150,
I/libpersona( 2960): KNOX_SDCARD not a persona
,I/SELinux ( 2960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2960 uid=10150 gids={50150, 9997} abi=armeabi-v7a,
,I/SELinux ( 2960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/TimaKeyStoreProvider( 2947): TimaSignature is unavailable
,D/ActivityThread( 2947): Added TimaKeyStore provider,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/SELinux ( 2960): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2799): [INFO]: SPID(0x00000001)Processing data has been completed
,I/SecureStorage( 2799): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
,E/Zygote  ( 2974): MountEmulatedStorage()
E/Zygote  ( 2974): v2
I/libpersona( 2974): KNOX_SDCARD checking this for 1000
I/libpersona( 2974): KNOX_SDCARD not a persona
,I/SELinux ( 2974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2974 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2960): TimaSignature is unavailable
,D/ActivityThread( 2960): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2974): TimaSignature is unavailable
,D/ActivityThread( 2974): Added TimaKeyStore provider
,W/ResourcesManager( 2974): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/iu.UploadsManager( 1854): End new media; added: 0, uploading: 0, time: 155 ms
,D/Launcher.Model( 1492): reloadBadges entered.
,D/BadgeProvider( 1586): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 1586): sendNotify, [notify] : null
D/BadgeProvider( 1586): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1586): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1586): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 2334): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2334): remove alarm
,D/Mms/MessagingNotification( 2334): updateAllHistoryAsRead()
,D/TP/SmsProvider( 1468): query,matched:0, calling pid = 2334
,D/TP/SmsProvider( 1468): match 0:Elapsed time : 3.866 ms
,D/Mms/SmsReceiverService( 2334): [end]    handleBootCompleted() consume time = 821.448489
,I/ActivityManager( 1018): Killing 1407:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,E/UpdateRequestReceiver( 2907): ignoring update request
,E/UpdateRequestReceiver( 2907): ignoring update request
,I/FOTA    ( 2974): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,I/DIAGMON_AGENT( 2947): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,E/UpdateRequestReceiver( 2907): ignoring update request
,W/libprocessgroup( 1018): failed to open /acct/uid_10096/pid_1407/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 2907): ignoring update request
,E/UpdateRequestReceiver( 2907): ignoring update request
,E/UpdateRequestReceiver( 2907): ignoring update request
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3011): MountEmulatedStorage()
E/Zygote  ( 3011): v2
I/libpersona( 3011): KNOX_SDCARD checking this for 10094
I/libpersona( 3011): KNOX_SDCARD not a persona
,I/SELinux ( 3011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3011): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3011 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 1586:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,D/TimaKeyStoreProvider( 3011): TimaSignature is unavailable
,D/ActivityThread( 3011): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10072/pid_1586/cgroup.procs: No such file or directory
,D/elm:15183( 3011): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3011): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3011): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 3011): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,V/EmergencyMode( 1425): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/elm:15183( 3011): ElmAgentService : onCreate()
,D/elm:15183( 3011): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 3011): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15183( 3011): BootCompletedState : startBootCompleted() call
,D/elm:15183( 3011): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3011): Get License : 0
,D/elm:15183( 3011): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 1680:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 2974): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,E/BluetoothHeadset( 2799): BTStateChangeCB is registed
,D/BluetoothHeadset( 2799): doBind(): CallingUid(myUserHandle) = 0
,V/EmergencyMode( 1425): [EmergencyBase] setBootTime
V/EmergencyMode( 1425): [EmergencyFactory] No Recovery State, kill my self.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 2799): BluetoothHeadset service is binded
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/Finsky  ( 2926): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DIAGMON_AGENT( 2947): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/BluetoothA2dp( 2799): doBind(): CallingUid(myUserHandle) = 0
,I/DIAGMON_AGENT( 2947): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 2947): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED,
I/DIAGMON_AGENT( 2947): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2947): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 2947): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/Zygote  ( 3034): MountEmulatedStorage()
E/Zygote  ( 3034): v2
I/libpersona( 3034): KNOX_SDCARD checking this for 1000
I/libpersona( 3034): KNOX_SDCARD not a persona,
I/SELinux ( 3034): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3034): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3034): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3034 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 2974): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth,
I/DBG_DM  ( 2974): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 2974): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,D/OverheatReceiver( 1176): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1176): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1176): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1176): isSafeMode = false
I/DBG_DM  ( 2974): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,W/libprocessgroup( 1018): failed to open /acct/uid_10138/pid_1680/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2974): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,D/BootupListener( 1468): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1018): name = internet_call_settings_visibility
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 1001
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/PhoneUtilsCommon( 1468): isSupportVoLTE is false.
,I/Telecom ( 1447): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/Telecom ( 1447): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,D/BluetoothAdapter( 2799): 680804275: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2799): 680804275: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2799): 680804275: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2799): 680804275: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2799): 680804275: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3034): TimaSignature is unavailable
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 2974): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3034): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!,
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,I/DBG_DM  ( 2974): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 2974): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 ,
,E/Zygote  ( 3052): MountEmulatedStorage()
E/Zygote  ( 3052): v2
,I/libpersona( 3052): KNOX_SDCARD checking this for 10012,
,I/libpersona( 3052): KNOX_SDCARD not a persona
,I/SELinux ( 3052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3052 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 3052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3052): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/Telecom ( 1447): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/Telecom ( 1447): InCallController: Unbinding from InCallService unbind
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3052): TimaSignature is unavailable
,D/ActivityThread( 3052): Added TimaKeyStore provider
,E/Zygote  ( 3068): MountEmulatedStorage()
,E/Zygote  ( 3068): v2
I/libpersona( 3068): KNOX_SDCARD checking this for 1000
I/libpersona( 3068): KNOX_SDCARD not a persona
,I/SELinux ( 3068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3078 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/Zygote  ( 3078): MountEmulatedStorage()
E/Zygote  ( 3078): v2
I/libpersona( 3078): KNOX_SDCARD checking this for 10003
I/libpersona( 3078): KNOX_SDCARD not a persona
,I/SELinux ( 3078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  309): Explicit concurrent mark sweep GC freed 8771(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 37.832ms
,W/ResourcesManager( 3052): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3052): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_DM  ( 2974): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 752us total 23.466ms
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,D/TimaKeyStoreProvider( 3078): TimaSignature is unavailable
D/ActivityThread( 3078): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 708us total 23.629ms
,I/MultiDex( 3052): VM with version 2.1.0 has multidex support
I/MultiDex( 3052): install
I/MultiDex( 3052): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager( 1018): Killing 1538:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3068): TimaSignature is unavailable
,D/ActivityThread( 3068): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 2097:com.vlingo.midas/u0a31 (adj 15): empty #31
,V/JNIHelp ( 3052): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/CameraApp( 3034): CameraApp.onCreate()... mFeature : null
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/testFeature( 3034): Feature.Feature(context)
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/testFeature( 3034): Feature.readInternalDefaultXml()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/testFeature( 3034): ResetFeatureValue
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/CameraFirmware_broadcast( 3034): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3034): CameraApp.getAppFeature()...
,E/Zygote  ( 3102): MountEmulatedStorage()
I/libpersona( 3102): KNOX_SDCARD checking this for 10100
E/Zygote  ( 3102): v2
I/libpersona( 3102): KNOX_SDCARD not a persona
,I/SELinux ( 3102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3102 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 2141:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
I/SELinux ( 3102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/audio_hw_primary(  283): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  283): audio_extn_get_parameters: returns 
V/msm8974_platform(  283): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  283): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  283): key: 'call_forwarding' value: ''
,V/InCall  ( 1892): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1892): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1892): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1892): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1892): InCallUtils - isCoverClosed false
,I/Telecom ( 1447): ProximitySensorManager: Proximity wake lock already released
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1892): InCallUtils - isCoverClosed false
,I/InCall  ( 1892): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1892): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1892): InCallPresenter -  - dismissCoverDialog()...
,D/TimaKeyStoreProvider( 3102): TimaSignature is unavailable
,D/ActivityThread( 3102): Added TimaKeyStore provider
,D/PackageManager( 1018): [MSG] MCS_UNBIND
W/ActivityThread( 3052): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3052): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e8ce4cc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3052): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1018): Killing 2156:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,I/InCall  ( 1892): CallSContextMotion - stopPutDownListening
D/InCall  ( 1892): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,D/PhoneStatusBarView( 1176): setCallBackground:0
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1892): InCallUtils - isCoverClosed false
,D/PackageIntentReceiver( 3102): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3102): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,I/ActivityManager( 1018): Killing 1509:com.android.printspooler/u0a136 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/VideoCallManager( 1892): Instantiating VideoCallManager
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 1892): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GFX construct_block_size_descriptor_2d second part( 1892): took 2.393906ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1892): took 5.239948ms for 0*0 texture 0,
,I/GFX raster( 1892): took 11.433229ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1892): Bitmap=0xb90202f8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb901fbc8 counterpartCT=4 counterpartW=176 counterparth=144
,V/AlarmManager( 1018): waitForAlarm result :4
,E/Zygote  ( 3127): MountEmulatedStorage(),
E/Zygote  ( 3127): v2
I/libpersona( 3127): KNOX_SDCARD checking this for 1000
,I/libpersona( 3127): KNOX_SDCARD not a persona
,I/SELinux ( 3127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
E/SMD     (  291): DCD OFF
I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3127 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/GoogleHttpClient( 1700): GMS http client unavailable, use old client,
,I/SELinux ( 3127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3127): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 1892): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/Adreno-EGL( 1892): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1892): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1892): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1892): Local Branch: 
I/Adreno-EGL( 1892): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1892): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1892):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC,
,I/ActivityManager( 1018): Killing 1721:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/GFX GPU raster( 1892): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1892): took 0.264427ms for 320*61440 texture 37809
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 28
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 3127): TimaSignature is unavailable
,D/ActivityThread( 3127): Added TimaKeyStore provider
,I/draw setup( 1892): took 10.997500ms for 320*240 texture 37809
E/GFX GPU raster( 1892): drawn
,I/GFX GPU raster ASTC( 1892): took 39.387657ms for 320*240 texture 12
I/GFX raster( 1892): took 39.467761ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1892): Bitmap=0xb9020278 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb901fde0 counterpartCT=4 counterpartW=320 counterparth=240
,D/UserAnalysis.PlaceProvider( 3078): PlaceProvider onCreate()
,E/        ( 1892): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1892): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1892): took 0.309688ms for 480*122880 texture 37813,
I/draw setup( 1892): took 0.644844ms for 480*640 texture 37813
E/GFX GPU raster( 1892): drawn
,I/GFX GPU raster ASTC( 1892): took 7.102031ms for 480*640 texture 12
I/GFX raster( 1892): took 7.175312ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1892): Bitmap=0xb901fde0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb924d490 counterpartCT=4 counterpartW=480 counterparth=640
,W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_1538/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_2097/cgroup.procs: No such file or directory
,D/Finsky  ( 2926): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/libprocessgroup( 1018): failed to open /acct/uid_10050/pid_2141/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10113/pid_2156/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_1721/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10136/pid_1509/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2974): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/        ( 1892): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1892): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1892): took 0.573385ms for 440*116864 texture 37809
I/draw setup( 1892): took 0.980834ms for 440*330 texture 37809
E/GFX GPU raster( 1892): drawn
,I/GFX GPU raster ASTC( 1892): took 4.858281ms for 440*330 texture 12
I/GFX raster( 1892): took 4.940103ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1892): Bitmap=0xb92516e8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb9251aa8 counterpartCT=4 counterpartW=440 counterparth=330
,D/UserAnalysis.SecureDbManager( 3078): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3078): SecurePlaceDbHelper() 
D/UserAnalysis( 3078): Create SecureDbHelper
,I/DBG_DM  ( 2974): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2974): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 2974): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,E/        ( 1892): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1892): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1892): took 0.420781ms for 480*163840 texture 37811
I/draw setup( 1892): took 0.755156ms for 480*640 texture 37811
E/GFX GPU raster( 1892): drawn
,I/GFX GPU raster ASTC( 1892): took 5.633335ms for 480*640 texture 12
,I/GFX raster( 1892): took 5.764585ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1892): Bitmap=0xb92910b8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb924d248 counterpartCT=4 counterpartW=480 counterparth=640
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 16521(884KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.371ms total 139.402ms
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,D/IntelligenceServiceApplication( 3078): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3078): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1018): No numeric data
,E/Zygote  ( 3149): MountEmulatedStorage()
E/Zygote  ( 3149): v2
I/libpersona( 3149): KNOX_SDCARD checking this for 10060
I/libpersona( 3149): KNOX_SDCARD not a persona
,I/SELinux ( 3149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3149 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2320:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
E/        ( 1892): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1892): took 2.536042ms for 0*0 texture 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/IntelligenceServiceApplication( 3078): no applications having user consent for prediction
,I/GFX generate_partition_tables( 1892): took 8.020885ms for 0*0 texture 0
,I/GFX raster( 1892): took 12.648124ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1892): Bitmap=0xb9251668 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb924aca8 counterpartCT=4 counterpartW=176 counterparth=144
,E/Zygote  ( 3160): MountEmulatedStorage()
,E/Zygote  ( 3160): v2
I/libpersona( 3160): KNOX_SDCARD checking this for 10009
I/libpersona( 3160): KNOX_SDCARD not a persona
,I/SELinux ( 3160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3160): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3160 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3149): TimaSignature is unavailable
,D/ActivityThread( 3149): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3160): TimaSignature is unavailable
,D/ActivityThread( 3160): Added TimaKeyStore provider
I/DBG_POLICYDM( 3068): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3068): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3068): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3068): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3068): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3068): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2320/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 3068): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3068): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,W/Settings( 2926): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2926): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/        ( 1892): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1892): took 2.043542ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1892): took 6.384166ms for 0*0 texture 0
,I/GFX raster( 1892): took 10.530468ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1892): Bitmap=0xb924ad10 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb924ae98 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1892): registerListener
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManager.StateNotifier( 1018): registerListenerCallback : binder = android.os.BinderProxy@379962e1, pid : 1892, uid : 1001, type : 1
,V/PlaceDetection v1.0.19 ( 3078): [PlaceDetection::stopService] Service stopped.
,I/sCloudBackupApp( 3149): sCloudBackupApp Version Info : 4.04.8.KK_APP
,D/[SBeam] ( 1307): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1307): SBeamEnabler.isSBeamSupported : EXIST
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3194): MountEmulatedStorage()
E/Zygote  ( 3194): v2
I/libpersona( 3194): KNOX_SDCARD checking this for 1000
I/libpersona( 3194): KNOX_SDCARD not a persona
I/SELinux ( 3194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3194 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/ActivityManager( 1018): Killing 2355:com.sec.android.omc/1000 (adj 15): empty #31
,E/SELinux ( 3194): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Tethering( 1018): No numeric data
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1018): No numeric data
V/PlaceDetection v1.0.19 ( 3078): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3078): Constructor Preference
,E/Tethering( 1018): No numeric data
,E/Zygote  ( 3209): MountEmulatedStorage()
E/Zygote  ( 3209): v2
I/libpersona( 3209): KNOX_SDCARD checking this for 10062
I/libpersona( 3209): KNOX_SDCARD not a persona
,I/SELinux ( 3209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3209 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2371:com.sec.modem.settings/1000 (adj 15): empty #31
,E/Tethering( 1018): No numeric data
,D/InCall  ( 1892): InCallPresenter -  - Finished InCallPresenter.setUp
,D/Volley  ( 2926): [356] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 2926): [363] DiskBasedCache.clear: Cache cleared.
,D/TimaKeyStoreProvider( 3194): TimaSignature is unavailable
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
D/ActivityThread( 3194): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/TimaKeyStoreProvider( 3209): TimaSignature is unavailable
,D/ActivityThread( 3209): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3068): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,V/GLSUser ( 1700): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/Finsky  ( 2926): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2926): [1] 2.run: Finished loading 1 libraries.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/NotificationAccessSettings( 1307): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,W/ResourcesManager( 1307): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/KnoxSetupWizardDbHelper( 3194): dbMigrationFlag : false
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2355/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2371/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/NotificationStore( 1700): System rebooted after Notification storage file was last written
I/NotificationStore( 1700): Deleting the file
,D/ShortcutReceiver( 3194):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/PersistentNotificationBroadcastReceiver( 1700): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/DBG_POLICYDM( 3068): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3068): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/KnoxShortcutUtil( 3194): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3194):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3194):  shortcut migration not required 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3235): MountEmulatedStorage(),
I/libpersona( 3235): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3235): v2
I/libpersona( 3235): KNOX_SDCARD not a persona
,I/SELinux ( 3235): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3235): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3235 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3235): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Finsky  ( 2926): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ExternalOEMControlProvider( 3209): onCreate
,I/DBG_POLICYDM( 3068): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3068): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3068): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false,
,E/Zygote  ( 3251): MountEmulatedStorage(),
E/Zygote  ( 3251): v2
I/libpersona( 3251): KNOX_SDCARD checking this for 1000
I/libpersona( 3251): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 3235): TimaSignature is unavailable
,D/ActivityThread( 3235): Added TimaKeyStore provider
I/ActivityManager( 1018): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3251 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3251): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3251): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/DBG_POLICYDM( 3068): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
E/SELinux ( 3251): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ScoverManager( 1307): serviceVersion : 16908288
I/ActivityManager( 1018): Killing 2386:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/SettingsProvider( 1018): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10062
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/TimaKeyStoreProvider( 3251): TimaSignature is unavailable
D/ActivityThread( 3251): Added TimaKeyStore provider
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1018): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10062
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/ResourcesManager( 3251): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,E/Zygote  ( 3269): MountEmulatedStorage()
,E/Zygote  ( 3269): v2
I/libpersona( 3269): KNOX_SDCARD checking this for 1000
I/libpersona( 3269): KNOX_SDCARD not a persona
,I/SELinux ( 3269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
I/ActivityManager( 1018): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3269 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2467:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 2449:com.wsomacp/u0a25 (adj 15): empty #32
I/ActivityManager( 1018): Killing 2401:com.sec.tcpdumpservice/1000 (adj 15): empty #33
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceMode( 3251): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3251): setReferenceIsDumpState : 0
,D/TimaKeyStoreProvider( 3269): TimaSignature is unavailable
,D/ActivityThread( 3269): Added TimaKeyStore provider
,E/KnoxSetupWizardClient( 3235): isShipMode : 1
I/KnoxSetupWizardClient( 3235): onReceive : android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3287): MountEmulatedStorage()
E/Zygote  ( 3287): v2
I/libpersona( 3287): KNOX_SDCARD checking this for 1000
I/libpersona( 3287): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3287 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2497:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31,
I/SELinux ( 3287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/StatusChecker( 2306): onReceive : android.intent.action.BOOT_COMPLETED
I/StatusChecker( 2306): onReceive : net.mt.init : DONE
,I/SELinux ( 3287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3287): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Finsky  ( 2926): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_2386/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2401/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_2449/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10142/pid_2497/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_2467/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3287): TimaSignature is unavailable,
D/ActivityThread( 3287): Added TimaKeyStore provider
,W/System.err( 3235): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 29
W/System.err( 3235): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3235): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3235): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3235): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3235): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3235): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/Zygote  ( 3304): MountEmulatedStorage(),
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/Zygote  ( 3304): v2
I/libpersona( 3304): KNOX_SDCARD checking this for 10116
I/libpersona( 3304): KNOX_SDCARD not a persona
,I/SELinux ( 3304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3304 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2514:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDM( 3269): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/ActivityManager( 1018): Killing 2632:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3304): TimaSignature is unavailable
I/DBG_FMMDM( 3269): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
I/DBG_FMMDM( 3269): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
D/ActivityThread( 3304): Added TimaKeyStore provider
I/DBG_FMMDM( 3269): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
I/art     (  309): Explicit concurrent mark sweep GC freed 8776(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.142ms total 22.816ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 679us total 18.745ms
,I/PageBuddyNotiSvc( 3304): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 16.871ms
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,E/Zygote  ( 3322): MountEmulatedStorage(),
E/Zygote  ( 3322): v2
I/libpersona( 3322): KNOX_SDCARD checking this for 1000
I/libpersona( 3322): KNOX_SDCARD not a persona
,I/SELinux ( 3322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/NPS_WSSNPS( 3287): [] android.intent.action.BOOT_COMPLETED
,E/SELinux ( 3322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3322 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ContextImpl( 3287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3287): [] Service onCreate!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 3304): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,I/LockPatternUtils( 1307): isSmartCardAuthenticationAvailable: false
,D/TimaKeyStoreProvider( 3322): TimaSignature is unavailable
,D/ActivityThread( 3322): Added TimaKeyStore provider
,E/Zygote  ( 3339): MountEmulatedStorage()
E/Zygote  ( 3339): v2
I/libpersona( 3339): KNOX_SDCARD checking this for 1000
I/libpersona( 3339): KNOX_SDCARD not a persona
,I/SELinux ( 3339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_2514/cgroup.procs: No such file or directory
,I/SELinux ( 3339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3339 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/Settings_Utils( 1307): isSupportVNFestival SM-A500FU XEO
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
I/PageBuddyNotiSvc( 3304): onCreate mCpBitFlag=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2632/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 2615:com.android.calendar/u0a135 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3339): TimaSignature is unavailable
,D/ActivityThread( 3339): Added TimaKeyStore provider
,D/NPS_WSSNPS( 3287): [] NpsServiceTask Start
,E/Zygote  ( 3355): MountEmulatedStorage()
,E/Zygote  ( 3355): v2
I/libpersona( 3355): KNOX_SDCARD checking this for 10125
I/libpersona( 3355): KNOX_SDCARD not a persona
,I/SELinux ( 3355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3355): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3355 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3355): TimaSignature is unavailable
,D/ActivityThread( 3355): Added TimaKeyStore provider
,W/InstanceID/Rpc( 1854): Found 10012
,I/PCWCLIENTTRACE_LOG( 3322): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3322): DEFAULT_LOGLEVEL : 3
W/ResourcesManager( 3355): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3355): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3355): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/NPS_WSSNPS( 3287): [50.150321] smlDBHelper
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3322): new DMDBOpenHelper instance
,D/SettingsProvider( 1018): name = access_control_enabled
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_2615/cgroup.procs: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3374): MountEmulatedStorage()
I/libpersona( 3374): KNOX_SDCARD checking this for 10069
E/Zygote  ( 3374): v2
I/libpersona( 3374): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3374 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 2680:com.android.keychain/1000 (adj 15): empty #31
,I/SELinux ( 3374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
E/SELinux ( 3374): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4176, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/PCWCLIENTTRACE_DMContentProvider( 3322): [URIMatcher] - result : 2
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,D/PowerUI ( 1176): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1176): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1425): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1425): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/NPS_WSSNPS( 3287): [50.150321] AsyncBulkFlagCheck
,V/Finsky  ( 2926): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/TimaKeyStoreProvider( 3374): TimaSignature is unavailable
,D/ActivityThread( 3374): Added TimaKeyStore provider
,I/DBG_FMMDM( 3269): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3269): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3269): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2680/cgroup.procs: No such file or directory
,I/NPS_WSSNPS( 3287): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3287): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3287): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,E/Zygote  ( 3390): MountEmulatedStorage()
I/libpersona( 3390): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3390): v2
I/libpersona( 3390): KNOX_SDCARD not a persona
I/SELinux ( 3390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3390 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2212:flipboard.app/u0a98 (adj 15): empty #31
I/ActivityManager( 1018): Killing 2736:flipboard.boxer.app/u0a99 (adj 15): empty #32
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3287): [50.150321] Service onDestroy
,D/QuickConnect( 3355): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3355): Util.setSCRunningSetting - [value]0
,D/TimaKeyStoreProvider( 3390): TimaSignature is unavailable
,D/ActivityThread( 3390): Added TimaKeyStore provider
,D/SettingsProvider( 1018): name = scon_is_running
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10125
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/FileShare-Server( 3374): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/NPS_WSSNPS( 3287): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3287): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3287): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3287): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3287): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3287): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3287): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3287): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3287): [50.150321] cpuBooster release : false
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 3355): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,D/NPS_WSSNPS( 3287): [50.150321] dsServerSocket close
,I/ActivityManager( 1018): Killing 2767:com.sec.usbsettings/1000 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/QuickConnect( 3355): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_2212/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10099/pid_2736/cgroup.procs: No such file or directory
,E/Zygote  ( 3405): MountEmulatedStorage(),
E/Zygote  ( 3405): v2
I/libpersona( 3405): KNOX_SDCARD checking this for 10131
I/libpersona( 3405): KNOX_SDCARD not a persona
I/SELinux ( 3405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_FMMDS( 3390): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3405 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2334:com.android.mms/u0a46 (adj 15): empty #31
,I/DBG_FMMDS( 3390): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/TimaKeyStoreProvider( 3405): TimaSignature is unavailable
,D/ActivityThread( 3405): Added TimaKeyStore provider
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,W/ResourcesManager( 3405): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3405): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3405): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3405): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/CountryDetector( 1018): No listener is left
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2767/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_2334/cgroup.procs: No such file or directory
,D/PCWCLIENTTRACE_DMContentProvider( 3322): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3390): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_FMMDS( 3390): [50.18.150420][Line:43][xdbDBInit] 
,D/SBrowserFeatureFlag( 3405): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 3405): onCreate()
,E/NetworkSettingsReceiver( 3405): onReceive: android.intent.action.BOOT_COMPLETED
,I/LockPatternUtils( 1307): isSmartCardAuthenticationAvailable: false
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SBrowserFeatureFlag( 3405): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2490c337
,D/SBrowserFeatureFlag( 3405): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3405): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,D/FileApkUtils( 1854): Spent 41ms computing apk sha1.
,D/FileApkUtils( 1854): Module already staged or being staged:chimera-modules/MapsModule.apk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1854): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/DexOptUtils( 1854): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.,
D/DexOptUtils( 1854): Lollipop platform, using <isa> directory.
D/DexOptUtils( 1854): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1854): Primary ABI of odexing process is armeabi-v7a
,I/DBG_FMMDS( 3390): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
E/Zygote  ( 3429): MountEmulatedStorage()
E/Zygote  ( 3429): v2
I/libpersona( 3429): KNOX_SDCARD checking this for 10135
I/libpersona( 3429): KNOX_SDCARD not a persona
,I/SELinux ( 3429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3429): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_FMMDS( 3390): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3429 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/DBG_FMMDS( 3390): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3390): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3390): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3390): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3390): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,D/TimaKeyStoreProvider( 3429): TimaSignature is unavailable
,D/ActivityThread( 3429): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 2827:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,W/ResourcesManager( 3429): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3429): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3429): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 2875:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 2755:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #32
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1018): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dex2oat ( 3428): ----------------------------------------------------
I/dex2oat ( 3428): <SS>: S T A R T I N G . . .
I/dex2oat ( 3428): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3428): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client( 3160): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,E/Zygote  ( 3453): MountEmulatedStorage()
I/libpersona( 3453): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3453): v2
I/libpersona( 3453): KNOX_SDCARD not a persona
I/SELinux ( 3453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3453 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,E/SELinux ( 3453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/FactoryTestApp( 2653): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2938)  
,D/TimaKeyStoreProvider( 3453): TimaSignature is unavailable
,D/ActivityThread( 3453): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,W/FOTA_Client( 3160): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_2827/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2875/cgroup.procs: No such file or directory
,E/Zygote  ( 3469): MountEmulatedStorage()
,I/libpersona( 3469): KNOX_SDCARD checking this for 10014
E/Zygote  ( 3469): v2
I/libpersona( 3469): KNOX_SDCARD not a persona
,I/SELinux ( 3469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3469 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,E/SELinux ( 3469): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10085/pid_2755/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3469): TimaSignature is unavailable
,D/ActivityThread( 3469): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1278): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/GCM     ( 1700): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 3453): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3493): MountEmulatedStorage()
,E/Zygote  ( 3493): v2
I/libpersona( 3493): KNOX_SDCARD checking this for 1000
,I/libpersona( 3493): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,V/OneTimeInitializerReceiver( 3469): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,I/CheckinService( 1854): Disabling old GoogleServicesFramework version
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/OneTimeService( 3469): OneTimeService.onHandleIntent
,I/SELinux ( 3493): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3493): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3493): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 3509): MountEmulatedStorage()
I/libpersona( 3509): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3509): v2
I/libpersona( 3509): KNOX_SDCARD not a persona
I/SELinux ( 3509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3509): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/USB_UICC(  299): Timeout! No signal received. Retry num = 30
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ActivityManager( 1018): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3509 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3493): TimaSignature is unavailable
D/ActivityThread( 3493): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/art     (  309): Explicit concurrent mark sweep GC freed 8770(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 24.684ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3509): TimaSignature is unavailable
D/ActivityThread( 3509): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 788us total 18.790ms
,D/SystemUpdateService( 1854): onCreate
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 16.924ms
,E/Zygote  ( 3538): MountEmulatedStorage()
I/libpersona( 3538): KNOX_SDCARD checking this for 10042
E/Zygote  ( 3538): v2
I/libpersona( 3538): KNOX_SDCARD not a persona
I/SELinux ( 3538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3538 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3538): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  299): Timeout! No signal received. Reach maximum retries!
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
E/USB_UICC(  299): usb_uicc_init_qmi failed ! 
I/USB_UICC(  299): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  299): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 2844:com.sec.dsm.system/1000 (adj 15): empty #31
,I/GCoreUlr( 1854): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3538): TimaSignature is unavailable
,D/ActivityThread( 3538): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/ActivityManager( 1018): Killing 2890:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ResourcesManager( 3493): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
I/SettingSearch/SearchIntentReceiver( 1307): InitSerachDBThread thread end!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 22784(1230KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 3.199ms total 159.500ms
,E/Zygote  ( 3562): MountEmulatedStorage(),
E/Zygote  ( 3562): v2
I/libpersona( 3562): KNOX_SDCARD checking this for 10139,
I/libpersona( 3562): KNOX_SDCARD not a persona
,I/SELinux ( 3562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3562 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,I/SELinux ( 3562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3538): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SystemUpdateService( 1854): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2844/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2890/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/GCoreUlr( 1643): DispatchingService.onCreate()
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3562): TimaSignature is unavailable
,D/ActivityThread( 3562): Added TimaKeyStore provider
,I/CheckinService( 1854): Checking schedule, now: 1452552474564 next: 1452984674341
I/CheckinService( 1854): active receiver: disabled
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1700): onCreate
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/CalendarProvider2( 3538): CalendarProvider2.onCreate() called,
,I/ConfigFetchService( 1854): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,V/AuthZen ( 1854): Handling intent: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthZenEventHandler( 1854): Handling event: android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3591 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3591): MountEmulatedStorage()
E/Zygote  ( 3591): v2
,I/libpersona( 3591): KNOX_SDCARD checking this for 1000
,I/libpersona( 3591): KNOX_SDCARD not a persona
I/SELinux ( 3591): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3591): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3591): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ResourcesManager( 3562): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3562): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3562): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3562): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3562): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3591): TimaSignature is unavailable
,D/ActivityThread( 3591): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaService( 1018): TIMA: in getTimaVersion
,D/TimaService( 1018): TIMA3: KeyStore3_init
E/TLC_TZ_KEYSTORE: ( 1018): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1018): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1018): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1018): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1018): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1018): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 8
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1018): ctx = 0xb95abd48, comm = 0xb92b8a48, sendmsg = 0xa1250000, recvmsg = 0xa1250440
I/TZ_init: ( 1018): TZ_init: sending initialization request...
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/TZ_init: ( 1018): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1018): trustlet initialization failed
I/TZ_init: ( 1018): TZ_init_START...
,I/SystemUpdateService( 1854): cancelUpdate (empty URL)
,I/SystemUpdateService( 1854): active receiver: disabled
,I/TZ_init: ( 1018): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1018): TZ_init: successful initialization
D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1018): Count : 1, Ret : 0
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 2947:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/art     ( 1700): Explicit concurrent mark sweep GC freed 24295(1406KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 10MB/16MB, paused 1.081ms total 40.493ms
,W/SQLiteConnectionPool( 1700): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,I/GLSUser ( 1854): [ChannelManager] Attempting to channel bind connection HttpClient.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3591): onCreate
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3625): MountEmulatedStorage()
E/Zygote  ( 3625): v2
I/libpersona( 3625): KNOX_SDCARD checking this for 10145
I/libpersona( 3625): KNOX_SDCARD not a persona
,I/SELinux ( 3625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3625 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 3625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3453): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3453): Resource data:2131165186
,I/Hs20UtilService( 3591): Starting #1
,I/Hs20UtilService( 3591): Message received 5003
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3453): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3453): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/Zygote  ( 3642): MountEmulatedStorage()
E/Zygote  ( 3642): v2
I/libpersona( 3642): KNOX_SDCARD checking this for 10019
I/libpersona( 3642): KNOX_SDCARD not a persona
,I/SELinux ( 3642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ContextImpl( 3493): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
I/ActivityManager( 1018): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3642 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2947/cgroup.procs: No such file or directory
,I/SELinux ( 3642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 3625): TimaSignature is unavailable
D/ActivityThread( 3625): Added TimaKeyStore provider
I/AMMetaDataParserService( 3453): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,I/ConfigFetchService( 1854): service connected
,I/AMMetaDataParserService( 3453): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3625): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3625): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3625): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 3625): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3625): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3642): TimaSignature is unavailable
,D/ActivityThread( 3642): Added TimaKeyStore provider
,E/Zygote  ( 3660): MountEmulatedStorage(),
E/Zygote  ( 3660): v2
I/libpersona( 3660): KNOX_SDCARD checking this for 1000
I/libpersona( 3660): KNOX_SDCARD not a persona
,I/SELinux ( 3660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3660 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3453): Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1854): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/SEAMService( 1018):  hashset_to_int_array returning null
,W/SEAMService( 1018):  hashset_to_int_array returning null
,E/SQLiteLog( 3493): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3493): (284) automatic index on seams_container_info(sp_id)
,E/Zygote  ( 3682): MountEmulatedStorage()
E/Zygote  ( 3682): v2
I/libpersona( 3682): KNOX_SDCARD checking this for 10104
I/libpersona( 3682): KNOX_SDCARD not a persona
,I/SELinux ( 3682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3682): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3682 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3660): TimaSignature is unavailable,
D/ActivityThread( 3660): Added TimaKeyStore provider
,W/SEAMService( 1018):  hashset_to_int_array returning null
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
W/ContextImpl( 3453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,I/Kids    ( 1854): [KidAccountFixer] No network connection
,I/RlzPingService( 3509): Setting next ping for 1453157275096
,I/ActivityManager( 1018): Killing 2960:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,W/ResourcesManager( 3660): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/GCoreUlr( 1643): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3682): TimaSignature is unavailable
,D/ActivityThread( 3682): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131034113
,E/SMD     (  291): DCD OFF
,W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_2960/cgroup.procs: No such file or directory
,D/SystemUpdateService( 1854): onDestroy
,W/ResourcesManager( 3453): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3453): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ConfigFetchService( 1854): ConfigApi connection successful.
,I/GFX construct_block_size_descriptor_2d second part( 3453): took 2.411250ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3453): took 6.013334ms for 0*0 texture 0
,I/GFX raster( 3453): took 9.677968ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb904e488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb904e808 counterpartCT=4 counterpartW=96 counterparth=96
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,I/AuthZen ( 1854): Fetching signing key...
,I/AMMetaDataParserService( 3453): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/KLMS-2.5.183: ( 3642): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 23:47:55 GMT+01:00 2016
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ResourcesManager( 3682): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1854): Signing key fetched successfully!
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,I/ActivityManager( 1018): Killing 2907:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/art     ( 1643): Explicit concurrent mark sweep GC freed 12416(744KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 1.654ms total 192.395ms
I/KLMS-2.5.183: ( 3642): KLMSAbstractReciever(): onReceive().END.
I/AuthZen ( 1854): Starting Enrollment...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3642): KLMSIntentService(): onCreate()
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3642): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/F_PHONE ( 3660): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
I/KLMS-2.5.183: ( 3642): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 3704): MountEmulatedStorage()
E/Zygote  ( 3704): v2
I/libpersona( 3704): KNOX_SDCARD checking this for 10022
,I/libpersona( 3704): KNOX_SDCARD not a persona
I/SELinux ( 3704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3704 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3642): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,I/SELinux ( 3704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3704): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3642): KLMSIntentService(): BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3719): MountEmulatedStorage(),
E/Zygote  ( 3719): v2
I/libpersona( 3719): KNOX_SDCARD checking this for 1000
I/libpersona( 3719): KNOX_SDCARD not a persona
,I/SELinux ( 3719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3719 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/TimaKeyStoreProvider( 3704): TimaSignature is unavailable
D/ActivityThread( 3704): Added TimaKeyStore provider
E/SELinux ( 3719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1018): failed to open /acct/uid_10086/pid_2907/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/GLSActivity( 1700): [ac] getting account id
,D/AuthZen ( 1854): getting auth token. Attempt 0
,D/TimaKeyStoreProvider( 3719): TimaSignature is unavailable
,D/ActivityThread( 3719): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3642): KLMSIntentService(): onDestroy()
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/F_PHONE ( 3660): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 3660): default registerAction()
I/F_PHONE ( 3660): [[com.sec.bcservice]] sendPendingMessage()
,W/ResourcesManager( 3719): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1700): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1700): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/BluetoothBDAdrressReceiver( 3719): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3719): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,I/GLSUser ( 1700): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/GLSUser ( 1700): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1700): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1700): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1700): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BluetoothBDTestService( 1468): onCreate()
,E/BluetoothBDTestService( 1468): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1468): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1468): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/Zygote  ( 3743): MountEmulatedStorage()
E/Zygote  ( 3743): v2
I/libpersona( 3743): KNOX_SDCARD checking this for 1000
I/libpersona( 3743): KNOX_SDCARD not a persona
,I/SELinux ( 3743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3743): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3743 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 3743): TimaSignature is unavailable
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityThread( 3743): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 3011:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3764): MountEmulatedStorage(),
,E/Zygote  ( 3764): v2
I/libpersona( 3764): KNOX_SDCARD checking this for 1000
I/libpersona( 3764): KNOX_SDCARD not a persona,
,I/SELinux ( 3764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ResourcesManager( 3743): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3764 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3034:com.sec.factory.camera/1000 (adj 15): empty #31
,I/SELinux ( 3764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3764): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  309): Explicit concurrent mark sweep GC freed 8763(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 23.494ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 19.492ms
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 3764): TimaSignature is unavailable
,I/GFX raster( 3453): took 0.828177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb904e488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9056858 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 3764): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 16.902ms
,I/AMMetaDataParserService( 3453): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/libprocessgroup( 1018): failed to open /acct/uid_10094/pid_3011/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3034/cgroup.procs: No such file or directory
,E/MTPRx   ( 3764): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1018): mCursor = null
V/MTPRx   ( 3764): sealedState: false
V/MTPRx   ( 3764): sealedUsbMassStorageState: false
,D/SettingsProvider( 1018): name = mtp_usb_connection_status
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/KnoxUsageLogPro( 3743): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 3743): premStatus:2
,I/KnoxUsageLogPro( 3743): isEulaShown : false
,I/KnoxUsageLogPro( 3743): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1018): Killing 3078:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/KnoxUsageLogPro( 3743): savePreference: key = previous_sys_time value = 1452552475856
,E/AuthZen ( 1854): Error getting auth token
E/AuthZen ( 1854): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 1854): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1854): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1854): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1854): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AuthZen ( 1854): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1854): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1854): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1854): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1854): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1854): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SettingsProvider( 1018): name = media_player_mode
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/a       ( 1854): Opening database auth.proximity.permit_store...
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/AuthZenTransactionCache( 1854): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1854): Clearing transaction cache
,I/KnoxUsageLogPro( 3743): savePreference: key = previous_elapsed_time value = 37894
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3453): took 2.295834ms for 0*0 texture 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_3078/cgroup.procs: No such file or directory
,I/GFX generate_partition_tables( 3453): took 7.461979ms for 0*0 texture 0
,I/GFX raster( 3453): took 10.670053ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90530d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9053178 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/SettingsProvider( 1018): name = mtp_running_status
,I/GCoreUlr( 1643): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = media_mount_count
,D/FactoryTestApp( 2653): [DummyFtClient$onDestroy](2653) Destroy DummyFtClient service
,D/FactoryTestApp( 2653): [Support$Values.getString](2653) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2653): [ModuleCommon$isConnectionModeNone](2653) mConnectionMode = gsm
I/FactoryTestApp( 2653): [ModuleCommon$isRunningFtClient](2653) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2653): [DummyFtClient$onDestroy](2653) kill process
I/Process ( 2653): Sending signal. PID: 2653 SIG: 9
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = mtp_sync_alive
,D/SettingsProvider( 1018): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
I/ActivityManager( 1018): Process com.sec.factory (pid 2653)(adj 0) has died(60,1107)
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.594844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9057a98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9057b60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/dex2oat ( 3428): Verification of void com.google.maps.api.android.lib6.gmm6.n.cj.g() took 107.586ms
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.829635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9054500 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9054658 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.713698ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90537d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9053930 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 27029(1681KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 26MB/39MB, paused 2.240ms total 160.399ms
,I/GFX raster( 3453): took 0.858073ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90571a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9057300 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecurityLogAgent:SEDenialService( 1018): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1018): Got CLOSE_WRITE Event sk.log
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService( 1018): Got CLOSE_WRITE Event sk.log
,I/PCWCLIENTTRACE_PushUtil( 3322): SPPPushClient is installed : true,
,I/PCWCLIENTTRACE_PushUtil( 3322): sales region : global,
I/PCWCLIENTTRACE_PushUtil( 3322): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3322): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3322): ACTION_BOOTUP - Version: 4.82,
D/PCWCLIENTTRACE_SYSTEMReceiver( 3322): ACTION_BOOTUP - Push type: [SPP, GCM]
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/Zygote  ( 3790): MountEmulatedStorage(),
E/Zygote  ( 3790): v2
I/libpersona( 3790): KNOX_SDCARD checking this for 10072
I/libpersona( 3790): KNOX_SDCARD not a persona,
I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534,
I/SELinux ( 3790): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3790): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3790): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3790 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,W/PCWCLIENTTRACE_PCWHandler( 3322): [ensureRegistration] - netwrok is not available. action ignored
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 3790): TimaSignature is unavailable
,D/ActivityThread( 3790): Added TimaKeyStore provider
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/ActivityManager( 1018): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3806 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/GFX raster( 3453): took 0.540730ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9057e58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9057fb0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3806): MountEmulatedStorage()
I/ActivityManager( 1018): Killing 2028:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
E/Zygote  ( 3806): v2,
I/libpersona( 3806): KNOX_SDCARD checking this for 10031
,I/AMMetaDataParserService( 3453): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1643): Unbound from all location providers,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/libpersona( 3806): KNOX_SDCARD not a persona,
,I/SELinux ( 3806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131034113
,E/SELinux ( 3806): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3453): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.821822ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb904e488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb90548e0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3806): TimaSignature is unavailable
,D/ActivityThread( 3806): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/AMMetaDataParserService( 3453): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 3538): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/BadgeProvider( 3790): onCreate
D/BadgeProvider( 3790): DatabaseHelper
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.822031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb904e488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9056858 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 3790): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ResourcesManager( 3806): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3828 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 2118:com.android.defcontainer/u0a4 (adj 15): empty #31,
I/ActivityManager( 1018): Killing 3068:com.policydm/1000 (adj 15): empty #32
,E/Zygote  ( 3828): MountEmulatedStorage(),
,I/ActivityManager( 1018): Killing 3102:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
E/Zygote  ( 3828): v2
,I/libpersona( 3828): KNOX_SDCARD checking this for 10146
I/libpersona( 3828): KNOX_SDCARD not a persona
,I/SELinux ( 3828): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3828): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3828): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3453): took 0.631302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90530d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb904eb60 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 3828): TimaSignature is unavailable
D/ActivityThread( 3828): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3453): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 3828): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/GCoreUlr( 1643): DispatchingService.onDestroy()
,I/GCoreUlr( 1643): Unbound from all location providers
,I/Babel_SMS( 3682): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3682): MmsConfig.loadMmsSettings
I/Babel_SMS( 3682): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 3682): MmsConfig.loadFromDatabase
,W/libprocessgroup( 1018): failed to open /acct/uid_10012/pid_2028/cgroup.procs: No such file or directory
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 1.237136ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb8dc0530 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8dc0568 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3068/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_3102/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10004/pid_2118/cgroup.procs: No such file or directory
,D/BadgeProvider( 3790): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3790): sendNotify, [notify] : null
D/BadgeProvider( 3790): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3790): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3790): update, [UpdateCount] : 1
,D/Launcher.Model( 1492): reloadBadges entered.
,E/Babel_SMS( 3682): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 3682): MmsConfig.loadFromResources
,E/Babel_SMS( 3682): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 3682): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/VlingoApplication( 3806): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,E/Zygote  ( 3852): MountEmulatedStorage(),
E/Zygote  ( 3852): v2
I/libpersona( 3852): KNOX_SDCARD checking this for 1000
I/libpersona( 3852): KNOX_SDCARD not a persona
,I/SELinux ( 3852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=3852 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/BluetoothAdapter( 3806): 584765500: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3806): 584765500: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3806): 584765500: getState() :  mService = null. Returning STATE_OFF
W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
I/VlingoAndroidCore( 3806): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
I/SELinux ( 3852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Killing 3127:com.samsung.helphub/1000 (adj 15): empty #31
,E/SELinux ( 3852): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.849479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9036c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d98940 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3852): TimaSignature is unavailable
,D/ActivityThread( 3852): Added TimaKeyStore provider
,I/dex2oat ( 3428): dex2oat took 2.694s (threads: 4)
,I/AMMetaDataParserService( 3453): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/DexOptUtils( 1854): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
D/DexOptUtils( 1854): Set odex to world readable.
,D/DexOptUtils( 1854): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,D/FileApkUtils( 1854): Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,D/GmsModuleFndr( 1854): Beginning GMS chimera module scan
,D/GmsModuleFndr( 1854): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1854): Beginning module configuration check
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3127/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1854): Module APKs unchanged, check complete
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3872): MountEmulatedStorage()
,E/Zygote  ( 3872): v2
I/libpersona( 3872): KNOX_SDCARD checking this for 1000
I/libpersona( 3872): KNOX_SDCARD not a persona
,I/SELinux ( 3872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=3872 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Killing 3149:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/Process ( 3828): Sending signal. PID: 3828 SIG: 9
,D/TimaKeyStoreProvider( 3872): TimaSignature is unavailable
,D/ActivityThread( 3872): Added TimaKeyStore provider
,W/ActivityManager( 1018): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 3625): Sending signal. PID: 3625 SIG: 9
,W/Settings( 3682): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/VlingoApplication( 3806): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,I/Babel_Crash( 3682): startup - clean
,D/VlingoApplication( 3806): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow( 3806): initQueue()
,D/SecurityLogAgent( 3872): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 3872): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 3872): StateMachine : Current State = 1
D/SecurityLogAgent( 3872): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/libprocessgroup( 1018): failed to open /acct/uid_10060/pid_3149/cgroup.procs: No such file or directory
,I/GFX raster( 3453): took 0.906770ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9019be8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9035578 counterpartCT=4 counterpartW=96 counterparth=96
,I/Babel   ( 3682): deleted: false for 0
,E/Zygote  ( 3890): MountEmulatedStorage(),
E/Zygote  ( 3890): v2
I/libpersona( 3890): KNOX_SDCARD checking this for 10152
I/libpersona( 3890): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/SELinux ( 3890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=3890 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
I/SELinux ( 3890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/lowmemorykiller(  254): Error writing /proc/3828/oom_score_adj; errno=22
,I/ActivityManager( 1018): Killing 3194:com.sec.knox.foldercontainer/1000 (adj 15): empty #31,
E/SELinux ( 3890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 1700): (10) POSIX Error : 11 SQLite Error : 3850
I/ActivityManager( 1018): Process com.android.exchange (pid 3828)(adj 11) has died(68,1118)
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.728542ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90364a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9036110 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3890): TimaSignature is unavailable
,D/ActivityThread( 3890): Added TimaKeyStore provider
,E/Zygote  ( 3905): MountEmulatedStorage()
,E/Zygote  ( 3905): v2
I/libpersona( 3905): KNOX_SDCARD checking this for 10032
I/libpersona( 3905): KNOX_SDCARD not a persona
I/SELinux ( 3905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3905 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
W/art     ( 3682): Suspending all threads took: 13.127ms
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
I/ActivityManager( 1018): Process com.android.email (pid 3625)(adj 11) has died(68,1118)
I/SELinux ( 3905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3905): TimaSignature is unavailable
,D/ActivityThread( 3905): Added TimaKeyStore provider
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.523073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb8d98940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9035578 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3453): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3453): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131034112
,E/SQLiteLog( 3890): (284) automatic index on shooting_modes(title_id)
,I/AMMetaDataParserService( 3453): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.640573ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb8dc0530 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9053550 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3194/cgroup.procs: No such file or directory
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/GFX raster( 3453): took 0.607760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb8dc0530 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9035578 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3453): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/ActivityManager( 1018): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=3923 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3923): MountEmulatedStorage()
,E/Zygote  ( 3923): v2
I/libpersona( 3923): KNOX_SDCARD checking this for 1000
I/libpersona( 3923): KNOX_SDCARD not a persona
,I/SELinux ( 3923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3923): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.746979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb900a770 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9053550 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3453): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.638854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9019be8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9035578 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3923): TimaSignature is unavailable
,D/ActivityThread( 3923): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,E/Zygote  ( 3939): MountEmulatedStorage()
,E/Zygote  ( 3939): v2
I/libpersona( 3939): KNOX_SDCARD checking this for 10033
I/libpersona( 3939): KNOX_SDCARD not a persona
,I/SELinux ( 3939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3939 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3939): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 3209:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131034113
,I/AMMetaDataParserService( 3453): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.853073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9035578 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9042980 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3939): TimaSignature is unavailable
,D/ActivityThread( 3939): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3453): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.826042ms for 96*96 texture 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9035578 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ddbcc0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3453): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc,
,W/AudioCapabilities( 3682): Unsupported mime audio/evrc
,W/AudioCapabilities( 3682): Unsupported mime audio/qcelp
,E/Zygote  ( 3954): MountEmulatedStorage()
I/libpersona( 3954): KNOX_SDCARD checking this for 1101
E/Zygote  ( 3954): v2
I/libpersona( 3954): KNOX_SDCARD not a persona
,I/SELinux ( 3954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3954 uid=1101 gids={41101, 9997} abi=armeabi-v7a
E/SELinux ( 3954): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 3052:com.google.android.gms:car/u0a12 (adj 15): empty #31
,W/AudioCapabilities( 3682): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3682): Unsupported mime audio/mpeg-L2
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.608698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90530d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9057158 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3954): TimaSignature is unavailable
,D/ActivityThread( 3954): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3453): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 3954): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,W/AudioCapabilities( 3682): Unsupported mime audio/x-ms-wma
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 11000ms
,W/AudioCapabilities( 3682): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3682): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3682): Unsupported mime audio/evrc
,W/libprocessgroup( 1018): failed to open /acct/uid_10062/pid_3209/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10012/pid_3052/cgroup.procs: No such file or directory
,V/SmartcardService( 3954): main Received broadcast
V/SmartcardService( 3954): Starting smartcard service after boot completed
,D/ActivityManager( 1018): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,W/VideoCapabilities( 3682): Unsupported mime video/wvc1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,W/VideoCapabilities( 3682): Unsupported mime video/x-ms-wmv
E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.598125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb8dc0530 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ddbcc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1018): Killing 3235:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3453): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3682): Unrecognized profile/level 32768/2 for video/mp4v-es
,E/Zygote  ( 3969): MountEmulatedStorage(),
W/VideoCapabilities( 3682): Unsupported mime video/wvc1
,E/Zygote  ( 3969): v2,
I/libpersona( 3969): KNOX_SDCARD checking this for 1000
I/libpersona( 3969): KNOX_SDCARD not a persona
,I/SELinux ( 3969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=3969 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
W/VideoCapabilities( 3682): Unsupported mime video/x-ms-wmv,
,I/SELinux ( 3969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3453): took 0.858802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9036c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9042980 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3682): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3682): Unsupported mime video/x-ms-wmv8
,I/art     (  309): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 691us total 26.526ms
,I/AMMetaDataParserService( 3453): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/TimaKeyStoreProvider( 3969): TimaSignature is unavailable
D/ActivityThread( 3969): Added TimaKeyStore provider
,W/VideoCapabilities( 3682): Unsupported mime video/mp43
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.220ms
W/VideoCapabilities( 3682): Unsupported mime video/sorenson
,W/VideoCapabilities( 3682): Unsupported mime video/mp4v-esdp
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 17.677ms
,I/VideoCapabilities( 3682): Unsupported profile 4 for video/mp4v-es
,W/ContextImpl( 3969): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.824167ms for 96*96 texture 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9019be8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9035a98 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3235/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
W/ResourcesManager( 3939): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3939): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 3986): MountEmulatedStorage()
I/libpersona( 3986): KNOX_SDCARD checking this for 10157
E/Zygote  ( 3986): v2
I/libpersona( 3986): KNOX_SDCARD not a persona
E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 3986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/GFX raster( 3453): took 0.720260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90364a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9057158 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 3986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3986 uid=10157 gids={50157, 9997} abi=armeabi-v7a,
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ResourcesManager( 3939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,D/TimaKeyStoreProvider( 3986): TimaSignature is unavailable
,D/ActivityThread( 3986): Added TimaKeyStore provider
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 3939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3939): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3939): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/GFX raster( 3453): took 0.556874ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb8d98940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9035a98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity,
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
W/ResourcesManager( 3986): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453,): Resource data:2131165203
,W/ResourcesManager( 3453): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3453): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3453): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GFX construct_block_size_descriptor_2d second part( 3453): took 2.830676ms for 0*0 texture 0,
,E/Zygote  ( 4001): MountEmulatedStorage()
I/libpersona( 4001): KNOX_SDCARD checking this for 10159
E/Zygote  ( 4001): v2
I/libpersona( 4001): KNOX_SDCARD not a persona
I/SELinux ( 4001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4001 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4001): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 2926:com.android.vending/u0a28 (adj 15): empty #31
,I/GFX generate_partition_tables( 3453): took 9.927554ms for 0*0 texture 0
,I/GFX raster( 3453): took 13.610938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9032c40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb90342c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
I/vclib   ( 3682): onServiceConnected
W/Babel   ( 3682): Attempted to change video mute state without an active call.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.777916ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9029008 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb90290b0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4001): TimaSignature is unavailable
D/ActivityThread( 4001): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3453): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/Zygote  ( 4016): MountEmulatedStorage()
I/libpersona( 4016): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4016): v2
I/libpersona( 4016): KNOX_SDCARD not a persona
,I/SELinux ( 4016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4016): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4016 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3251:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3453): took 0.789011ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9029008 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb90343f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/TimaKeyStoreProvider( 4016): TimaSignature is unavailable
,D/ActivityThread( 4016): Added TimaKeyStore provider
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/Intent to TravelDirActivity( 4001): inside TravelBroadcastReceiver
,I/GFX raster( 3453): took 0.838335ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9029008 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb902c408 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,I/ActivityManager( 1018): Killing 3269:com.fmm.dm/1000 (adj 15): empty #31
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.604271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90343f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9034600 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 4016): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4016): [PushClientApplication] Push log off : This is Ship build version
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3251/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10028/pid_2926/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3453): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,E/SPPClientService( 4016): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
E/SPPClientService( 4016): [SystemStateMoniter] Current Time : 39803
,D/SPPClientService( 4016): PushLog.txt file is not deleted.
,D/SPPClientService( 4016): PushLog.txt file is not deleted.
,D/SPPClientService( 4016): ============PushLog. stop!
,I/System.out( 3806): INFO:Resource not found:/Common.properties Using default values
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3269/cgroup.procs: No such file or directory
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.767083ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90343f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb901dd18 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3453): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,E/Zygote  ( 4045): MountEmulatedStorage()
,E/Zygote  ( 4045): v2
I/libpersona( 4045): KNOX_SDCARD checking this for 10166
I/libpersona( 4045): KNOX_SDCARD not a persona
I/SELinux ( 4045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4045 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2306:com.sec.android.app.mt/1000 (adj 15): empty #31
,E/SELinux ( 4045): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/ContextImpl( 3453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/TimaKeyStoreProvider( 4045): TimaSignature is unavailable
,D/ActivityThread( 4045): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131099648
,W/ResourcesManager( 3453): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3453): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 1.380313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb955b548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb955b820 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/Process ( 3939): Sending signal. PID: 3939 SIG: 9
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2306/cgroup.procs: No such file or directory
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3453): took 2.419896ms for 0*0 texture 0
,I/ActivityManager( 1018): Process com.sec.android.app.sns3 (pid 3939)(adj 0) has died(51,1133)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GFX generate_partition_tables( 3453): took 9.051250ms for 0*0 texture 0,
I/GFX raster( 3453): took 12.566094ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9050bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb901ac50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/Zygote  ( 4060): MountEmulatedStorage()
I/libpersona( 4060): KNOX_SDCARD checking this for 10034
E/Zygote  ( 4060): v2
I/libpersona( 4060): KNOX_SDCARD not a persona
,I/SELinux ( 4060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 4060): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4060 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.667292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90542f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb902e1d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/TimaKeyStoreProvider( 4060): TimaSignature is unavailable
,D/ActivityThread( 4060): Added TimaKeyStore provider
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.640989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9036c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9056f40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ResourcesManager( 4045): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4045): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4045): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ResourcesManager( 3905): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3905): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3905): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.629115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb901ac50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c82dd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ResourcesManager( 3905): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ActivityThread( 4045): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4045): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e3afaf6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4045): Installed default security provider GmsCore_OpenSSL
E/Zygote  ( 4081): MountEmulatedStorage()
E/Zygote  ( 4081): v2
I/libpersona( 4081): KNOX_SDCARD checking this for 1000
I/libpersona( 4081): KNOX_SDCARD not a persona
I/SELinux ( 4081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4081 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Killing 3287:com.wssnps/1000 (adj 15): empty #31
,E/SELinux ( 4081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 1700): (10) POSIX Error : 11 SQLite Error : 3850
,D/TimaKeyStoreProvider( 4081): TimaSignature is unavailable
,D/ActivityThread( 4081): Added TimaKeyStore provider
,E/SMD     (  291): DCD OFF
,I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4081): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4081): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3287/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4081): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.734584ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9015e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9056780 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3453): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/Zygote  ( 4100): MountEmulatedStorage()
,E/Zygote  ( 4100): v2
I/libpersona( 4100): KNOX_SDCARD checking this for 10041
I/libpersona( 4100): KNOX_SDCARD not a persona
,I/SELinux ( 4100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4100 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3339:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/SELinux ( 4100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen,
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131099648
,E/SELinux ( 4100): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3453): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3453): took 0.737084ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb955b548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9050b80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4100): TimaSignature is unavailable
,D/ActivityThread( 4100): Added TimaKeyStore provider
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.706510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9050bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9032c40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3339/cgroup.procs: No such file or directory,
,I/DBG_POLICYDM( 4081): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3453): took 0.686770ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90542f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9056780 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false,
I/AMMetaDataParserService( 3453): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/DBG_POLICYDM( 4081): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/SA      ( 4100): [SSP] onCreated
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.637292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9036c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9050b80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/art     ( 4045): Suspending all threads took: 5.454ms
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.647292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb901ac50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9019be8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4100): [TPM] There is no property file
,I/SA      ( 4100): [SCU] isHaveSA() - false
,I/SA      ( 4100): [TPM] getModelProperty : null
I/SA      ( 4100): [TPM] getCSCProperty : null
,I/SA      ( 4100): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 4100): [DM] PRODUCT AMOLED FEATURE: false
,I/SA      ( 4100): [DM] TFT FEATURE: false
,I/SA      ( 4100): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4100): [DM] init START
,I/SA      ( 4100): [DM] This device is not a Vodafone,
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourceType( 4100): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4100): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,I/GFX raster( 3453): took 0.740468ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9015e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90343f0 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourceType( 4100): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4100): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4100): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,I/dex2oat ( 4119): ----------------------------------------------------
I/dex2oat ( 4119): <SS>: S T A R T I N G . . .
I/dex2oat ( 4119): <SS>: Zip is absent. Canceled.
W/ResourceType( 4100): No package identifier when getting value for resource number 0x00000000
,I/dex2oat ( 4119): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads644789219.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads644789219.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ResourceType( 4100): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75),
W/ResourceType( 4100): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4100): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4100): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75),
W/ResourceType( 4100): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
I/AMMetaDataParserService( 3453): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
W/ResourceType( 4100): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4100): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75),
W/ResourceType( 4100): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4100): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4100): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4100): [SCU] isHaveSA() - false
I/SA      ( 4100): support phone number id : false
I/SA      ( 4100): [DM] Supports Ref Jpn : true
,I/SA      ( 4100): [DM] init END
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,I/SA      ( 4100): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131099648
I/SA      ( 4100): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3453): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/GFX raster( 3453): took 1.374011ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb955b548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9053068 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4100): [OR] onReceive END
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SA      ( 4100): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4100): [ODM] queryOpenData(key= GEO_IP )
,I/SA      ( 4100): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4100): [LBE] REF_JPN : true
I/SA      ( 4100): [BDC] create
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.674271ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9050bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8ff5568 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/dex2oat ( 4119): dex2oat took 124.862ms (threads: 4)
,E/YouTube MDX( 4045): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.623021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90542f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9032c40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SA      ( 4100): [DBMV2] getEmailID
,I/SA      ( 4100): [DBMV2] getDataV02ForItems
,I/SA      ( 4100): [SSP] query invoked
,I/SA      ( 4100): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4100): [SCU] get signed id from samsung account1.0 DB.
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.644010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9036c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9053068 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 4100): [BDC] destroy
,I/ActivityManager( 1018): Killing 3355:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,I/AMMetaDataParserService( 3453): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.663959ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb901ac50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9053550 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.739636ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9015e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9010988 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4045): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache,
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131099648
,I/AMMetaDataParserService( 3453): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.690625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb955b548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d98940 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.627292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9050bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb90354f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/libprocessgroup( 1018): failed to open /acct/uid_10125/pid_3355/cgroup.procs: No such file or directory
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.841094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb90542f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8dc0530 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.714584ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9036c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9010988 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3453): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.820260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb901ac50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90343f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.739634ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9015e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9032c40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131099648
,I/AMMetaDataParserService( 3453): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 1.354271ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb8d98940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9020008 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4045): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4045): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 4045): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4045): Found 10012
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.718021ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb901ac50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb90360d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.638385ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9053618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb90343f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.625625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb901ff98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb902e1d8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4045): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/AMMetaDataParserService( 3453): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.626562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9036c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ff5568 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.716041ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9015e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90343f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131099648
,I/AMMetaDataParserService( 3453): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.758281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb8d98940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90542f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.788386ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb901ac50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9010988 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3453): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.635313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9053618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb90354f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.649114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb901ff98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9019be8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3453): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.646563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9036c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90343f0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4181): MountEmulatedStorage(),
I/libpersona( 4181): KNOX_SDCARD checking this for 10101
E/Zygote  ( 4181): v2
I/libpersona( 4181): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4181 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.753594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9015e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90542f8 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
E/SELinux ( 4181): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3453): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/ActivityManager( 1018): Killing 3374:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
W/ContextImpl( 3453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running ac,tivitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
D/TimaKeyStoreProvider( 4181): TimaSignature is unavailable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity,
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/ActivityThread( 4181): Added TimaKeyStore provider
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131165197
,W/ResourcesManager( 3453): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3453): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,I/AMMetaDataParserService( 3453): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/AMMetaDataParserService( 3453): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_3374/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3453): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/SSRM:n  ( 1018): SIOP:: AP = 390
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131165197
,I/AMMetaDataParserService( 3453): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,I/AMMetaDataParserService( 3453): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3453): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3453): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131165197
,I/AMMetaDataParserService( 3453): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,I/AMMetaDataParserService( 3453): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3453): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3453): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/Gmail   ( 4181): getAccountsCursor
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3453): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131099648
,W/ResourcesManager( 3453): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3453): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/AMMetaDataParserService( 3453): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/GAV2    ( 4181): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/AMMetaDataParserService( 3453): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4181): Observing account changes for notifications
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/AlarmManager( 1018): waitForAlarm result :8
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 4181): Error finding the version of the Email provider.....
E/Gmail   ( 4181): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4181): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 4181): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4181): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4181): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4181): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 4181): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4181): We do not support migrating this version of the Email provider.
,D/accuweather( 1564): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1564): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1564): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1564): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,I/Gmail   ( 4181): getAccountsCursor
,E/accuweather( 1564): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 23 48
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:assistant
I/AMMetaDataParserService( 3453): Resource data:2131165220
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3453): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3453): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3453): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3453): getResourceTypeNamexml
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.704063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9751fb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9751d78 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3453): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/Zygote  ( 4219): MountEmulatedStorage()
,I/libpersona( 4219): KNOX_SDCARD checking this for 10092
E/Zygote  ( 4219): v2
I/libpersona( 4219): KNOX_SDCARD not a persona
I/SELinux ( 4219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4219 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4219): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/        ( 3453): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3453): took 0.642188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3453): Bitmap=0xb9751e58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9765200 counterpartCT=4 counterpartW=96 counterparth=96
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/AMMetaDataParserService( 3453): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog,
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity,
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
D/TimaKeyStoreProvider( 4219): TimaSignature is unavailable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.setti,ngs.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
D/ActivityThread( 4219): Added TimaKeyStore provider
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getRe,sourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ContextImpl( 3453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.LanguageSettings
,I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ManageApplications
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
,I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
,I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
,I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.MediaFormat
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3453): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3453): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3453): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
E/SQLiteLog( 4181): (283) recovered 5 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/SensorService( 1018): [SO] 0.172 0.134 10.209
E/File    ( 4181): fail readDirectory() errno=2
I/Gmail   ( 4181): notifyAccountChanged
I/Gmail   ( 4181): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4181): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4181): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4181): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     ( 1018): Explicit concurrent mark sweep GC freed 36829(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/39MB, paused 2.226ms total 166.217ms
D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1018): Killing 3390:com.fmm.ds/1000 (adj 15): empty #31
,I/Gmail   ( 4181): getAccountsCursor
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityThread( 4181): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2e72c6ed that was originally bound here
E/ActivityThread( 4181): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2e72c6ed that was originally bound here
E/ActivityThread( 4181): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 4181): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 4181): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 4181): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 4181): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 4181): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4181): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4181): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4181): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4181): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4181): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4181): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4181): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4181): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4181): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@601a5af
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4181): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 4181): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 4181): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3390/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 3405:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_3405/cgroup.procs: No such file or directory
,I/Gmail   ( 4181): getAccountsCursor
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4238): MountEmulatedStorage()
,E/Zygote  ( 4238): v2
I/libpersona( 4238): KNOX_SDCARD checking this for 10092
I/libpersona( 4238): KNOX_SDCARD not a persona
,I/SELinux ( 4238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4238): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4238 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4238): TimaSignature is unavailable
,D/ActivityThread( 4238): Added TimaKeyStore provider
,I/com.dropbox.android.service.DropboxNetworkReceiver( 4219): Setting receiver enabled: false
,E/ActivityThread( 4219): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider,
,I/ActivityManager( 1018): Killing 3160:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/dbxyzptlk.db300200.aw.h( 4219): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
,D/breakpad( 4219): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,I/dbxyzptlk.db300200.aw.h( 4219): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
,I/dbxyzptlk.db300200.aw.h( 4219): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
,I/libDropboxSync.so( 4219): Setting global terminate handler.
,I/dbxyzptlk.db300200.aw.h( 4219): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10009/pid_3160/cgroup.procs: No such file or directory
,I/com.dropbox.sync.android.L( 4219): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/com.dropbox.sync.android.L( 4219): Removing unclaimed file/directory in cache: "local-dbapp_noauth"
,I/com.dropbox.sync.android.bf( 4219): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,W/art     ( 4219): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4219): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1854): Explicit concurrent mark sweep GC freed 24830(1885KB) AllocSpace objects, 22(352KB) LOS objects, 24% free, 10MB/13MB, paused 1.257ms total 56.970ms
,I/iu.UploadsManager( 1854): End new media; added: 0, uploading: 0, time: 103 ms
,I/com.dropbox.sync.android.aS( 4219): Created NativeDbappNoAuthClientProvider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,I/System.out( 4219): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4219): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4219): (HTTPLog)-Static: isShipBuild true
I/System.out( 4219): (HTTPLog)-Thread-662-936902391: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4219): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10092
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10092
,W/com.dropbox.sync.android.NativeHttp( 4219): GET failed: java.net.UnknownHostException: Unable to resolve host "api.dropbox.com": No address associated with hostname
,W/libDropboxSync.so(status)( 4219): NETWORK: CoreLogger.cpp:82: java.net.UnknownHostException: Unable to resolve host "api.dropbox.com": No address associated with hostname
,I/com.dropbox.sync.android.DbxSyncService( 4219): DbxSyncService starting.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4275): MountEmulatedStorage()
I/libpersona( 4275): KNOX_SDCARD checking this for 10057
E/Zygote  ( 4275): v2
I/libpersona( 4275): KNOX_SDCARD not a persona
I/SELinux ( 4275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4275 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 4275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4275): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 3453:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/art     (  309): Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 22.813ms
,D/TimaKeyStoreProvider( 4275): TimaSignature is unavailable
,D/ActivityThread( 4275): Added TimaKeyStore provider
,E/SMD     (  291): DCD OFF
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 873us total 27.146ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 17.768ms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3453/cgroup.procs: No such file or directory
,D/LocationManagerService( 1018): getProviders()=[passive]
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 3469:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1700): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1700): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VelvetNetworkClient( 4275): Network connection not availble
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4314): MountEmulatedStorage()
E/Zygote  ( 4314): v2
I/libpersona( 4314): KNOX_SDCARD checking this for 10012
I/libpersona( 4314): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4314 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 4314): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 4314): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 4314): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SearchBackgroundTaskFac( 4275): Checking for language pack updates
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TimaKeyStoreProvider( 4314): TimaSignature is unavailable
,D/ActivityThread( 4314): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ResourcesManager( 4314): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ResourcesManager( 4314): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GservicesUpdateTask( 4275): Updating Gservices keys
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/VelvetNetworkClient( 4275): Network connection not availble
,I/MultiDex( 4314): VM with version 2.1.0 has multidex support
I/MultiDex( 4314): install
I/MultiDex( 4314): VM has multidex support, MultiDex support library is disabled.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VelvetNetworkClient( 4275): Network connection not availble
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,V/JNIHelp ( 4314): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService; callingUser = 0; userId(target) = 0
,I/art     ( 1700): Explicit concurrent mark sweep GC freed 9611(570KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.205ms total 63.484ms
,D/AuthorizationBluetoothService( 1700): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1700): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityThread( 4314): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4314): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e8ce4cc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4314): Installed default security provider GmsCore_OpenSSL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_3469/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1700): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1700): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1700): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1700): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
D/WearableService( 4314): callingUid 10012, callindPid: 4314
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1700): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 4275): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,E/MDM     ( 1643): [175] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1643): [176] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1700): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 1176): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1176): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Search.LoginHelper( 4275): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4275): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4275): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/Search.LoginHelper( 4275): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4275): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4275): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/KnoxNotification( 1176): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1176): ----- inflateViews : modified KnoxViewLocal -----
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1176): PersonaID is invalid or persona doesn't exists. : 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/LibraryLoader( 4275): Time to load native libraries: 12 ms (timestamps 4330-4342)
I/LibraryLoader( 4275): Expected native library version number "",actual native library version number ""
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1700): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1700): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1700): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1700): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 4275): Attempt to remove local handle scope entry from IRT, ignoring
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1643): [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1854): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4374): MountEmulatedStorage()
,E/Zygote  ( 4374): v2
I/libpersona( 4374): KNOX_SDCARD checking this for 10098
I/libpersona( 4374): KNOX_SDCARD not a persona
,I/SELinux ( 4374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc flipboard.app for broadcast flipboard.app/flipboard.gcm.FlipboardGCMBroadcastReceiver: pid=4374 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4374): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Search.LoginHelper( 4275): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4275): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4275): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/Search.LoginHelper( 4275): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4275): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4275): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4275): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4275): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/TimaKeyStoreProvider( 4374): TimaSignature is unavailable
D/ActivityThread( 4374): Added TimaKeyStore provider
D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/art     ( 4275): Attempt to remove local handle scope entry from IRT, ignoring
,W/RefreshDomainCookieTask( 4275): Search parameters fetch failed: com.google.android.apps.gsa.shared.api.io.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
,W/RefreshDomainCookieTask( 4275): Search parameters fetch failed
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.android.gms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4374): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4374): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,E/SQLiteLog( 1700): (10) POSIX Error : 11 SQLite Error : 3850
,I/System.out( 4374): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 4374): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4374): (HTTPLog)-Static: isShipBuild true
I/System.out( 4374): (HTTPLog)-Thread-677-1062080210: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4374): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10098
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10098
,E/Fabric  ( 4374): Unknown error while loading Crashlytics settings. Crashes will be cached until settings can be retrieved.
,I/System.out( 4374): Parsed section Cover Stories, private: false
,W/flip    ( 4374): [WARN:2] registerNotification failed: Network not available
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1700): GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1700): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 4374): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 4374): Time to load native libraries: 1 ms (timestamps 5303-5304)
I/LibraryLoader( 4374): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4374): Binding Chromium to main looper Looper (main, tid 1) {1ce637b}
,I/LibraryLoader( 4374): Expected native library version number "",actual native library version number ""
,I/chromium( 4374): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4374): Initializing chromium process, singleProcess=true
,W/art     ( 4374): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4374): ApplicationContext is null in ApplicationStatus
,W/chromium( 4374): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4374): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4374): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 4374): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4374): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4374): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4374): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4374): Local Branch: 
I/Adreno-EGL( 4374): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4374): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4374):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 4374): Requires BLUETOOTH permission
,D/ActivityManager( 1018): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,I/HomeSyncInstallReceiver( 1454): This pkg do not need BT addr. Do nothing
,I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4456): MountEmulatedStorage(),
E/Zygote  ( 4456): v2
I/libpersona( 4456): KNOX_SDCARD checking this for 10044
,I/libpersona( 4456): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=4456 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 4456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 4456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 4468): MountEmulatedStorage(),
E/Zygote  ( 4468): v2
I/libpersona( 4468): KNOX_SDCARD checking this for 10100,
I/SELinux ( 4468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 4468): KNOX_SDCARD not a persona,
,I/SELinux ( 4468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4468 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup,
,D/TimaKeyStoreProvider( 4456): TimaSignature is unavailable
,D/ActivityThread( 4456): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 4468): TimaSignature is unavailable
,D/ActivityThread( 4468): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4456): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4456): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4456): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4488): MountEmulatedStorage()
E/Zygote  ( 4488): v2
I/libpersona( 4488): KNOX_SDCARD checking this for 10035
I/libpersona( 4488): KNOX_SDCARD not a persona
,I/SELinux ( 4488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageChangeEventReceiver: pid=4488 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4488): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/PCWCLIENTTRACE_PushUtil( 3322): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3322): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3322): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3322): [onReceive] - android.intent.action.PACKAGE_ADDED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/PackageIntentReceiver( 4468): ACTION_PACKAGE_ADDED
E/Zygote  ( 4503): MountEmulatedStorage()
I/libpersona( 4503): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4503): v2
I/libpersona( 4503): KNOX_SDCARD not a persona
,I/SELinux ( 4503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4503 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 4488): TimaSignature is unavailable
D/PackageIntentReceiver( 4468): Not GearManger package! 
D/ActivityThread( 4488): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 3429:com.android.calendar/u0a135 (adj 15): empty #31
I/SELinux ( 4503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4516): MountEmulatedStorage()
E/Zygote  ( 4516): v2
I/libpersona( 4516): KNOX_SDCARD checking this for 1000
,I/libpersona( 4516): KNOX_SDCARD not a persona
I/SELinux ( 4516): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=4516 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3562:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/SELinux ( 4516): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4516): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4503): TimaSignature is unavailable,
D/ActivityThread( 4503): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4516): TimaSignature is unavailable
D/ActivityThread( 4516): Added TimaKeyStore provider
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4188, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1425): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1425): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/FeatureConfig( 4503): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/NearbySource( 4456): Nearby Source Create!
,D/NearbyContext( 4456): Nearby Context Create!
,I/DBG_POLICYDM( 4081): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.example.hello
,E/SPPClientService( 4488): ============PushLog. commonIsShipBuild. stop!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SPPClientService( 4488): [PushClientApplication] Push log off : This is Ship build version
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_3429/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_3562/cgroup.procs: No such file or directory
W/ResourcesManager( 4503): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 4540): MountEmulatedStorage()
E/Zygote  ( 4540): v2
I/libpersona( 4540): KNOX_SDCARD checking this for 1000
I/libpersona( 4540): KNOX_SDCARD not a persona
W/ResourcesManager( 4503): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/SELinux ( 4540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ResourcesManager( 4503): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/AlarmManager( 1018): waitForAlarm result :4,
,I/SELinux ( 4540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=4540 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/SPPClientService( 4488): PushLog.txt file is not deleted.
I/ActivityManager( 1018): Killing 3493:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/SPPClientService( 4488): PushLog.txt file is not deleted.
D/SPPClientService( 4488): ============PushLog. stop!
W/ContextImpl( 4456): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 4456): Samsung link source created
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4540): TimaSignature is unavailable
W/ResourcesManager( 4503): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityThread( 4540): Added TimaKeyStore provider
,W/ResourcesManager( 4503): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=4555 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a,
E/Zygote  ( 4555): MountEmulatedStorage()
I/libpersona( 4555): KNOX_SDCARD checking this for 10038
E/Zygote  ( 4555): v2
I/libpersona( 4555): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Killing 3704:com.android.managedprovisioning/u0a22 (adj 15): empty #31
I/SELinux ( 4555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4555): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4503): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4503): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4503): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/Zygote  ( 4571): MountEmulatedStorage()
I/libpersona( 4571): KNOX_SDCARD checking this for 10091
E/Zygote  ( 4571): v2
I/libpersona( 4571): KNOX_SDCARD not a persona
,I/SELinux ( 4571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
D/TimaKeyStoreProvider( 4555): TimaSignature is unavailable
,D/ActivityThread( 4555): Added TimaKeyStore provider
,I/SELinux ( 4571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4571): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4571 uid=10091 gids={50091, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3719:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
W/ResourcesManager( 4503): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4503): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/AcmsPackageEventListener( 4540): Received: android.intent.action.PACKAGE_ADDED
,D/TimaKeyStoreProvider( 4571): TimaSignature is unavailable
,D/ActivityThread( 4571): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ResourcesManager( 4555): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4555): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ContactProvider( 4456): getAllContactInfoList Start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4503): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 4540): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3719/cgroup.procs: No such file or directory
,W/ResourcesManager( 4503): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
W/ResourcesManager( 4503): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  ( 4588): MountEmulatedStorage()
,E/Zygote  ( 4588): v2
I/libpersona( 4588): KNOX_SDCARD checking this for 10156
I/libpersona( 4588): KNOX_SDCARD not a persona
,I/SELinux ( 4588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=4588 uid=10156 gids={50156, 9997} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 3764:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/SELinux ( 4588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4588): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 4540): Enter Oncreate
D/AcmsServiceMonitor( 4540): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 4540): creating AcmsCore
D/AcmsCore( 4540): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 4540): AcmsCore
,W/ResourcesManager( 4503): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,I/art     (  309): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 25.077ms
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 1 +
,D/TimaKeyStoreProvider( 4588): TimaSignature is unavailable
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityThread( 4588): Added TimaKeyStore provider
I/PackagesMonitor( 4456): PackagesMonitor onReceive :com.example.hello
,D/lights  ( 1018): lcd : 1 -
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.055ms
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ContactProvider( 4456): getAllContactInfoList End
I/syncContacts( 4456): thread: 683, sync time = 139
,W/ResourcesManager( 4503): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/AcmsCore( 4540): init
D/AcmsCore( 4540): Looper handler is not null
D/AcmsCore( 4540): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 4540): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsCertificateMngr( 4540): AcmsCertificateMngr
D/AcmsServiceMonitor( 4540): Incrementing - Counter value: 1
D/AcmsRevocationMngr( 4540): AcmsRevocationMngr
D/AcmsCore( 4540): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 4540): onStartCommand
D/AcmsService( 4540): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 4540): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 4540): Incrementing - Counter value: 2
D/AcmsService( 4540): Incremented Counter Value : onStartCommand
,D/ActivityThread( 4540): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/GalaxyFinderApplication( 4503): system/finder_cp/cpdata.xml file not found
,I/TapandpayWidget:TapandpayAppWidgetProvider( 4588): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 4588): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 25.742ms
,I/TapandpayWidget:Utils( 4588): Clear T&P info.
,D/AcmsService( 4540): Inside handle Intent
D/AcmsService( 4540): App added - package name: com.example.hello
D/AcmsCore( 4540): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4540): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4540): Incrementing - Counter value: 3
D/AcmsCore( 4540): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 4540): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 4540): Decrementing - Counter value: 2
,D/TapandpayWidget:TapandpayAppWidgetProvider( 4588): Widget is not attached.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4607): MountEmulatedStorage(),
I/libpersona( 4607): KNOX_SDCARD checking this for 10028,
E/Zygote  ( 4607): v2
I/libpersona( 4607): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4607 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3493/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10022/pid_3704/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3764/cgroup.procs: No such file or directory
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 30931(1766KB) AllocSpace objects, 2(52KB) LOS objects, 33% free, 26MB/39MB, paused 2.177ms total 142.764ms
,I/SELinux ( 4607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4607): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4607): TimaSignature is unavailable
,D/ActivityThread( 4607): Added TimaKeyStore provider
,E/SMD     (  291): DCD OFF
,I/SL_DEBUG( 4555): isLoggable:: isProductShip = 1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SL_DEBUG( 4555): isLoggable:: SL_DEBUG_EXIST = false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4627): MountEmulatedStorage()
E/Zygote  ( 4627): v2
I/libpersona( 4627): KNOX_SDCARD checking this for 10046
I/libpersona( 4627): KNOX_SDCARD not a persona
,I/SELinux ( 4627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4627): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=4627 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3743:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4627): TimaSignature is unavailable
D/ActivityThread( 4627): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ResourcesManager( 4627): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4627): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4627): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4627): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4627): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4627): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3743/cgroup.procs: No such file or directory
,D/ActivityThread( 4555): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
,D/Finsky  ( 4607): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Mms/MmsApp( 4627): [start]    onCreate() consume time = 0.0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4555): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4555): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/art     ( 4627): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 159.897ms
,I/SA      ( 4100): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4100): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 4100): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10176 extra.user_handle.:0 ]
,D/Finsky  ( 4607): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/art     ( 4627): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 145.476ms
,E/Zygote  ( 4683): MountEmulatedStorage()
,E/Zygote  ( 4683): v2
I/libpersona( 4683): KNOX_SDCARD checking this for 10012
I/libpersona( 4683): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4683 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 4683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
D/Mms/ArtClassLoader( 4627): init before art
,E/SELinux ( 4683): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/Mms/TelephonyPermission( 4627): start operation mode monitor
,D/TimaKeyStoreProvider( 4683): TimaSignature is unavailable
D/PackageManager( 1018): [MSG] SEND_PENDING_BROADCAST
D/ActivityThread( 4683): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 3304): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 4627): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Settings( 4607): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4607): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GAv4    ( 4571): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4571):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4571):   adb logcat -s GAv4
,D/RegisteredComponentCache( 1454): Collect Tech packages for Knox
,W/ResourcesManager( 4683): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4683): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PersonaManager( 1454): isKioskContainerExistOnDevice
,W/GAv4    ( 4571): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/PersonaManager( 1454): isKioskContainerExistOnDevice
,D/Mms/TelephonyPermission( 4627): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4627): isDefault true
D/RegisteredServicesCache( 1454): empty dynamic service
,D/Mms/MmsApp( 4627): onCreate() com.android.mms
,W/GAv4    ( 4571): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/GAV2    ( 4181): Thread[GAThread,5,main]: No campaign data found.
,W/GAv4    ( 4571): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Mms/MmsApp( 4627): [start]    initCountryIso consume time = 560.896458
,D/CountryDetector( 1018): The first listener is added
,I/GAv4-SVC( 1854): Google Analytics 7.8.99 is starting up.
,D/Mms/MmsApp( 4627): [end]    initCountryIso consume time = 8.533594
,D/Mms/MmsConfig( 4627): [start]    MmsConfig.init() consume time = 0.294375
,I/ActivityManager( 1018): Killing 3790:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/Finsky  ( 4607): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4607): [1] 2.run: Finished loading 1 libraries.
,D/Mms/MmsConfig( 4627): before partial update
,I/MultiDex( 4683): VM with version 2.1.0 has multidex support
I/MultiDex( 4683): install
I/MultiDex( 4683): VM has multidex support, MultiDex support library is disabled.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/IntentResolver( 1018): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1018): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/MmsConfig( 4627): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4627): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4627): isAuth is false
D/Mms/MmsConfig( 4627): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/BackupManagerService( 1018): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1468): query,matched:2117, calling pid = 4627,
D/TP/MmsSmsProvider( 1468): match 2117:Elapsed time : 1.271 ms
,V/BackupManagerService( 1018): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1018): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2a86aafd
,D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Loading module APK com.google.android.play.games
,D/EasySignUpManager_1.0.1( 4627): isAuth is false
D/EasySignUpManager_1.0.1( 4627): getServiceStatus : serviceId (1) is OFF
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/CscParser( 4627): mps_code.dat does not exist
E/CscParser( 4627): customer_path =/system/csc/customer.xml
,E/CscParser( 4627): fileName + /system/csc/customer.xml
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/Finsky  ( 4607): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/AnalyticsTrackerProxyImpl( 4571): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/CscParser( 4627): mps_code.dat does not exist
E/CscParser( 4627): customer_path =/system/csc/customer.xml
E/CscParser( 4627): fileName + /system/csc/customer.xml
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
V/AlarmManager( 1018): waitForAlarm result :8
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
V/JNIHelp ( 4683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/Finsky  ( 4607): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/CscParser( 4627): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4627):  enable multiwindow = true
,W/art     ( 4627): Verification of boolean com.android.mms.ui.ConversationListFragment.onOptionsItemSelected(android.view.MenuItem) took 104.488ms,
,W/ActivityThread( 4683): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4683): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e8ce4cc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4683): Installed default security provider GmsCore_OpenSSL
,E/Mms/MessageUtils( 4627): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 4627): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4627): [end]    init() consume time = 255.274374
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/Contact( 4627): [start]    init() consume time = 24.657761
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{2698193c u0 com.samsung.android.providers.context/.ContextService},
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2,
,D/Mms/Contact( 4627): [end]    init consume time = 92.186406
,D/TP/MmsSmsProvider( 1468): query,matched:13, calling pid = 4627
,D/TP/MmsSmsProvider( 1468): match 13:Elapsed time : 5.962 ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigFetchService( 1854): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/Mms/DraftCache( 4627): [start]    rebuildCache consume time = 34.907813
,W/libprocessgroup( 1018): failed to open /acct/uid_10072/pid_3790/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1018): applying state to connected service
,D/Mms/ArtClassLoader( 4627): init [DONE] art
,I/ConfigFetchService( 1854): launchTask
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1468): query,matched:12, calling pid = 4627
,D/Mms/MethodReflector( 4627): getSubId is called
,D/Mms/TelephonyUtils( 4627): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1468): match 12:Elapsed time : 3.003 ms
,D/Mms/MethodReflector( 4627): getTelephonyProperty is called
D/Mms/DownloadManager( 4627): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4627): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4627): auto download without roaming -> true
,D/Mms/DownloadManager( 4627): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 4627): getSubId is called
,D/Mms/MethodReflector( 4627): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4627): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4627): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 4627): getTelephonyProperty is called
D/Mms/DownloadManager( 4627): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4627): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4627): auto download without roaming -> true
D/Mms/DownloadManager( 4627): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4627): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4627): mAutoDownload ------> true
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/PeopleContactsSync( 1854): CP2 sync disabled
,D/Mms/DraftCache( 4627): [end]    rebuildCache consume time = 97.428593
,D/ComposerPerformance( 4627): 1452552485496 ms / [DONE] Composer constructor
,D/Mms/Conversation( 4627): [start]    init() consume time = 16.944688
,D/Vision  ( 1854): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1854): Failed to find package metadata for com.example.hello
D/Vision  ( 1854): No vision deps
,D/TP/MmsSmsProvider( 1468): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1468): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1468): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1468): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1468): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
,D/Mms/Conversation( 4627): [end]    init consume time = 32.382187
,D/Mms/MessagingNotification( 4627): [start]    init() consume time = 1.318386
,D/Mms/MessagingNotification( 4627): [end]    init consume time = 1.83901
,D/TP/MmsSmsProvider( 1468): query,matched:0, calling pid = 4627
,V/TP/MmsSmsProvider( 1468): getSimpleConversations entered.
,V/ConfigFetchTask( 1854): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VnUzRysUPPPXWr8cOc5NUCJSTyHRVAzQWaeay-hXKPCQT0Lf7czAHvE7FOxCJOKw39misaRLyRB8uwXJFzlhPrEMcaLIGfzDi1ApbyP6dPdetfR4jFw4cNOYOCLW-5FJ8ree0j3AHkxZucLwTDuEWCuUHXbT2iXx1xPF7250Jh9YbpMZ-kN87Pr7cLXomlU4oGYQ5h8HwQ3WO6MtTx-l5YdbBPjZwfuyOQ6Nq1B6xeqaMz_XM
,D/Mms/Synchronizer( 4627): [start]    doSync consume time = 9.192813
,D/Mms/SpamFilter( 4627): [start]    SpamFilter fill() begin consume time = 2.535677
,D/TP/MmsSmsProvider( 1468): match 0:Elapsed time : 9.363 ms
,D/TP/MmsSmsProvider( 1468): update, matched:300, calling pid = 4627
V/TP/MmsSmsProvider( 1468): syncDBData start
,V/TP/MmsSmsProvider( 1468): syncDBData sms end
,V/TP/MmsSmsProvider( 1468): syncDBData mms end
,V/TP/MmsSmsProvider( 1468): syncDBData end
,E/CII     ( 4627): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4627): ReservationManager()
I/Mms/ReservationManager( 4627): resetAfterConnected()
,D/Mms/Synchronizer( 4627): [end]    doSync consume time = 16.741666
,D/TP/MmsSmsProvider( 1468): query,matched:7, calling pid = 4627
,D/TP/MmsSmsProvider( 1468): match 7:Elapsed time : 2.244 ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4738): MountEmulatedStorage()
E/Zygote  ( 4738): v2
I/libpersona( 4738): KNOX_SDCARD checking this for 10072
I/libpersona( 4738): KNOX_SDCARD not a persona
,I/SELinux ( 4738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/GoogleURLConnFactory( 1854): Using platform SSLCertificateSocketFactory
,I/Icing   ( 1854): Storage manager: low false usage 1.79MB avail 7.89GB capacity 9.93GB
,I/SELinux ( 4738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4738 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/SELinux ( 4738): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{20330be6 u0 com.android.settings/.wifi.WifiCredService}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1468): query,matched:400, calling pid = 4627
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/SpamFilter( 4627): [end]    SpamFilter fill() finished consume time = 57.058542
,I/art     ( 4238): WaitForGcToComplete blocked for 28.334ms for cause HomogeneousSpaceCompact
,D/TimaKeyStoreProvider( 4738): TimaSignature is unavailable
,D/ActivityThread( 4738): Added TimaKeyStore provider
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 4607): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/System.out( 1854): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/Mms/ReservationManager( 4627): getReservedSendMessageCount(): retMessageCount=0
,I/System.out( 1854): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1854): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1854): (HTTPLog)-Thread-227-124503309: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1854): (HTTPLog)-Static: isSBSettingEnabled false
D/Mms/MmsApp( 4627): [end]    onCreate() consume time = 47.219062
,D/Mms/DownloadManager( 4627): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4627): roaming ------> false, mSimSlot = 0,
,D/Mms/MethodReflector( 4627): getSubId is called
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Mms/TelephonyUtils( 4627): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4627): getTelephonyProperty is called
D/Mms/DownloadManager( 4627): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4627): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4627): auto download without roaming -> true
D/Mms/DownloadManager( 4627): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 4627): mAutoDownload ------> true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): uids 10012
,D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ConfigFetchTask( 1854): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 1854): fetch service done; releasing wakelock
,I/ConfigFetchService( 1854): stopping self
,D/BadgeProvider( 4738): onCreate
D/BadgeProvider( 4738): DatabaseHelper
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Icing   ( 1854): Received bad json for section weights override -- ignoring.,
W/Icing   ( 1854): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 1854): Received bad json for section weights override -- ignoring.
,W/Icing   ( 1854): Received bad json for corpus context scoring override -- ignoring.
,E/Zygote  ( 4761): MountEmulatedStorage()
E/Zygote  ( 4761): v2
I/libpersona( 4761): KNOX_SDCARD checking this for 10120
,I/libpersona( 4761): KNOX_SDCARD not a persona
I/SELinux ( 4761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4761 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/SELinux ( 4761): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4571): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/FreeMessageStatusReceiver( 4627): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4761): TimaSignature is unavailable
,D/ActivityThread( 4761): Added TimaKeyStore provider
,D/Mms/FreeMessageReceiverService( 4627): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 4627): onHandleIntent: ACTION_PACKAGE_ADDED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4571): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4571): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 4779): MountEmulatedStorage()
,E/Zygote  ( 4779): v2
,I/SELinux ( 4779): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 4779): KNOX_SDCARD checking this for 10047,
I/libpersona( 4779): KNOX_SDCARD not a persona
,I/SELinux ( 4779): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4779): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=4779 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 3872:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3852:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #32
,D/TimaKeyStoreProvider( 4779): TimaSignature is unavailable
,D/ActivityThread( 4779): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 4627): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1468): query,matched:26, calling pid = 4627
,I/GLSUser ( 1700): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1700): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1700): [GLSUser] Extracting token using key: Auth
W/ResourcesManager( 4761): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/GLSActivity( 1700): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/TP/SmsProvider( 1468): match 26:Elapsed time : 11.005 ms
,W/ResourcesManager( 4779): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4779): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4779): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,D/TP/MmsSmsProvider( 1468): query,matched:6, calling pid = 4627
,D/TP/MmsSmsProvider( 1468): match 6:Elapsed time : 2.655 ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3872/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3852/cgroup.procs: No such file or directory
,W/Finsky  ( 4607): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/Watchdog( 1018): !@Sync 1
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1018): name = audio_safe_volume_state
E/Zygote  ( 4794): MountEmulatedStorage()
E/Zygote  ( 4794): v2
I/libpersona( 4794): KNOX_SDCARD checking this for 10025
I/libpersona( 4794): KNOX_SDCARD not a persona
,I/SELinux ( 4794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4794): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4794 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4794): TimaSignature is unavailable
,D/ActivityThread( 4794): Added TimaKeyStore provider
,I/GLSUser ( 1700): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1700): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1700): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1700): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1018): Killing 3806:com.vlingo.midas/u0a31 (adj 15): empty #31
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 4571): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4794): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/MyFiles ( 4779): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,I/ActivityManager( 1018): Killing 3923:com.sec.modem.settings/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/TactileAssist( 1018): enable value -1
,I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
,I/TactileAssist( 1018): List of disabled apps :
,E/Zygote  ( 4812): MountEmulatedStorage(),
E/Zygote  ( 4812): v2
,I/libpersona( 4812): KNOX_SDCARD checking this for 10004
,I/libpersona( 4812): KNOX_SDCARD not a persona
,I/SELinux ( 4812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/OMACP   ( 4794): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,I/ActivityManager( 1018): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4812 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
I/SELinux ( 4812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4812): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/Omacp( 4627): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_3806/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4812): TimaSignature is unavailable
,D/ActivityThread( 4812): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 31565(1834KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/40MB, paused 15.555ms total 217.376ms
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=4827 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 4827): MountEmulatedStorage(),
,E/Zygote  ( 4827): v2
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/SELinux ( 4827): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 4827): KNOX_SDCARD checking this for 10053
I/libpersona( 4827): KNOX_SDCARD not a persona
,I/SELinux ( 4827): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4827): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3923/cgroup.procs: No such file or directory
I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,D/TimaKeyStoreProvider( 4827): TimaSignature is unavailable
,D/ActivityThread( 4827): Added TimaKeyStore provider
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4794): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/Finsky  ( 4607): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/ResourcesManager( 4827): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/Compatibility( 4827): onReceive() it will make start service
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,I/art     ( 1700): Explicit concurrent mark sweep GC freed 16759(957KB) AllocSpace objects, 6(196KB) LOS objects, 40% free, 10MB/17MB, paused 1.112ms total 74.357ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4827): onHandleIntent()
,D/Compatibility( 4827): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10176, android.intent.extra.user_handle=0}]
,D/Compatibility( 4827): found: 2
,E/Zygote  ( 4849): MountEmulatedStorage()
E/Zygote  ( 4849): v2
I/libpersona( 4849): KNOX_SDCARD checking this for 1000
I/libpersona( 4849): KNOX_SDCARD not a persona
,D/Compatibility( 4827): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 4827): skipping ResolveInfo{ce06c99 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 4827): considering ResolveInfo{33fb0b5e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 4827): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 4827): enabling receiver ResolveInfo{80eab3f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4849 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/Compatibility( 4827): enabling receiver ResolveInfo{18264c0c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/SELinux ( 4849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/Compatibility( 4827): enabling receiver ResolveInfo{10c23955 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/SELinux ( 4849): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GLSUser ( 1700): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1700): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1700): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1700): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityThread( 4571): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4571): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29a4065: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4571): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,D/Compatibility( 4827): enabling receiver ResolveInfo{3ce87f6a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Compatibility( 4827): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,I/ActivityManager( 1018): Killing 3954:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,W/Finsky  ( 4607): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 4849): TimaSignature is unavailable
,D/ActivityThread( 4849): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_1101/pid_3954/cgroup.procs: No such file or directory
,W/BaseAppContext( 1854): Using Auth Proxy for data requests.
,W/ContextImpl( 4849): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4868): MountEmulatedStorage(),
I/libpersona( 4868): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4868): v2
I/libpersona( 4868): KNOX_SDCARD not a persona
I/SELinux ( 4868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4868): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=4868 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 3986:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 4868): TimaSignature is unavailable
,D/ActivityThread( 4868): Added TimaKeyStore provider
I/art     (  309): Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 814us total 30.234ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.139ms,
,W/ResourcesManager( 4868): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.599ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4883): MountEmulatedStorage()
,E/Zygote  ( 4883): v2
I/libpersona( 4883): KNOX_SDCARD checking this for 1000
I/libpersona( 4883): KNOX_SDCARD not a persona
,I/SELinux ( 4883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4883 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1018): Killing 4001:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,I/SELinux ( 4883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4883): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1018): failed to open /acct/uid_10157/pid_3986/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4883): TimaSignature is unavailable
,D/ActivityThread( 4883): Added TimaKeyStore provider
,W/ResourcesManager( 4883): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10159/pid_4001/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 4060:com.sec.android.soagent/u0a34 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10034/pid_4060/cgroup.procs: No such file or directory
,W/art     ( 1854): Verification of android.content.ContentValues com.google.android.gms.games.broker.GameAgent.buildExtendedGameContentValues(android.content.Context, com.google.android.gms.games.server.api.FirstPartyApplication, com.google.android.gms.games.server.api.Application, com.google.android.gms.games.server.api.Instance, com.google.android.gms.games.server.api.MarketInstance, boolean, boolean, boolean, java.lang.String, android.content.ContentValues) took 122.961ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4905): MountEmulatedStorage(),
E/Zygote  ( 4905): v2
I/libpersona( 4905): KNOX_SDCARD checking this for 10010
I/libpersona( 4905): KNOX_SDCARD not a persona
,I/SELinux ( 4905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=4905 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/SELinux ( 4905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4905): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4905): TimaSignature is unavailable
,D/ActivityThread( 4905): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 4275): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/Icing   ( 1854): updateResources: need to parse f{com.google.android.gms}
,E/SMD     (  291): DCD OFF
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
,I/ActivityManager( 1018): Killing 3538:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1854): Internal init done: storage state 0,
,I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/UpdateIcingCorporaServi( 4275): UpdateCorporaTask done [took 202 ms] updated apps [took 202 ms] 
I/ActivityManager( 1018): Killing 4045:com.google.android.youtube/u0a166 (adj 15): empty #31
,V/AlarmManager( 1018): waitForAlarm result :8
,I/GLSUser ( 1700): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1700): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1700): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1700): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1018): Killing 4181:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 4607): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4607): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_3538/cgroup.procs: No such file or directory
,I/Icing   ( 1854): Post-init done
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4607): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4607): [1] DailyHygiene.reschedule: Scheduling new run in 746 minutes (failures=5)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2974): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 14 sec
,I/ActivityManager( 1018): Killing 4219:com.dropbox.android/u0a92 (adj 15): empty #31
I/ActivityManager( 1018): Killing 4238:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #32
,D/DeviceConnectionService( 1643): client connected with version: 7571000
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=4924 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 4924): MountEmulatedStorage(),
E/Zygote  ( 4924): v2
I/libpersona( 4924): KNOX_SDCARD checking this for 10142
I/libpersona( 4924): KNOX_SDCARD not a persona
,I/SELinux ( 4924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 4924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4924): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10166/pid_4045/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4924): TimaSignature is unavailable
,D/ActivityThread( 4924): Added TimaKeyStore provider
,V/TaskCloserActivity( 4924): TaskCloserActivity enter()
,V/TaskCloserActivity( 4924): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 3682:com.google.android.talk/u0a104 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Mms/MmsApp( 4627):  start initViewCache mms
D/Mms/ComposeMessageFragment( 4627): [start]    fillCache consume time = 2000.507343
,D/Mms/ComposeMessageFragment( 4627): fillCache, easy = false
,E/Zygote  ( 4943): MountEmulatedStorage()
,E/Zygote  ( 4943): v2
I/libpersona( 4943): KNOX_SDCARD checking this for 1000
I/libpersona( 4943): KNOX_SDCARD not a persona
,I/SELinux ( 4943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4943 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4943): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4943): TimaSignature is unavailable
,D/ActivityThread( 4943): Added TimaKeyStore provider
,I/ValidateNoPeople( 1018): mEvictionCount: 0
,D/ContactProvider( 4456): getAllContactInfoList Start
,E/MTPRx   ( 4943): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1018): mCursor = null
,V/MTPRx   ( 4943): sealedState: false
V/MTPRx   ( 4943): sealedUsbMassStorageState: false
E/MTPRx   ( 4943): check value of boot_completed is1
E/MTPRx   ( 4943): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4943): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4943): Status for mount/Unmount :removed
E/MTPRx   ( 4943): SDcard is not available
,W/MTPRx   ( 4943): value of connected istrue
W/MTPRx   ( 4943): value of configured istrue
W/MTPRx   ( 4943): value of mtpEnabled istrue
W/MTPRx   ( 4943): value of ptpEnabled isfalse
,E/MTPRx   ( 4943): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4943): mFirstTime: false
,D/AbsListView( 4627): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 4627): [end]    fillCache consume time = 109.847709
,D/ContactProvider( 4456): getAllContactInfoList End
I/syncContacts( 4456): thread: 685, onChange
,D/        ( 4943): MTP: reading debug level property
,E/MTPJNIInterface( 4943): Getting CryptionKey from JAVA
,E/MTPRx   ( 4943): currentUserId is 0
,E/MTPRx   ( 4943): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4943): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4943): is_Privatemode is NOT 1
,D/SettingsProvider( 1018): name = boot_time_connected
,E/MTPRx   ( 4943): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4943): noti = 17
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,W/libprocessgroup( 1018): failed to open /acct/uid_10092/pid_4238/cgroup.procs: No such file or directory
,D/SecContentProvider( 1018): uri = 18 selection = isUsbMediaPlayerAvailable
W/libprocessgroup( 1018): failed to open /acct/uid_10101/pid_4181/cgroup.procs: No such file or directory
,E/MTPRx   ( 4943): sending MTP_ICON_ENABLED to stack
W/libprocessgroup( 1018): failed to open /acct/uid_10092/pid_4219/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_3682/cgroup.procs: No such file or directory
,D/SettingsProvider( 1018): name = mtp_running_status
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,E/MTPRx   ( 4943): else part ... so first time!!!
E/MTPPlaObsrvr( 4943): inside setContext()
E/MTPPlaObsrvr( 4943):  inside createplafiles
,E/MTPPlaObsrvr( 4943): playlist count is0
,E/MTPPlaObsrvr( 4943):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4943):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4943): Inside registerContentObserver
,E/MtpAdbObserver( 4943): inside setContext()
,E/MtpAdbObserver( 4943): Inside registerContentObserver
W/Settings( 4943): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1018): name = mtp_running_status
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,E/MtpService( 4943): onCreate.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,V/MtpMediaDBManager( 4943): inside deleteAllDB
,E/MtpService( 4943): < MTP > Registering BroadCast receiver :::::
,D/Mms/BubbleViewCache( 4627): fillCache bubble = 1
D/Mms/Contact( 4627): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4627): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 4627): [start]    invalidate() consume time = 77.885468
,D/Mms/ContactsCache( 4627): [end]    invalidate() consume time = 0.386771
,I/ActivityManager( 1018): Killing 4374:flipboard.app/u0a98 (adj 15): empty #31
,E/MtpService( 4943): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4943): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4943): onStartCommand.
D/MtpService( 1225): updating state; isCurrentUser=true, mMtpLocked=false
,W/MTPRx   ( 4943): calling native method
E/MTPJNIInterface( 4943): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4943): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/MtpMediaDBManager( 4943): inside Thread updateDB
,E/Zygote  ( 4965): MountEmulatedStorage()
E/Zygote  ( 4965): v2
I/libpersona( 4965): KNOX_SDCARD checking this for 1000
I/libpersona( 4965): KNOX_SDCARD not a persona
I/SELinux ( 4965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MTPJNIInterface( 4943): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4943): noti = 10,
W/MTPRx   ( 4943): calling native method
E/MTPRx   ( 4943): Checking the driver time out
E/MTPJNIInterface( 4943): noti = 2
D/        ( 4943): deleting sockets before message queue initialization
D/        ( 4943): event handler thread is created, so set the flag
,E/MTPRx   ( 4943): called native method
E/MTPJNIInterface( 4943): setting Media scanner status0
E/MTPJNIInterface( 4943): After setting Media scanner status0
E/MtpService( 4943): onStartCommand.
,E/MtpMediaDBManager( 4943): count : 27
W/MTPRx   ( 4943): notification from stack 1
,E/        ( 4943): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4943): Getting media scanner status0
E/MtpService( 4943): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4943): DeviceName is Thali Test (Galaxy A5)
,D/TimaKeyStoreProvider( 4965): TimaSignature is unavailable
,D/ActivityThread( 4965): Added TimaKeyStore provider
,W/MtpMediaDBManager( 4943): sending db update complete noti to stack
E/MTPJNIInterface( 4943): noti = 29
,E/SQLiteLog( 4943): (5) database is locked
,E/MTPJNIInterface( 4943): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4943): SDcard is not available
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_4374/cgroup.procs: No such file or directory
,E/        ( 4943): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4943): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4943): SDcard is not available
E/SQLiteLog( 4943): (21) API call with NULL database connection pointer
E/SQLiteLog( 4943): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4943): (21) API call with NULL database connection pointer
E/SQLiteLog( 4943): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4943): (21) API call with NULL database connection pointer
E/SQLiteLog( 4943): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4943): (21) API call with NULL database connection pointer
E/SQLiteLog( 4943): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4943): notification from stack 2
,D/        ( 4943): [mtp_init_device] Library open with 32 bits.
D/        ( 4943): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4943): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4943): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 4943):  [sua_support_present:1287] returning false 
D/        ( 4943): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
D/TMNetworkReceiver( 4965): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 4965): TMNetworkReceiver.onReceive() Enter
,D/TMNetworkReceiver( 4965): MirrorLink feauture level: using UEvent
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,I/ActivityManager( 1018): Killing 4016:com.sec.spp.push/u0a35 (adj 15): empty #31

```
