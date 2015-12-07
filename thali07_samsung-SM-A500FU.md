#### Test 502422852e23b2c_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/TP/MmsSmsProvider( 1465): query,matched:2117, calling pid = 2318
D/TP/MmsSmsProvider( 1465): match 2117:Elapsed time : 1.858 ms
D/EasySignUpManager_1.0.1( 2318): isAuth is false
D/EasySignUpManager_1.0.1( 2318): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2318): mps_code.dat does not exist
E/CscParser( 2318): customer_path =/system/csc/customer.xml
E/CscParser( 2318): fileName + /system/csc/customer.xml
E/CscParser( 2318): mps_code.dat does not exist
E/CscParser( 2318): customer_path =/system/csc/customer.xml
E/CscParser( 2318): fileName + /system/csc/customer.xml
D/CscParser( 2318): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2318):  enable multiwindow = true
E/Mms/MessageUtils( 2318): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2318): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2318): [end]    init() consume time = 76.078906
D/Mms/Contact( 2318): [start]    init() consume time = 1.522656
D/TP/MmsSmsProvider( 1465): query,matched:13, calling pid = 2318
D/TP/MmsSmsProvider( 1465): match 13:Elapsed time : 0.914 ms
D/Mms/Contact( 2318): [end]    init consume time = 18.445521
D/Mms/DraftCache( 2318): [start]    rebuildCache consume time = 8.093385
D/TP/MmsSmsProvider( 1465): query,matched:12, calling pid = 2318
D/TP/MmsSmsProvider( 1465): match 12:Elapsed time : 1.529 ms
D/Mms/MethodReflector( 2318): getSubId is called
D/Mms/TelephonyUtils( 2318): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2318): getTelephonyProperty is called
D/Mms/DownloadManager( 2318): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2318): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2318): auto download without roaming -> true
D/Mms/DownloadManager( 2318): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2318): getSubId is called
D/Mms/MethodReflector( 2318): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2318): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2318): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2318): getTelephonyProperty is called
D/Mms/DownloadManager( 2318): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2318): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2318): auto download without roaming -> true
D/Mms/DownloadManager( 2318): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2318): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2318): mAutoDownload ------> true
D/Mms/DraftCache( 2318): [end]    rebuildCache consume time = 9.731667
D/ComposerPerformance( 2318): 1449497245400 ms / [DONE] Composer constructor
D/Mms/Conversation( 2318): [start]    init() consume time = 17.405625
E/CII     ( 2318): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 2318): ReservationManager()
I/Mms/ReservationManager( 2318): resetAfterConnected()
D/TP/MmsSmsDatabaseHelper( 1465): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1465): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1465): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1465): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1465): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1465): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1465): query,matched:7, calling pid = 2318
D/TP/MmsSmsProvider( 1465): match 7:Elapsed time : 3.934 ms
I/Mms/ReservationManager( 2318): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1465): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
D/Mms/MmsApp( 2318): [end]    onCreate() consume time = 20.655
D/Mms/SmsReceiver( 2318): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
V/TP/MmsSmsDatabaseHelper( 1465): updateThread(), thread_id = 9223372036854775807
--------- beginning of system
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
V/TP/MmsSmsDatabaseHelper( 1465): sUpgradeVersion = 0, db.getVersion() = 81
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
D/Mms/DownloadManager( 2318): Service state changed: Bundle[mParcelledData.dataSize=744]
I/splitIntent( 1018): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/DownloadManager( 2318): roaming ------> false, mSimSlot = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/TP/MmsSmsProvider( 1465): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1465): need read changed broadcast:false
D/Mms/ArtClassLoader( 2318): init [DONE] art
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Mms/MethodReflector( 2318): getSubId is called
D/Mms/TelephonyUtils( 2318): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2318): getTelephonyProperty is called
D/Mms/DownloadManager( 2318): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2318): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2318): auto download without roaming -> true
D/Mms/DownloadManager( 2318): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 2318): mAutoDownload ------> true
E/Zygote  ( 2418): MountEmulatedStorage()
E/Zygote  ( 2418): v2
I/libpersona( 2418): KNOX_SDCARD checking this for 10020
I/libpersona( 2418): KNOX_SDCARD not a persona
I/SELinux ( 2418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2418 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
D/Mms/Conversation( 2318): [end]    init consume time = 37.288125
D/Mms/SmsReceiverService( 2318): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
I/SELinux ( 2418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/Mms/TelephonyPermission( 2318): isDefault true
D/Mms/SmsReceiverService( 2318): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
E/SELinux ( 2418): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/Mms/SmsReceiverService( 2318): handleSIMStatus()
D/Mms/SmsReceiverService( 2318): handleSIMStatus(): SIM_STATUS = ABSENT
D/Mms/MessagingNotification( 2318): [start]    init() consume time = 11.399583
D/TimaKeyStoreProvider( 2418): TimaSignature is unavailable
D/ActivityThread( 2418): Added TimaKeyStore provider
D/Mms/MessagingNotification( 2318): [end]    init consume time = 6.541146
D/Mms/SpamFilter( 2318): [start]    SpamFilter fill() begin consume time = 5.897136
D/Mms/Synchronizer( 2318): [start]    doSync consume time = 3.624062
D/TP/MmsSmsProvider( 1465): query,matched:0, calling pid = 2318
V/TP/MmsSmsProvider( 1465): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1465): query,matched:400, calling pid = 2318
W/ResourcesManager( 2418): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2418): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2418): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1465): match 0:Elapsed time : 3.282 ms
D/TP/MmsSmsProvider( 1465): update, matched:300, calling pid = 2318
V/TP/MmsSmsProvider( 1465): syncDBData start
D/Mms/SpamFilter( 2318): [end]    SpamFilter fill() finished consume time = 9.053333
V/TP/MmsSmsProvider( 1465): syncDBData sms end
V/TP/MmsSmsProvider( 1465): syncDBData mms end
V/TP/MmsSmsProvider( 1465): syncDBData end
D/Mms/Synchronizer( 2318): [end]    doSync consume time = 4.216355
D/Mms/MessagingNotification( 2318): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1465): query,matched:26, calling pid = 2318
D/TP/SmsProvider( 1465): match 26:Elapsed time : 1.700 ms
D/TP/MmsSmsProvider( 1465): query,matched:6, calling pid = 2318
D/TP/MmsSmsProvider( 1465): match 6:Elapsed time : 1.568 ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2437): MountEmulatedStorage()
E/Zygote  ( 2437): v2
I/libpersona( 2437): KNOX_SDCARD checking this for 10025
I/libpersona( 2437): KNOX_SDCARD not a persona
I/SELinux ( 2437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2437 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 2437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2437): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2437): TimaSignature is unavailable
D/ActivityThread( 2437): Added TimaKeyStore provider
W/ResourcesManager( 2437): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/VibratorService( 1018): hasVibrator - useVibetonz: true
D/EasySignUpManager_1.15.0305( 2418): serviceId : 0, features : -1
I/splitIntent( 1018): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1018): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
D/SecContentProvider2( 1018): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1018): mCursor = null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 1018): isCopyContactToSimAllowed = true
E/Zygote  ( 2454): MountEmulatedStorage()
E/Zygote  ( 2454): v2
I/libpersona( 2454): KNOX_SDCARD checking this for 10044
I/libpersona( 2454): KNOX_SDCARD not a persona
I/SELinux ( 2454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2454 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 2454): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2454): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2470): MountEmulatedStorage()
E/Zygote  ( 2470): v2
I/libpersona( 2470): KNOX_SDCARD checking this for 10054
I/libpersona( 2470): KNOX_SDCARD not a persona
I/SELinux ( 2470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2470 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
E/SELinux ( 2470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2454): TimaSignature is unavailable
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityThread( 2454): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2470): TimaSignature is unavailable
D/ActivityThread( 2470): Added TimaKeyStore provider
E/Zygote  ( 2483): MountEmulatedStorage()
E/Zygote  ( 2483): v2
I/libpersona( 2483): KNOX_SDCARD checking this for 10142
I/libpersona( 2483): KNOX_SDCARD not a persona
I/SELinux ( 2483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2483): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2483 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1495, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ResourcesManager( 2470): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2483): TimaSignature is unavailable
D/ActivityThread( 2483): Added TimaKeyStore provider
D/Recents_RecreateReceiver( 2470): onReceive by home
I/OMACP   ( 2437): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
V/TaskCloserActivity( 2483): TaskCloserActivity enter()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/TaskCloserActivity( 2483): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
E/Zygote  ( 2502): MountEmulatedStorage()
I/libpersona( 2502): KNOX_SDCARD checking this for 10139
E/Zygote  ( 2502): v2
I/libpersona( 2502): KNOX_SDCARD not a persona
I/SELinux ( 2502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2502 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
D/TimaKeyStoreProvider( 2502): TimaSignature is unavailable
D/ActivityThread( 2502): Added TimaKeyStore provider
W/ResourcesManager( 2502): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2502): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2502): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2502): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2502): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SMD     (  287): DCD OFF
W/art     ( 2418): Verification of void com.android.contacts.common.list.l.P() took 108.652ms
D/Mms/Omacp( 2318): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/USB_UICC(  296): Timeout! No signal received. Retry num = 22
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 2437): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/AbsListView( 2418): Get MotionRecognitionManager
D/MotionRecognitionService( 1018):  ssp status : false
D/NearbySource( 2454): Nearby Source Create!
D/NearbyContext( 2454): Nearby Context Create!
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2454): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 2454): Samsung link source created
D/ContactProvider( 2454): getAllContactInfoList Start
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/GalleryCacheReady( 2454): Receive : home resume
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 2318): ui event
I/splitIntent( 1018): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/BootupListener( 1465): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1018): name = internet_call_settings_visibility
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1001
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/PhoneUtilsCommon( 1465): isSupportVoLTE is false.
E/SQLiteLog( 1230): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/StatusChecker( 2293): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2293): onReceive : net.mt.init : DONE
D/ContactProvider( 2454): getAllContactInfoList End
I/syncContacts( 2454): thread: 253, sync time = 87
D/StatusChecker( 2293): Service state changed : 3 mSub-1
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
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 2520): 
D/AndroidRuntime( 2520): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2520): CheckJNI is OFF
D/AndroidRuntime( 2520): readGMSProperty: start
D/AndroidRuntime( 2520): readGMSProperty: already setted!!
D/AndroidRuntime( 2520): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2520): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2520): readGMSProperty: end
D/AndroidRuntime( 2520): addProductProperty: start
W/ResourcesManager( 1658): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1658): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 1658): VM with version 2.1.0 has multidex support
I/MultiDex( 1658): install
I/MultiDex( 1658): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 1658): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 1658): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 1658): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d7dea9b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1658): Installed default security provider GmsCore_OpenSSL
E/AffinityControl( 2520): AffinityControl: registerfunction enter
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 2520): Calling main entry com.android.commands.am.Am
V/UserPresentBroadcastReceiver( 1773): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1495): onPause
D/Launcher( 1495): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1495
D/AndroidRuntime( 2520): Shutting down VM
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, iello
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2537): MountEmulatedStorage()
E/Zygote  ( 2537): v2
I/libpersona( 2537): KNOX_SDCARD checking this for 10174
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2537 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/libpersona( 2537): KNOX_SDCARD not a persona
I/SELinux ( 2537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2537): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
V/ActivityThread( 1495): updateVisibility : ActivityRecord{e44486d token=android.os.BinderProxy@2e14bcff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 2537): TimaSignature is unavailable
D/ActivityThread( 2537): Added TimaKeyStore provider
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1495): onStop
V/ActivityThread( 1495): updateVisibility : ActivityRecord{e44486d token=android.os.BinderProxy@2e14bcff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
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
D/Launcher( 1495): onTrimMemory. Level: 20
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
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/WebViewFactory( 2537): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/art     ( 2520): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/LibraryLoader( 2537): Time to load native libraries: 6 ms (timestamps 9097-9103)
I/LibraryLoader( 2537): Expected native library version number "",actual native library version number ""
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
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
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1658): COMPAT: Multi user not supported
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,V/WebViewChromiumFactoryProvider( 2537): Binding Chromium to main looper Looper (main, tid 1) {1b6a985c}
I/LibraryLoader( 2537): Expected native library version number "",actual native library version number ""
I/chromium( 2537): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BrowserStartupController( 2537): Initializing chromium process, singleProcess=true
,W/art     ( 2537): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2537): ApplicationContext is null in ApplicationStatus
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/chromium( 2537): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
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
E/SQLiteLog( 1658): (283) recovered 56 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
,I/Scheduler( 1658): Use PeriodicScheduler
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 23
,W/InstanceID/Rpc( 1658): Found 10012
,D/BluetoothAdapter( 2537): 382125281: getState() :  mService = null. Returning STATE_OFF
,I/GCM     ( 1658): GCM config loaded
,D/AuthorizationBluetoothService( 1658): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1658): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/8)
,W/art     ( 2537): Attempt to remove local handle scope entry from IRT, ignoring
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,D/a       ( 1658): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AwContents( 2537): onDetachedFromWindow called when already detached. Ignoring
,V/GmsCoreStatsServiceLauncher( 1897): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PhoneWindow( 2537): *FMB* installDecor mIsFloating : false,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/PhoneWindow( 2537): *FMB* installDecor flags : 8456448
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemWebViewEngine( 2537): CordovaWebView is running on device made by: samsung
,W/art     ( 2537): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2537): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 2044): callingUid 10012, callindPid: 2044
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/OpenGLRenderer( 2537): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,W/chromium( 2537): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,E/GmsWearableLS( 1773): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PhoneWindow( 2537): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
D/PhoneWindow( 2537): *FMB* isFloatingMenuEnabled return false
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 2537
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2537): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 2537): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2537): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2537): Enabling debug mode 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1180): There is/are notification(s) 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 2537): Timeline: Activity_idle id: android.os.BinderProxy@24826978 time:29634
,I/ActivityManager( 1018): Displayed Component not be shown by security: +789ms
,W/ActivityManager( 1018): mDVFSHelper.release()
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{22d0518 u0 com.example.hello/.MainActivity t228} time:29639
,I/SamsungIME( 1785): getCurrentCandidateView
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Mms/MmsApp( 2318):  start initViewCache mms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 41483(2MB) AllocSpace objects, 3(162KB) LOS objects, 33% free, 25MB/37MB, paused 1.948ms total 170.921ms
,D/Mms/ComposeMessageFragment( 2318): [start]    fillCache consume time = 1975.547395
D/Mms/ComposeMessageFragment( 2318): fillCache, easy = false
,D/SamsungIME( 1785): Dismiss ExpandCandiate
,E/MDM     ( 1773): [183] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
,D/TP/SmsProvider( 1465): query,matched:0, calling pid = 1897
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/TP/SmsProvider( 1465): match 0:Elapsed time : 3.421 ms
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BindingManager( 2537): Cannot call determinedVisibility() - never saw a connection for the pid: 2537
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1465): Query uri=content://mms, match=0, calling pid = 1897
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/chromium( 2537): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SurfaceFlinger(  256): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  256): id=10 Removed iello (-2/8)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1465): query,matched:0, calling pid = 1897
,D/TP/SmsProvider( 1465): match 0:Elapsed time : 1.299 ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1897): Restart initialization of location
,D/TP/MmsProvider( 1465): Query uri=content://mms, match=0, calling pid = 1897,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1785): KeybaordView init() : load resources
,D/AbsListView( 2318): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 2318): [end]    fillCache consume time = 232.077552
,I/SamsungIME( 1785): getCurrentKeyboard
I/SamsungIME( 1785): getTextKeyboard
,D/JsMessageQueue( 2537): Set native->JS mode to OnlineEventsBridgeMode
,D/SamsungIME( 1785): [SwiftkeyWrapper] currentLangauge : 1701729619
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/AndroidProtocolHandler( 2537): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/art     ( 1658): No such thread id for suspend: 22
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/BubbleViewCache( 2318): fillCache bubble = 1
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
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1284): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1284): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
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
,W/art     ( 1511): Suspending all threads took: 23.856ms
,D/jxcore_app_log( 2537): JniHelper::setJavaVM(0xb8ec9450), pthread_self() = -1187047392
,D/JX-Cordova( 2537): jxcore cordova android initializing
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 24
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/AdaptiveEventManager( 1180): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
,D/AdaptiveEventManager( 1180): currentCityId is null
D/AdaptiveEventManager( 1180): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1180): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1180): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1180): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1180): mWeatherInfo is not reliable
D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,E/daemonapp( 1284): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather,
E/daemonapp( 1284): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
D/daemonapp( 1284): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2611): MountEmulatedStorage()
E/Zygote  ( 2611): v2
I/libpersona( 2611): KNOX_SDCARD checking this for 10135
I/libpersona( 2611): KNOX_SDCARD not a persona
,I/SELinux ( 2611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/jxcore-log( 2537): Initializing JXcore engine
W/jxcore-log( 2537): JXcore engine is ready
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2611 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 2611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,W/jxcore-log( 2537): Starting JXcore engine,
E/SELinux ( 2611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1449497248101
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1449518848099
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1449518820000
D/daemonapp( 1284): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449518820000
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1449518820000
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TimaKeyStoreProvider( 2611): TimaSignature is unavailable
,D/ActivityThread( 2611): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2611): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2611): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2611): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 2626): MountEmulatedStorage()
,E/Zygote  ( 2626): v2
I/libpersona( 2626): KNOX_SDCARD checking this for 1000
I/libpersona( 2626): KNOX_SDCARD not a persona
,I/SELinux ( 2626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2626 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/audit   ( 1852): type=1400 msg=audit(1449497248.155:203): avc:  denied  { ioctl } for  pid=2537 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1852):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1852): type=1300 msg=audit(1449497248.155:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=beeadd58 items=0 ppid=304 ppcomm=main pid=2537 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1852): type=1320 msg=audit(1449497248.155:203): 
,E/SELinux ( 2626): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/art     (  304): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 656us total 27.609ms
D/TimaKeyStoreProvider( 2626): TimaSignature is unavailable
D/ActivityThread( 2626): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 721us total 19.425ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 17.077ms
,D/SecurityLogAgent( 2626):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 2626):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2626):  SeDenialReceiver : Start file Zipping Service 
W/ContextImpl( 2626): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecurityLogAgent( 2626): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 2626): FileZippingService : file path =  /data/misc/audit/audit.old
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2626): FileZippingService : onPremise disabled. Zipping..  
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SIP     ( 1465): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1465): fail readDirectory() errno=2
,E/Zygote  ( 2645): MountEmulatedStorage()
I/libpersona( 2645): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2645): v2
I/libpersona( 2645): KNOX_SDCARD not a persona
I/SELinux ( 2645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/SecurityLogAgent( 2626): DenialLogFileZipCreator : createZip
,I/SELinux ( 2645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2645): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecurityLogAgent( 2626): DenialLogFileZipCreator : Not empty 
I/ActivityManager( 1018): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2645 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/SecurityLogAgent( 2626): DenialLogFileZipCreator : Files exceeded the max limit 
,D/SecurityLogAgent( 2626): DenialLogFileZipCreator File existence : true audit.old file size 631
,W/jxcore-log( 2537): Platform android
W/jxcore-log( 2537): 
W/jxcore-log( 2537): Process ARCH arm
W/jxcore-log( 2537): 
,D/SecurityLogAgent( 2626): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,D/SecurityLogAgent( 2626): FileZippingService : completed task. Returning wakelock . 
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2645): TimaSignature is unavailable
,D/ActivityThread( 2645): Added TimaKeyStore provider
,W/ResourcesManager( 2645): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/jxcore-log( 2537): JXcore Cordova bridge is ready!
I/jxcore-log( 2537): 
,W/jxcore-log( 2537): JXcore engine is started
,D/FactoryTestApp( 2645): [FactoryTestBroadcastReceiver$onReceive](2645) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2645): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/jxcore-log( 2537): >> samsung-SM-A500FU
E/jxcore-log( 2537): 
,I/jxcore-log( 2537): Total memory 1983787008
I/jxcore-log( 2537): 
,I/jxcore-log( 2537): Free memory 252108800
I/jxcore-log( 2537): 
I/jxcore-log( 2537): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2537): 
,I/jxcore-log( 2537): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2537): 
,I/jxcore-log( 2537): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2537): 
,D/FactoryTestApp( 2645): [XMLDataStorage$parseXML](2645) is Live Demo : false
,D/FactoryTestApp( 2645): [XMLDataStorage$parseXML](2645) modelXML=sm-a500fu.dat
D/FactoryTestApp( 2645): [XMLDataStorage$parseXML](2645) deviceXML=a5ulte.dat
D/FactoryTestApp( 2645): [XMLDataStorage$parseXML](2645) nameXML=a5ultexx.dat
D/FactoryTestApp( 2645): [XMLDataStorage$parseAsset](2645) parseAsset Is Started
,I/jxcore-log( 2537): Size 720 1280
I/jxcore-log( 2537): 
I/jxcore-log( 2537): Screen Brightness 5
I/jxcore-log( 2537): 
E/jxcore-log( 2537): Dummy Error Log.
E/jxcore-log( 2537): 
,I/FactoryTestApp( 2645): [XMLDataStorage$parseAsset](2645) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2645): [XMLDataStorage$parseAsset](2645) Decode base file: factory.dat
,V/AlarmManager( 1018): waitForAlarm result :4
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=FACTORY_TEST_APP
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=FAILHIST_VERSION
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=MODEL_NAME
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=MODEL_NUMBER
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=CHIPSET_NAME
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=DEVICE_TYPE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=BATT_TYPE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=PANEL_TYPE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SPEAKER_COUNT
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=MIC_COUNT
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TORCH_MODE_FLASH_ON_CURRENT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_LTE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_DUAL_STANBY_ONE_CP
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_RCV
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=FACTORY_TEST_APO
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_EPEN
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_SENSORHUB
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=NEED_CAMDRIVER_OPEN
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=HW_VER_EFS
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_HOVER_HIGHTLIGHT
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=FONT_SIZE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=RAM_SIZE_IF
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=MULTI_TSK_THD
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_SEMI_FUNCTION_TEST
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_DISABLE_SCROLLING_CACHE
D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_TEST_POWER
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_TEST_HOME
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_TEST_BACK
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=IS_VIBETONZ_UNSUPPORTED,
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=AT_GPSSTEST
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=PA0_TEMP_ADC
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=PA1_TEMP_ADC
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=HALL_IC_TEST
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=READ_TARGET_GEOMAGNETIC
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_SELFTEST_MIN_MELFAS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_SELFTEST_MAX_MELFAS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=BOOTLOADER_VERSION
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=BATTERY_TEST_MODE
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=BATTERY_VF_OCV
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_COMMAND_CMD
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=KEY_PRESSED_POWER
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=LPA_MODE_SET
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2645): [XMLDataStorage$redefinitionById](2645) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2645): [XMLDataStorage$parseAsset](2645) SemiFunctionMenu
,D/FactoryTestApp( 2645): [XMLDataStorage$parseAsset](2645) parseAsset Is Completed
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2645): [ModuleCommon$ModuleCommon](2645) Create ModuleCommon
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2645): [Support$Kernel.read](2645) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2645): [ModuleCommon$readFactoryMode](2645) mode: ON
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2645): [FactoryTestBroadcastReceiver$onReceive](2645) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2645): [Support$Values.getBoolean](2645) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 2645): [Support$Properties.get](2645) property=ro.factory.factory_binary
D/FactoryTestApp( 2645): [FactoryTestBroadcastReceiver$onReceive](2645) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2645): [ModuleCommon$getFtClientEnableState](2645) result : false
I/FactoryTestApp( 2645): [ModuleCommon$connectedJIG](2645) ...
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2645): [ModuleCommon$connectedJIG](2645) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2645): [Support$Kernel.read](2645) path=/sys/class/sec/switch/adc, value=1f
,I/FactoryTestApp( 2645): [ModuleCommon$connectedJIG](2645) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2645): [ModuleCommon$isConnectionModeNone](2645) mConnectionMode = gsm
I/FactoryTestApp( 2645): [ModuleCommon$isRunningFtClient](2645) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2645): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2645) start DummyFtClient service for APO
,W/ContextImpl( 2645): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2645): User mode
,I/FactoryTestApp( 2645): [ModuleCommon$disableFtClient](2645) ...
,D/FactoryTestApp( 2645): [DummyFtClient$onCreate](2645) Create DummyFtClient service
I/FactoryTestApp( 2645): [XMLDataStorage$parsingXML](2645) FtClient => data parsing was completed.
D/FactoryTestApp( 2645): [DummyFtClient$onReceive](2645) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2645): [ModuleCommon$isConnectionModeNone](2645) mConnectionMode = gsm
,D/FactoryTestApp( 2645): [Support$Values.getBoolean](2645) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2645): [DummyFtClient$onStartCommand](2645) ...
,I/WifiService( 1018): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager( 1018): boot completed
,D/UsbDeviceManager( 1018): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1018): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1018): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,I/KeyguardEffectViewUtil( 1180): set resource id
,D/SettingsProvider( 1018): name = keyguard_default_wallpaper_res_id,
,D/UsbDeviceManager( 1018): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb,
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10054
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BOOT_COMPLETED
,D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1018): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1018): [PALM] SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1018): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/PalmMotion( 1018): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SamsungIME( 1785): showDlgMsgBox : false true true
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,D/NfcService( 1450): call the applyRouting
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2670): MountEmulatedStorage()
E/Zygote  ( 2670): v2
I/libpersona( 2670): KNOX_SDCARD checking this for 1000
I/libpersona( 2670): KNOX_SDCARD not a persona
I/SELinux ( 2670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2670 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/RecoverySystem( 1018): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1018): No recovery log file
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,I/jxcore-log( 2537): getBuffer is called!!!!
I/jxcore-log( 2537): 
,V/OtaStartupReceiver( 1465): onOtaspChanged: mOtaspMode=1
D/TimaKeyStoreProvider( 2670): TimaSignature is unavailable
,D/ActivityThread( 2670): Added TimaKeyStore provider
D/Reset_Reason( 1018): resetString = NPON
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
I/BootReceiver( 1018): Copying audit failures to DropBox
I/BootReceiver( 1018): Checking for fsck errors
,E/Zygote  ( 2691): MountEmulatedStorage()
,E/Zygote  ( 2691): v2
I/libpersona( 2691): KNOX_SDCARD checking this for 1001
I/libpersona( 2691): KNOX_SDCARD not a persona
,I/SELinux ( 2691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/SELinux ( 2691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2691 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
E/SELinux ( 2691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 2691): TimaSignature is unavailable
,D/ActivityThread( 2691): Added TimaKeyStore provider
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 25
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/File    ( 2670): fail readDirectory() errno=2
,W/ResourcesManager( 2691): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FactoryTestApp( 2645): [ProtectedFactoryTestBroadcastReceiver$onReceive](2645) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2645): [ProtectedFactoryTestBroadcastReceiver$onReceive](2645) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2645): User mode
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/NotificationReceiver( 2318): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,D/Mms/NotificationReceiver( 2318): handleBootCompleted()
,D/Mms/RcsOwnCapsManager( 2318): queue Uri = content://im/queue-messages?box=pending
,D/TP/ImProvider( 1465): im query match24
,D/TP/ImProvider( 1465): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1465): ftSesstionId must be a long.
,D/TP/ImProvider( 1465): getQueuedImMessages
D/TP/ImProvider( 1465): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/NotificationReceiver( 2318):  getPendingMessageIds: no pending messages.
,D/Mms/ActionsFactory( 2318): Call to GET_LAST_MESSAGES_SENT
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
,D/SettingsProvider( 1018): name = db_smartlock_supported
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/AccessibilityManagerService( 1018): setmDNIeNegative (false)
,D/SensorService( 1018): [SO] 0.153 0.096 10.209
,W/Settings( 1316): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1018): name = block_emergency_message
,D/SettingsProvider( 1018): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/SmartFaceService( 1018): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1018): no icon
E/SmartFaceService( 1018): mActiveServiceType: 0
,E/SmartFaceService( 1018): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1018): updateClientsDone. def. do nothing.
E/SmartFaceService( 1018): Service Type to Worker: 0
E/SmartFaceService( 1018): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1018): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1018): [SO] activate (ident=0xb9771d98, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1018): unregisterListener ::   
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb9784e68, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,V/AlarmManagerEXT( 1018): mGmsLocationBundling: false
,D/RCPManagerService( 1018): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1018):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
D/RCPManagerService( 1018): BootReceiver.onReceive(): Starting RCP Proxy for user = null
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,E/RCPManagerService( 1018):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1018): android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1018): runAdminUpdate
D/EnterpriseUtils( 1018): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService( 1018): nothing to selfUpdate
V/ApplicationPolicy( 1018): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1018): refresh widget status for user 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname flipboard.app
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname flipboard.app
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,W/PhoneRestrictionPolicy( 1018): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
D/KnoxMUMContainerPolicy( 1018): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
I/KnoxMUMContainerPolicy( 1018): MSG_REMOVE_ORPHANED_CONTAINERS received
W/PhoneRestrictionPolicy( 1018):  >>>> deliveryBlockedMsgs
D/WifiP2pService( 1018): P2pDisabledState{ what=143415 }
D/WifiP2pService( 1018): DefaultState{ what=143415 }
D/Tethering( 1018): Boot complete.
D/ConnectivityService( 1018): Got NetworkFactory Messenger for WIFI,
,D/ConnectivityService( 1018): Got NetworkFactory Messenger for WIFI_P2P
D/WIFI_P2P( 1018): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/WifiStateMachine( 1018): Blacklist file delete
W/PhoneRestrictionPolicy( 1018): cvList size 0
W/PhoneRestrictionPolicy( 1018):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1018): cvList size 0
V/EnterpriseBillingEngine( 1018): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1018): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1018): getCurrentActiveProfiles - start - 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,V/EnterpriseBillingPolicyStorage( 1018): getCurrentActiveProfiles - end - null
,V/EnterpriseBillingEngine( 1018): handleAllprofiles - end
,D/UsbHostNotification( 1018): boot completed
,D/UsbHostRestrictor( 1018): mBootCompletedReceiver onReceive
,D/UsbHostRestrictor( 1018): initSetUsbBlock STARTED
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,D/UsbHostRestrictor( 1018): SIM was never inserted
,D/UsbHostRestrictor( 1018): writableHostSysNode[false]
D/UsbHostRestrictor( 1018): Can NOT Write Disable Sys Node to [ON]
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,D/PersonaManagerService( 1018): ACTION_BOOT_COMPLETED
,D/UsbStorageNotification( 1018): boot completed
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
E/PersonaManagerServiceHandler( 1018):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/KnoxKeyguardUpdateMonitor( 1018): onBootComplete
,D/GpsLocationProvider_ex( 1018): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1018): set_capabilities_callback: 55u
I/libmdmdetect( 1018): ESOC framework not supported
,I/libmdmdetect( 1018): Found internal modem: modem
E/PerMgrLib( 1018): Peripheral manager is not supported on this device
,I/KnoxKeyguardUpdateMonitor( 1018): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1018): onTrustChanged user:0, enable:false
,D/qmi_secgps_clnt( 1018): qmi_secgps_client_init()
D/KeyguardViewMediator( 1180): onTrustChanged( Showing = false , userId = 0 )
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,E/Geofence_Adapter( 1018): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1018): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1018): BOOT_COMPLETED native_cleanup 
,D/StorageNotification( 1180): boot completed
,D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,D/WIFI    ( 1018): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/StatusBarManagerService( 1018): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
D/PhoneStatusBar( 1180): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2726): MountEmulatedStorage()
,E/Zygote  ( 2726): v2
I/libpersona( 2726): KNOX_SDCARD checking this for 10099
I/libpersona( 2726): KNOX_SDCARD not a persona
,I/SELinux ( 2726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2726 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 2726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/i       ( 1018): No model
,E/SELinux ( 2726): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/FactoryTest( 1018): Not factory mode
D/FactoryTest( 1018): Not factory mode. isFactoryMode() returend false
D/w       ( 1018): isUserBuild = true
,D/TimaKeyStoreProvider( 2726): TimaSignature is unavailable
,D/ActivityThread( 2726): Added TimaKeyStore provider
,D/SSRM:n  ( 1018): SIOP:: AP = 370
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1018): [SO] activate (ident=0xb9784e68, enabled=0)
,I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1018): [SO] changed settle time [1]
,D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb9784e68, enabled=1)
D/SensorService( 1018): [SO] AR_init
,I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/SensorService( 1018): [SO] currT = 31941052000, prevT = 31501049000, diff = 440003000, [0.172 0.096 10.209]
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,E/ActivityThread( 2726): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2726): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1018): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
,I/splitIntent( 1018): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
E/LocSvc_utils_cfg( 1018): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,I/DrmEventReceiver( 1018): DrmEventReceiver : onReceive
,I/DrmEventReceiver( 1018): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,I/DrmEventReceiver( 1018): DrmEventReceiver : beginStartingService
I/System.out( 1018): start Service
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1018): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
,V/DownloadManager( 1230): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/Zygote  ( 2745): MountEmulatedStorage()
I/libpersona( 2745): KNOX_SDCARD checking this for 10085
,E/Zygote  ( 2745): v2
I/libpersona( 2745): KNOX_SDCARD not a persona
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,I/SELinux ( 2745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1018): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK,
I/ActivityManager( 1018): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2745 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/qmi_secgps_clnt( 1018): SECGPS: Set GNSS RF CONFIG : 1
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/qmi_secgps_clnt( 1018): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,D/SensorService( 1018): [SO] currT = 32011166000, prevT = 31501049000, diff = 510117000, [0.172 0.096 10.209]
D/SensorService( 1018): [SO] 0.172 0.096 10.209
D/SensorService( 1018): [SO] [100 -> 255]
,E/Zygote  ( 2757): MountEmulatedStorage(),
E/Zygote  ( 2757): v2
I/libpersona( 2757): KNOX_SDCARD checking this for 1000
I/libpersona( 2757): KNOX_SDCARD not a persona
,I/SELinux ( 2757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2757 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
I/SELinux ( 2757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/TimaKeyStoreProvider( 2745): TimaSignature is unavailable
,D/ActivityThread( 2745): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2757): TimaSignature is unavailable
,D/ActivityThread( 2757): Added TimaKeyStore provider
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onInitialize : 160
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onSetOnInfoListener : add 160
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1018): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,I/DrmEventService( 1018): action event :android.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,I/TimaServiceEventReceiver( 1018): TimaServiceEventReceiver : onReceive
,D/MediaScannerReceiver( 1230): action: android.intent.action.BOOT_COMPLETED
,I/ANDROID_DRM_FRWORKS_DrmManager(  281): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0,
W/ResourcesManager( 2745): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2745): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2745): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 2745): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/CscReceiver( 1465): onReceive android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/CursorWrapperInner( 2318): Cursor finalized without prior close()
,D/CscUpdateService( 1465): onStart
,E/CscUpdateService( 1465): costomer file is exists : it has been preconfiged.
,I/CscUpdateService( 1465): set_CSC_version
,E/CscParser( 1465): update(): xml file exist,
,E/Zygote  ( 2781): MountEmulatedStorage()
E/Zygote  ( 2781): v2
I/libpersona( 2781): KNOX_SDCARD checking this for 10160
I/libpersona( 2781): KNOX_SDCARD not a persona
I/SELinux ( 2781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2781 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/SELinux ( 2781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2781): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/CscUtil ( 1465): isWifiOnly = false
,I/System.out( 1465): HandDataNode = null
I/CscUpdateService( 1465): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1465): This is normal boot : CSC not updated
,E/Zygote  ( 2797): MountEmulatedStorage()
I/libpersona( 2797): KNOX_SDCARD checking this for 10003
E/Zygote  ( 2797): v2
I/libpersona( 2797): KNOX_SDCARD not a persona
,I/SELinux ( 2797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2797 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/SELinux ( 2797): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/CscParser( 1465): update(): xml file exist
D/MediaScannerService( 1230): !@start scanning volume internal: [/system/media, /oem/media]
,D/TimaKeyStoreProvider( 2781): TimaSignature is unavailable
,D/ActivityThread( 2781): Added TimaKeyStore provider
,D/CscGPS  ( 1465): CSCGPS.updateParameters
D/CscGPS  ( 1465): supl host : null
D/CscGPS  ( 1465): SUPL Host is null or invalid
D/CscGPS  ( 1465): supl_ver : null
D/CscGPS  ( 1465): SUPL Ver is null or invalid
D/CscGPS  ( 1465): supl port : null
D/CscGPS  ( 1465): SUPL PORT is null or invalid
D/CscGPS  ( 1465): LPP : null
D/CscGPS  ( 1465): LPP is null or invalid
D/CscGPS  ( 1465): CSC don't have any AGPS value.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/TimaKeyStoreProvider( 2797): TimaSignature is unavailable
D/ActivityThread( 2797): Added TimaKeyStore provider
,I/CscUpdateService( 1465): same CSC Version
D/CscUtil ( 1465): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
,W/ResourcesManager( 2781): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/MtpService( 1230): updating state; isCurrentUser=true, mMtpLocked=false
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 26
,E/SQLiteLog( 1230): (283) recovered 340 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,D/[0]UMC:UMCContentProvider( 2781): @onCreate
,D/TP/MmsProvider( 1465): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1465): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1465): need read changed broadcast:false
,I/Mms:transaction( 2318): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2318): [start]    nonBlockingUpdateMessageIndicator() consume time = 2424.436144
,I/Mms/ReservationManager( 2318): resetAfterConnected()
,D/TP/MmsSmsProvider( 1465): query,matched:7, calling pid = 2318
,D/Mms/MessagingNotification( 2318): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2318): isDefault true
,D/TP/MmsSmsProvider( 1465): match 7:Elapsed time : 3.982 ms
,D/TP/MmsProvider( 1465): Query uri=content://mms, match=0, calling pid = 2318
,I/Mms/ReservationManager( 2318): getReservedSendMessageCount(): retMessageCount=0
,D/[0]UMC:Core( 2781): onCreate(): 
,D/[0]UMC:Core( 2781): @isManagedProfileUser
D/[0]UMC:Core( 2781): userId: 0
,D/TP/MmsSmsProvider( 1465): query,matched:200, calling pid = 2318
,D/[0]UMC:Core( 2781): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2781): userInfo.isManagedProfile() : false
,I/SecureStorage( 2797): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/[0]UMC:DeviceInfo( 2781): USA==US==
,I/SecureStorage( 2797): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  345): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2797
I/SecureStorage(  345): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2797): [INFO]: SPID(0x00000000)SS Daemon is running
,I/SecureStorage( 2797): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  345): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2797
I/SecureStorage(  345): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,D/USER_AGENT( 2781): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,D/[0]UMC:AdminManager( 2781): init - start
,D/[0]UMC:AdminManager( 2781): loadAdmins
,D/[0]UMC:AdminManager( 2781): init - end
,D/GSLBManager( 2781): migrateStoredUrlFromOldPref
,D/GSLBManager( 2781):  key : segd-api
,D/GSLBManager( 2781):  value : https://eu-segd-api.secb2b.com:443/v2
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 42788(2MB) AllocSpace objects, 20(729KB) LOS objects, 33% free, 26MB/39MB, paused 2.168ms total 145.552ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1465): match 200:Elapsed time : 144.246 ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
D/MediaScanner( 1230): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/GSLBManager( 2781):  key : umc-cdn
,D/GSLBManager( 2781):  value : 
D/SettingsProvider( 1018): name = next_alarm_formatted
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10085
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/Zygote  ( 2820): MountEmulatedStorage()
,E/Zygote  ( 2820): v2
,I/libpersona( 2820): KNOX_SDCARD checking this for 10048
,I/libpersona( 2820): KNOX_SDCARD not a persona
,I/SELinux ( 2820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2820 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,I/SELinux ( 2820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/GSLBManager( 2781):  key : segp-api
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/GSLBManager( 2781):  value : 
,D/TimaKeyStoreProvider( 2820): TimaSignature is unavailable
,D/ActivityThread( 2820): Added TimaKeyStore provider
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,E/Zygote  ( 2830): MountEmulatedStorage()
E/Zygote  ( 2830): v2
I/libpersona( 2830): KNOX_SDCARD checking this for 1000
I/libpersona( 2830): KNOX_SDCARD not a persona
,I/SELinux ( 2830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/GSLBManager( 2781):  key : myknoxapi
D/GSLBManager( 2781):  value : 
,I/SELinux ( 2830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 2830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/MediaScanner( 1230): processDirectory :  /system/media,
,I/ActivityManager( 1018): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2830 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/GSLBManager( 2781): migrateStoredUrlFromOldPref : Finished Migrating
D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2781): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2781): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2781): isContainer : 0
,D/Mms/SmsReceiverService( 2318): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1018): isManagedProfileUser(): userId = 0
D/Mms/TelephonyPermission( 2318): isDefault true
D/Mms/SmsReceiverService( 2318): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2318): [start]    handleBootCompleted() consume time = 274.259219
,D/TP/SmsProvider( 1465): query,matched:0, calling pid = 2318
E/[0]UMC:UMCAdmin( 2781): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2781): isContainer : 0
,D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdmin - UMC App Admin deactivated
D/TP/SmsProvider( 1465): match 0:Elapsed time : 2.304 ms
,W/ResourcesManager( 2820): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 2820): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2820): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2781): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,D/[0]UMC:CoreReceiver( 2781): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2781):  check PreETag 
,D/TimaKeyStoreProvider( 2830): TimaSignature is unavailable
,D/ActivityThread( 2830): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1465): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1465): deleteConversation threadId: 9223372036854775806
,D/TP/SmsProvider( 1465): query,matched:51, calling pid = 2318
,D/TP/MmsSmsProvider( 1465): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1465): updateThread(), thread_id = 9223372036854775806
,D/TP/SmsProvider( 1465): match 51:Elapsed time : 2.884 ms
,V/TP/MmsSmsDatabaseHelper( 1465): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1465): (284) automatic index on im_threads(normal_thread_id)
,D/[0]UMC:CoreReceiver( 2781): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2781): Enter loadList
V/MediaScanner( 1230):  prescan time: 387ms (DB items: 141)
V/MediaScanner( 1230):     scan time: 87ms (Caching mode: true), (makeEntry time: 53ms ~60%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1230): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1230):    total time: 474ms
V/MediaScanner( 1230): checked files: 133  directories : 6  (I: 0, U: 0)
,D/[0]UMC:CoreReceiver( 2781): handleAutoEnrollmentAndUMCAdminDeactivation
,D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdminIfNotRequired : -1
,D/Mms/MessagingNotification( 2318): isBlockingModeEnabled() = false, Zen mode = 0
,D/MediaScanner( 1230): checkDefaultSounds
,D/MediaScanner( 1230): system alarm_alert  : Vwiurug_etwofi5wgg
W/art     ( 2745): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 151.692ms
,D/TP/MmsSmsProvider( 1465): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1465): need read changed broadcast:false
,D/SettingsProvider( 1018): name = block_emergency_message
D/MediaScanner( 1230): OK. alarm_alert is already exist in setting DB.
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
W/ActivityManager( 1018): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10048
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/MediaScanner( 1230): system notification_sound  : K_Oprkltf5wgg
,E/[0]UMC:Utils( 2781): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2781): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdmin : -1
,D/[0]UMC:UMCAdmin( 2781): isContainer : 0
,D/Mms/Conversation( 2318): deleteTempConversation(),deleted=0
,D/MediaScanner( 1230): OK. notification_sound is already exist in setting DB.
,D/EnterpriseDeviceManagerService( 1018): isManagedProfileUser(): userId = 0
,D/MediaScanner( 1230): system ringtone  : Wmfi_lpf_pwirywu5wgg
,E/[0]UMC:UMCAdmin( 2781): No active admin owned by uid 10160
,D/[0]UMC:UMCAdmin( 2781): isContainer : 0
,D/[0]UMC:UMCAdmin( 2781): deactivateUMCAdmin - UMC App Admin deactivated
,D/MediaScanner( 1230): OK. ringtone is already exist in setting DB.
,D/FactoryTestApp( 2645): [DummyFtClient$mBroadcastReceiver](2645) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2645): [DummyFtClient$mBroadcastReceiver](2645) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2645): [DummyFtClient$mBroadcastReceiver](2645) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/BadgeProvider( 1570): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/MediaScannerService( 1230): !@done scanning volume internal
D/SmsProvider( 1465): Update uri=content://sms/outbox, match=8
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/TP/MmsSmsProvider( 1465): need read changed broadcast:false
,D/[0]UMC:ByodSetupStarter( 2781): Container ID : 0
,D/MediaScannerService( 1230): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,E/SQLiteLog( 2830): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,I/WifiCredService( 1316): onCreate
,V/[0]UMC:Utils( 2781): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2781): shutdown
,D/Mms/SmsReceiverService( 2318): moveOutboxMessagesToFailedBox messageCount: 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2781): @GuardService - stopService Result = true
,D/Mms/SmsReceiverService( 2318): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2318): [SIM-1]sendFirstQueuedMessage()
,D/BadgeProvider( 1570): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1570): sendNotify, [notify] : null
D/BadgeProvider( 1570): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1570): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1570): update, [UpdateCount] : 1
,I/art     ( 2781): System.exit called, status: 0
I/AndroidRuntime( 2781): VM exiting with result code 0, cleanup skipped.
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started
,D/Launcher.Model( 1495): reloadBadges entered.
,D/Mms/MessagingNotification( 2318): setBadgeCount(), count=0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/DSM     ( 2830): [Lines:107] Normal booted
D/DSM     ( 2830): [Lines:114] Boot completed
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter finished
,D/Mms/MessagingNotification( 2318): remove alarm
,D/MediaScanner( 1230): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/TP/SmsProvider( 1465): query,matched:26, calling pid = 2318
,D/WifiTimerReceiver( 1316): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1316): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1316): Action boot completed received
D/TP/SmsProvider( 1465): match 26:Elapsed time : 2.001 ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1465): query,matched:0, calling pid = 2318
,D/TP/SmsProvider( 1465): match 0:Elapsed time : 1.911 ms
,E/Zygote  ( 2865): MountEmulatedStorage()
E/Zygote  ( 2865): v2
I/libpersona( 2865): KNOX_SDCARD checking this for 1000
I/libpersona( 2865): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2865 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2865): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2865): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 2865): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MessagingNotification( 2318): updateAllHistoryAsRead()
,V/MediaScanner( 1230): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1230): Skipping:
D/MediaScanner( 1230): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1230): Skipping:
D/MediaScanner( 1230): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,I/ActivityManager( 1018): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2781)(adj 0) has died(159,1017)
,I/art     (  304): Explicit concurrent mark sweep GC freed 8768(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.404ms total 33.432ms
,V/MediaScanner( 1230): processDirectory :  /storage/extSdCard
,W/MediaScanner( 1230): Error opening directory, reason : Permission denied.
W/MediaScanner( 1230): 7klwibgf7fxlKdCbid7
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 18.186ms
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2865): TimaSignature is unavailable
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 18.440ms
D/ActivityThread( 2865): Added TimaKeyStore provider
,V/MediaScanner( 1230):  prescan time: 51ms (DB items: 27)
D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
V/MediaScanner( 1230):     scan time: 42ms (Caching mode: true), (makeEntry time: 9ms ~21%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1230): postscan time: 17ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1230):    total time: 110ms
V/MediaScanner( 1230): checked files: 10  directories : 17  (I: 0, U: 0)
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1284): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1284): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1284): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1284): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/MediaScannerService( 1230): !@done scanning volume external
D/SettingsProvider( 1018): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10162
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
I/art     ( 1465): Explicit concurrent mark sweep GC freed 39011(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/12MB, paused 965us total 102.135ms
,D/NearbySettings( 1316): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1316): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1316): MountReceiver.onReceive - Create mPrefHandler
,I/art     ( 1465): WaitForGcToComplete blocked for 108.076ms for cause Explicit
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
D/FactoryTestApp( 2645): [DummyFtClient$mBroadcastReceiver](2645) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2645): [DummyFtClient$mBroadcastReceiver](2645) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,D/FactoryTestApp( 2645): [DummyFtClient$sendBootCompletedAndFinish](2645) ...
D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=MODEL_COMMUNICATION_MODE, value=gsm
D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/FactoryTestApp( 2645): [ModuleCommon$isConnectionModeNone](2645) mConnectionMode = gsm
,D/Mms/MessagingNotification( 2318): [end]    nonBlockingUpdateMessageIndicator() consume time = 326.570052
,D/FactoryTestApp( 2645): [IPCWriterToSecPhoneService$ResponseWriter](2645) Create IPCWriterToSecPhoneService
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,D/SettingsProvider( 1018): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
I/FactoryTestApp( 2645): [IPCWriterToSecPhoneService$connectToSecPhoneService](2645)  
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,W/ResourcesManager( 2865): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
W/ContextImpl( 2645): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/daemonapp( 1284): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1284): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,E/daemonapp( 1284): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/NearbySettings( 1316): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1316): MountReceiver.onReceive - Internal Path
I/iu.UploadsManager( 1897): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/art     ( 1465): Explicit concurrent mark sweep GC freed 1880(73KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 926us total 44.408ms
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1449497250760
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1449518820000
D/daemonapp( 1284): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1284): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,E/Zygote  ( 2885): MountEmulatedStorage()
E/Zygote  ( 2885): v2
,I/libpersona( 2885): KNOX_SDCARD checking this for 1000
I/libpersona( 2885): KNOX_SDCARD not a persona
,I/SELinux ( 2885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2885 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1018): name = personal_mode_enabled
,I/FactoryTestApp( 2645): [IPCWriterToSecPhoneService$onServiceConnected](2645) connected done
D/FactoryTestApp( 2645): [IPCWriterToSecPhoneService$write](2645) Send Response Message to SecPhone
D/FactoryTestApp( 2645): [IPCWriterToSecPhoneService$write](2645) Response ��
,D/daemonapp( 1284): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449518820000
W/ActivityThread( 2865): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/AT_Distributor(  310): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 14
D/daemonapp( 1284): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1449518820000
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
I/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,D/FactoryTestApp( 2645): [IPCWriterToSecPhoneService$handleMessage](2645) Send BOOTING COMPLETED done
,D/TimaKeyStoreProvider( 2885): TimaSignature is unavailable
D/ActivityThread( 2885): Added TimaKeyStore provider
,W/ResourcesManager( 1465): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 1465): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/AT_Distributor(  310): SetAtdStatus(), 1_1_0
D/AT_Distributor(  310): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/Mms/SmsReceiver( 2318): unregisterForServiceStateChanges, already unregistered
,D/Mms/MessagingNotification( 2318): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2318): isDefault true
,I/SmartcardBootCompleteReceiver( 1316): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1316): Received intent with action - android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 2885): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/TP/MmsProvider( 1465): Query uri=content://mms, match=0, calling pid = 2318
,W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/comdaemonstockapp( 1284): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1284): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/SmartcardBootCompleteReceiver( 1316): Broadcast sent with current lockscreen type
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 27
,I/iu.UploadsManager( 1897): End new media; added: 0, uploading: 0, time: 245 ms
,I/SecureStorage(  345): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
W/ContextImpl( 1861): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 2865): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SecUISvc( 1861): Service started flags 0 startId 1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/[SBeam] ( 1316): SBeamEnabler.initPreferenceForSbeam : 0
,D/SecUISvc( 1861): Thread created.
,I/LcdtestApp( 2865): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,E/Zygote  ( 2905): MountEmulatedStorage()
,E/Zygote  ( 2905): v2,
I/libpersona( 2905): KNOX_SDCARD checking this for 10028
I/libpersona( 2905): KNOX_SDCARD not a persona
,I/SELinux ( 2905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2905 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 2905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/SecureStorage( 2797): [INFO]: SPID(0x00000001)Processing data has been completed
,I/SecureStorage( 2797): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2905): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2917): MountEmulatedStorage()
,E/Zygote  ( 2917): v2
I/libpersona( 2917): KNOX_SDCARD checking this for 10086
I/libpersona( 2917): KNOX_SDCARD not a persona
,I/SELinux ( 2917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2917 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 2917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Killing 1196:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
E/SELinux ( 2917): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SettingSearch/SearchIntentReceiver( 1316): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1316): search setting db init!!
,D/TimaKeyStoreProvider( 2905): TimaSignature is unavailable
,D/ActivityThread( 2905): Added TimaKeyStore provider
,E/Zygote  ( 2935): MountEmulatedStorage()
D/TimaKeyStoreProvider( 2917): TimaSignature is unavailable
D/ActivityThread( 2917): Added TimaKeyStore provider,
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2935 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,E/Zygote  ( 2935): v2
I/libpersona( 2935): KNOX_SDCARD checking this for 1000
I/libpersona( 2935): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Killing 1423:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/SELinux ( 2935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/SettingSearch/SearchIntentReceiver( 1316): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/TimaKeyStoreProvider( 2935): TimaSignature is unavailable
,D/ActivityThread( 2935): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1465): query,matched:200, calling pid = 2318
,D/TP/MmsSmsProvider( 1465): match 200:Elapsed time : 3.404 ms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1196/cgroup.procs: No such file or directory,
,E/Zygote  ( 2953): MountEmulatedStorage()
,E/Zygote  ( 2953): v2
I/libpersona( 2953): KNOX_SDCARD checking this for 1000
I/libpersona( 2953): KNOX_SDCARD not a persona
,I/SELinux ( 2953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2953 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2953): TimaSignature is unavailable
,D/ActivityThread( 2953): Added TimaKeyStore provider
,E/Zygote  ( 2968): MountEmulatedStorage()
,E/Zygote  ( 2968): v2
I/libpersona( 2968): KNOX_SDCARD checking this for 10150
I/libpersona( 2968): KNOX_SDCARD not a persona
,I/SELinux ( 2968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 2968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2968 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/SELinux ( 2968): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1423/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 2968): TimaSignature is unavailable
,D/ActivityThread( 2968): Added TimaKeyStore provider
,W/ResourcesManager( 2953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1465): query,matched:0, calling pid = 2318
,D/TP/SmsProvider( 1465): match 0:Elapsed time : 1.742 ms
,D/TP/SmsProvider( 1465): query,matched:51, calling pid = 2318
,D/TP/SmsProvider( 1465): match 51:Elapsed time : 1.091 ms
,D/Mms/MessagingNotification( 2318): isBlockingModeEnabled() = false, Zen mode = 0
,D/BadgeProvider( 1570): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/FOTA    ( 2953): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,I/DIAGMON_AGENT( 2935): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,E/UpdateRequestReceiver( 2917): ignoring update request
,D/Launcher.Model( 1495): reloadBadges entered.
,D/BadgeProvider( 1570): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 1570): sendNotify, [notify] : null
D/BadgeProvider( 1570): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1570): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1570): update, [UpdateCount] : 1
,E/UpdateRequestReceiver( 2917): ignoring update request
,D/Mms/MessagingNotification( 2318): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2318): remove alarm
,D/Mms/MessagingNotification( 2318): updateAllHistoryAsRead()
,D/TP/SmsProvider( 1465): query,matched:0, calling pid = 2318
,D/TP/SmsProvider( 1465): match 0:Elapsed time : 1.313 ms
,E/UpdateRequestReceiver( 2917): ignoring update request
,D/Mms/SmsReceiverService( 2318): [end]    handleBootCompleted() consume time = 771.525521
,I/ActivityManager( 1018): Killing 1393:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,E/UpdateRequestReceiver( 2917): ignoring update request
,E/UpdateRequestReceiver( 2917): ignoring update request
,I/DBG_DM  ( 2953): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,E/UpdateRequestReceiver( 2917): ignoring update request
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2953): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 2953): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,E/Zygote  ( 3002): MountEmulatedStorage()
E/Zygote  ( 3002): v2
I/libpersona( 3002): KNOX_SDCARD checking this for 10094
I/libpersona( 3002): KNOX_SDCARD not a persona
,I/SELinux ( 3002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3002 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3002): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 1570:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3002): TimaSignature is unavailable
,D/ActivityThread( 3002): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10096/pid_1393/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10072/pid_1570/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2953): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 2953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/elm:15183( 3002): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3002): ELMEngine.ELMEngine( context ).
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,D/elm:15183( 3002): MDMBridge.setEnterpriseBridge()
,D/Finsky  ( 2905): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/elm:15183( 3002): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/OverheatReceiver( 1180): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1180): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1180): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1180): isSafeMode = false
,D/BootupListener( 1465): intent.getAction() = android.intent.action.BOOT_COMPLETED
,V/EmergencyMode( 1412): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
D/SettingsProvider( 1018): name = internet_call_settings_visibility
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1001
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/PhoneUtilsCommon( 1465): isSupportVoLTE is false.
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,D/elm:15183( 3002): ElmAgentService : onCreate()
,D/elm:15183( 3002): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/DBG_DM  ( 2953): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/Telecom ( 1437): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/elm:15183( 3002): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 3002): BootCompletedState : startBootCompleted() call
,I/DBG_DM  ( 2953): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_DM  ( 2953): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,D/elm:15183( 3002): MDMBridge.getAllLicenseInfoFromSDK()
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 2953): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,I/Telecom ( 1437): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,E/BluetoothHeadset( 2797): BTStateChangeCB is registed
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,I/elm:15183( 3002): Get License : 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
D/BluetoothHeadset( 2797): doBind(): CallingUid(myUserHandle) = 0
D/elm:15183( 3002): ElmAgentService : onDestroy().
,I/DBG_DM  ( 2953): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 2953): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3025): MountEmulatedStorage(),
I/libpersona( 3025): KNOX_SDCARD checking this for 10012
E/Zygote  ( 3025): v2
I/libpersona( 3025): KNOX_SDCARD not a persona
I/SELinux ( 3025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3025 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/ActivityManager( 1018): Killing 1710:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,E/SELinux ( 3025): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,E/BluetoothHeadset( 2797): BluetoothHeadset service is binded
W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/Telecom ( 1437): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/Telecom ( 1437): InCallController: Unbinding from InCallService unbind
,D/BluetoothA2dp( 2797): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,I/DBG_DM  ( 2953): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 2953): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 2953): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/DIAGMON_AGENT( 2935): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,D/TimaKeyStoreProvider( 3025): TimaSignature is unavailable
,D/ActivityThread( 3025): Added TimaKeyStore provider
,D/BluetoothAdapter( 2797): 48166898: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2797): 48166898: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2797): 48166898: getState() :  mService = null. Returning STATE_OFF
I/DIAGMON_AGENT( 2935): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,D/BluetoothAdapter( 2797): 48166898: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2797): 48166898: getState() :  mService = null. Returning STATE_OFF
,I/DBG_DM  ( 2953): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 2953): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,W/ResourcesManager( 3025): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3025): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(155/onStartCommand)] ,
,W/libprocessgroup( 1018): failed to open /acct/uid_10138/pid_1710/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 2935): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,I/DIAGMON_AGENT( 2935): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,I/DIAGMON_AGENT( 2935): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2935): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/MultiDex( 3025): VM with version 2.1.0 has multidex support
I/MultiDex( 3025): install
I/MultiDex( 3025): VM has multidex support, MultiDex support library is disabled.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/EmergencyMode( 1412): [EmergencyBase] setBootTime
V/EmergencyMode( 1412): [EmergencyFactory] No Recovery State, kill my self.
,E/Zygote  ( 3043): MountEmulatedStorage()
I/libpersona( 3043): KNOX_SDCARD checking this for 10003
E/Zygote  ( 3043): v2
I/libpersona( 3043): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3043 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,V/audio_hw_primary(  282): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  282): audio_extn_get_parameters: returns 
V/msm8974_platform(  282): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  282): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  282): key: 'call_forwarding' value: ''
,V/InCall  ( 1884): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1884): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1884): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ScoverManager( 1884): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1884): InCallUtils - isCoverClosed false
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1884): InCallUtils - isCoverClosed false
I/Telecom ( 1437): ProximitySensorManager: Proximity wake lock already released
I/InCall  ( 1884): InCallPresenter -  - InCallState = NO_CALLS
,I/SELinux ( 3043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/InCall  ( 1884): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,D/InCall  ( 1884): InCallPresenter -  - dismissCoverDialog()...
I/SELinux ( 3043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2953): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/DBG_DM  ( 2953): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,E/Zygote  ( 3050): MountEmulatedStorage()
,I/libpersona( 3050): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3050): v2
I/libpersona( 3050): KNOX_SDCARD not a persona
I/SELinux ( 3050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/InCall  ( 1884): CallSContextMotion - stopPutDownListening
I/SELinux ( 3050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/InCall  ( 1884): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...,
I/ActivityManager( 1018): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3050 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3050): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PhoneStatusBarView( 1180): setCallBackground:0
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
I/ActivityManager( 1018): Killing 1552:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/InCall  ( 1884): InCallUtils - isCoverClosed false
,V/JNIHelp ( 3025): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/TimaKeyStoreProvider( 3043): TimaSignature is unavailable
D/ActivityThread( 3043): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3050): TimaSignature is unavailable
,D/ActivityThread( 3050): Added TimaKeyStore provider
,D/VideoCallManager( 1884): Instantiating VideoCallManager
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GFX construct_block_size_descriptor_2d second part( 1884): took 3.169689ms for 0*0 texture 0
,E/SMD     (  287): DCD OFF
,I/GFX generate_partition_tables( 1884): took 5.666302ms for 0*0 texture 0
,I/GFX raster( 1884): took 13.062293ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb926e110 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb926d9e0 counterpartCT=4 counterpartW=176 counterparth=144
,W/ActivityThread( 3025): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3025): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@318eca8f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3025): Installed default security provider GmsCore_OpenSSL
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
E/Zygote  ( 3074): MountEmulatedStorage()
E/Zygote  ( 3074): v2
I/libpersona( 3074): KNOX_SDCARD checking this for 1000
I/Adreno-EGL( 1884): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1884): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1884): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1884): Local Branch: 
I/Adreno-EGL( 1884): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1884): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1884):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/libpersona( 3074): KNOX_SDCARD not a persona
,I/SELinux ( 3074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/ActivityManager( 1018): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/art     ( 2905): Verification of android.content.Intent com.google.android.finsky.utils.NotificationManager.createDefaultClickIntent(android.content.Context, java.lang.String, java.lang.String, java.lang.String, java.lang.String) took 173.261ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 8765(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 688us total 24.257ms
,I/GFX GPU raster( 1884): eglCreateImageKHR: EGL_SUCCESS
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 28
,I/glCompressedTexImage2D( 1884): took 0.304375ms for 320*61440 texture 37809
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 18.490ms
,D/TimaKeyStoreProvider( 3074): TimaSignature is unavailable
,D/ActivityThread( 3074): Added TimaKeyStore provider
,I/draw setup( 1884): took 12.090104ms for 320*240 texture 37809
E/GFX GPU raster( 1884): drawn
,I/GFX GPU raster ASTC( 1884): took 44.696197ms for 320*240 texture 12
I/GFX raster( 1884): took 44.783020ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb926e090 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb926dbf8 counterpartCT=4 counterpartW=320 counterparth=240
,I/ActivityManager( 1018): Killing 2091:com.vlingo.midas/u0a31 (adj 15): empty #31
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.347ms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_1552/cgroup.procs: No such file or directory
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1884): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1884): took 0.344011ms for 480*122880 texture 37813
I/draw setup( 1884): took 0.699479ms for 480*640 texture 37813
E/GFX GPU raster( 1884): drawn
,I/GFX GPU raster ASTC( 1884): took 7.498541ms for 480*640 texture 12
I/GFX raster( 1884): took 7.580469ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb926dbf8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb949b2a8 counterpartCT=4 counterpartW=480 counterparth=640
,I/ActivityManager( 1018): Killing 2141:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,I/CameraApp( 3050): CameraApp.onCreate()... mFeature : null
I/testFeature( 3050): Feature.Feature(context)
I/testFeature( 3050): Feature.readInternalDefaultXml()
I/testFeature( 3050): ResetFeatureValue
,I/CameraFirmware_broadcast( 3050): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3050): CameraApp.getAppFeature()...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3093): MountEmulatedStorage()
,E/Zygote  ( 3093): v2
,I/libpersona( 3093): KNOX_SDCARD checking this for 10100
I/libpersona( 3093): KNOX_SDCARD not a persona
I/SELinux ( 3093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3093 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 3093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 2156:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1884): eglCreateImageKHR: EGL_SUCCESS
,D/UserAnalysis.PlaceProvider( 3043): PlaceProvider onCreate()
,I/glCompressedTexImage2D( 1884): took 0.456719ms for 440*116864 texture 37809
I/draw setup( 1884): took 0.832031ms for 440*330 texture 37809
E/GFX GPU raster( 1884): drawn
,I/GFX GPU raster ASTC( 1884): took 5.791979ms for 440*330 texture 12
I/GFX raster( 1884): took 5.926353ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb949f500 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb949f8c0 counterpartCT=4 counterpartW=440 counterparth=330
,D/TimaKeyStoreProvider( 3093): TimaSignature is unavailable
,D/ActivityThread( 3093): Added TimaKeyStore provider
,D/UserAnalysis.SecureDbManager( 3043): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3043): SecurePlaceDbHelper() 
D/UserAnalysis( 3043): Create SecureDbHelper
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
D/PackageIntentReceiver( 3093): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3093): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,I/GFX GPU raster( 1884): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1884): took 0.459948ms for 480*163840 texture 37811
I/draw setup( 1884): took 0.881302ms for 480*640 texture 37811
E/GFX GPU raster( 1884): drawn
,I/DBG_DM  ( 2953): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,I/GFX GPU raster ASTC( 1884): took 6.467396ms for 480*640 texture 12
I/GFX raster( 1884): took 6.554011ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb94deed0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb949b060 counterpartCT=4 counterpartW=480 counterparth=640
,D/Finsky  ( 2905): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1884): took 2.466666ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1884): took 7.543021ms for 0*0 texture 0
,I/GFX raster( 1884): took 12.201928ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb949f480 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb9498ac0 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1884): took 2.336823ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1884): took 6.215522ms for 0*0 texture 0
,I/GFX raster( 1884): took 10.930573ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb9498b28 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb9498cb0 counterpartCT=4 counterpartW=176 counterparth=144
,I/DBG_DM  ( 2953): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ScoverManager( 1884): registerListener
,I/DBG_DM  ( 2953): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
I/DBG_DM  ( 2953): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,W/libprocessgroup( 1018): failed to open /acct/uid_10050/pid_2141/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_2091/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10113/pid_2156/cgroup.procs: No such file or directory
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 16505(875KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.246ms total 139.366ms
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManager.StateNotifier( 1018): registerListenerCallback : binder = android.os.BinderProxy@165fb349, pid : 1884, uid : 1001, type : 1
,I/ActivityManager( 1018): Killing 1511:com.android.printspooler/u0a136 (adj 15): empty #31
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,D/IntelligenceServiceApplication( 3043): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3043): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
E/Zygote  ( 3120): MountEmulatedStorage()
E/Zygote  ( 3120): v2
I/libpersona( 3120): KNOX_SDCARD checking this for 10060
I/libpersona( 3120): KNOX_SDCARD not a persona
I/SELinux ( 3120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,E/Tethering( 1018): No numeric data
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3120 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Killing 1680:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/SELinux ( 3120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/InCall  ( 1884): InCallPresenter -  - Finished InCallPresenter.setUp
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3139): MountEmulatedStorage()
E/Zygote  ( 3139): v2
I/libpersona( 3139): KNOX_SDCARD checking this for 1000
I/libpersona( 3139): KNOX_SDCARD not a persona
I/GoogleHttpClient( 1658): GMS http client unavailable, use old client
,I/SELinux ( 3139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3120): TimaSignature is unavailable
,D/ActivityThread( 3120): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/IntelligenceServiceApplication( 3043): no applications having user consent for prediction
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 3074): [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,E/Zygote  ( 3153): MountEmulatedStorage()
I/libpersona( 3153): KNOX_SDCARD checking this for 10009
E/Zygote  ( 3153): v2
I/libpersona( 3153): KNOX_SDCARD not a persona
,I/SELinux ( 3153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 3139): TimaSignature is unavailable
D/ActivityThread( 3139): Added TimaKeyStore provider
,I/SELinux ( 3153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3153): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3153 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_1680/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10136/pid_1511/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 3043): [PlaceDetection::stopService] Service stopped.
,D/TimaKeyStoreProvider( 3153): TimaSignature is unavailable
,D/ActivityThread( 3153): Added TimaKeyStore provider
,W/Settings( 2905): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2905): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/sCloudBackupApp( 3120): sCloudBackupApp Version Info : 4.04.8.KK_APP
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3177): MountEmulatedStorage(),
I/libpersona( 3177): KNOX_SDCARD checking this for 10062
E/Zygote  ( 3177): v2
I/libpersona( 3177): KNOX_SDCARD not a persona
,I/SELinux ( 3177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,V/PlaceDetection v1.0.19 ( 3043): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3043): Constructor Preference
I/SELinux ( 3177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3177 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2306:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3177): TimaSignature is unavailable
,D/ActivityThread( 3177): Added TimaKeyStore provider
,D/Volley  ( 2905): [351] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2905): [358] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1018): Killing 2341:com.sec.modem.settings/1000 (adj 15): empty #31
,D/[SBeam] ( 1316): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1316): SBeamEnabler.isSBeamSupported : EXIST
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1018): No numeric data
,E/Zygote  ( 3195): MountEmulatedStorage()
,E/Zygote  ( 3195): v2
I/libpersona( 3195): KNOX_SDCARD checking this for 1000
,I/libpersona( 3195): KNOX_SDCARD not a persona
,I/SELinux ( 3195): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3195): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/Tethering( 1018): No numeric data
I/ActivityManager( 1018): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3195 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2350:com.sec.android.omc/1000 (adj 15): empty #31
,E/SELinux ( 3195): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Tethering( 1018): No numeric data
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/TimaKeyStoreProvider( 3195): TimaSignature is unavailable
,D/ActivityThread( 3195): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 2905): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2905): [1] 2.run: Finished loading 1 libraries.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2306/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2350/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2341/cgroup.procs: No such file or directory
,D/KnoxSetupWizardDbHelper( 3195): dbMigrationFlag : false
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/GLSUser ( 1658): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,I/ExternalOEMControlProvider( 3177): onCreate
,E/Tethering( 1018): No numeric data
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 2905): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ShortcutReceiver( 3195):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 3224): MountEmulatedStorage()
E/Zygote  ( 3224): v2
I/libpersona( 3224): KNOX_SDCARD checking this for 1000
I/libpersona( 3224): KNOX_SDCARD not a persona
,I/SELinux ( 3224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3224 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
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
,V/GmsCoreStatsServiceLauncher( 1897): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3224): TimaSignature is unavailable
,D/ActivityThread( 3224): Added TimaKeyStore provider
,D/KnoxShortcutUtil( 3195): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3195):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3195):  shortcut migration not required 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/NotificationStore( 1658): System rebooted after Notification storage file was last written
I/NotificationStore( 1658): Deleting the file
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,W/ResourcesManager( 3224): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/Zygote  ( 3240): MountEmulatedStorage()
E/Zygote  ( 3240): v2
I/libpersona( 3240): KNOX_SDCARD checking this for 1000
I/libpersona( 3240): KNOX_SDCARD not a persona
,I/SELinux ( 3240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3240 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2373:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,I/SELinux ( 3240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SELinux ( 3240): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 3074): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/SettingsProvider( 1018): name = PREVIOUS_ELAPSED_TIME
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10062
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/Finsky  ( 2905): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/ServiceMode( 3224): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 3224): setReferenceIsDumpState : 0
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/ActivityManager( 1018): Killing 2388:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3240): TimaSignature is unavailable
W/NotificationAccessSettings( 1316): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
D/ActivityThread( 3240): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,I/DBG_POLICYDM( 3074): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,E/Zygote  ( 3260): MountEmulatedStorage()
,E/Zygote  ( 3260): v2
I/libpersona( 3260): KNOX_SDCARD checking this for 1000
I/libpersona( 3260): KNOX_SDCARD not a persona
I/SELinux ( 3260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Killing 2437:com.wsomacp/u0a25 (adj 15): empty #31
,E/SELinux ( 3260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3074): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,W/ResourcesManager( 1316): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3260): TimaSignature is unavailable
,D/ActivityThread( 3260): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,D/PersistentNotificationBroadcastReceiver( 1658): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/ActivityManager( 1018): Killing 2454:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 29
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2373/cgroup.procs: No such file or directory
,E/KnoxSetupWizardClient( 3240): isShipMode : 1
I/KnoxSetupWizardClient( 3240): onReceive : android.intent.action.BOOT_COMPLETED
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/Zygote  ( 3281): MountEmulatedStorage()
I/libpersona( 3281): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3281): v2
I/libpersona( 3281): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3281 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2293:com.sec.android.app.mt/1000 (adj 15): empty #31,
I/ActivityManager( 1018): Killing 2502:com.sec.android.app.camera/u0a139 (adj 15): empty #32
I/ActivityManager( 1018): Killing 2483:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #33
,I/ActivityManager( 1018): Killing 2626:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/SELinux ( 3281): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3281): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3281): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NPS_WSSNPS( 3260): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3260): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3260): [] Service onCreate!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3294): MountEmulatedStorage()
E/Zygote  ( 3294): v2
I/libpersona( 3294): KNOX_SDCARD checking this for 1000
I/libpersona( 3294): KNOX_SDCARD not a persona
,I/SELinux ( 3294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3294 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3294): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/System.err( 3240): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3240): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3240): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3240): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3240): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3240): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3240): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
D/ScoverManager( 1316): serviceVersion : 16908288
,D/TimaKeyStoreProvider( 3281): TimaSignature is unavailable
D/ActivityThread( 3281): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8794(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 674us total 22.692ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_2388/cgroup.procs: No such file or directory
,D/NPS_WSSNPS( 3260): [] NpsServiceTask Start
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.730ms,
,D/TimaKeyStoreProvider( 3294): TimaSignature is unavailable
,D/ActivityThread( 3294): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 17.432ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_2437/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_2454/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10142/pid_2483/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2293/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2626/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,E/Zygote  ( 3315): MountEmulatedStorage()
E/Zygote  ( 3315): v2
I/libpersona( 3315): KNOX_SDCARD checking this for 10116
,I/libpersona( 3315): KNOX_SDCARD not a persona
I/SELinux ( 3315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3315 uid=10116 gids={50116, 9997} abi=armeabi-v7a
E/SELinux ( 3315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_2502/cgroup.procs: No such file or directory
,D/NPS_WSSNPS( 3260): [50.150321] smlDBHelper
,D/TimaKeyStoreProvider( 3315): TimaSignature is unavailable
,D/ActivityThread( 3315): Added TimaKeyStore provider
,I/DBG_DM  ( 2953): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/NPS_WSSNPS( 3260): [50.150321] AsyncBulkFlagCheck
,I/PageBuddyNotiSvc( 3315): Intent received : action=android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1018): name = access_control_enabled
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 3315): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3260): [50.150321] IsRemain_AsyncBulkCheck
W/ContextImpl( 3260): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/NPS_WSSNPS( 3260): [50.150321] IsRemain_Asyncing nothing
,E/Zygote  ( 3335): MountEmulatedStorage()
E/Zygote  ( 3335): v2
I/libpersona( 3335): KNOX_SDCARD checking this for 10069
I/libpersona( 3335): KNOX_SDCARD not a persona
,I/SELinux ( 3335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3335 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 3335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 2611:com.android.calendar/u0a135 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/NPS_WSSNPS( 3260): [50.150321] Service onDestroy
,I/NPS_WSSNPS( 3260): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3260): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3260): [50.150321] smlBREmailDelete
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_FMMDM( 3281): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/NPS_WSSNPS( 3260): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3260): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3260): [50.150321] smlBRMiniDiaryDelete
,I/PageBuddyNotiSvc( 3315): onCreate mCpBitFlag=0
,I/NPS_WSSNPS( 3260): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3260): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3260): [50.150321] cpuBooster release : false
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3349 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 3349): MountEmulatedStorage()
I/libpersona( 3349): KNOX_SDCARD checking this for 10125
E/Zygote  ( 3349): v2
I/libpersona( 3349): KNOX_SDCARD not a persona
,I/SELinux ( 3349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/DBG_FMMDM( 3281): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3281): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
D/NPS_WSSNPS( 3260): [50.150321] dsServerSocket close
I/DBG_FMMDM( 3281): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,I/ActivityManager( 1018): Killing 2670:com.android.keychain/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3335): TimaSignature is unavailable
,D/ActivityThread( 3335): Added TimaKeyStore provider
,I/SELinux ( 3349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
E/SELinux ( 3349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4186, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 3358): MountEmulatedStorage()
I/libpersona( 3358): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 3358): v2
I/libpersona( 3358): KNOX_SDCARD not a persona
I/SELinux ( 3358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3358): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3358 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/BluetoothAdapter( 2537): disable()
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1180): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1180): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,I/LockPatternUtils( 1316): isSmartCardAuthenticationAvailable: false
,D/TimaKeyStoreProvider( 3349): TimaSignature is unavailable
,D/ActivityThread( 3349): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3358): TimaSignature is unavailable
,D/ActivityThread( 3358): Added TimaKeyStore provider
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
E/BluetoothManagerService( 1018): Bluetooth is already disabled. DO NOT disable again.
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/Settings_Utils( 1316): isSupportVNFestival SM-A500FU XEO
,D/WifiService( 1018): setWifiEnabled: false pid=2537, uid=10174
D/SettingsProvider( 1018): name = wifi_on
,I/jxcore-log( 2537): ****TEST TOOK:  5087  ms ****
I/jxcore-log( 2537): 
,I/jxcore-log( 2537): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2537): 
,D/FileShare-Server( 3335): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
W/ResourcesManager( 3349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3349): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_LOG( 3358): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 3358): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3358): new DMDBOpenHelper instance
,D/QuickConnect( 3349): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3349): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1018): name = scon_is_running
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 10125
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/PCWCLIENTTRACE_DMContentProvider( 3358): [URIMatcher] - result : 2
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_2611/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2670/cgroup.procs: No such file or directory
,V/Finsky  ( 2905): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 3349): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/DBG_FMMDM( 3281): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3281): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3281): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/QuickConnect( 3349): PeriphStartReceiver.onReceive - no need to start,
,E/Zygote  ( 3386): MountEmulatedStorage(),
E/Zygote  ( 3386): v2
I/libpersona( 3386): KNOX_SDCARD checking this for 1000
I/libpersona( 3386): KNOX_SDCARD not a persona
,I/SELinux ( 3386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3386 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2213:flipboard.app/u0a98 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 2726:flipboard.boxer.app/u0a99 (adj 15): empty #32
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3397): MountEmulatedStorage()
I/libpersona( 3397): KNOX_SDCARD checking this for 10131
E/Zygote  ( 3397): v2
I/libpersona( 3397): KNOX_SDCARD not a persona
I/SELinux ( 3397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3397 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2757:com.sec.usbsettings/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3386): TimaSignature is unavailable
D/ActivityThread( 3386): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3397): TimaSignature is unavailable
,D/ActivityThread( 3397): Added TimaKeyStore provider
,W/ResourcesManager( 3397): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3397): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3397): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3397): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/DBG_FMMDS( 3386): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3386): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/AndroidRuntime( 3383): 
D/AndroidRuntime( 3383): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3383): CheckJNI is OFF
D/AndroidRuntime( 3383): readGMSProperty: start
D/AndroidRuntime( 3383): readGMSProperty: already setted!!
D/AndroidRuntime( 3383): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3383): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3383): readGMSProperty: end
D/AndroidRuntime( 3383): addProductProperty: start
,I/ActivityManager( 1018): Killing 2318:com.android.mms/u0a46 (adj 15): empty #31
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1018): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/FactoryTestApp( 2645): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2892)  
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SBrowserFeatureFlag( 3397): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 3397): onCreate()
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3428 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3428): MountEmulatedStorage()
,E/Zygote  ( 3428): v2
I/libpersona( 3428): KNOX_SDCARD checking this for 1000
I/libpersona( 3428): KNOX_SDCARD not a persona
,I/SELinux ( 3428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PCWCLIENTTRACE_DMContentProvider( 3358): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3386): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,D/FileApkUtils( 1897): Spent 67ms computing apk sha1.
D/FileApkUtils( 1897): Module already staged or being staged:chimera-modules/MapsModule.apk
,E/NetworkSettingsReceiver( 3397): onReceive: android.intent.action.BOOT_COMPLETED
,I/art     ( 1897): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/CountryDetector( 1018): No listener is left
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,W/libprocessgroup( 1018): failed to open /acct/uid_10099/pid_2726/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2757/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_2213/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_2318/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3428): TimaSignature is unavailable
I/DBG_FMMDS( 3386): [50.18.150420][Line:43][xdbDBInit] 
,D/ActivityThread( 3428): Added TimaKeyStore provider
,W/InstanceID/Rpc( 1897): Found 10012
,E/AffinityControl( 3383): AffinityControl: registerfunction enter
,E/SBrowserFeatureFlag( 3397): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@29a49206
,D/SBrowserFeatureFlag( 3397): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3397): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/AndroidRuntime( 3383): Calling main entry com.android.commands.pm.Pm
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 1018): START PACKAGE DELETE: observer{284002498}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/DexOptUtils( 1897): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
,D/DexOptUtils( 1897): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 1897): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1897): Primary ABI of odexing process is armeabi-v7a
,E/Zygote  ( 3450): MountEmulatedStorage()
E/Zygote  ( 3450): v2
I/libpersona( 3450): KNOX_SDCARD checking this for 10135
I/libpersona( 3450): KNOX_SDCARD not a persona
,D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,I/SELinux ( 3450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3450 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2820:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
D/PackageManager( 1018): !@killApplicatoin: 10174, uninstall pkg
,I/SELinux ( 3450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 2537:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,D/TimaKeyStoreProvider( 3450): TimaSignature is unavailable
D/ActivityThread( 3450): Added TimaKeyStore provider
E/USB_UICC(  296): Timeout! No signal received. Retry num = 30
,W/ContextImpl( 3428): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,I/DBG_FMMDS( 3386): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/DBG_FMMDS( 3386): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3386): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3386): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3386): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/dex2oat ( 3456): ----------------------------------------------------
I/dex2oat ( 3456): <SS>: S T A R T I N G . . .
I/dex2oat ( 3456): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3456): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/DBG_FMMDS( 3386): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3386): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/WindowState( 1018): WIN DEATH: Window{138a5569 u0 com.example.hello/com.example.hello.MainActivity}
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
I/SurfaceFlinger(  256): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (-2/7)
I/SurfaceFlinger(  256): id=11 Removed NainActivit (-2/7)
,D/InputDispatcher( 1018): Focus left window: 2537
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,E/USB_UICC(  296): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  296): usb_uicc_init_qmi failed ! 
I/USB_UICC(  296): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  296): usb_uicc_cleanup, Issuing QMI deinit ... 
,W/PackageSettings( 1018): Skipping PackageSetting{191d5534 com.test.thalitest/10175} due to missing metadata
,W/ActivityManager( 1018): Force removing ActivityRecord{22d0518 u0 com.example.hello/.MainActivity t228}: app died, no saved state
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,I/LockPatternUtils( 1316): isSmartCardAuthenticationAvailable: false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/ActivityManager( 1018): Killing 2745:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
D/Launcher( 1495): onRestart, Launcher: 698651142
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10174 user=0: pkg removed
,W/ResourcesManager( 3450): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3450): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3450): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/FOTA_Client( 3153): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1018): Spurious death for ProcessRecord{3851e210 2537:com.example.hello/u0a174}, curProc for 2537: null
,D/Launcher( 1495): onStart, Launcher: 698651142
D/Launcher.HomeView( 1495): onStart
,D/Launcher( 1495): onResume, Launcher: 698651142
,D/SettingsProvider( 1018): name = kids_home_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/Launcher.HomeView( 1495): onResume
,D/Launcher( 1495): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_2820/cgroup.procs: No such file or directory
,E/Zygote  ( 3484): MountEmulatedStorage()
E/Zygote  ( 3484): v2
I/libpersona( 3484): KNOX_SDCARD checking this for 1000
I/libpersona( 3484): KNOX_SDCARD not a persona
,I/SELinux ( 3484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_DM  ( 2953): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,W/libprocessgroup( 1018): failed to open /acct/uid_10085/pid_2745/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3484): TimaSignature is unavailable
,D/ActivityThread( 3484): Added TimaKeyStore provider
,W/GeofencerStateMachine( 1773): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1785): mOCRHelper is null
,W/ResourcesManager( 1465): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,D/daemonapp( 1284): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/MenuAppsGridFragment( 1495): onResume
,D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,I/SurfaceFlinger(  256): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/RegisteredComponentCache( 1450): Collect Tech packages for Knox
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ResourcesManager( 3484): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/PersonaManager( 1450): isKioskContainerExistOnDevice
,D/InputDispatcher( 1018): Focus entered window: 1495
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1495): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher( 1495): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/FOTA_Client( 3153): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3506): MountEmulatedStorage()
E/Zygote  ( 3506): v2
I/libpersona( 3506): KNOX_SDCARD checking this for 10014
I/libpersona( 3506): KNOX_SDCARD not a persona
,I/SELinux ( 3506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3506 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/SELinux ( 3506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3506): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3518): MountEmulatedStorage()
E/Zygote  ( 3518): v2
I/libpersona( 3518): KNOX_SDCARD checking this for 10139
I/libpersona( 3518): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 3506): TimaSignature is unavailable,
I/SELinux ( 3518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityThread( 3506): Added TimaKeyStore provider
,I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3518 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 3518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3518): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/art     (  304): Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 26.432ms
,D/PersonaManager( 1450): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 3518): TimaSignature is unavailable
D/ActivityThread( 3518): Added TimaKeyStore provider
,D/TimaService( 1018): TIMA: in getTimaVersion
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 20.722ms
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
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 16.986ms
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/TLC_TZ_KEYSTORE: ( 1018): ctx = 0xb96633a0, comm = 0xb9744970, sendmsg = 0x9f3f0000, recvmsg = 0x9f3f0440
I/TZ_init: ( 1018): TZ_init: sending initialization request...
,E/Zygote  ( 3538): MountEmulatedStorage(),
E/Zygote  ( 3538): v2
I/libpersona( 3538): KNOX_SDCARD checking this for 10042,
I/libpersona( 3538): KNOX_SDCARD not a persona
,I/SELinux ( 3538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
E/TZ_init: ( 1018): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1018): trustlet initialization failed
I/TZ_init: ( 1018): TZ_init_START...
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3538 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/TZ_init: ( 1018): TZ_init_with_data: sending initialization request...
I/SELinux ( 3538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/TZ_init: ( 1018): TZ_init: successful initialization
E/SELinux ( 3538): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory ,
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1018): Count : 1, Ret : 0
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 2537 uid 10174
,D/TimaKeyStoreProvider( 3538): TimaSignature is unavailable
,D/ActivityThread( 3538): Added TimaKeyStore provider
,D/SamsungIME( 1785): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3428): Resource data:Inside bundle  check
,D/RegisteredServicesCache( 1450): empty dynamic service
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,W/ResourcesManager( 3518): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3518): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3518): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3518): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 3518): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,I/AMMetaDataParserService( 3428): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3428): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3428): Resource data:2131165186
,W/ActivityManager( 1018): mDVFSHelper.release()
,W/ResourcesManager( 3428): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3428): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3428): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3428): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3428): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3428): getResourceTypeNamexml
,I/ActivityManager( 1018): Killing 2830:com.sec.dsm.system/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3428): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,V/OneTimeInitializerReceiver( 3506): OneTimeInitializerReceiver.onReceive
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
,I/ActivityManager( 1018): Displayed Component not be shown by security: +592ms
,D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty,
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1018): uID is 10174
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0,
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=228_task.xml
,D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,D/SensorService( 1018): [SO] activate (ident=0xb9784e68, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb9784e68, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/AMMetaDataParserService( 3428): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10174
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,I/AMMetaDataParserService( 3428): Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
W/ContextImpl( 3428): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
D/PanelView( 1180): There is/are notification(s) 
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ContextImpl( 3484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 44078(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 26MB/39MB, paused 2.468ms total 613.413ms
I/art     ( 1018): WaitForGcToComplete blocked for 269.262ms for cause Explicit
,E/SMD     (  287): DCD OFF
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,D/WallpaperManager( 1495): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1495): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/Timeline( 1495): Timeline: Activity_idle id: android.os.BinderProxy@2e14bcff time:37301
,D/PackageManager( 1018): delete codoeFile: 
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
I/AASA_removePackage( 1018): UID=10174 Target=com.example.hello
,D/PackageManager( 1018): result of delete: 1{284002498}
,D/AndroidRuntime( 3383): Shutting down VM
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 7922(379KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.449ms total 189.753ms
,W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/ActivityManager( 1018): Killing 2865:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{c966d0e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t227} time:37404
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
,W/ResourcesManager( 3538): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1018): no available spell checker services found
,D/SensorService( 1018): [SO] currT = 37431066000, prevT = 37001128000, diff = 429938000, [0.172 0.115 10.228]
D/SensorService( 1018): [SO] 0.172 0.115 10.228
D/SensorService( 1018): [SO] [100 -> 255]
,I/AMMetaDataParserService( 3428): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,I/AMMetaDataParserService( 3428): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3428): getResourcePackageName:assistant
I/AMMetaDataParserService( 3428): Resource data:2131034113
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3428): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3428): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3428): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3560 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/AMMetaDataParserService( 3428): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3428): getResourceTypeNamexml,
E/        ( 3428): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,V/OneTimeService( 3506): OneTimeService.onHandleIntent
,I/libpersona( 3560): KNOX_SDCARD checking this for 10145
E/Zygote  ( 3560): MountEmulatedStorage()
I/libpersona( 3560): KNOX_SDCARD not a persona
E/Zygote  ( 3560): v2
I/GFX construct_block_size_descriptor_2d second part( 3428): took 2.680156ms for 0*0 texture 0
I/SELinux ( 3560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3560): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GFX generate_partition_tables( 3428): took 6.252552ms for 0*0 texture 0
I/GFX raster( 3428): took 10.139844ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3428): Bitmap=0xb9295d30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb929c808 counterpartCT=4 counterpartW=96 counterparth=96
,I/SettingSearch/SearchIntentReceiver( 1316): InitSerachDBThread thread end!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3560): TimaSignature is unavailable
,I/AMMetaDataParserService( 3428): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/ActivityThread( 3560): Added TimaKeyStore provider
,E/Zygote  ( 3575): MountEmulatedStorage()
I/libpersona( 3575): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3575): v2
I/libpersona( 3575): KNOX_SDCARD not a persona
,I/SELinux ( 3575): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1018): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3575 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3575): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3575): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 2953): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/CalendarProvider2( 3538): CalendarProvider2.onCreate() called
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3575): TimaSignature is unavailable
,D/ActivityThread( 3575): Added TimaKeyStore provider
,I/ActivityManager( 1018): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3591 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 3591): MountEmulatedStorage()
E/Zygote  ( 3591): v2
I/libpersona( 3591): KNOX_SDCARD checking this for 10015
I/libpersona( 3591): KNOX_SDCARD not a persona
,I/SELinux ( 3591): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3591): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3591): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3560): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3560): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3560): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3560): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3560): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 3383): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/ActivityManager( 1018): Killing 2885:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
E/        ( 3428): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3428): took 0.823021ms for 96*96 texture 0
W/ResourcesManager( 3575): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3428): Bitmap=0xb9295d30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb92a4970 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3591): TimaSignature is unavailable
,D/ActivityThread( 3591): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3428): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/SEAMService( 1018):  hashset_to_int_array returning null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/SEAMService( 1018):  hashset_to_int_array returning null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 3484): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3484): (284) automatic index on seams_container_info(sp_id)
,W/ContextImpl( 3575): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/SEAMService( 1018):  hashset_to_int_array returning null
,E/Zygote  ( 3610): MountEmulatedStorage(),
E/Zygote  ( 3610): v2
,I/libpersona( 3610): KNOX_SDCARD checking this for 1000
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,I/libpersona( 3610): KNOX_SDCARD not a persona
,I/SELinux ( 3610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/SELinux ( 3610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/ActivityManager( 1018): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3610 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,E/SELinux ( 3610): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/F_PHONE ( 3575): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
W/ContextImpl( 3575): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3610): TimaSignature is unavailable
D/GCM     ( 1897): COMPAT: Multi user not supported
D/ActivityThread( 3610): Added TimaKeyStore provider
,E/        ( 3428): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/GFX construct_block_size_descriptor_2d second part( 3428): took 2.383282ms for 0*0 texture 0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 3610): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2830/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2865/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2885/cgroup.procs: No such file or directory
,D/F_PHONE ( 3575): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3575): default registerAction()
I/F_PHONE ( 3575): [[com.sec.bcservice]] sendPendingMessage()
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/GFX generate_partition_tables( 3428): took 7.470000ms for 0*0 texture 0
,I/GFX raster( 3428): took 10.808803ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3428): Bitmap=0xb92a1270 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92a1338 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/AMMetaDataParserService( 3428): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/GCM     ( 1658): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/BluetoothBDAdrressReceiver( 3610): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3610): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1465): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1465): onCreate()
,E/BluetoothBDTestService( 1465): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1465): bd_address_path: /efs/bluetooth/bt_addr
,I/CheckinService( 1897): Disabling old GoogleServicesFramework version
,E/BluetoothBDTestService( 1465): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/Zygote  ( 3639): MountEmulatedStorage()
I/libpersona( 3639): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3639): v2
I/libpersona( 3639): KNOX_SDCARD not a persona
,I/SELinux ( 3639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3639 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3639): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 2935:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3639): TimaSignature is unavailable
,D/ActivityThread( 3639): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3639): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 3660): MountEmulatedStorage(),
,E/Zygote  ( 3660): v2
I/libpersona( 3660): KNOX_SDCARD checking this for 1000
I/libpersona( 3660): KNOX_SDCARD not a persona
,I/SELinux ( 3660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3660 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/SystemUpdateService( 1897): onCreate
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/SELinux ( 3660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 3660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2935/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1897): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3660): TimaSignature is unavailable
,D/ActivityThread( 3660): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3660): onCreate
,D/SystemUpdateService( 1897): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/FactoryTestApp( 2645): [DummyFtClient$onDestroy](2645) Destroy DummyFtClient service
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3683): MountEmulatedStorage()
E/Zygote  ( 3683): v2
I/libpersona( 3683): KNOX_SDCARD checking this for 10019
I/libpersona( 3683): KNOX_SDCARD not a persona
,I/SELinux ( 3683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3683 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1658): onCreate
,D/FactoryTestApp( 2645): [Support$Values.getString](2645) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2645): [ModuleCommon$isConnectionModeNone](2645) mConnectionMode = gsm
I/FactoryTestApp( 2645): [ModuleCommon$isRunningFtClient](2645) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2645): [DummyFtClient$onDestroy](2645) kill process
I/Process ( 2645): Sending signal. PID: 2645 SIG: 9
,I/Hs20UtilService( 3660): Starting #1
,I/Hs20UtilService( 3660): Message received 5003
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/CheckinService( 1897): Checking schedule, now: 1449497255819 next: 1450001434676
,I/CheckinService( 1897): active receiver: disabled
,D/TimaKeyStoreProvider( 3683): TimaSignature is unavailable
,D/ActivityThread( 3683): Added TimaKeyStore provider
,I/KnoxUsageLogPro( 3639): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 3639): premStatus:2
,I/KnoxUsageLogPro( 3639): isEulaShown : false
I/KnoxUsageLogPro( 3639): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1018): Killing 2968:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/KnoxUsageLogPro( 3639): savePreference: key = previous_sys_time value = 1449497255843
,I/ConfigFetchService( 1897): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/KnoxUsageLogPro( 3639): savePreference: key = previous_elapsed_time value = 38077
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/ActivityManager( 1018): Process com.sec.factory (pid 2645)(adj 0) has died(140,1065)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.183: ( 3683): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 15:07:35 GMT+01:00 2015
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/GCoreUlr( 1773): DispatchingService.onCreate()
,I/KLMS-2.5.183: ( 3683): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3428): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3428): took 0.588125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3428): Bitmap=0xb92a5d30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92a5df8 counterpartCT=4 counterpartW=96 counterparth=96
,V/AuthZen ( 1897): Handling intent: android.intent.action.BOOT_COMPLETED
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthZenEventHandler( 1897): Handling event: android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3683): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3683): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3683): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/AMMetaDataParserService( 3428): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
I/libpersona( 3712): KNOX_SDCARD checking this for 10022
E/Zygote  ( 3712): MountEmulatedStorage()
I/libpersona( 3712): KNOX_SDCARD not a persona
E/Zygote  ( 3712): v2
I/ActivityManager( 1018): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3712 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
I/SELinux ( 3712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/KLMS-2.5.183: ( 3683): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SELinux ( 3712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/KLMS-2.5.183: ( 3683): KLMSIntentService(): BOOT_COMPLETED
,I/SystemUpdateService( 1897): cancelUpdate (empty URL)
I/SystemUpdateService( 1897): active receiver: disabled
E/SELinux ( 3712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/RlzPingService( 3591): Setting next ping for 1450102056185
,D/TimaKeyStoreProvider( 3712): TimaSignature is unavailable
,I/KLMS-2.5.183: ( 3683): KLMSIntentService(): onDestroy()
,D/ActivityThread( 3712): Added TimaKeyStore provider
,W/BaseAppContext( 1897): Using Auth Proxy for data requests.
,W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_2968/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2953): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,E/        ( 3428): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3428): took 0.824323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3428): Bitmap=0xb92a14a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92a17c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ConfigFetchService( 1897): service connected
,I/AMMetaDataParserService( 3428): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1897): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/ActivityManager( 1018): Killing 2917:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/GLSUser ( 1897): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/ChimeraCfgMgr( 1897): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1773): Explicit concurrent mark sweep GC freed 12043(736KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 1.604ms total 218.146ms
,I/dex2oat ( 3456): dex2oat took 2.365s (threads: 4)
,D/DexOptUtils( 1897): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
,D/DexOptUtils( 1897): Set odex to world readable.
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId,
D/DexOptUtils( 1897): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,W/libprocessgroup( 1018): failed to open /acct/uid_10086/pid_2917/cgroup.procs: No such file or directory
,D/FileApkUtils( 1897): Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GmsModuleFndr( 1897): Beginning GMS chimera module scan
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3753): MountEmulatedStorage()
,E/Zygote  ( 3753): v2
I/libpersona( 3753): KNOX_SDCARD checking this for 1000
,I/libpersona( 3753): KNOX_SDCARD not a persona
,I/SELinux ( 3753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3753 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Killing 3002:com.sec.esdk.elm/u0a94 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SELinux ( 3753): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3428): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3428): took 0.960260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3428): Bitmap=0xb92a09b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92a0a80 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 1658): Explicit concurrent mark sweep GC freed 23972(1375KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 10MB/16MB, paused 4.137ms total 55.736ms
,D/GmsModuleFndr( 1897): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1897): Beginning module configuration check
,W/SQLiteConnectionPool( 1658): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ChimeraCfgMgr( 1897): Module APKs unchanged, check complete
,I/AMMetaDataParserService( 3428): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3428): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3428): took 0.698854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3428): Bitmap=0xb92a17c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92a1a80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AuthZen ( 1897): Fetching signing key...
,I/AMMetaDataParserService( 3428): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/TimaKeyStoreProvider( 3753): TimaSignature is unavailable
,D/ActivityThread( 3753): Added TimaKeyStore provider
,I/AuthZen ( 1897): Signing key fetched successfully!
,E/SQLiteLog( 3560): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3560): (3850) statement aborts at 34: [DELETE FROM Mailbox WHERE accountKey not in (select _id from Account)] disk I/O error
,W/BaseAppContext( 1897): Using Auth Proxy for data requests.
,E/SQLiteLog( 1897): (28) failed to open "/data/data/com.google.android.gms/databases/keys.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 1897): Failed to open database '/data/data/com.google.android.gms/databases/keys.db'.
E/SQLiteDatabase( 1897): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 1897): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 1897): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1897): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1897): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.authzen.keyservice.j.c(SourceFile:228)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:186)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/SQLiteDatabase( 1897): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteDatabase( 1897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1897): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 1897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 1897): Couldn't open keys.db for writing (will try read-only):
E/SQLiteOpenHelper( 1897): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 1897): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 1897): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 1897): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1897): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.authzen.keyservice.j.c(SourceFile:228)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:186)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/SQLiteOpenHelper( 1897): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteOpenHelper( 1897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1897): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 1897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1897): Opened keys.db in read-only mode
,W/System.err( 3560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,I/AuthZen ( 1897): Starting Enrollment...
,W/System.err( 3560): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 3560): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
W/System.err( 3560): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 3560): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 3560): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.deleteUnlinked(EmailProvider.java:887)
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:961)
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2091)
W/System.err( 3560): 	at android.content.ContentProvider.query(ContentProvider.java:993)
W/System.err( 3560): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err( 3560): 	at android.content.ContentResolver.query(ContentResolver.java:489)
W/System.err( 3560): 	at android.content.ContentResolver.query(ContentResolver.java:433)
W/System.err( 3560): 	at com.android.emailcommon.provider.EmailContent$Account.restoreAccounts(EmailContent.java:5733)
W/System.err( 3560): 	at com.android.email.adapter.ProtocolAdapter.buildAccountInfoTable(ProtocolAdapter.java:283)
W/System.err( 3560): 	at com.android.email.adapter.ProtocolAdapter.initProtocolAdapter(ProtocolAdapter.java:588)
W/System.err( 3560): 	at com.android.email.Controller.<init>(Controller.java:332)
W/System.err( 3560): 	at com.android.email.Controller.getInstance(Controller.java:358)
W/System.err( 3560): 	at com.android.email.RefreshManager.getInstance(RefreshManager.java:358)
W/System.err( 3560): 	at com.android.email.Email.onCreate(Email.java:481)
W/System.err( 3560): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 3560): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
W/System.err( 3560): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
W/System.err( 3560): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
W/System.err( 3560): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3560): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3560): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 3560): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3560): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3560): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3560): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteLog( 3560): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3560): (3850) statement aborts at 48: [DELETE FROM Message WHERE accountKey not in (select _id from Account)] disk I/O error
,E/SQLiteLog( 3428): (10) unixWrite() File Descriptor : 36 gets errno : 9
E/SQLiteLog( 3428): (10) unixWrite() File Descriptor : 36 gets errno : 9
,E/SQLiteDatabase( 3428): Error inserting actname=com.android.contacts.activities.PeopleActivity amicon=[B@1e7ef88e appname=com.android.contacts id=1449497256570 amtitle=Search amstate=1 amintent=android.intent.assistant.main.search amlabel=2131690214
E/SQLiteDatabase( 3428): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 3428): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
E/SQLiteDatabase( 3428): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3428): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3428): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3428): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3428): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3428): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/        ( 3428): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/System.err( 3560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,W/System.err( 3560): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 3560): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
W/System.err( 3560): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 3560): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 3560): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
I/GFX raster( 3428): took 0.554687ms for 96*96 texture 0
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.deleteUnlinked(EmailProvider.java:887)
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:963)
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3428): Bitmap=0xb929f618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb929f878 counterpartCT=4 counterpartW=96 counterparth=96
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2091)
W/System.err( 3560): 	at android.content.ContentProvider.query(ContentProvider.java:993)
W/System.err( 3560): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err( 3560): 	at android.content.ContentResolver.query(ContentResolver.java:489)
W/System.err( 3560): 	at android.content.ContentResolver.query(ContentResolver.java:433)
W/System.err( 3560): 	at com.android.emailcommon.provider.EmailContent$Account.restoreAccounts(EmailContent.java:5733)
W/System.err( 3560): 	at com.android.email.adapter.ProtocolAdapter.buildAccountInfoTable(ProtocolAdapter.java:283)
W/System.err( 3560): 	at com.android.email.adapter.ProtocolAdapter.initProtocolAdapter(ProtocolAdapter.java:588)
W/System.err( 3560): 	at com.android.email.Controller.<init>(Controller.java:332)
W/System.err( 3560): 	at com.android.email.Controller.getInstance(Controller.java:358)
W/System.err( 3560): 	at com.android.email.RefreshManager.getInstance(RefreshManager.java:358)
W/System.err( 3560): 	at com.android.email.Email.onCreate(Email.java:481)
I/ActivityManager( 1018): Killing 3043:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
W/System.err( 3560): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 3560): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
W/System.err( 3560): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
W/System.err( 3560): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
W/System.err( 3560): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3560): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3560): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 3560): ,	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3560): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3560): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3560): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteLog( 3560): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 3560): (3850) statement aborts at 23: [DELETE FROM IRMTemplate WHERE AccountKey not in (select _id from Account)] disk I/O error
W/System.err( 3560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,W/System.err( 3560): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 3560): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
W/System.err( 3560): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 3560): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 3560): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
D/AuthZen ( 1897): getting auth token. Attempt 0
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.deleteUnlinked(EmailProvider.java:887)
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.getDatabase(EmailProvider.java:965)
W/System.err( 3560): 	at com.android.email.provider.EmailProvider.query(EmailProvider.java:2091)
W/System.err( 3560): 	at android.content.ContentProvider.query(ContentProvider.java:993)
W/System.err( 3560): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err( 3560): 	at android.content.ContentResolver.query(ContentResolver.java:489)
W/System.err( 3560): 	at android.content.ContentResolver.query(ContentResolver.java:433)
W/System.err( 3560): 	at com.android.emailcommon.provider.EmailContent$Account.restoreAccounts(EmailContent.java:5733)
W/System.err( 3560): 	at com.android.email.adapter.ProtocolAdapter.buildAccountInfoTable(ProtocolAdapter.java:283)
W/System.err( 3560): 	at com.android.email.adapter.ProtocolAdapter.initProtocolAdapter(ProtocolAdapter.java:588)
W/System.err( 3560): 	at com.android.email.Controller.<init>(Controller.java:332)
W/System.err( 3560): 	at com.android.email.Controller.getInstance(Controller.java:358)
W/System.err( 3560): 	at com.android.email.RefreshManager.getInstance(RefreshManager.java:358)
W/System.err( 3560): 	at com.android.email.Email.onCreate(Email.java:481)
W/System.err( 3560): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 3560): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
W/System.err( 3560): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
W/System.err( 3560): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
W/System.err( 3560): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3560): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3560): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 3560): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3560): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3560): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/System.err( 3560): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/AMMetaDataParserService( 3428): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/SQLiteLog( 3428): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3428): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3428): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3428): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3428): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3428): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3428): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3428): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3428): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3428): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3428): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3428): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3428): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3428): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3428): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3428): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3428): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3428): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3428): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3428): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3428): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3428): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3428): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3428): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3428): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3428): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3428): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3428): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3428): ,	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3428): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3428): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3428): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3428): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3428): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 3560): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3560): (3850) statement aborts at 41: [delete from Account where _id in (select accountKey from Account_CB where typeMsg = 1)] disk I/O error
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1018): failed to open /acct/uid_10094/pid_3002/cgroup.procs: No such file or directory
I/ActivityManager( 1018): Killing 3050:com.sec.factory.camera/1000 (adj 15): empty #31
D/ChimeraCfgMgr( 1897): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1897): onDestroy
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/MTPRx   ( 3753): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,E/Zygote  ( 3775): MountEmulatedStorage()
E/Zygote  ( 3775): v2
I/libpersona( 3775): KNOX_SDCARD checking this for 10104
I/libpersona( 3775): KNOX_SDCARD not a persona
,I/SELinux ( 3775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3775 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/SELinux ( 3775): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 1897): (28) failed to open "/data/data/com.google.android.gms/databases/playlog.db" with flag (131138) and mode_t (0) due to error (30)

```
