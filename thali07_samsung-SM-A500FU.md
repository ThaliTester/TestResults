#### Test 50388019385b4d9_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/SBrowserFeatureFlag( 2386): initialized in static block : loadCscFeatureValue() succeed! 
D/Mms/ArtClassLoader( 2318): init before art
D/Mms/TelephonyPermission( 2318): start operation mode monitor
--------- beginning of system
W/ResourcesManager( 2318): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2318): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2318): isDefault true
D/Mms/MmsApp( 2318): onCreate() com.android.mms
D/ManifestProvider( 2386): onCreate()
E/OperatorBookmarksSIMReceiver( 2386): onReceive runs..android.intent.action.SIM_STATE_CHANGED
D/Mms/MmsApp( 2318): [start]    initCountryIso consume time = 300.4975
D/CountryDetector( 1017): The first listener is added
D/Mms/MmsApp( 2318): [end]    initCountryIso consume time = 15.809479
D/Mms/MmsConfig( 2318): [start]    MmsConfig.init() consume time = 0.421771
D/Mms/MmsConfig( 2318): before partial update
D/Mms/MmsConfig( 2318): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2318): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2318): isAuth is false
D/Mms/MmsConfig( 2318): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/TP/MmsSmsProvider( 1462): query,matched:2117, calling pid = 2318
D/TP/MmsSmsProvider( 1462): match 2117:Elapsed time : 3.585 ms
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
D/Mms/MmsConfig( 2318): [end]    init() consume time = 79.953749
D/Mms/Contact( 2318): [start]    init() consume time = 3.51974
D/TP/MmsSmsProvider( 1462): query,matched:13, calling pid = 2318
D/TP/MmsSmsProvider( 1462): match 13:Elapsed time : 1.446 ms
D/Mms/Contact( 2318): [end]    init consume time = 10.655104
D/Mms/DraftCache( 2318): [start]    rebuildCache consume time = 8.779479
D/Mms/MethodReflector( 2318): getSubId is called
D/Mms/TelephonyUtils( 2318): getLongSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 1462): query,matched:12, calling pid = 2318
D/TP/MmsSmsProvider( 1462): match 12:Elapsed time : 2.018 ms
D/Mms/ArtClassLoader( 2318): init [DONE] art
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
D/Mms/DraftCache( 2318): [end]    rebuildCache consume time = 12.682032
D/ComposerPerformance( 2318): 1450189275207 ms / [DONE] Composer constructor
D/Mms/Conversation( 2318): [start]    init() consume time = 15.481562
D/TP/MmsSmsDatabaseHelper( 1462): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1462): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1462): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1462): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1462): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1462): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1462): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
E/CII     ( 2318): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 2318): ReservationManager()
I/Mms/ReservationManager( 2318): resetAfterConnected()
V/TP/MmsSmsDatabaseHelper( 1462): updateThread(), thread_id = 9223372036854775807
D/TP/MmsSmsProvider( 1462): query,matched:7, calling pid = 2318
V/TP/MmsSmsDatabaseHelper( 1462): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1462): match 7:Elapsed time : 4.702 ms
I/Mms/ReservationManager( 2318): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MmsApp( 2318): [end]    onCreate() consume time = 42.307344
D/Mms/SmsReceiver( 2318): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
D/TP/MmsSmsProvider( 1462): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1462): need read changed broadcast:false
D/Mms/Conversation( 2318): [end]    init consume time = 2.840573
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/DownloadManager( 2318): Service state changed: Bundle[mParcelledData.dataSize=744]
I/splitIntent( 1017): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/DownloadManager( 2318): roaming ------> false, mSimSlot = 0
D/Mms/MessagingNotification( 2318): [start]    init() consume time = 4.648125
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/MethodReflector( 2318): getSubId is called
D/Mms/TelephonyUtils( 2318): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2318): getTelephonyProperty is called
D/Mms/DownloadManager( 2318): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2318): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2318): auto download without roaming -> true
D/Mms/DownloadManager( 2318): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 2318): mAutoDownload ------> true
E/Zygote  ( 2417): MountEmulatedStorage()
I/libpersona( 2417): KNOX_SDCARD checking this for 10020
E/Zygote  ( 2417): v2
I/libpersona( 2417): KNOX_SDCARD not a persona
I/SELinux ( 2417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2417 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
D/Mms/MessagingNotification( 2318): [end]    init consume time = 21.95375
I/SELinux ( 2417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2417): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/Mms/SpamFilter( 2318): [start]    SpamFilter fill() begin consume time = 6.512031
D/Mms/Synchronizer( 2318): [start]    doSync consume time = 1.409323
D/TP/MmsSmsProvider( 1462): query,matched:0, calling pid = 2318
V/TP/MmsSmsProvider( 1462): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1462): match 0:Elapsed time : 1.884 ms
D/TP/MmsSmsProvider( 1462): update, matched:300, calling pid = 2318
V/TP/MmsSmsProvider( 1462): syncDBData start
V/TP/MmsSmsProvider( 1462): syncDBData sms end
D/TP/MmsSmsProvider( 1462): query,matched:400, calling pid = 2318
V/TP/MmsSmsProvider( 1462): syncDBData mms end
D/Mms/SmsReceiverService( 2318): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
V/TP/MmsSmsProvider( 1462): syncDBData end
D/Mms/TelephonyPermission( 2318): isDefault true
D/Mms/SmsReceiverService( 2318): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2318): handleSIMStatus()
D/Mms/SmsReceiverService( 2318): handleSIMStatus(): SIM_STATUS = ABSENT
D/Mms/Synchronizer( 2318): [end]    doSync consume time = 9.388646
D/TimaKeyStoreProvider( 2417): TimaSignature is unavailable
D/Mms/SpamFilter( 2318): [end]    SpamFilter fill() finished consume time = 7.531979
D/ActivityThread( 2417): Added TimaKeyStore provider
D/Mms/MessagingNotification( 2318): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1462): query,matched:26, calling pid = 2318
D/TP/SmsProvider( 1462): match 26:Elapsed time : 1.429 ms
W/ResourcesManager( 2417): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2417): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2417): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1462): query,matched:6, calling pid = 2318
D/TP/MmsSmsProvider( 1462): match 6:Elapsed time : 2.191 ms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2435): MountEmulatedStorage()
E/Zygote  ( 2435): v2
I/libpersona( 2435): KNOX_SDCARD checking this for 10025
I/libpersona( 2435): KNOX_SDCARD not a persona
I/SELinux ( 2435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2435 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 2435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2435): TimaSignature is unavailable
D/ActivityThread( 2435): Added TimaKeyStore provider
W/ResourcesManager( 2435): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/VibratorService( 1017): hasVibrator - useVibetonz: true
D/EasySignUpManager_1.15.0305( 2417): serviceId : 0, features : -1
I/splitIntent( 1017): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1017): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2452): MountEmulatedStorage()
I/libpersona( 2452): KNOX_SDCARD checking this for 10044
E/Zygote  ( 2452): v2
I/libpersona( 2452): KNOX_SDCARD not a persona
I/SELinux ( 2452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2452 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/SecContentProvider2( 1017): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1017): mCursor = null
D/SecContentProvider2( 1017): isCopyContactToSimAllowed = true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2452): TimaSignature is unavailable
D/ActivityThread( 2452): Added TimaKeyStore provider
E/Zygote  ( 2469): MountEmulatedStorage()
I/libpersona( 2469): KNOX_SDCARD checking this for 10054
E/Zygote  ( 2469): v2
I/libpersona( 2469): KNOX_SDCARD not a persona
I/SELinux ( 2469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2469 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
I/SELinux ( 2469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/SELinux ( 2469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2480): MountEmulatedStorage()
I/libpersona( 2480): KNOX_SDCARD checking this for 10142
E/Zygote  ( 2480): v2
I/libpersona( 2480): KNOX_SDCARD not a persona
I/SELinux ( 2480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2469): TimaSignature is unavailable
D/ActivityThread( 2469): Added TimaKeyStore provider
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2480 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2480): TimaSignature is unavailable
D/ActivityThread( 2480): Added TimaKeyStore provider
W/ResourcesManager( 2452): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2469): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
I/OMACP   ( 2435): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1491, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
V/TaskCloserActivity( 2480): TaskCloserActivity enter()
V/TaskCloserActivity( 2480): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/Recents_RecreateReceiver( 2469): onReceive by home
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2500): MountEmulatedStorage()
E/Zygote  ( 2500): v2
I/libpersona( 2500): KNOX_SDCARD checking this for 10139
I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2500 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/libpersona( 2500): KNOX_SDCARD not a persona
I/SELinux ( 2500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2500): TimaSignature is unavailable
D/ActivityThread( 2500): Added TimaKeyStore provider
D/Mms/Omacp( 2318): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
W/ResourcesManager( 2500): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2500): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2500): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2500): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2500): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
E/SMD     (  288): DCD OFF
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
E/USB_UICC(  296): Timeout! No signal received. Retry num = 22
W/art     ( 2417): Verification of void com.android.contacts.common.list.l.P() took 131.739ms
D/AndroidRuntime( 2516): 
D/AndroidRuntime( 2516): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2516): CheckJNI is OFF
D/AndroidRuntime( 2516): readGMSProperty: start
D/AndroidRuntime( 2516): readGMSProperty: already setted!!
D/AndroidRuntime( 2516): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2516): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2516): readGMSProperty: end
D/AndroidRuntime( 2516): addProductProperty: start
D/NearbySource( 2452): Nearby Source Create!
D/NearbyContext( 2452): Nearby Context Create!
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/ContextImpl( 2452): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/SLinkSource( 2452): Samsung link source created
D/AbsListView( 2417): Get MotionRecognitionManager
D/MotionRecognitionService( 1017):  ssp status : false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider( 2452): getAllContactInfoList Start
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/GalleryCacheReady( 2452): Receive : home resume
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 2318): ui event
E/AffinityControl( 2516): AffinityControl: registerfunction enter
I/splitIntent( 1017): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/BootupListener( 1462): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/PhoneUtilsCommon( 1462): isSupportVoLTE is false.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/StatusChecker( 2293): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2293): onReceive : net.mt.init : DONE
E/SQLiteLog( 1227): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
D/StatusChecker( 2293): Service state changed : 3 mSub-1
D/AndroidRuntime( 2516): Calling main entry com.android.commands.am.Am
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ContactProvider( 2452): getAllContactInfoList End
I/syncContacts( 2452): thread: 253, sync time = 111
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1491): onPause
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1491
D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 2516): Shutting down VM
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2532): MountEmulatedStorage()
E/Zygote  ( 2532): v2
I/libpersona( 2532): KNOX_SDCARD checking this for 10176
I/libpersona( 2532): KNOX_SDCARD not a persona
I/SELinux ( 2532): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2532 uid=10176 gids={50176, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2532): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2532): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
V/ActivityThread( 1491): updateVisibility : ActivityRecord{399d421a token=android.os.BinderProxy@30d422f0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TimaKeyStoreProvider( 2532): TimaSignature is unavailable
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ActivityThread( 2532): Added TimaKeyStore provider
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1491): onStop
V/ActivityThread( 1491): updateVisibility : ActivityRecord{399d421a token=android.os.BinderProxy@30d422f0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
D/Launcher( 1491): onTrimMemory. Level: 20
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
I/WebViewFactory( 2532): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/ResourcesManager( 1659): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1659): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 1659): VM with version 2.1.0 has multidex support
I/MultiDex( 1659): install
I/MultiDex( 1659): VM has multidex support, MultiDex support library is disabled.
W/art     ( 2516): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/LibraryLoader( 2532): Time to load native libraries: 11 ms (timestamps 8920-8931)
I/LibraryLoader( 2532): Expected native library version number "",actual native library version number ""
,V/JNIHelp ( 1659): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromiumFactoryProvider( 2532): Binding Chromium to main looper Looper (main, tid 1) {3fe110b2}
,I/LibraryLoader( 2532): Expected native library version number "",actual native library version number ""
,I/chromium( 2532): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2532): Initializing chromium process, singleProcess=true
,W/ActivityThread( 1659): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 1659): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ef1f4e9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1659): Installed default security provider GmsCore_OpenSSL
W/art     ( 2532): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2532): ApplicationContext is null in ApplicationStatus
W/chromium( 2532): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2532): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2532): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2532): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2532): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2532): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2532): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2532): Local Branch: 
I/Adreno-EGL( 2532): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2532): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2532):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1768): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothAdapter( 2532): 466322942: getState() :  mService = null. Returning STATE_OFF
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
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
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
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/art     ( 2532): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AwContents( 2532): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PhoneWindow( 2532): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2532): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2532): CordovaWebView is running on device made by: samsung
,D/GCM     ( 1659): COMPAT: Multi user not supported
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/art     ( 2532): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2532): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 23
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/OpenGLRenderer( 2532): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 2532): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 2532): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2532): *FMB* isFloatingMenuEnabled return false
,I/Scheduler( 1659): Use PeriodicScheduler
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/InstanceID/Rpc( 1659): Found 10012
,D/InputDispatcher( 1017): Focus entered window: 2532
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2532): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2532): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2532): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2532): Enabling debug mode 0
,I/GCM     ( 1659): GCM config loaded
,D/AuthorizationBluetoothService( 1659): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1659): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1177): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +817ms
W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{23177c87 u0 com.example.hello/.MainActivity t228} time:29539
,I/Timeline( 2532): Timeline: Activity_idle id: android.os.BinderProxy@6e36aae time:29547
,I/SamsungIME( 1777): getCurrentCandidateView
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,D/a       ( 1659): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1777): Dismiss ExpandCandiate
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1948): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SamsungIME( 1777): getDebugLevel  : 0x4f4c
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1777): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1777): KeybaordView init() : load resources
,W/BindingManager( 2532): Cannot call determinedVisibility() - never saw a connection for the pid: 2532
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1777): getCurrentKeyboard
I/SamsungIME( 1777): getTextKeyboard
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1777): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
I/chromium( 2532): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,D/WearableService( 2067): callingUid 10012, callindPid: 2067
,I/Mms/MmsApp( 2318):  start initViewCache mms,
,D/Mms/ComposeMessageFragment( 2318): [start]    fillCache consume time = 1948.598124
,D/Mms/ComposeMessageFragment( 2318): fillCache, easy = false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/JsMessageQueue( 2532): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2532): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 22772(1253KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 25MB/37MB, paused 2.080ms total 149.724ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsWearableLS( 1768): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1768): [183] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 1948
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/SmsProvider( 1462): match 0:Elapsed time : 2.516 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsProvider( 1462): Query uri=content://mms, match=0, calling pid = 1948
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 1948
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1462): match 0:Elapsed time : 47.675 ms
,D/jxcore_app_log( 2532): JniHelper::setJavaVM(0xb7268450), pthread_self() = -1216569416
,D/LocationInitializer( 1948): Restart initialization of location
,D/JX-Cordova( 2532): jxcore cordova android initializing
,D/TP/MmsProvider( 1462): Query uri=content://mms, match=0, calling pid = 1948
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/AbsListView( 2318): Get MotionRecognitionManager
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/MotionRecognitionService( 1017):  ssp status : false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/ComposeMessageFragment( 2318): [end]    fillCache consume time = 436.51276
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
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
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 2532): Initializing JXcore engine
W/jxcore-log( 2532): JXcore engine is ready
,W/jxcore-log( 2532): Starting JXcore engine
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 24
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1300): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1300): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1300): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1300): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,E/audit   ( 1850): type=1400 msg=audit(1450189277.830:203): avc:  denied  { ioctl } for  pid=2532 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1850):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1850): type=1300 msg=audit(1450189277.830:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=bed56d58 items=0 ppid=305 ppcomm=main pid=2532 auid=4294967295 uid=10176 gid=10176 euid=10176 suid=10176 fsuid=10176 egid=10176 sgid=10176 fsgid=10176 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1850): type=1320 msg=audit(1450189277.830:203): 
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/BubbleViewCache( 2318): fillCache bubble = 1
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,E/daemonapp( 1300): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1300): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/AdaptiveEventManager( 1177): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/daemonapp( 1300): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
D/AdaptiveEventManager( 1177): currentCityId is null
D/AdaptiveEventManager( 1177): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1177): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
,D/AdaptiveEventManager( 1177): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1177): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1177): mWeatherInfo is not reliable
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,E/daemonapp( 1300): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/daemonapp( 1300): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2611): MountEmulatedStorage()
E/Zygote  ( 2611): v2,
I/libpersona( 2611): KNOX_SDCARD checking this for 10135
I/libpersona( 2611): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2611 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,I/SELinux ( 2611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,I/SELinux ( 2611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1450189277939
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1450210877935
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1300): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1450210860000
D/daemonapp( 1300): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1450210860000
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1450210860000
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/TimaKeyStoreProvider( 2611): TimaSignature is unavailable
,D/ActivityThread( 2611): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SIP     ( 1462): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1462): fail readDirectory() errno=2
,E/Zygote  ( 2628): MountEmulatedStorage()
E/Zygote  ( 2628): v2
I/libpersona( 2628): KNOX_SDCARD checking this for 1000
I/libpersona( 2628): KNOX_SDCARD not a persona
,I/SELinux ( 2628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/jxcore-log( 2532): Platform android,
W/jxcore-log( 2532): 
W/jxcore-log( 2532): Process ARCH arm
W/jxcore-log( 2532): 
,I/SELinux ( 2628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2628 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 2628): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  305): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 704us total 22.406ms
W/ResourcesManager( 2611): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2611): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2611): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2628): TimaSignature is unavailable
,D/ActivityThread( 2628): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 19.224ms
,I/jxcore-log( 2532): JXcore Cordova bridge is ready!
I/jxcore-log( 2532): 
,W/jxcore-log( 2532): JXcore engine is started
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 18.639ms
,D/SecurityLogAgent( 2628):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION,
D/SecurityLogAgent( 2628):  SeDenialReceiver : File path = /data/misc/audit/audit.old,
,E/jxcore-log( 2532): >> samsung-SM-A500FU
E/jxcore-log( 2532): 
D/SecurityLogAgent( 2628):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,I/jxcore-log( 2532): Total memory 1983787008
I/jxcore-log( 2532): 
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
I/jxcore-log( 2532): Free memory 262365184
I/jxcore-log( 2532): 
I/jxcore-log( 2532): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2532): 
I/jxcore-log( 2532): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2532): 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,I/jxcore-log( 2532): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2532): 
,I/jxcore-log( 2532): Size 720 1280
I/jxcore-log( 2532): 
,V/AlarmManager( 1017): waitForAlarm result :4
,I/jxcore-log( 2532): Screen Brightness 5
I/jxcore-log( 2532): 
E/jxcore-log( 2532): Dummy Error Log.
E/jxcore-log( 2532): 
,D/SecurityLogAgent( 2628): FileZippingService : onHandleIntent 
,D/SecurityLogAgent( 2628): FileZippingService : file path =  /data/misc/audit/audit.old
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2646): MountEmulatedStorage()
I/libpersona( 2646): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2646): v2
I/libpersona( 2646): KNOX_SDCARD not a persona
I/SELinux ( 2646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2646): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2646 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/SecurityLogAgent( 2628): FileZippingService : onPremise disabled. Zipping..  
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : Not empty 
,D/TimaKeyStoreProvider( 2646): TimaSignature is unavailable
D/SecurityLogAgent( 2628): DenialLogFileZipCreator : Files exceeded the max limit 
D/ActivityThread( 2646): Added TimaKeyStore provider
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator File existence : true audit.old file size 1345
,D/SecurityLogAgent( 2628): DenialLogFileZipCreator : denied strings found . Starts zipping . 
D/SecurityLogAgent( 2628): ProcessFileZipCreator : File name = denialLog
,W/ResourcesManager( 2646): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/SecurityLogAgent( 2628): ProcessFileZipCreator : Created temp file 
,D/SecurityLogAgent( 2628): ProcessFileZipCreator br.readline() has read  12 lines. 
D/SecurityLogAgent( 2628): ProcessFileZipCreator denialxxx.txt file file existence : true size after copying : 0
,D/SecurityLogAgent( 2628): ProcessFileZipCreator : Source = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog639325974.txt
D/SecurityLogAgent( 2628): ProcessFileZipCreator : Destination = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog639325974.txt.zip
,D/SecurityLogAgent( 2628): ProcessFileZipCreator : File compressed.
D/SecurityLogAgent( 2628): ProcessFileZipCreatordenialLog639325974.txt has been deleted after compression. 
,D/SecurityLogAgent( 2628): FileCipher : getKey Called 
,I/SecureStorage( 2628): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 2628): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  351): [INFO]: SPID(0x00000000)Credentials: uid 1000, gid 1000, pid 2628
I/SecureStorage(  351): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2628): [INFO]: SPID(0x00000000)SS Daemon is running
D/SecurityLogAgent( 2628): FileCipher : Secure Storage Supported 
,I/SecureStorage( 2628): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  351): [INFO]: SPID(0x00000000)Credentials: uid 1000, gid 1000, pid 2628,
I/SecureStorage(  351): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,D/FactoryTestApp( 2646): [FactoryTestBroadcastReceiver$onReceive](2646) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2646): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2646): [XMLDataStorage$parseXML](2646) is Live Demo : false
D/FactoryTestApp( 2646): [XMLDataStorage$parseXML](2646) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2646): [XMLDataStorage$parseXML](2646) deviceXML=a5ulte.dat
D/FactoryTestApp( 2646): [XMLDataStorage$parseXML](2646) nameXML=a5ultexx.dat
D/FactoryTestApp( 2646): [XMLDataStorage$parseAsset](2646) parseAsset Is Started
,I/FactoryTestApp( 2646): [XMLDataStorage$parseAsset](2646) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2646): [XMLDataStorage$parseAsset](2646) Decode base file: factory.dat
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=FACTORY_TEST_APP
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=FAILHIST_VERSION
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=MODEL_NAME
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=MODEL_NUMBER
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=CHIPSET_NAME
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=DEVICE_TYPE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=BATT_TYPE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=PANEL_TYPE
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SPEAKER_COUNT
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=MIC_COUNT
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_LTE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_DUAL_STANBY_ONE_CP
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_RCV
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=FACTORY_TEST_APO
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_BOOST_MEDIASCAN
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_NVBACKUP_CMD
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_EPEN
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_CAM_ISP
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_CAM_FRONT_NOT_ISP
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=NEED_CAMDRIVER_OPEN
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=HW_VER_EFS
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=FONT_SIZE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=RAM_SIZE_IF
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=MULTI_TSK_THD
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SEMI_FUNCTION_FONT_SIZE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=NEED_LPA_MODE_SET
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_SEMI_FUNCTION_TEST
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_FM_RADIO
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_GRAPHIC_ACCLETOR
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_DISABLE_SCROLLING_CACHE
D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_TEST_POWER
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_TEST_HOME,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_TEST_BACK
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SEMI_KEY_TEST_VOLUME_UP,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SEMI_KEY_TEST_HOME,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=IS_KEY_TEST_THRESHOLD,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=IS_VIBETONZ_UNSUPPORTED,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=AT_GPSSTEST,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=AT_BATTEST_RESET_WHEN_READ,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SUPPORT_CHARGE_COUNT,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=PA0_TEMP_ADC,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=PA1_TEMP_ADC,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=NEED_ACK_FOR_CAMERA_STOP,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=HALL_IC_TEST,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=READ_TARGET_GEOMAGNETIC
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SYS_INFO_MEMORY_SIZE,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SYS_INFO_MODEL_NAME,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_NODE_COUNT_WIDTH,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_NODE_COUNT_HEIGHT,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_SELFTEST_MIN_MELFAS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_SELFTEST_MAX_MELFAS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TOUCH_KEY_SPEC_MAX,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=BOOTLOADER_VERSION,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=BATTERY_TEST_MODE,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=BATTERY_VF_OCV,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=PA0_THERMISTER_ADC,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=PA1_THERMISTER_ADC,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_COMMAND_CMD
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_COMMAND_STATUS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=PATH_HALLIC_STATE,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=KEY_PRESSED_POWER,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=HUMITEMP_THERMISTER_PAM,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=HUMITEMP_THERMISTER_BATT_CELCIUS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=HUMITEMP_THERMISTER_S_HUB_BATT,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS,
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=LPA_MODE_SET
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2646): [XMLDataStorage$redefinitionById](2646) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2646): [XMLDataStorage$parseAsset](2646) SemiFunctionMenu
,D/FactoryTestApp( 2646): [XMLDataStorage$parseAsset](2646) parseAsset Is Completed
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=CHIPSET_MANUFACTURE, value=Qualcomm
I/FactoryTestApp( 2646): [ModuleCommon$ModuleCommon](2646) Create ModuleCommon
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,I/jxcore-log( 2532): getBuffer is called!!!!
I/jxcore-log( 2532): 
,D/FactoryTestApp( 2646): [Support$Kernel.read](2646) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2646): [ModuleCommon$readFactoryMode](2646) mode: ON
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2646): [FactoryTestBroadcastReceiver$onReceive](2646) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2646): [Support$Values.getBoolean](2646) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 2646): [Support$Properties.get](2646) property=ro.factory.factory_binary
D/FactoryTestApp( 2646): [FactoryTestBroadcastReceiver$onReceive](2646) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2646): [ModuleCommon$getFtClientEnableState](2646) result : false
I/FactoryTestApp( 2646): [ModuleCommon$connectedJIG](2646) ...
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2646): [ModuleCommon$connectedJIG](2646) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
D/FactoryTestApp( 2646): [Support$Kernel.read](2646) path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 2646): [ModuleCommon$connectedJIG](2646) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2646): [ModuleCommon$isConnectionModeNone](2646) mConnectionMode = gsm
I/FactoryTestApp( 2646): [ModuleCommon$isRunningFtClient](2646) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2646): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2646) start DummyFtClient service for APO
W/ContextImpl( 2646): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2646): User mode
I/FactoryTestApp( 2646): [ModuleCommon$disableFtClient](2646) ...
,D/FactoryTestApp( 2646): [DummyFtClient$onCreate](2646) Create DummyFtClient service
I/FactoryTestApp( 2646): [XMLDataStorage$parsingXML](2646) FtClient => data parsing was completed.
D/FactoryTestApp( 2646): [DummyFtClient$onReceive](2646) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2646): [ModuleCommon$isConnectionModeNone](2646) mConnectionMode = gsm
,D/FactoryTestApp( 2646): [Support$Values.getBoolean](2646) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2646): [DummyFtClient$onStartCommand](2646) ...
,I/WifiService( 1017): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager( 1017): boot completed
,D/UsbDeviceManager( 1017): handleMessage -> MSG_BOOT_COMPLETED
,I/KeyguardEffectViewUtil( 1177): set resource id
,D/SettingsProvider( 1017): name = keyguard_default_wallpaper_res_id
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BOOT_COMPLETED
,D/KeyguardUpdateMonitor( 1177): handleBootCompleted()
,D/KeyguardUpdateMonitor( 1177): handleBootCompleted()
,I/PalmMotion( 1017): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1017): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1017): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1017): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/UsbDeviceManager( 1017): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1017): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/UsbDeviceManager( 1017): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,D/SamsungIME( 1777): showDlgMsgBox : false true true
,I/RecoverySystem( 1017): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1017): No recovery log file
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,D/Reset_Reason( 1017): resetString = NPON
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/SMD     (  288): DCD OFF
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BootReceiver( 1017): Copying audit failures to DropBox
,I/BootReceiver( 1017): Checking for fsck errors
,D/NfcService( 1449): call the applyRouting
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 25
,V/OtaStartupReceiver( 1462): onOtaspChanged: mOtaspMode=1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2677 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,I/SecureStorage(  351): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
I/libpersona( 2677): KNOX_SDCARD checking this for 1001
E/Zygote  ( 2677): MountEmulatedStorage()
I/libpersona( 2677): KNOX_SDCARD not a persona
E/Zygote  ( 2677): v2
I/SELinux ( 2677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2677): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2677): TimaSignature is unavailable
,D/ActivityThread( 2677): Added TimaKeyStore provider
,E/Zygote  ( 2692): MountEmulatedStorage()
E/Zygote  ( 2692): v2
I/libpersona( 2692): KNOX_SDCARD checking this for 1000
I/libpersona( 2692): KNOX_SDCARD not a persona
I/SELinux ( 2692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecureStorage( 2628): [INFO]: SPID(0x00000001)Processing data has been completed
I/SecureStorage( 2628): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
D/SecurityLogAgent( 2628): FileCipher : Got the key bytes 
D/SecurityLogAgent( 2628): FileCipher : Saving Key to SecureStorage.  
,I/SecureStorage( 2628): [INFO]: SPID(0x00000001)Processing data
,I/ActivityManager( 1017): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2692 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SecureStorage(  351): [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 2628
I/SecureStorage(  351): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000104
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 2692): TimaSignature is unavailable
,D/ActivityThread( 2692): Added TimaKeyStore provider
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 2677): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,E/File    ( 2692): fail readDirectory() errno=2
,D/FactoryTestApp( 2646): [ProtectedFactoryTestBroadcastReceiver$onReceive](2646) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2646): [ProtectedFactoryTestBroadcastReceiver$onReceive](2646) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2646): User mode
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Mms/NotificationReceiver( 2318): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,D/Mms/NotificationReceiver( 2318): handleBootCompleted()
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/RcsOwnCapsManager( 2318): queue Uri = content://im/queue-messages?box=pending
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TP/ImProvider( 1462): im query match24
D/TP/ImProvider( 1462): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1462): ftSesstionId must be a long.
D/TP/ImProvider( 1462): getQueuedImMessages
,D/TP/ImProvider( 1462): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Mms/NotificationReceiver( 2318):  getPendingMessageIds: no pending messages.
D/Mms/ActionsFactory( 2318): Call to GET_LAST_MESSAGES_SENT
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
D/SensorService( 1017): [SO] 0.172 0.134 10.209
D/SettingsProvider( 1017): name = db_smartlock_supported
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/AccessibilityManagerService( 1017): setmDNIeNegative (false)
,W/Settings( 1288): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1017): name = block_emergency_message
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/SmartFaceService( 1017): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1017): no icon
E/SmartFaceService( 1017): mActiveServiceType: 0
E/SmartFaceService( 1017): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1017): updateClientsDone. def. do nothing.
E/SmartFaceService( 1017): Service Type to Worker: 0
E/SmartFaceService( 1017): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1017): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1017): [SO] activate (ident=0xb7a8d918, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb7a8d918, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/RCPManagerService( 1017): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1017):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED ,
D/RCPManagerService( 1017): BootReceiver.onReceive(): Starting RCP Proxy for user = null
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
E/RCPManagerService( 1017):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,V/AlarmManagerEXT( 1017): mGmsLocationBundling: false
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1017): android.intent.action.BOOT_COMPLETED,
D/EnterpriseDeviceManagerService( 1017): runAdminUpdate,
D/EnterpriseUtils( 1017): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService( 1017): nothing to selfUpdate
V/ApplicationPolicy( 1017): boot completed - refreshWidgetStatus,
V/ApplicationPolicy( 1017): refresh widget status for user 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/,ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
W/PhoneRestrictionPolicy( 1017): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
D/KnoxMUMContainerPolicy( 1017): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
I/KnoxMUMContainerPolicy( 1017): MSG_REMOVE_ORPHANED_CONTAINERS received
W/PhoneRestrictionPolicy( 1017):  >>>> deliveryBlockedMsgs
W/PhoneRestrictionPolicy( 1017): cvList size 0
D/WifiP2pService( 1017): P2pDisabledState{ what=143415 }
W/PhoneRestrictionPolicy( 1017):  >>>> deliveryBlockedMsgs
D/WifiP2pService( 1017): DefaultState{ what=143415 }
W/PhoneRestrictionPolicy( 1017): cvList size 0
D/ConnectivityService( 1017): Got NetworkFactory Messenger for WIFI_P2P
D/Tethering( 1017): Boot complete.
D/WIFI_P2P( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/ConnectivityService( 1017): Got NetworkFactory Messenger for WIFI
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/WifiStateMachine( 1017): Blacklist file delete
,V/EnterpriseBillingEngine( 1017): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1017): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1017): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1017): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1017): handleAllprofiles - end
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,D/UsbHostNotification( 1017): boot completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,D/UsbHostRestrictor( 1017): mBootCompletedReceiver onReceive
,D/UsbHostRestrictor( 1017): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1017): SIM was never inserted
,D/UsbHostRestrictor( 1017): writableHostSysNode[false]
D/UsbHostRestrictor( 1017): Can NOT Write Disable Sys Node to [ON]
,D/PersonaManagerService( 1017): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1017):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
W/SecureStorage(  351): [WARN]: SPID(0x00000002)Trying update data block to DB
D/UsbStorageNotification( 1017): boot completed
D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1017): set_capabilities_callback: 55u
,D/KnoxKeyguardUpdateMonitor( 1017): onBootComplete
,I/libmdmdetect( 1017): ESOC framework not supported
,I/libmdmdetect( 1017): Found internal modem: modem
,E/PerMgrLib( 1017): Peripheral manager is not supported on this device
E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_cleanup 
,D/qmi_secgps_clnt( 1017): qmi_secgps_client_init()
,I/KnoxKeyguardUpdateMonitor( 1017): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1017): onTrustChanged user:0, enable:false
D/WIFI    ( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/StorageNotification( 1177): boot completed
,D/KeyguardViewMediator( 1177): onTrustChanged( Showing = false , userId = 0 )
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,I/SecureStorage(  351): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,I/i       ( 1017): No model
,D/StatusBarManagerService( 1017): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/PhoneStatusBar( 1177): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/FactoryTest( 1017): Not factory mode
D/FactoryTest( 1017): Not factory mode. isFactoryMode() returend false
D/w       ( 1017): isUserBuild = true
D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,E/Zygote  ( 2727): MountEmulatedStorage(),
I/libpersona( 2727): KNOX_SDCARD checking this for 10099
E/Zygote  ( 2727): v2
,I/libpersona( 2727): KNOX_SDCARD not a persona
I/SELinux ( 2727): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2727 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,I/SELinux ( 2727): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2727): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/SecureStorage( 2628): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 2628): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,D/SecurityLogAgent( 2628): FileCipher : Key loaded. 
,D/SecurityLogAgent( 2628): ProcessFileZipCreator : source file  :  file existence : true size after compression : 160
D/SecurityLogAgent( 2628): FileCipher : File ciphering 
D/SecurityLogAgent( 2628): FileCipher : Source file name = denialLog639325974.txt.zip source file size 160
,D/SSRM:n  ( 1017): SIOP:: AP = 380
,D/SecurityLogAgent( 2628): FileCipher : Destination file name = denialLog-967296276.zip dest file Size 176
D/SecurityLogAgent( 2628): FileCipher : File ciphered successful 
D/SecurityLogAgent( 2628): ProcessFileZipCreator : source after encryption :  file existence : true file size:176
D/SecurityLogAgent( 2628): ProcessFileZipCreator : File ciphered 
D/SecurityLogAgent( 2628): ProcessFileZipCreatordenialLog639325974.txt.zip has been deleted after encryption. 
,D/SecurityLogAgent( 2628): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 2628): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 2628): StateMachine : Current State = 1
,D/SecurityLogAgent( 2628): FileZippingService : completed task. Returning wakelock . 
,D/TimaKeyStoreProvider( 2727): TimaSignature is unavailable
,D/ActivityThread( 2727): Added TimaKeyStore provider
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1017): [SO] activate (ident=0xb7a8d918, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
,E/LocSvc_utils_cfg( 1017): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,D/SensorService( 1017): [SO] changed settle time [1]
,D/SensorService( 1017): [SO] setDelay [66000000]
,D/SensorService( 1017): [SO] activate (ident=0xb7a8d918, enabled=1)
,D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1017): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,I/qmi_secgps_clnt( 1017): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1017): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1017): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,D/SensorService( 1017): [SO] currT = 32124239000, prevT = 31741041000, diff = 383198000, [0.172 0.115 10.228]
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1017): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02,
,D/SensorService( 1017): [SO] currT = 32191062000, prevT = 31741041000, diff = 450021000, [0.172 0.134 10.228]
,D/SensorService( 1017): [SO] 0.172 0.134 10.228
D/SensorService( 1017): [SO] [100 -> 255]
,E/ActivityThread( 2727): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2727): Failed to find provider info for flipboard.auth.internal
,W/CursorWrapperInner( 2318): Cursor finalized without prior close()
,I/splitIntent( 1017): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
,I/splitIntent( 1017): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/DrmEventReceiver( 1017): DrmEventReceiver : onReceive
,I/DrmEventReceiver( 1017): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1017): DrmEventReceiver : beginStartingService
I/System.out( 1017): start Service
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/DownloadManager( 1227): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2746): MountEmulatedStorage()
,E/Zygote  ( 2746): v2
I/libpersona( 2746): KNOX_SDCARD checking this for 10085
I/libpersona( 2746): KNOX_SDCARD not a persona
,I/SELinux ( 2746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2746 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 2746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2761): MountEmulatedStorage()
E/Zygote  ( 2761): v2
,I/libpersona( 2761): KNOX_SDCARD checking this for 1000
,I/SELinux ( 2761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 2761): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2761 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1017): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,I/SELinux ( 2761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/TimaKeyStoreProvider( 2746): TimaSignature is unavailable
D/ActivityThread( 2746): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,E/SELinux ( 2761): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 26
,D/WVMDrmPlugIn(  282): WVMDrmPlugin::onInitialize : 1357
,D/WVMDrmPlugIn(  282): WVMDrmPlugin::onSetOnInfoListener : add 1357
,I/TimaServiceEventReceiver( 1017): TimaServiceEventReceiver : onReceive
,W/ResourcesManager( 2746): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2746): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2746): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2761): TimaSignature is unavailable
W/ResourcesManager( 2746): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DrmEventService( 1017): action event :android.intent.action.BOOT_COMPLETED
W/ResourcesManager( 2746): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/ActivityThread( 2761): Added TimaKeyStore provider
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
I/ANDROID_DRM_FRWORKS_DrmManager(  282): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,D/MediaScannerReceiver( 1227): action: android.intent.action.BOOT_COMPLETED
,E/CscReceiver( 1462): onReceive android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1462): onStart
E/CscUpdateService( 1462): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1462): set_CSC_version
,E/CscParser( 1462): update(): xml file exist
,E/Zygote  ( 2781): MountEmulatedStorage()
,I/libpersona( 2781): KNOX_SDCARD checking this for 10003
E/Zygote  ( 2781): v2
I/libpersona( 2781): KNOX_SDCARD not a persona
,I/SELinux ( 2781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2781): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2781 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/CscUtil ( 1462): isWifiOnly = false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/System.out( 1462): HandDataNode = null
I/CscUpdateService( 1462): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1462): This is normal boot : CSC not updated,
,D/TimaKeyStoreProvider( 2781): TimaSignature is unavailable
,D/ActivityThread( 2781): Added TimaKeyStore provider
,E/CscParser( 1462): update(): xml file exist
I/libpersona( 2799): KNOX_SDCARD checking this for 10160
E/Zygote  ( 2799): MountEmulatedStorage()
I/libpersona( 2799): KNOX_SDCARD not a persona
E/Zygote  ( 2799): v2
,I/SELinux ( 2799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/SELinux ( 2799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CscGPS  ( 1462): CSCGPS.updateParameters
I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2799 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
D/CscGPS  ( 1462): supl host : null
D/CscGPS  ( 1462): SUPL Host is null or invalid
D/CscGPS  ( 1462): supl_ver : null
D/CscGPS  ( 1462): SUPL Ver is null or invalid
D/CscGPS  ( 1462): supl port : null
D/CscGPS  ( 1462): SUPL PORT is null or invalid
D/CscGPS  ( 1462): LPP : null
D/CscGPS  ( 1462): LPP is null or invalid
D/CscGPS  ( 1462): CSC don't have any AGPS value.
,I/CscUpdateService( 1462): same CSC Version
D/CscUtil ( 1462): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
D/TimaKeyStoreProvider( 2799): TimaSignature is unavailable
,D/ActivityThread( 2799): Added TimaKeyStore provider
,W/ResourcesManager( 2799): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/MediaScannerService( 1227): !@start scanning volume internal: [/system/media, /oem/media]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,I/SecureStorage( 2781): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,E/SQLiteLog( 1227): (283) recovered 422 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,D/TP/MmsProvider( 1462): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1462): update , handleReadChangedBroadcast
,D/TP/MmsSmsProvider( 1462): need read changed broadcast:false
,I/Mms:transaction( 2318): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2318): [start]    nonBlockingUpdateMessageIndicator() consume time = 2377.386458
,I/Mms/ReservationManager( 2318): resetAfterConnected()
,D/TP/MmsSmsProvider( 1462): query,matched:7, calling pid = 2318
,D/TP/MmsSmsProvider( 1462): match 7:Elapsed time : 1.918 ms
,D/Mms/MessagingNotification( 2318): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2318): isDefault true
,D/TP/MmsProvider( 1462): Query uri=content://mms, match=0, calling pid = 2318
,I/Mms/ReservationManager( 2318): getReservedSendMessageCount(): retMessageCount=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2820): MountEmulatedStorage()
,E/Zygote  ( 2820): v2
,I/libpersona( 2820): KNOX_SDCARD checking this for 1000
,I/libpersona( 2820): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TP/MmsSmsProvider( 1462): query,matched:200, calling pid = 2318
D/TP/MmsSmsProvider( 1462): match 200:Elapsed time : 1.242 ms
,I/SELinux ( 2820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecureStorage( 2781): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  351): [INFO]: SPID(0x00000002)Credentials: uid 10003, gid 10003, pid 2781
I/SecureStorage(  351): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 2781): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2781): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  351): [INFO]: SPID(0x00000002)Credentials: uid 10003, gid 10003, pid 2781
I/SecureStorage(  351): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,D/TimaKeyStoreProvider( 2820): TimaSignature is unavailable
,D/ActivityThread( 2820): Added TimaKeyStore provider
,D/[0]UMC:UMCContentProvider( 2799): @onCreate
,E/Zygote  ( 2830): MountEmulatedStorage()
I/libpersona( 2830): KNOX_SDCARD checking this for 10048
E/Zygote  ( 2830): v2
I/libpersona( 2830): KNOX_SDCARD not a persona
I/SELinux ( 2830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2830 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 2830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1017): name = next_alarm_formatted
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10085
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,D/TimaKeyStoreProvider( 2830): TimaSignature is unavailable
,D/ActivityThread( 2830): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/[0]UMC:Core( 2799): onCreate(): 
,D/[0]UMC:Core( 2799): @isManagedProfileUser
,D/[0]UMC:Core( 2799): userId: 0
,D/[0]UMC:Core( 2799): userInfo: UserInfo{0:Thali Test:13}
,D/[0]UMC:Core( 2799): userInfo.isManagedProfile() : false
,D/[0]UMC:DeviceInfo( 2799): USA==US==
,D/USER_AGENT( 2799): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,D/[0]UMC:AdminManager( 2799): init - start
,D/[0]UMC:AdminManager( 2799): loadAdmins
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,D/[0]UMC:AdminManager( 2799): init - end
,D/GSLBManager( 2799): migrateStoredUrlFromOldPref
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 42315(2MB) AllocSpace objects, 20(729KB) LOS objects, 33% free, 26MB/39MB, paused 2.214ms total 150.658ms
,D/Mms/SmsReceiverService( 2318): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,D/Mms/TelephonyPermission( 2318): isDefault true
D/Mms/SmsReceiverService( 2318): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2318): [start]    handleBootCompleted() consume time = 234.787969
,D/GSLBManager( 2799):  key : segd-api
D/GSLBManager( 2799):  value : https://eu-segd-api.secb2b.com:443/v2
,D/GSLBManager( 2799):  key : umc-cdn
,D/GSLBManager( 2799):  value : 
,W/art     ( 2746): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 134.859ms
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 2318
,D/TP/SmsProvider( 1462): match 0:Elapsed time : 4.076 ms
D/MediaScanner( 1227): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/GSLBManager( 2799):  key : segp-api
,D/GSLBManager( 2799):  value : 
W/ResourcesManager( 2830): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2830): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1462): query,matched:51, calling pid = 2318
,D/TP/SmsProvider( 1462): match 51:Elapsed time : 2.766 ms
,D/TP/MmsSmsProvider( 1462): getThreadUnReadCount unreadCount=0 imUnreadCount=0
,D/TP/MmsSmsProvider( 1462): deleteConversation threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1462): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1462): updateThread(), thread_id = 9223372036854775806
,D/GSLBManager( 2799):  key : myknoxapi
,D/GSLBManager( 2799):  value : 
,D/Mms/MessagingNotification( 2318): isBlockingModeEnabled() = false, Zen mode = 0
,V/TP/MmsSmsDatabaseHelper( 1462): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
,D/BadgeProvider( 1569): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TP/MmsSmsProvider( 1462): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1462): need read changed broadcast:false
,D/Mms/Conversation( 2318): deleteTempConversation(),deleted=0
,E/SQLiteLog( 2820): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,D/Launcher.Model( 1491): reloadBadges entered.
,D/BadgeProvider( 1569): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1569): sendNotify, [notify] : null
D/BadgeProvider( 1569): update, [uri] : content://com.sec.badge/apps/2
D/SmsProvider( 1462): Update uri=content://sms/outbox, match=8
,D/BadgeProvider( 1569): update, [BadgeCount] : badgecount=0
,D/TP/MmsSmsProvider( 1462): need read changed broadcast:false
,D/BadgeProvider( 1569): update, [UpdateCount] : 1
,D/GSLBManager( 2799): migrateStoredUrlFromOldPref : Finished Migrating
D/[0]UMC:UMCAdmin( 2799): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2799): Admin not found in package com.samsung.knoxpb.mdm
,D/Mms/SmsReceiverService( 2318): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2318): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2318): [SIM-1]sendFirstQueuedMessage()
,D/Mms/MessagingNotification( 2318): setBadgeCount(), count=0
,E/[0]UMC:Utils( 2799): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2799): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2799): isContainer : 0
,D/Mms/MessagingNotification( 2318): remove alarm
,D/TP/SmsProvider( 1462): query,matched:26, calling pid = 2318
,D/TP/SmsProvider( 1462): match 26:Elapsed time : 2.938 ms
,V/MediaScanner( 1227): processDirectory :  /system/media
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 2318
,D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
D/TP/SmsProvider( 1462): match 0:Elapsed time : 1.890 ms
,D/DSM     ( 2820): [Lines:107] Normal booted
D/SettingsProvider( 1017): name = block_emergency_message
D/DSM     ( 2820): [Lines:114] Boot completed
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10048
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/Mms/MessagingNotification( 2318): updateAllHistoryAsRead()
,E/[0]UMC:UMCAdmin( 2799): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2799): isContainer : 0
,W/ActivityManager( 1017): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/[0]UMC:UMCAdmin( 2799): deactivateUMCAdmin - UMC App Admin deactivated
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2857): MountEmulatedStorage()
V/MediaScanner( 1227):  prescan time: 449ms (DB items: 141)
E/Zygote  ( 2857): v2
V/MediaScanner( 1227):     scan time: 36ms (Caching mode: true), (makeEntry time: 24ms ~66%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 485ms
V/MediaScanner( 1227): checked files: 133  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1227): checkDefaultSounds
D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
,I/ActivityManager( 1017): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2857 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 2857): KNOX_SDCARD checking this for 1000
I/libpersona( 2857): KNOX_SDCARD not a persona
,I/SELinux ( 2857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,I/SELinux ( 2857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
E/SELinux ( 2857): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 1190:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/[0]UMC:GuardService( 2799): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,D/Mms/SmsReceiver( 2318): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2318): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2318): isDefault true
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 39008(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/12MB, paused 982us total 55.695ms
,D/[0]UMC:CoreReceiver( 2799): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2799):  check PreETag 
,D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
,I/art     (  305): Explicit concurrent mark sweep GC freed 8780(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 810us total 31.655ms
,D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
,D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/Mms/MessagingNotification( 2318): [end]    nonBlockingUpdateMessageIndicator() consume time = 246.423072
,D/TimaKeyStoreProvider( 2857): TimaSignature is unavailable
,D/ActivityThread( 2857): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 18.421ms
D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
D/TP/MmsProvider( 1462): Query uri=content://mms, match=0, calling pid = 2318
I/WifiCredService( 1288): onCreate
,D/FactoryTestApp( 2646): [DummyFtClient$mBroadcastReceiver](2646) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2646): [DummyFtClient$mBroadcastReceiver](2646) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2646): [DummyFtClient$mBroadcastReceiver](2646) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/MediaScannerService( 1227): !@done scanning volume internal
,D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.674ms
,W/ResourcesManager( 2857): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1462): query,matched:200, calling pid = 2318
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1462): match 200:Elapsed time : 6.164 ms,
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1190/cgroup.procs: No such file or directory,
,E/Zygote  ( 2876): MountEmulatedStorage()
E/Zygote  ( 2876): v2
I/libpersona( 2876): KNOX_SDCARD checking this for 1000
I/libpersona( 2876): KNOX_SDCARD not a persona
,I/SELinux ( 2876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/[0]UMC:CoreReceiver( 2799): bulk enrolled package: null
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,I/SELinux ( 2876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,V/[0]UMC:ProfileStorage( 2799): Enter loadList
E/SELinux ( 2876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[0]UMC:CoreReceiver( 2799): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2799): deactivateUMCAdminIfNotRequired : -1
,I/ActivityManager( 1017): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/[0]UMC:Utils( 2799): Admin not found in package com.samsung.knoxpb.mdm
D/WifiTimerReceiver( 1288): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1288): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1288): Action boot completed received
,E/[0]UMC:Utils( 2799): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2799): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2799): isContainer : 0
,D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2799): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2799): isContainer : 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
D/[0]UMC:UMCAdmin( 2799): deactivateUMCAdmin - UMC App Admin deactivated
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/TimaKeyStoreProvider( 2876): TimaSignature is unavailable
,D/ActivityThread( 2876): Added TimaKeyStore provider
,W/ActivityThread( 2857): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/NearbySettings( 1288): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1288): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1288): MountReceiver.onReceive - Create mPrefHandler
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 2318
,D/[0]UMC:ByodSetupStarter( 2799): Container ID : 0,
,D/TP/SmsProvider( 1462): match 0:Elapsed time : 17.688 ms
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 27,
,D/NearbySettings( 1288): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
V/NearbySettings( 1288): MountReceiver.mPrefHandler - 7002
D/SettingsProvider( 1017): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,V/[0]UMC:Utils( 2799): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2799): shutdown
I/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2799): @GuardService - stopService Result = true
,I/art     ( 2799): System.exit called, status: 0
I/AndroidRuntime( 2799): VM exiting with result code 0, cleanup skipped.
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,W/ResourcesManager( 2876): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/TP/SmsProvider( 1462): query,matched:51, calling pid = 2318
,I/NearbySettings( 1288): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 1288): MountReceiver.onReceive - Internal Path
D/TP/SmsProvider( 1462): match 51:Elapsed time : 2.154 ms
,D/SettingsProvider( 1017): name = personal_mode_enabled
,D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/MediaScanner( 1227): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,I/SecureStorage(  351): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,I/LcdtestApp( 2857): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,E/Zygote  ( 2899): MountEmulatedStorage()
I/libpersona( 2899): KNOX_SDCARD checking this for 10086
E/Zygote  ( 2899): v2
I/libpersona( 2899): KNOX_SDCARD not a persona
I/SELinux ( 2899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2899 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 2899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Killing 1408:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
E/SELinux ( 2899): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2799)(adj 0) has died(143,1021)
,D/Mms/MessagingNotification( 2318): isBlockingModeEnabled() = false, Zen mode = 0
W/ResourcesManager( 1462): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SecureStorage( 2781): [INFO]: SPID(0x00000003)Processing data has been completed
V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SecureStorage( 2781): [INFO]: SPID(0x00000003)Skip using SecureStorageExceptionJNI
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1227): Skipping:,
I/libpersona( 2915): KNOX_SDCARD checking this for 1000
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
I/libpersona( 2915): KNOX_SDCARD not a persona
,E/Zygote  ( 2915): MountEmulatedStorage()
E/Zygote  ( 2915): v2
I/SELinux ( 2915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 2899): TimaSignature is unavailable
,D/ActivityThread( 2899): Added TimaKeyStore provider
I/SELinux ( 2915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
E/SELinux ( 2915): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BadgeProvider( 1569): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2915 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/MediaScanner( 1227):  prescan time: 190ms (DB items: 27)
V/MediaScanner( 1227):     scan time: 22ms (Caching mode: true), (makeEntry time: 12ms ~54%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 18ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 230ms
,V/MediaScanner( 1227): checked files: 10  directories : 17  (I: 0, U: 0)
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1408/cgroup.procs: No such file or directory
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1300): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1300): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1300): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1300): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,I/SmartcardBootCompleteReceiver( 1288): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1288): Received intent with action - android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 2915): TimaSignature is unavailable
,D/SettingsProvider( 1017): name = aw_daemon_service_key_version_check
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/MediaScannerService( 1227): !@done scanning volume external
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10162
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/ActivityThread( 2915): Added TimaKeyStore provider
,D/FactoryTestApp( 2646): [DummyFtClient$mBroadcastReceiver](2646) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2646): [DummyFtClient$mBroadcastReceiver](2646) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2646): [DummyFtClient$sendBootCompletedAndFinish](2646) ...
D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2646): [ModuleCommon$isConnectionModeNone](2646) mConnectionMode = gsm
,D/FactoryTestApp( 2646): [IPCWriterToSecPhoneService$ResponseWriter](2646) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2646): [IPCWriterToSecPhoneService$connectToSecPhoneService](2646)  
,W/ContextImpl( 1288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,I/SmartcardBootCompleteReceiver( 1288): Broadcast sent with current lockscreen type
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ContextImpl( 2646): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1300): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/Launcher.Model( 1491): reloadBadges entered.
,D/BadgeProvider( 1569): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1569): sendNotify, [notify] : null
D/BadgeProvider( 1569): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1569): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1569): update, [UpdateCount] : 1
,E/daemonapp( 1300): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/FactoryTestApp( 2646): [IPCWriterToSecPhoneService$onServiceConnected](2646) connected done
D/FactoryTestApp( 2646): [IPCWriterToSecPhoneService$write](2646) Send Response Message to SecPhone
D/FactoryTestApp( 2646): [IPCWriterToSecPhoneService$write](2646) Response ��
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1450189281026
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1450210860000,
D/daemonapp( 1300): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1300): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/Mms/MessagingNotification( 2318): setBadgeCount(), count=0
,D/daemonapp( 1300): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1450210860000
,I/iu.UploadsManager( 1948): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/Mms/MessagingNotification( 2318): remove alarm
,D/AT_Distributor(  310): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/[SBeam] ( 1288): SBeamEnabler.initPreferenceForSbeam : 0
,D/FactoryTestApp( 2646): [IPCWriterToSecPhoneService$handleMessage](2646) Send BOOTING COMPLETED done
,D/Mms/MessagingNotification( 2318): updateAllHistoryAsRead()
,I/SettingSearch/SearchIntentReceiver( 1288): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1288): search setting db init!!
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 2318
,D/TP/SmsProvider( 1462): match 0:Elapsed time : 1.628 ms
,D/Mms/SmsReceiverService( 2318): [end]    handleBootCompleted() consume time = 517.671511
,I/ActivityManager( 1017): Killing 1390:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,I/DIAGMON_AGENT( 2915): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/ContextImpl( 1288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 67
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1450210860000
,I/SettingSearch/SearchIntentReceiver( 1288): BOOT_COMPLETED call InitSerachDBThread thread start!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2941): MountEmulatedStorage()
,E/Zygote  ( 2941): v2
I/libpersona( 2941): KNOX_SDCARD checking this for 1000
I/libpersona( 2941): KNOX_SDCARD not a persona
,I/SELinux ( 2941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2941): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/AT_Distributor(  310): SetAtdStatus(), 1_1_0
D/AT_Distributor(  310): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
E/UpdateRequestReceiver( 2899): ignoring update request
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/comdaemonstockapp( 1300): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/comdaemonstockapp( 1300): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,E/UpdateRequestReceiver( 2899): ignoring update request
,W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_1390/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 2941): TimaSignature is unavailable
,D/ActivityThread( 2941): Added TimaKeyStore provider
E/Zygote  ( 2958): MountEmulatedStorage()
E/Zygote  ( 2958): v2
I/libpersona( 2958): KNOX_SDCARD checking this for 10150
I/libpersona( 2958): KNOX_SDCARD not a persona
,I/SELinux ( 2958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 2958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2958 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/SELinux ( 2958): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2958): TimaSignature is unavailable
,D/ActivityThread( 2958): Added TimaKeyStore provider
,W/ContextImpl( 1876): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1876): Thread created.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/UpdateRequestReceiver( 2899): ignoring update request
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SecUISvc( 1876): Service started flags 0 startId 1
,W/ResourcesManager( 2941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,E/Zygote  ( 2977): MountEmulatedStorage()
,E/Zygote  ( 2977): v2
I/libpersona( 2977): KNOX_SDCARD checking this for 10028
,I/libpersona( 2977): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2977 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 2977): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DIAGMON_AGENT( 2915): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/iu.UploadsManager( 1948): End new media; added: 0, uploading: 0, time: 166 ms
,I/DIAGMON_AGENT( 2915): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,D/TimaKeyStoreProvider( 2977): TimaSignature is unavailable
,D/ActivityThread( 2977): Added TimaKeyStore provider
,E/UpdateRequestReceiver( 2899): ignoring update request
,E/UpdateRequestReceiver( 2899): ignoring update request
,E/UpdateRequestReceiver( 2899): ignoring update request
,I/DIAGMON_AGENT( 2915): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,I/DIAGMON_AGENT( 2915): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2915): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2915): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/BluetoothHeadset( 2781): BTStateChangeCB is registed
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/BluetoothHeadset( 2781): doBind(): CallingUid(myUserHandle) = 0
,E/Zygote  ( 2998): MountEmulatedStorage()
E/Zygote  ( 2998): v2
I/libpersona( 2998): KNOX_SDCARD checking this for 10094
I/libpersona( 2998): KNOX_SDCARD not a persona
,I/SELinux ( 2998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=2998 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 2998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 1569:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,I/FOTA    ( 2941): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,E/BluetoothHeadset( 2781): BluetoothHeadset service is binded
,D/BluetoothA2dp( 2781): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapter( 2781): 1064725752: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2781): 1064725752: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2781): 1064725752: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2781): 1064725752: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2781): 1064725752: getState() :  mService = null. Returning STATE_OFF
,D/TimaKeyStoreProvider( 2998): TimaSignature is unavailable
,D/ActivityThread( 2998): Added TimaKeyStore provider
,I/DBG_DM  ( 2941): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3015): MountEmulatedStorage()
E/Zygote  ( 3015): v2
I/libpersona( 3015): KNOX_SDCARD checking this for 1000
,I/libpersona( 3015): KNOX_SDCARD not a persona
I/SELinux ( 3015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
D/elm:15183( 2998): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) },
D/elm:15183( 2998): ELMEngine.ELMEngine( context ).
,D/elm:15183( 2998): MDMBridge.setEnterpriseBridge()
,I/SELinux ( 3015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3015): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3015 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 2998): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 2998): ElmAgentService : onCreate(),
,D/elm:15183( 2998): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 2998): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 2998): BootCompletedState : startBootCompleted() call
,D/TimaKeyStoreProvider( 3015): TimaSignature is unavailable
,V/EmergencyMode( 1418): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
D/elm:15183( 2998): MDMBridge.getAllLicenseInfoFromSDK()
,D/ActivityThread( 3015): Added TimaKeyStore provider
,I/elm:15183( 2998): Get License : 0
D/elm:15183( 2998): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 1714:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1569/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2941): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 2941): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,I/ActivityManager( 1017): Killing 1552:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10138/pid_1714/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3015): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3015): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3015): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache],
,E/Zygote  ( 3039): MountEmulatedStorage()
,E/Zygote  ( 3039): v2
I/libpersona( 3039): KNOX_SDCARD checking this for 10009
I/libpersona( 3039): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/SELinux ( 3039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/DBG_POLICYDM( 3015): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3015): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] ,
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3039 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3039): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3015): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3015): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,D/TimaKeyStoreProvider( 3039): TimaSignature is unavailable
,D/ActivityThread( 3039): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3015): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,V/EmergencyMode( 1418): [EmergencyBase] setBootTime
V/EmergencyMode( 1418): [EmergencyFactory] No Recovery State, kill my self.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3055): MountEmulatedStorage()
,E/Zygote  ( 3055): v2
I/ActivityManager( 1017): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 3055): KNOX_SDCARD checking this for 1000
I/libpersona( 3055): KNOX_SDCARD not a persona
,I/SELinux ( 3055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3055): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_1552/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3055): TimaSignature is unavailable
,D/ActivityThread( 3055): Added TimaKeyStore provider
,I/DBG_DM  ( 2941): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 2941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,D/OverheatReceiver( 1177): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1177): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1177): VZW on -> change to Global UX [safe mode]
,I/DBG_DM  ( 2941): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
D/OverheatReceiver( 1177): isSafeMode = false
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/CameraApp( 3055): CameraApp.onCreate()... mFeature : null
I/testFeature( 3055): Feature.Feature(context)
I/testFeature( 3055): Feature.readInternalDefaultXml()
I/testFeature( 3055): ResetFeatureValue
,I/DBG_DM  ( 2941): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/CameraFirmware_broadcast( 3055): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3055): CameraApp.getAppFeature()...
I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 2941): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2941): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,D/BootupListener( 1462): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/PhoneUtilsCommon( 1462): isSupportVoLTE is false.
I/DBG_DM  ( 2941): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] ,
I/DBG_DM  ( 2941): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
E/SMD     (  288): DCD OFF
,I/DBG_DM  ( 2941): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,E/Zygote  ( 3072): MountEmulatedStorage(),
E/Zygote  ( 3072): v2
I/libpersona( 3072): KNOX_SDCARD checking this for 10100
I/libpersona( 3072): KNOX_SDCARD not a persona
,I/SELinux ( 3072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3072 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2117:com.vlingo.midas/u0a31 (adj 15): empty #31
,I/SELinux ( 3072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2941): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 2941): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,I/DBG_DM  ( 2941): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(155/onStartCommand)] 
E/USB_UICC(  296): Timeout! No signal received. Retry num = 28
,W/ContextImpl( 2941): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3072): TimaSignature is unavailable
I/art     (  305): Explicit concurrent mark sweep GC freed 8763(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 702us total 29.995ms
D/ActivityThread( 3072): Added TimaKeyStore provider
,I/Telecom ( 1439): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/Telecom ( 1439): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 776us total 20.569ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.080ms
,E/Zygote  ( 3088): MountEmulatedStorage()
I/libpersona( 3088): KNOX_SDCARD checking this for 10012
E/Zygote  ( 3088): v2
I/libpersona( 3088): KNOX_SDCARD not a persona
,I/SELinux ( 3088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3088 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_POLICYDM( 3015): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/PackageIntentReceiver( 3072): ACTION_BOOT_COMPLETED
I/DBG_POLICYDM( 3015): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SELinux ( 3088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/DBG_POLICYDM( 3015): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/SELinux ( 3088): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/Telecom ( 1439): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
D/Finsky  ( 2977): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/PackageIntentReceiver( 3072): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/Telecom ( 1439): InCallController: Unbinding from InCallService unbind
,E/DBG_POLICYDM( 3015): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/ActivityManager( 1017): Killing 2139:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,I/DBG_DM  ( 2941): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 2941): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3088): TimaSignature is unavailable
,D/ActivityThread( 3088): Added TimaKeyStore provider
,I/GoogleHttpClient( 1659): GMS http client unavailable, use old client
,E/Zygote  ( 3113): MountEmulatedStorage()
I/libpersona( 3113): KNOX_SDCARD checking this for 10003
E/Zygote  ( 3113): v2
I/libpersona( 3113): KNOX_SDCARD not a persona
I/SELinux ( 3113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3113 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 3113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3113): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3131): MountEmulatedStorage()
E/Zygote  ( 3131): v2
I/libpersona( 3131): KNOX_SDCARD checking this for 1000
I/libpersona( 3131): KNOX_SDCARD not a persona
,I/SELinux ( 3131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,D/TimaKeyStoreProvider( 3113): TimaSignature is unavailable,
W/ResourcesManager( 3088): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3088): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ActivityThread( 3113): Added TimaKeyStore provider,
,I/SELinux ( 3131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3131): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/audio_hw_primary(  283): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  283): audio_extn_get_parameters: returns 
V/msm8974_platform(  283): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  283): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  283): key: 'call_forwarding' value: ''
,W/libprocessgroup( 1017): failed to open /acct/uid_10031/pid_2117/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10050/pid_2139/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3131): TimaSignature is unavailable
,D/ActivityThread( 3131): Added TimaKeyStore provider
,V/InCall  ( 1884): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1884): ProximitySensor -  - mFromRcsShare: false
,I/MultiDex( 3088): VM with version 2.1.0 has multidex support
I/MultiDex( 3088): install
I/MultiDex( 3088): VM has multidex support, MultiDex support library is disabled.
I/InCall  ( 1884): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1884): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1884): InCallUtils - isCoverClosed false
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
I/Telecom ( 1439): ProximitySensorManager: Proximity wake lock already released
,D/InCall  ( 1884): InCallUtils - isCoverClosed false
I/InCall  ( 1884): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1884): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,D/InCall  ( 1884): InCallPresenter -  - dismissCoverDialog()...
,I/InCall  ( 1884): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1884): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,D/PhoneStatusBarView( 1177): setCallBackground:0
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1884): InCallUtils - isCoverClosed false
V/JNIHelp ( 3088): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/UserAnalysis.PlaceProvider( 3113): PlaceProvider onCreate()
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3015): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3015): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3015): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/ActivityThread( 3088): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3088): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@92dd47d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3088): Installed default security provider GmsCore_OpenSSL
,D/VideoCallManager( 1884): Instantiating VideoCallManager
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1884): took 2.018802ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1884): took 5.143489ms for 0*0 texture 0
,I/GFX raster( 1884): took 10.869740ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb761c7a8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb761c078 counterpartCT=4 counterpartW=176 counterparth=144
,D/UserAnalysis.SecureDbManager( 3113): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3113): SecurePlaceDbHelper() 
D/UserAnalysis( 3113): Create SecureDbHelper
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1884): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1884): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1884): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1884): Local Branch: 
I/Adreno-EGL( 1884): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1884): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1884):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/GFX GPU raster( 1884): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1884): took 0.249323ms for 320*61440 texture 37809
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/draw setup( 1884): took 11.287187ms for 320*240 texture 37809
,E/GFX GPU raster( 1884): drawn
,I/GFX GPU raster ASTC( 1884): took 41.224012ms for 320*240 texture 12
I/GFX raster( 1884): took 41.305783ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb761c728 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb761c290 counterpartCT=4 counterpartW=320 counterparth=240
,E/Zygote  ( 3158): MountEmulatedStorage(),
E/Zygote  ( 3158): v2
I/libpersona( 3158): KNOX_SDCARD checking this for 1000
I/libpersona( 3158): KNOX_SDCARD not a persona
,I/SELinux ( 3158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3158 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1678:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/ActivityManager( 1017): Killing 1508:com.android.printspooler/u0a136 (adj 15): empty #32
,I/SELinux ( 3158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Killing 2154:com.google.android.apps.magazines/u0a113 (adj 15): empty #33,
,E/SELinux ( 3158): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1884): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1884): took 0.323750ms for 480*122880 texture 37813
I/draw setup( 1884): took 0.692292ms for 480*640 texture 37813
E/GFX GPU raster( 1884): drawn
,I/GFX GPU raster ASTC( 1884): took 7.590626ms for 480*640 texture 12
I/GFX raster( 1884): took 7.676720ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb761c290 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7849940 counterpartCT=4 counterpartW=480 counterparth=640
,I/ActivityManager( 1017): Killing 2302:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3158): TimaSignature is unavailable
,D/ActivityThread( 3158): Added TimaKeyStore provider
,D/IntelligenceServiceApplication( 3113): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3113): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1884): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1884): took 0.345729ms for 440*116864 texture 37809
I/draw setup( 1884): took 0.728385ms for 440*330 texture 37809
E/GFX GPU raster( 1884): drawn
,I/GFX GPU raster ASTC( 1884): took 4.576511ms for 440*330 texture 12
I/GFX raster( 1884): took 4.655678ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb784db98 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb784df58 counterpartCT=4 counterpartW=440 counterparth=330
,E/Zygote  ( 3174): MountEmulatedStorage()
I/libpersona( 3174): KNOX_SDCARD checking this for 10060
E/Zygote  ( 3174): v2
I/libpersona( 3174): KNOX_SDCARD not a persona
I/SELinux ( 3174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3174 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2341:com.sec.modem.settings/1000 (adj 15): empty #31
,I/SELinux ( 3174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640,
E/SELinux ( 3174): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GFX GPU raster( 1884): eglCreateImageKHR: EGL_SUCCESS
D/IntelligenceServiceApplication( 3113): no applications having user consent for prediction
,I/glCompressedTexImage2D( 1884): took 0.430729ms for 480*163840 texture 37811
I/draw setup( 1884): took 0.755052ms for 480*640 texture 37811
E/GFX GPU raster( 1884): drawn
,I/ActivityManager( 1017): Killing 2354:com.sec.android.omc/1000 (adj 15): empty #31
,I/GFX GPU raster ASTC( 1884): took 6.848073ms for 480*640 texture 12
I/GFX raster( 1884): took 6.934480ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb788d568 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb78496f8 counterpartCT=4 counterpartW=480 counterparth=640
,I/DBG_DM  ( 2941): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,D/TimaKeyStoreProvider( 3174): TimaSignature is unavailable
,I/DBG_FMMDM( 3158): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/ActivityThread( 3174): Added TimaKeyStore provider
,D/Finsky  ( 2977): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 3113): [PlaceDetection::stopService] Service stopped.
,I/DBG_FMMDM( 3158): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3158): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3158): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2941): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1884): took 2.394844ms for 0*0 texture 0,
,I/DBG_DM  ( 2941): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
I/DBG_DM  ( 2941): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/GFX generate_partition_tables( 1884): took 15.962970ms for 0*0 texture 0
,I/GFX raster( 1884): took 23.262762ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb784db18 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7847158 counterpartCT=4 counterpartW=176 counterparth=144
,V/PlaceDetection v1.0.19 ( 3113): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3113): Constructor Preference
,E/        ( 1884): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,E/Zygote  ( 3195): MountEmulatedStorage()
E/Zygote  ( 3195): v2
I/libpersona( 3195): KNOX_SDCARD checking this for 1000
I/libpersona( 3195): KNOX_SDCARD not a persona
,I/GFX construct_block_size_descriptor_2d second part( 1884): took 2.401667ms for 0*0 texture 0
I/SELinux ( 3195): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3195 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3195): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Killing 2371:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,E/SELinux ( 3195): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GFX generate_partition_tables( 1884): took 6.329948ms for 0*0 texture 0
,I/GFX raster( 1884): took 11.000677ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1884): Bitmap=0xb78471c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7847348 counterpartCT=4 counterpartW=176 counterparth=144
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ScoverManager( 1884): registerListener
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_1678/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2302/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10136/pid_1508/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10113/pid_2154/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3195): TimaSignature is unavailable
,D/ActivityThread( 3195): Added TimaKeyStore provider
,E/Zygote  ( 3210): MountEmulatedStorage()
I/libpersona( 3210): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3210): v2
I/libpersona( 3210): KNOX_SDCARD not a persona
,I/SELinux ( 3210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3210 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3210): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2354/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2341/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2371/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3210): TimaSignature is unavailable
,D/ActivityThread( 3210): Added TimaKeyStore provider
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 17247(923KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 25MB/38MB, paused 2.189ms total 146.388ms
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1017): registerListenerCallback : binder = android.os.BinderProxy@1b24f13b, pid : 1884, uid : 1001, type : 1
E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,D/InCall  ( 1884): InCallPresenter -  - Finished InCallPresenter.setUp
,D/KnoxSetupWizardDbHelper( 3195): dbMigrationFlag : false
,I/sCloudBackupApp( 3174): sCloudBackupApp Version Info : 4.04.8.KK_APP
,I/PCWCLIENTTRACE_LOG( 3210): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3210): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 3210): new DMDBOpenHelper instance
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/Settings( 2977): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2977): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/[SBeam] ( 1288): SBeamEnabler.isSBeamSupported : [-1]
E/Zygote  ( 3231): MountEmulatedStorage()
E/Zygote  ( 3231): v2
I/libpersona( 3231): KNOX_SDCARD checking this for 10062
I/libpersona( 3231): KNOX_SDCARD not a persona
D/[SBeam] ( 1288): SBeamEnabler.isSBeamSupported : EXIST
I/SELinux ( 3231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/ShortcutReceiver( 3195):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1017): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3231 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2386:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/PCWCLIENTTRACE_DMContentProvider( 3210): [URIMatcher] - result : 2
,I/DBG_FMMDM( 3158): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3158): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3158): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/KnoxShortcutUtil( 3195): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3195):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3195):  shortcut migration not required 
,E/Tethering( 1017): No numeric data
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3231): TimaSignature is unavailable
,E/Tethering( 1017): No numeric data
D/ActivityThread( 3231): Added TimaKeyStore provider
,E/Tethering( 1017): No numeric data
,E/Zygote  ( 3248): MountEmulatedStorage()
I/libpersona( 3248): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3248): v2
I/libpersona( 3248): KNOX_SDCARD not a persona
I/SELinux ( 3248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3248 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2452:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2435:com.wsomacp/u0a25 (adj 15): empty #32
E/SELinux ( 3248): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3260): MountEmulatedStorage(),
E/Zygote  ( 3260): v2
I/libpersona( 3260): KNOX_SDCARD checking this for 1000
E/Tethering( 1017): No numeric data
I/libpersona( 3260): KNOX_SDCARD not a persona
,I/SELinux ( 3260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2480:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,E/SELinux ( 3260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3248): TimaSignature is unavailable
,D/ActivityThread( 3248): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3260): TimaSignature is unavailable
,D/ActivityThread( 3260): Added TimaKeyStore provider
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,I/ActivityManager( 1017): Killing 2500:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,W/NotificationAccessSettings( 1288): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,D/Volley  ( 2977): [371] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2977): [378] DiskBasedCache.clear: Cache cleared.
,W/ResourcesManager( 1288): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 29
,I/ActivityManager( 1017): Killing 2293:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_2386/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_2435/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_2452/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_2480/cgroup.procs: No such file or directory
,E/KnoxSetupWizardClient( 3260): isShipMode : 1
I/KnoxSetupWizardClient( 3260): onReceive : android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 1017): Killing 2628:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 1017): Exception when sending broadcast to ComponentInfo{com.sec.android.app.mt/com.sec.android.app.mt.StatusChecker}
W/BroadcastQueue( 1017): android.os.TransactionTooLargeException
W/BroadcastQueue( 1017): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1017): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1017): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1017): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1017): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1017): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/DBG_FMMDS( 3248): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,E/Zygote  ( 3284): MountEmulatedStorage()
E/Zygote  ( 3284): v2
I/libpersona( 3284): KNOX_SDCARD checking this for 1000
I/libpersona( 3284): KNOX_SDCARD not a persona
,I/SELinux ( 3284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/DBG_FMMDS( 3248): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3284 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3284): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ExternalOEMControlProvider( 3231): onCreate,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,V/GLSUser ( 1659): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     (  305): Explicit concurrent mark sweep GC freed 8809(375KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 24.368ms
D/TimaKeyStoreProvider( 3284): TimaSignature is unavailable
,D/ActivityThread( 3284): Added TimaKeyStore provider
,D/Finsky  ( 2977): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 2977): [1] 2.run: Finished loading 1 libraries.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 34.585ms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_2500/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2293/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2628/cgroup.procs: No such file or directory
,I/NotificationStore( 1659): System rebooted after Notification storage file was last written,
I/NotificationStore( 1659): Deleting the file
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 727us total 47.988ms
,D/Finsky  ( 2977): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/Zygote  ( 3302): MountEmulatedStorage(),
I/libpersona( 3302): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3302): v2
I/libpersona( 3302): KNOX_SDCARD not a persona
I/SELinux ( 3302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/ActivityManager( 1017): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3302 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/System.err( 3260): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
D/PCWCLIENTTRACE_DMContentProvider( 3210): [URIMatcher] - result : 2
W/System.err( 3260): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3260): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3260): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3260): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3260): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3260): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ScoverManager( 1288): serviceVersion : 16908288
,D/TimaKeyStoreProvider( 3302): TimaSignature is unavailable
D/ActivityThread( 3302): Added TimaKeyStore provider
,V/GmsCoreStatsServiceLauncher( 1948): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/SettingsProvider( 1017): name = PREVIOUS_SYS_TIME
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1017): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/StatusChecker( 3284): onReceive : android.intent.action.BOOT_COMPLETED
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/StatusChecker( 3284): onReceive : net.mt.init : DONE
,E/DBG_FMMDS( 3248): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,W/ResourcesManager( 3302): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4183, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/DBG_FMMDS( 3248): [50.18.150420][Line:43][xdbDBInit] 
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3324 uid=10116 gids={50116, 9997} abi=armeabi-v7a
E/Zygote  ( 3324): MountEmulatedStorage()
E/Zygote  ( 3324): v2
I/libpersona( 3324): KNOX_SDCARD checking this for 10116
I/libpersona( 3324): KNOX_SDCARD not a persona
,I/SELinux ( 3324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3324): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Finsky  ( 2977): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ServiceMode( 3302): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3302): setReferenceIsDumpState : 0
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BluetoothAdapter( 2532): disable()
,D/PowerUI ( 1177): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1177): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/TimaKeyStoreProvider( 3324): TimaSignature is unavailable
,D/ActivityThread( 3324): Added TimaKeyStore provider
,E/BluetoothManagerService( 1017): Bluetooth is already disabled. DO NOT disable again.
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: false pid=2532, uid=10176
,D/SettingsProvider( 1017): name = wifi_on
,I/jxcore-log( 2532): ****TEST TOOK:  5064  ms ****
I/jxcore-log( 2532): 
,I/jxcore-log( 2532): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2532): 
,E/Zygote  ( 3341): MountEmulatedStorage()
E/Zygote  ( 3341): v2
I/libpersona( 3341): KNOX_SDCARD checking this for 1000
I/libpersona( 3341): KNOX_SDCARD not a persona
I/SELinux ( 3341): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3341): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3341): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3341 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2611:com.android.calendar/u0a135 (adj 15): empty #31
,I/DBG_FMMDS( 3248): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
I/ActivityManager( 1017): Killing 2692:com.android.keychain/1000 (adj 15): empty #31
,D/PersistentNotificationBroadcastReceiver( 1659): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/DBG_FMMDS( 3248): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3248): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3248): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3248): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3248): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3248): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/PageBuddyNotiSvc( 3324): Intent received : action=android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3341): TimaSignature is unavailable
,D/ActivityThread( 3341): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 2727:flipboard.boxer.app/u0a99 (adj 15): empty #31
,I/FOTA_Client( 3039): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/ContextImpl( 3324): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 3324): onCreate mCpBitFlag=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/FOTA_Client( 3039): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2692/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_2611/cgroup.procs: No such file or directory
,E/Zygote  ( 3366): MountEmulatedStorage()
I/libpersona( 3366): KNOX_SDCARD checking this for 10125
E/Zygote  ( 3366): v2
I/libpersona( 3366): KNOX_SDCARD not a persona
,I/SELinux ( 3366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3366 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 3366): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NPS_WSSNPS( 3341): [] android.intent.action.BOOT_COMPLETED
W/ContextImpl( 3341): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3377): MountEmulatedStorage()
,I/libpersona( 3377): KNOX_SDCARD checking this for 10014
E/Zygote  ( 3377): v2
I/libpersona( 3377): KNOX_SDCARD not a persona
I/SELinux ( 3377): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 3366): TimaSignature is unavailable
D/ActivityThread( 3366): Added TimaKeyStore provider
I/ActivityManager( 1017): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3377 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2210:flipboard.app/u0a98 (adj 15): empty #31
,I/SELinux ( 3377): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3377): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3341): [] Service onCreate!!
,D/TimaKeyStoreProvider( 3377): TimaSignature is unavailable
D/ActivityThread( 3377): Added TimaKeyStore provider
,I/LockPatternUtils( 1288): isSmartCardAuthenticationAvailable: false
,E/Zygote  ( 3396): MountEmulatedStorage()
,E/Zygote  ( 3396): v2
I/libpersona( 3396): KNOX_SDCARD checking this for 1000
I/libpersona( 3396): KNOX_SDCARD not a persona
,I/SELinux ( 3396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3396 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3396): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3366): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3366): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3366): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Settings_Utils( 1288): isSupportVNFestival SM-A500FU XEO
,D/NPS_WSSNPS( 3341): [50.150321] NpsServiceTask Start
,D/TimaKeyStoreProvider( 3396): TimaSignature is unavailable
,D/ActivityThread( 3396): Added TimaKeyStore provider
,D/NPS_WSSNPS( 3341): [50.150321] smlDBHelper
,V/OneTimeInitializerReceiver( 3377): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2941): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/ActivityManager( 1017): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3417 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 3417): MountEmulatedStorage()
I/libpersona( 3417): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3417): v2
I/libpersona( 3417): KNOX_SDCARD not a persona
I/SELinux ( 3417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3417): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AndroidRuntime( 3361): 
D/AndroidRuntime( 3361): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3361): CheckJNI is OFF
D/AndroidRuntime( 3361): readGMSProperty: start
D/AndroidRuntime( 3361): readGMSProperty: already setted!!
D/AndroidRuntime( 3361): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3361): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3361): readGMSProperty: end
D/AndroidRuntime( 3361): addProductProperty: start
,V/OneTimeService( 3377): OneTimeService.onHandleIntent
,D/TimaKeyStoreProvider( 3417): TimaSignature is unavailable
,D/ActivityThread( 3417): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 2761:com.sec.usbsettings/1000 (adj 15): empty #31
,W/InstanceID/Rpc( 1948): Found 10012
,D/QuickConnect( 3366): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
D/QuickConnect( 3366): Util.setSCRunningSetting - [value]0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/SettingsProvider( 1017): name = scon_is_running
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed,
D/SettingsProvider( 1017): selectionArgs: false
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
D/SettingsProvider( 1017): selectionArgs: 10125
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/NPS_WSSNPS( 3341): [50.150321] AsyncBulkFlagCheck
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/NPS_WSSNPS( 3341): [50.150321] IsRemain_AsyncBulkCheck
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_2727/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_2210/cgroup.procs: No such file or directory
I/NPS_WSSNPS( 3341): [50.150321] IsRemain_Asyncing nothing
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2761/cgroup.procs: No such file or directory
W/ContextImpl( 3341): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3451): MountEmulatedStorage()
I/libpersona( 3451): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3451): v2
I/libpersona( 3451): KNOX_SDCARD not a persona
I/SELinux ( 3451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3451 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3451): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/AffinityControl( 3361): AffinityControl: registerfunction enter
,D/NPS_WSSNPS( 3341): [50.150321] Service onDestroy
I/QuickConnect( 3366): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,D/TimaKeyStoreProvider( 3451): TimaSignature is unavailable
D/ActivityThread( 3451): Added TimaKeyStore provider
,V/Finsky  ( 2977): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/SettingsProvider( 1017): name = access_control_enabled
,I/QuickConnect( 3366): PeriphStartReceiver.onReceive - no need to start
,I/NPS_WSSNPS( 3341): [50.150321] smlBRConfigurationDelete
D/AndroidRuntime( 3361): Calling main entry com.android.commands.pm.Pm
,I/NPS_WSSNPS( 3341): [50.150321] smlBRMessageDelete
I/NPS_WSSNPS( 3341): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3341): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3341): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3341): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3341): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3341): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3341): [50.150321] cpuBooster release : false
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): START PACKAGE DELETE: observer{739591316}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
,D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0,
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10176, uninstall pkg
,E/Zygote  ( 3470): MountEmulatedStorage()
E/Zygote  ( 3470): v2
I/libpersona( 3470): KNOX_SDCARD checking this for 10131
I/libpersona( 3470): KNOX_SDCARD not a persona
I/SELinux ( 3470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3470 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2318:com.android.mms/u0a46 (adj 15): empty #31,
I/SELinux ( 3470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3470): TimaSignature is unavailable
,D/ActivityThread( 3470): Added TimaKeyStore provider
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 30
,W/PackageSettings( 1017): Skipping PackageSetting{4ecb16 com.test.thalitest/10175} due to missing metadata
,D/CountryDetector( 1017): No listener is left
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3487): MountEmulatedStorage()
,E/Zygote  ( 3487): v2
I/libpersona( 3487): KNOX_SDCARD checking this for 10069
I/libpersona( 3487): KNOX_SDCARD not a persona
I/SELinux ( 3487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3487 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2830:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,I/SELinux ( 3487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Force stopping com.example.hello appid=10176 user=-1: uninstall pkg
,E/SELinux ( 3487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2532:com.example.hello/u0a176 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1017): Force removing ActivityRecord{23177c87 u0 com.example.hello/.MainActivity t228}: app died, no saved state
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/FocusedStackFrame( 1017): Set to : 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 2532
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,D/TimaKeyStoreProvider( 3487): TimaSignature is unavailable
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/ActivityThread( 3487): Added TimaKeyStore provider
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,E/USB_UICC(  296): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  296): usb_uicc_init_qmi failed ! 
I/USB_UICC(  296): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  296): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/FileApkUtils( 1948): Spent 101ms computing apk sha1.
D/FileApkUtils( 1948): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1948): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/Launcher( 1491): onRestart, Launcher: 799856556
,D/DexOptUtils( 1948): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1948): Lollipop platform, using <isa> directory.
D/DexOptUtils( 1948): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1948): Primary ABI of odexing process is armeabi-v7a
,W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_2318/cgroup.procs: No such file or directory
,W/ResourcesManager( 3470): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3470): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3470): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3470): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10176 user=0: pkg removed
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3451): onCreate
,I/dex2oat ( 3508): ----------------------------------------------------
I/dex2oat ( 3508): <SS>: S T A R T I N G . . .
I/dex2oat ( 3508): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3508): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/SBrowserFeatureFlag( 3470): initialized in static block : loadCscFeatureValue() succeed! 
,I/FactoryTestApp( 2646): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2935)  
,D/ManifestProvider( 3470): onCreate()
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1777): mOCRHelper is null
,I/Hs20UtilService( 3451): Starting #1
,W/GeofencerStateMachine( 1768): Ignoring removeGeofence because network location is disabled.
,I/Hs20UtilService( 3451): Message received 5003
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
W/ResourcesManager( 1462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,E/Zygote  ( 3518): MountEmulatedStorage()
,E/Zygote  ( 3518): v2
I/libpersona( 3518): KNOX_SDCARD checking this for 10019
I/libpersona( 3518): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3518 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3518): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  305): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 23.348ms,
,D/TimaKeyStoreProvider( 3518): TimaSignature is unavailable
,D/ActivityThread( 3518): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 682us total 17.206ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 16.720ms
,D/Launcher( 1491): onStart, Launcher: 799856556
D/Launcher.HomeView( 1491): onStart
,D/Launcher( 1491): onResume, Launcher: 799856556
,D/SettingsProvider( 1017): name = kids_home_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/NPS_WSSNPS( 3341): [50.150321] dsServerSocket close
D/SettingsProvider( 1017): ret = -1
,I/ActivityManager( 1017): Killing 2746:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
D/RegisteredComponentCache( 1449): Collect Tech packages for Knox
D/Launcher.HomeView( 1491): onResume
,D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/FileShare-Server( 3487): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/PersonaManager( 1449): isKioskContainerExistOnDevice
,E/NetworkSettingsReceiver( 3470): onReceive: android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 1017): Killing 2820:com.sec.dsm.system/1000 (adj 15): empty #31
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/MenuAppsGridFragment( 1491): onResume
,D/ActivityManager( 1017): handle home activity for 0
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/RCPManagerService( 1017): PackageReceiver onReceive()
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10176 container id = 0
,I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10176
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/InputDispatcher( 1017): Focus entered window: 1491
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1491): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 2532 uid 10176
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=228_task.xml
,E/SBrowserFeatureFlag( 3470): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2facd7ac
,D/SBrowserFeatureFlag( 3470): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3470): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/PersonaManager( 1449): isKioskContainerExistOnDevice
,D/SamsungIME( 1777): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3547 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/Zygote  ( 3547): MountEmulatedStorage()
I/libpersona( 3547): KNOX_SDCARD checking this for 10135
E/Zygote  ( 3547): v2
I/libpersona( 3547): KNOX_SDCARD not a persona
,I/SELinux ( 3547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Killing 2857:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,I/SELinux ( 3547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3518): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Dec 15 15:21:24 GMT+01:00 2015
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.5.183: ( 3518): KLMSAbstractReciever(): onReceive().END.
,D/TimaKeyStoreProvider( 3547): TimaSignature is unavailable
,D/ActivityThread( 3547): Added TimaKeyStore provider
,D/RegisteredServicesCache( 1449): empty dynamic service
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1017): [SO] activate (ident=0xb7a8d918, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb7a8d918, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/KLMS-2.5.183: ( 3518): KLMSIntentService(): onCreate()
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10176
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,I/KLMS-2.5.183: ( 3518): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/PanelView( 1177): There is/are notification(s) 
,E/Zygote  ( 3563): MountEmulatedStorage(),
I/ActivityManager( 1017): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3563 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,E/Zygote  ( 3563): v2
,I/libpersona( 3563): KNOX_SDCARD checking this for 10022
I/libpersona( 3563): KNOX_SDCARD not a persona
,I/SELinux ( 3563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/KLMS-2.5.183: ( 3518): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SELinux ( 3563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/KLMS-2.5.183: ( 3518): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/SELinux ( 3563): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3547): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3547): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3547): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3518): KLMSIntentService(): BOOT_COMPLETED
,I/DBG_DM  ( 2941): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/TimaKeyStoreProvider( 3563): TimaSignature is unavailable
,D/ActivityThread( 3563): Added TimaKeyStore provider
,I/LockPatternUtils( 1288): isSmartCardAuthenticationAvailable: false
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/RlzPingService( 3417): Setting next ping for 1450794084589
,I/KLMS-2.5.183: ( 3518): KLMSIntentService(): onDestroy()
,I/ActivityManager( 1017): Killing 2876:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Displayed Component not be shown by security: +759ms
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1017): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 3590): MountEmulatedStorage()
E/Zygote  ( 3590): v2
E/SMD     (  288): DCD OFF
I/libpersona( 3590): KNOX_SDCARD checking this for 1000
,I/libpersona( 3590): KNOX_SDCARD not a persona
,I/SELinux ( 3590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3590 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 3590): TimaSignature is unavailable
,D/ActivityThread( 3590): Added TimaKeyStore provider
D/SensorService( 1017): [SO] currT = 37321079000, prevT = 36901168000, diff = 419911000, [0.172 0.134 10.228]
D/SensorService( 1017): [SO] 0.172 0.134 10.228
D/SensorService( 1017): [SO] [100 -> 255]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 44972(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 26MB/39MB, paused 3.429ms total 610.306ms
,I/art     ( 1017): WaitForGcToComplete blocked for 122.731ms for cause Explicit
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 1017): delete codoeFile: 
,E/Zygote  ( 3607): MountEmulatedStorage()
E/Zygote  ( 3607): v2
I/libpersona( 3607): KNOX_SDCARD checking this for 1000
I/libpersona( 3607): KNOX_SDCARD not a persona
,I/SELinux ( 3607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3607 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10176, packageName = com.example.hello
,I/AASA_removePackage( 1017): UID=10176 Target=com.example.hello
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1017): result of delete: 1{739591316}
,D/TimaKeyStoreProvider( 3607): TimaSignature is unavailable
,D/ActivityThread( 3607): Added TimaKeyStore provider
,D/AndroidRuntime( 3361): Shutting down VM
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3622): MountEmulatedStorage()
,E/Zygote  ( 3622): v2
I/libpersona( 3622): KNOX_SDCARD checking this for 10139
I/libpersona( 3622): KNOX_SDCARD not a persona
,I/SELinux ( 3622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3622 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2915:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/SELinux ( 3622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 3622): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3631 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 3631): KNOX_SDCARD checking this for 10042
E/Zygote  ( 3631): MountEmulatedStorage()
I/libpersona( 3631): KNOX_SDCARD not a persona
E/Zygote  ( 3631): v2
I/SELinux ( 3631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 3631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3631): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 3622): TimaSignature is unavailable
,D/ActivityThread( 3622): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3631): TimaSignature is unavailable
,D/ActivityThread( 3631): Added TimaKeyStore provider
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{16e9663 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t227} time:37599
,W/ResourcesManager( 3622): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3622): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3622): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3622): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3622): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 3590): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Choreographer( 1491): Skipped 46 frames!  The application may be doing too much work on its main thread.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,D/WallpaperManager( 1491): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1491): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 10642(516KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 3.479ms total 323.698ms
,D/GCM     ( 1948): COMPAT: Multi user not supported
,I/Timeline( 1491): Timeline: Activity_idle id: android.os.BinderProxy@30d422f0 time:37669
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/art     ( 3361): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/MTPRx   ( 3607): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 3631): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Zygote  ( 3655): MountEmulatedStorage()
I/libpersona( 3655): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3655): v2
I/libpersona( 3655): KNOX_SDCARD not a persona
I/SELinux ( 3655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3655 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
I/SELinux ( 3655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
D/SecContentProvider2( 1017): mCursor = null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1017): mCursor = null
,V/MTPRx   ( 3607): sealedState: false
V/MTPRx   ( 3607): sealedUsbMassStorageState: false
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1017): name = mtp_usb_connection_status
,D/GCM     ( 1659): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1017): name = media_player_mode
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met,
,I/ActivityManager( 1017): Killing 2899:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = mtp_running_status
,D/TimaKeyStoreProvider( 3655): TimaSignature is unavailable
,D/ActivityThread( 3655): Added TimaKeyStore provider
,D/SettingsProvider( 1017): name = media_mount_count
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1017): name = mtp_sync_alive
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/Zygote  ( 3676): MountEmulatedStorage(),
E/Zygote  ( 3676): v2
I/libpersona( 3676): KNOX_SDCARD checking this for 10145,
I/libpersona( 3676): KNOX_SDCARD not a persona,
I/SELinux ( 3676): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3676 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 3676): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3676): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3655): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/CheckinService( 1948): Disabling old GoogleServicesFramework version
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3676): TimaSignature is unavailable
,D/ActivityThread( 3676): Added TimaKeyStore provider
,D/SettingsProvider( 1017): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = boot_time_connected
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ResourcesManager( 3676): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 3676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3676): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/UsbSettingsManager( 1017): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1017): onPackageRemoved : com.example.hello
,I/GCoreUlr( 1948): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}],
,I/CalendarProvider2( 3631): CalendarProvider2.onCreate() called
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_2830/cgroup.procs: No such file or directory
,D/SystemUpdateService( 1948): onCreate
,W/libprocessgroup( 1017): failed to open /acct/uid_10085/pid_2746/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2820/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2857/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2876/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2915/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2941): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,W/libprocessgroup( 1017): failed to open /acct/uid_10086/pid_2899/cgroup.procs: No such file or directory
,I/CheckinService( 1948): Checking schedule, now: 1450189285463 next: 1450532165529
,I/CheckinService( 1948): active receiver: disabled
,D/SystemUpdateService( 1948): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/SettingsProvider( 1017): name = mtp_open_session
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1659): onCreate
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/ConfigFetchService( 1948): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/PCWCLIENTTRACE_PushUtil( 3210): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3210): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3210): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3210): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3210): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3210): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1768): DispatchingService.onCreate()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ContextImpl( 1288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/AuthZen ( 1948): Handling intent: android.intent.action.BOOT_COMPLETED
,D/TimaService( 1017): TIMA: in getTimaVersion
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/ActivityManager( 1017): Killing 2958:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/TimaService( 1017): TIMA3: KeyStore3_init
E/TLC_TZ_KEYSTORE: ( 1017): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1017): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1017): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1017): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1017): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1017): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/AuthZenEventHandler( 1948): Handling event: android.intent.action.BOOT_COMPLETED
,W/PCWCLIENTTRACE_PCWHandler( 3210): [ensureRegistration] - netwrok is not available. action ignored
,W/ContextImpl( 1288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3710): MountEmulatedStorage(),
I/ActivityManager( 1017): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3710 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2998:com.sec.esdk.elm/u0a94 (adj 15): empty #31
E/Zygote  ( 3710): v2
I/libpersona( 3710): KNOX_SDCARD checking this for 10031
I/libpersona( 3710): KNOX_SDCARD not a persona
,I/SELinux ( 3710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/SELinux ( 3710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
D/QSEECOMAPI: ( 1017): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1017): ctx = 0xb7c67a90, comm = 0xb7b42170, sendmsg = 0xa0b7c000, recvmsg = 0xa0b7c440,
I/TZ_init: ( 1017): TZ_init: sending initialization request...
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/TZ_init: ( 1017): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1017): trustlet initialization failed
I/TZ_init: ( 1017): TZ_init_START...,
,E/SELinux ( 3710): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/TZ_init: ( 1017): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1017): TZ_init: successful initialization
D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 8
E/TLC_TZ_KEYSTORE: ( 1017): Count : 1, Ret : 0
,I/SettingSearch/SearchIntentReceiver( 1288): InitSerachDBThread thread end!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SystemUpdateService( 1948): cancelUpdate (empty URL)
D/TimaKeyStoreProvider( 3710): TimaSignature is unavailable
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityThread( 3710): Added TimaKeyStore provider
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,I/SystemUpdateService( 1948): active receiver: disabled
,W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_2958/cgroup.procs: No such file or directory
,E/dex2oat ( 3508): Failed to write Failed to write Fai for /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex: Bad file number
E/dex2oat ( 3508): Unable to write to file /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
E/dex2oat ( 3508): Failed to write ELF file /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/art     ( 1768): Explicit concurrent mark sweep GC freed 12523(763KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 1.082ms total 178.844ms
,E/dex2oat ( 3508): Failed to create oat file: /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
,W/libprocessgroup( 1017): failed to open /acct/uid_10094/pid_2998/cgroup.procs: No such file or directory
,W/BaseAppContext( 1948): Using Auth Proxy for data requests.
,D/FactoryTestApp( 2646): [DummyFtClient$onDestroy](2646) Destroy DummyFtClient service,
,D/FactoryTestApp( 2646): [Support$Values.getString](2646) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2646): [ModuleCommon$isConnectionModeNone](2646) mConnectionMode = gsm
,I/FactoryTestApp( 2646): [ModuleCommon$isRunningFtClient](2646) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2646): [DummyFtClient$onDestroy](2646) kill process
,I/Process ( 2646): Sending signal. PID: 2646 SIG: 9
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/SQLiteLog( 3676): (28) failed to open "/data/data/com.android.email/databases/EmailProvider.db" with flag (131138) and mode_t (0) due to error (30)
,W/ResourcesManager( 3710): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/art     ( 1659): Explicit concurrent mark sweep GC freed 19563(1157KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 10MB/16MB, paused 990us total 47.307ms
,I/AMMetaDataParserService( 3590): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3590): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3590): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3590): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3590): Resource data:2131165186
,D/ChimeraCfgMgr( 1948): Loading module com.google.android.gms.kids from APK com.google.android.gms

```
