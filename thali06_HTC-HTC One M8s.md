#### Test 61703351926082e_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  960): acquireWL(af8317a): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 2958 10069 null
D/PMS     (  960): acquireWL(249fc588): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 2958 10069 null
--------- beginning of main
D/TodoTaskshortcut( 2958): update TASK shortcut>
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
D/PMS     (  960): releaseWL(af8317a): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
I/ActivityManager(  960): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=2984 uid=10035 gids={50035, 9997} abi=arm64-v8a
,I/TodoTaskNotifyService( 2958): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  960): releaseWL(249fc588): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 2958): stopSelfResult true
I/ActivityManager(  960): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3008 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Messaging( 2836): supportCMAS(SIE)/init? false/true
D/MmsConfig( 2836): networkCode: 
D/MessageCustFlag( 2836): sku_id=118
D/MmsConfig( 2836): SIE smsPri: null
D/MmsConfig( 2836): networkCode: 
D/MmsConfig( 2836): packageName: com.htc.vvm.att does not exist
D/Messaging( 2836): mNeedToUpdateDate2 start
D/ReportIndicatorCache( 2836): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 2836): 
D/MmsAsyncWorkHandler( 2836): HM tk = 20001
D/ReportIndicatorCache( 2836): MSG_QUERY_REPORTS >>
D/SettingsManager( 2836): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2f2086ec
D/SMSBackup( 3008): Got a database change event
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1471):  slotId = -1000
D/MmsSmsV2Provider( 1471): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
E/SQLiteLog( 1471): (284) automatic index on pending_msgs(msg_id)
E/SQLiteLog( 1471): (284) automatic index on sqlite_sq_556057B070(thread_id)
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1471):  slotId = -1000
D/MmsSmsV2Provider( 1471): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 2836): [DraftCache/1] DraftCache.constructor
D/DraftCache( 2836): [DraftCache/1] refresh
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
I/Messaging( 2836): mccmnc> 
D/MmsConfig( 2836): networkCode: 
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1471): sku_id=118
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1471):  slotId = -1000
D/MmsSmsV2Provider( 1471): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 2836): ViewCache CreatePreloadOnlyConversationList
D/DraftCache( 2836): [DraftCache/56] rebuildCache
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
D/Process (  960): killProcessQuiet, pid=2526
I/ActivityManager(  960): Killing 2526:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1471):  slotId = -1000
D/MmsSmsV2Provider( 1471): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 2836): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/Messaging( 2836): mNeedToUpdateDate2: false
D/MessageCustFlag( 2836): sense_version=6.0
D/Jerry   ( 2836): start to preload cursor >>>>>>>
E/cutils-trace( 3028): Error opening trace file: Permission denied (13)
D/MessagingNotification( 2836): New incoming message, can't cancel notification now
D/MessagingNotification( 2836): newMsgCnt: 0, false
D/CustomizationManager( 3028): ====startRecUseTime====
D/htc.customization.log.level( 3028):  is 
W/CustomizationLogLevel( 3028): Level value is invalid, use default level 2
I/ActivityManager(  960): Recipient 2526
V/IccIntentReceiver( 1633): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT icc slot: 0
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/Jerry   ( 1471): URI_DRAFT
I/SIMStateChangeReceiver( 2049): SIM state: ABSENT
I/SIMStateChangeReceiver( 2049): remove notification
D/PhoneStorageUtil( 2836): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 2836): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 2836): createReceiver
D/DraftCache( 2836): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 2836): [DraftCache/56] rebuildCache time: 8
D/MmsAsyncWorkHandler( 2836): 
D/MmsAsyncWorkHandler( 2836): HM tk = 20002
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/MmsSmsV2Provider( 1471):  slotId = -1000
E/SQLiteLog( 1471): (284) automatic index on pending_msgs(msg_id)
E/SQLiteLog( 1471): (284) automatic index on sqlite_sq_556059DC20(thread_id)
D/TelephUtils( 1471): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
V/MmsProvider( 1471): Update uri=content://mms, match=0
V/MmsProvider( 1471): selection=st=129 AND m_type!=134
D/MmsSmsDatabaseHelper( 1471): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,recipient_address TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,body TEXT,name TEXT,priority INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0) result: true
D/FlexNetS( 2049): updateSvcAllowedInSettings:false
D/MmsSmsDatabaseHelper( 1471): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1471): sku_id=118
D/MmsSmsDatabaseHelper( 1471): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,ExtraUri TEXT,vCALs INTEGER,vCALe INTEGER,_data TEXT,text TEXT) result: true
D/MmsSmsDatabaseHelper( 1471): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, htc_category INTEGER DEFAULT 0,cs_timestamp LONG DEFAULT -1, cs_id TEXT, cs_synced INTEGER DEFAULT 0, seen INTEGER DEFAULT 0, extra INTEGER DEFAULT 0, phone_type INTEGER DEFAULT 0, date2 INTEGER DEFAULT 0, smilext TEXT, text_only INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0) result: true
D/MmsSmsDatabaseHelper( 1471): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/Messaging( 2836): Reset downloading state: 0
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/AccFlag ( 1471): sku_id=118
V/MmsSystemEventReceiver( 2836): TransactionService is going to be woken up.
D/Messaging( 2836): ViewCache CreatePreload
D/Messaging( 2836): ViewCache CreatePreloadOnlyMultipleOpsList
D/ExchangePolicystatus( 2836): onReceive()
D/ExchangePolicystatus( 2836): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2836): onReceive(): else
D/CustomizationManager( 3028):  Read ACC file spent 0.034 (s)
D/SmsReceiver( 2836): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/CIDMapFileReader( 3028): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3028): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3028): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3028): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3028): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3028): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3028): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3028): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 3028): Parsing tag category name = system
V/TransactionService( 2836): 1-Creating TransactionService
I/CustomizationCIDLoader( 3028): Parsing tag category name = application
I/CustomizationCIDLoader( 3028): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3028): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3028): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3028): Parsing tag category name = Settings
D/AutoSetting( 1421): receiver - intent: android.intent.action.USER_PRESENT
I/CustomizationCIDLoader( 3028): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3028): add string-array item, value = 42507
I/CustomizationCIDLoader( 3028): add string-array item, value = 21902
I/CustomizationCIDLoader( 3028): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 3028): add string-array item, value = 23420
I/CustomizationCIDLoader( 3028): add string-array item, value = 22299
I/CustomizationCIDLoader( 3028): add string-array item, value = 24002
I/CustomizationCIDLoader( 3028): add string-array item, value = 23210
I/CustomizationCIDLoader( 3028): add string-array item, value = 23205
I/CustomizationCIDLoader( 3028): add string-array item, value = 23806
I/CustomizationCIDLoader( 3028): add string-array item, value = 23430
I/CustomizationCIDLoader( 3028): add string-array item, value = 23408
I/CustomizationCIDLoader( 3028): add string-array item, value = 27205
I/CustomizationCIDLoader( 3028): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 3028): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 3028):  Read CID file spent 0.103 (s)
D/Cust_MMSMS( 2836): _has_set_default_values_2=true
D/CustomizationManager( 3028):  All configurations done spent 0.103 (s)
V/TransactionService( 2836): onStartCommand: 1
D/MmsSystemEventReceiver( 2836): unRegisterForConnectionStateChanges
V/TransactionService( 2836): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 2836): Loading previous transactions.
I/ActivityManager(  960): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=3063 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/MsgPreferenceUtils( 2836): def_index: 0
D/AutoSetting( 1421): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1471): device_type: 1
D/MsgPreferenceUtils( 2836): globalIndex = 1
D/TransactionService( 2836): Force clearing mTransactionList
D/TransactionService( 2836): Force set service start id to 1
V/TransactionService( 2836): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 2836): unRegisterForConnectionStateChanges
D/TransactionService( 2836): stopSelfResult: true, mLastHandledServiceId: 1
D/MsgPreferenceUtils( 2836): phone state: true
D/MsgPreferenceUtils( 2836): sd state: false
D/MsgPreferenceUtils( 2836): vIndex = 0
V/TransactionService( 2836): Destroying TransactionService
V/TransactionService( 2836): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1525): loadItems() com.htc.launcher.pageview.WidgetManager@1f2bb889 +
I/Prism.WidgetManager( 1525): onLoadItems() +
I/Prism.ItemManager( 2434): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 2434): loadItems() com.htc.launcher.pageview.WidgetManager@3c55489e +
I/Prism.WidgetManager( 2434): onLoadItems() +
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 3028 on display 0
D/PMS     (  960): acquireHCC(3105f4da): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 960 1000 null
D/PMS     (  960): acquireHCC(2abfdd0b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 960 1000 null
W/asset   (  960): Copying FileAsset 0x55608b29e0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  960): acquireWL(355e84a6): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 960 1000 null
I/AnimationUtil(  960): isHTCRecent(HelloWorld/Recent screens.)/6
I/FeedHostManager( 1525): [onPause]
I/FeedProviderManager( 1525): onPause
I/FeedHostManager( 1525): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3f354535
I/SocialFeedProvider( 1525): +onPause
I/SocialFeedProvider( 1525): -onPause
W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 3063): -onCreate()
I/ActivityManager(  960): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3098 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ResourcesManager( 1525): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 2434): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/Settings:HtcSettingsApplication( 3063): [3063/3063] onCreate()
D/TetherSettings( 3063): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3063): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3063): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3063): Cust_ConnectToPC   : spcsc>false
D/        ( 3063): Cust_ConnectToPC   : IPT>true
D/        ( 3063): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3063): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/asset   ( 3098): Copying FileAsset 0xac046870 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/SmartNS_Utility( 3063): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3063): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3063): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3063): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3063): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_PSService( 3063): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3063): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3063):  defaultType:0
D/StatusBarManagerService(  960): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
I/ActivityManager(  960): Killing 2559:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=2559
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/TrimMemoryManager( 1525): [trimMemory] 20
I/WebViewFactory( 3098): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/ActivityManager(  960): Recipient 2559
W/ResourcesManager( 1525): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2434): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  960): Killing 2572:com.htc.zero:re_proc/u0a110 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=2572
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/LibraryLoader( 3098): Time to load native libraries: 10 ms (timestamps 9123-9133)
I/LibraryLoader( 3098): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3098): Binding Chromium to main looper Looper (main, tid 1) {18b3859f}
I/LibraryLoader( 3098): Expected native library version number "",actual native library version number ""
I/chromium( 3098): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/asset   ( 1525): Copying FileAsset 0x5560972740 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
I/BrowserStartupController( 3098): Initializing chromium process, singleProcess=true
W/asset   ( 2434): Copying FileAsset 0x55605404f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
W/art     ( 3098): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3098): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  960): Recipient 2572
I/Prism.WidgetManager( 1525): onLoadItems() -
I/Prism.ItemManager( 1525): loadItems() com.htc.launcher.pageview.WidgetManager@1f2bb889 -
W/chromium( 3098): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
I/Prism.WidgetManager( 2434): onLoadItems() -
I/Prism.ItemManager( 2434): loadItems() com.htc.launcher.pageview.WidgetManager@3c55489e -
W/chromium( 3098): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3098): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3098): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3098): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 3098): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 3098): Build Date: 03/09/15 Mon
I/Adreno-EGL( 3098): Local Branch: 
I/Adreno-EGL( 3098): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 3098): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 3098):                  d74aa161a12b9c6fc6332151
D/PhoneApp( 1471): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1471): -- N1 =0
D/PhoneApp( 1471): -- N2 =0
D/PhoneApp( 1471): -- N3 =0
W/System.err(  960): java.lang.Throwable: stack dump
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c061efb:true
D/BluetoothAdapter( 3098): 850748746: getState() :  mService = null. Returning STATE_OFF
D/DotMatrix( 2101): [CoverService] onDestroy, version: 1.3
I/SensorManager( 2101): unregisterListenerImpl++: listener = com.htc.dotmatrix.CoverService$7@3bb63ec0
W/SensorService(  960): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  960): disable: get sensor name = CM36686 Proximity sensor
V/UserPresentBroadcastReceiver( 1775): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
W/SensorService(  960): pid=2101, uid=10041
W/SensorService(  960): Active sensors: size = 3
W/SensorService(  960): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  960): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  960): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  960): SensorService::listenerSensor++: mName = com.htc.dotmatrix.CoverService$7@3bb63ec0, eanble = 0, strlen(mName) = 41
W/SensorService(  960): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  960): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@2325b4e6
W/SensorService(  960): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3cafb9c9
W/SensorService(  960): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 2101): [CoverService] unregisterCallContentObserver()
D/Process (  960): killProcessQuiet, pid=2101
I/ActivityManager(  960): Killing 2101:com.htc.dotmatrix/u0a41 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  960): Recipient 2101
V/IccIntentReceiver( 1633): IccIntent: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED icc state: null icc slot: 0
I/ActivityManager(  960): Start proc com.htc.showme for broadcast com.htc.showme/.update.MobileNetworkTurnOnReceiver: pid=3141 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/art     ( 3098): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3098): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3098): CordovaWebView is running on device made by: HTC
E/SQLiteLog( 1882): (283) recovered 100 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
I/[AppShowMeDebug]MobileNetworkTurnOnReceiver( 3141): onReceive statefalse
D/Process (  960): killProcessQuiet, pid=2485
I/ActivityManager(  960): Killing 2485:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/Scheduler( 1882): Use PeriodicScheduler
I/ActivityManager(  960): Recipient 2485
I/ActivityManager(  960): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=3164 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/art     ( 3098): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3098): Attempt to remove local handle scope entry from IRT, ignoring
W/InstanceID/Rpc( 1882): Found 10024
I/art     (  409): Explicit concurrent mark sweep GC freed 8632(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 280us total 25.952ms
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 238us total 20.057ms
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 127us total 17.518ms,
,W/chromium( 3098): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FindExtension( 3098): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 3098): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3d79b508, mServedView=org.apache.cordova.engine.SystemWebView{e2ab4a1 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@20be26c6
,I/InputMethodManagerService(  960): Disable input method client, pid=1525
I/htcbackup-core( 3164): ModelRegistry: Loading model meta data from resources...
D/StatusBarManagerService(  960): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  960): Enable input method client, pid=3098
,I/PhoneStatusBar( 1224): setImeWindowStatus(false,false)
,I/ActivityManager(  960): Displayed com.example.hello/.MainActivity: +1s121ms
W/XT9_C   ( 1354): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1354): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1354): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1354): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/PMS     (  960): releaseWL(355e84a6): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/htcbackup-core( 3164): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF,
I/htcbackup-core( 3164): SuperSaverModeReceiver: going to send resume event
,I/htcbackup-core( 3164): BackupRestoreManager: onHandleIntent,
,D/PMS     (  960): acquireWL(1af2d451): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 960 1000 null
,I/htcbackup-core( 3164): BackupRestoreManager: resume
D/UsbDeviceManager(  960): boot completed
V/SystemUIService( 1224): BOOT_COMPLETED received
D/UsbDeviceManager(  960): [USBNET] handleMessage: 4; mConnected=true, mConfiguration=true
D/UsbDeviceManager(  960): [USBNET] update2: 105,0
D/UsbDeviceManager(  960): sendStickyBroadcast: broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true; SetCurrentFunctions= mtp,mass_storage,adb
,D/UsbDeviceManager(  960): [USBNET] handleMessage: 105; mConnected=true, mConfiguration=true
,W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1626 com.android.server.usb.UsbDeviceManager$UsbHandler.handleMessage:1624 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:155 android.os.HandlerThread.run:61 
D/PMS     (  960): releaseWL(1af2d451): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  960): acquireWL(272ef642): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 960 1000 null
W/BindingManager( 3098): Cannot call determinedVisibility() - never saw a connection for the pid: 3098
,D/PMS     (  960): releaseWL(272ef642): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  960): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=3203 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/chromium( 3098): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/ActivityManager(  960): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3218 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/UsbnetService(  960): onReceive ACTION_USB_STATE: true,false
D/Tethering(  960): got USB_STATE change: usbConnected=true, mRndisEnabled=false, mUsbTetherRequested=false
,D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/UsbDeviceManager(  960): [USBNET] sendStickyBroadcast ACTION_USB_CONNECT2PC: 1
,D/MountService(  960): sharing = 0 
W/ResourcesManager(  960): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/MountService(  960): Unmount PCTOOL.ISO
D/VoldConnector(  960): SND -> {10 mountISO unmount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,D/MountService(  960): unmountISO --
,I/RecoverySystem(  960): No recovery log file
,I/ActivityManager(  960): Start proc com.futuredial for broadcast com.futuredial/.ui.BootCompletedReceiver: pid=3248 uid=10082 gids={50082, 9997, 3002, 3001} abi=arm64-v8a
,W/Atfwd_Sendcmd(  423): AtCmdFwd service not published, waiting... retryCnt : 3,
W/ResourcesManager( 3248): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
W/ResourcesManager( 3248): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/JsMessageQueue( 3098): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3098): Unable to open asset URL: file:///android_asset/www/jxcore.js,
,I/BootReceiver(  960): Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG)
,E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  960): Copying audit failures to DropBox,
E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  960): Copied 0 worth of audits to DropBox,
,I/BootReceiver(  960): Checking for fsck errors
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  960): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,D/Process (  960): killProcessQuiet, pid=2434
I/ActivityManager(  960): Killing 2434:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 3203): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=3203 dbg=false s=true,
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE),
E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/ActivityManager(  960): Recipient 2434
,I/BootReceiver(  960): Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  960): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml,
,I/DeviceManagement( 3203): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/DeviceManagement( 3203): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
,D/PMS     (  960): acquireWL(2e47a184): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{10024}
V/AlarmManager(  960): sending alarm PendingIntent{37ce2d6d: PendingIntentRecord{23eebda2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=40316, Int=0
,I/DeviceManagement( 3203): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,I/[FDDMI]BootCompletedReceiver( 3248): BootCompletedReceiver :android.intent.action.BOOT_COMPLETED
,D/jxcore_app_log( 3098): JniHelper::setJavaVM(0xaaeeb8f8), pthread_self() = -1407254904
,I/ActivityManager(  960): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=3276 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
,I/DeviceManagement( 3203): WorkflowService: Starting workflow service,
I/DeviceManagement( 3203): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c0525d8] args=[Bundle[mParcelledData.dataSize=132]]
,I/DeviceManagement( 3203): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
D/OtaStartupReceiver( 1471): onReceive: android.intent.action.BOOT_COMPLETED
W/HtcActiveEngineManager(  960): Can't find out the target sensor
,I/DeviceManagement( 3203): ModelRegistry: Loading model meta data from resources...
,E/WifiStateMachine(  960): handleMessage: E msg.what=131206
E/WifiStateMachine(  960): processMsg: InitialState
E/WifiStateMachine(  960):  InitialState CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState CMD_BOOT_COMPLETED 0 0
,E/WifiStateMachine(  960): handleMessage: X
D/ConnectivityService(  960): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  960): NetworkFactory connected
D/WIFI    (  960): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    (  960):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
D/WIFI    (  960): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  960): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/UsbnetService(  960): onReceive ACTION_BOOT_COMPLETED
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/UsbnetService(  960): UsbnetHandler::handleMessage+:4
D/UsbnetService(  960): MESSAGE_BOOT_COMPLETED+
D/UsbnetService(  960): systemReady+
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1473 com.android.server.backup.BackupManagerService.notifyBackupEnabled:10562 com.android.server.backup.BackupManagerService.access$3400:164 com.android.server.backup.BackupManagerService$BootCompleteReceiver.onReceive:10549 android.app.LoadedApk$ReceiverDispatcher$Args.run:950 
D/WifiService(  960): updateDevicePolicy Exchange policy allowWifiStatus = 1
D/WifiService(  960): updateDevicePolicy Exchange policy allowInternetSharingStatus = 1
D/UsbnetService(  960): systemReady-
,D/UsbnetService(  960): UsbnetHandler::handleMessage-
D/ConnectivityService(  960): Got NetworkFactory Messenger for usbnet
,D/ConnectivityService(  960): NetworkFactory connected
D/usbnet  (  960): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/usbnet  (  960):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  960): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
,I/ActivityManager(  960): Start proc com.htc.autobot for broadcast com.htc.autobot/.UsbReceiver: pid=3300 uid=10047 gids={50047, 9997, 3003, 3002, 3001, 5003, 1024} abi=arm64-v8a,
I/DeviceManagement( 3203): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,D/Process (  960): killProcessQuiet, pid=2466
I/ActivityManager(  960): Killing 2466:com.htc.sense.socialplugins/u0a21 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 3203): SessionStateController: Checking invariants...
,W/jxcore-log( 3098): Initializing JXcore engine
W/jxcore-log( 3098): JXcore engine is ready
,I/ActivityManager(  960): Recipient 2466,
,W/jxcore-log( 3098): Starting JXcore engine
,W/jxcore-log( 3098): Platform android,
W/jxcore-log( 3098): 
W/jxcore-log( 3098): Process ARCH arm
W/jxcore-log( 3098): 
,D/UsbReceiver( 3300): onReceiver android.intent.action.BOOT_COMPLETED,
,D/HtcModeClient( 3300): power connected, start service
,D/Utils   ( 3300): CMD:getprop ro.htc.htcmode.socket.type
,I/System  ( 3300): exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.util.Utils.systemCmd:34)
,I/jxcore-log( 3098): JXcore Cordova bridge is ready!
I/jxcore-log( 3098): 
,W/jxcore-log( 3098): JXcore engine is started,
,I/ActivityManager(  960): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=3325 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/MediaProvider( 3276): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0,
D/MediaProvider( 3276): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3276): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3276): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3276): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3276): [MP][DEBUG] Storage State: removed
D/HtcModeClient( 3300): sSocketMode = LocalSocket
D/HtcModeClient( 3300): start the htcmodeservice thread
,D/HtcModeClient( 3300): initCanAgent
,I/CANMesgAgentLocalSocket( 3300): CANAgent Id = 0
,E/SQLiteLog( 3276): (283) recovered 48 frames from WAL file /data/data/com.android.providers.media/databases/external.db-wal
,E/jxcore-log( 3098): >> HTC-HTC One M8s,
E/jxcore-log( 3098): 
,I/jxcore-log( 3098): Total memory 1931808768
I/jxcore-log( 3098): 
I/jxcore-log( 3098): Free memory 84340736
I/jxcore-log( 3098): 
I/jxcore-log( 3098): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3098): 
I/jxcore-log( 3098): process.cwd /data/data/com.example.hello/files/www/jxcore,
I/jxcore-log( 3098): 
,I/jxcore-log( 3098): userPath [ 'www', 'www' ]
I/jxcore-log( 3098): 
,D/PMS     (  960): releaseHCC(3105f4da): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  960): releaseHCC(2abfdd0b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/art     (  960): Explicit concurrent mark sweep GC freed 33473(2MB) AllocSpace objects, 53(3MB) LOS objects, 33% free, 15MB/23MB, paused 1.387ms total 155.719ms
,I/jxcore-log( 3098): Size 1080 1776
I/jxcore-log( 3098): 
,D/HtcModeClient( 3300): sense info: version = none, id = 2,
I/jxcore-log( 3098): Screen Brightness 142
I/jxcore-log( 3098): 
E/jxcore-log( 3098): Dummy Error Log.
E/jxcore-log( 3098): 
D/HtcModeClient( 3300): onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
D/HtcModeClient( 3300): connectState: BT_TURNON_BYME = false
D/HtcModeClient( 3300): connectState: CONNECTION_READY = false
D/HtcModeClient( 3300): connectState: ENABLE_PROJECTBYAPP = false
D/HtcModeClient( 3300): connectState: ENTER_PROJECTMODE = false
D/HtcModeClient( 3300): display info: width = 1080, height = 1776
D/HtcModeClient( 3300): display info: mode = 10
D/HtcModeClient( 3300): connectState: PHONE_PULGIN = false
D/HtcModeClient( 3300): connectState: Force_AWAKE = false
D/HtcModeClient( 3300): connectState: PHONE_PULGIN = true
D/HtcModeClient( 3300): connectState: POWERCONNECTED_READY = true
,I/DeviceManagement( 3203): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,W/ContextImpl( 3325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,V/AlarmManager(  960): sending alarm PendingIntent{26281995: PendingIntentRecord{151c7aaa android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=40876, Int=0
,D/PowerSaverNotificationService( 3325): updateNotification, mToggle = false,
,D/AlertReceiver( 2601): beginStartingService,
D/PMS     (  960): acquireWL(33fc369b): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 2049 10011 null
,D/PMS     (  960): acquireWL(11e8aa38): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 2601 10010 null
,D/PMS     (  960): releaseWL(33fc369b): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
,D/DFPI.PIReciver( 2934): onReceiver action:android.intent.action.BOOT_COMPLETED,
D/DFPI    ( 2934): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@3bb63ec0
,W/CustomizationIntentService( 1633): failed at default contact creation!
W/CustomizationIntentService( 1633): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10038) to be run in process android.process.acore (with uid 10013)
W/CustomizationIntentService( 1633): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1793)
W/CustomizationIntentService( 1633): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1768)
W/CustomizationIntentService( 1633): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2266)
W/CustomizationIntentService( 1633): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2253)
W/CustomizationIntentService( 1633): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:658)
W/CustomizationIntentService( 1633): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:143)
W/CustomizationIntentService( 1633): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:104)
W/CustomizationIntentService( 1633): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1633): 	at android.os.Looper.loop(Looper.java:155)
W/CustomizationIntentService( 1633): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/CustomizationIntentService( 1633): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
W/CustomizationIntentService( 1633): AFH Enable: false, LEONCHAME: false
W/CustomizationIntentService( 1633): hasBeenInit true
W/CustomizationIntentService( 1633): isNewChameleonHFASupported false
W/CustomizationIntentService( 1633): isHFA true
W/CustomizationIntentService( 1633): setupWizRun 1
,D/HtcAlertService( 2601): start to updateAlertNotification!,
D/DFPI    ( 2934): set install APK prefrence is false
,D/HtcAlertService( 2601): No fired or scheduled alerts
D/HtcAlertUtils( 2601): -- cancelReminderNotification --
,D/HtcAlertUtils( 2601): broadcastExistReminder!
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  960): releaseWL(11e8aa38): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/AlertReceiver( 2601): stopSelfResult true
,D/Process (  960): killProcessQuiet, pid=2908
I/ActivityManager(  960): Killing 2908:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 2908,
,I/DeviceManagement( 3203): SessionStateController: Checking invariants...
,I/ActivityManager(  960): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3370 uid=10020 gids={50020, 9997, 1028, 1015} abi=arm64-v8a
,D/Process (  960): killProcessQuiet, pid=1740
I/ActivityManager(  960): Killing 1740:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 3203): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true,
,I/DeviceManagement( 3203): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2c0525d8],
,I/ActivityManager(  960): Recipient 1740,
,I/jxcore-log( 3098): getBuffer is called!!!!
I/jxcore-log( 3098): 
,I/DeviceManagement( 3203): WorkflowService: Stopping workflow service
,D/Process (  960): killProcessQuiet, pid=2958,
I/ActivityManager(  960): Killing 2958:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/htcbackup-core( 3164): BackupRestoreManager: Storage is not configured,
,E/htcbackup-core( 3164): BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE
,I/ActivityManager(  960): Recipient 2958,
,W/System.err( 3164): Starting the HTTP client
,W/htcbackup-core( 3164): BackupServiceClientResourceProxy: Reseting appServerErrorCount,
,W/htcbackup-core( 3164): BackupRestoreManager: No sense account found - aborting
,I/htcbackup-core( 3164): BackupRestoreManager: DM is not ready, pending resume
,D/FlexNetS( 2049): setNetMode:0, false
D/FlexNetS( 2049): set2gLowSignalEnablePref: false
,V/FlexNetS( 2049): [DRX] setHigherPowerIn2GPref to: true
D/FlexNetS( 2049): setSimCardisWhiteList: false
V/FlexNetS( 2049): setSimCardCamp3GNetworkSignalPref to: false
D/FlexNetS( 2049): setCampNetworkisBlackList: false
D/Process (  960): killProcessQuiet, pid=2984
I/ActivityManager(  960): Killing 2984:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,V/FlexNetS( 2049): [DRX] setHigherPowerIn2GPref to: true
,I/ActivityManager(  960): Recipient 2984
,V/FlexNetS( 2049): setRilHandOverW2GEnable: 0,
,D/FlexNetS( 2049): updateSvcAllowedInSettings:false
,I/ActivityManager(  960): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3399 uid=10026 gids={50026, 9997} abi=arm64-v8a,
D/Process (  960): killProcessQuiet, pid=3008
I/ActivityManager(  960): Killing 3008:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 3008
,V/OneTimeInitializerReceiver( 3399): OneTimeInitializerReceiver.onReceive,
,V/OneTimeService( 3399): OneTimeService.onHandleIntent
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=2790, uid=10027, userID:0,
,D/PMS     (  960): acquireWL(260675): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1775 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  960): releaseWL(260675): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  960): Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3429 uid=10029 gids={50029, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=arm64-v8a,
,D/PMS     (  960): acquireWL(19a6960a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1775 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(19a6960a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=2790, uid=10027, userID:0
,I/RlzPingService( 2790): Setting next ping for 1458028709448,
,D/PMS     (  960): acquireWL(15c5a498): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1775 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(15c5a498): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): acquireWL(22dd94f1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1775 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): releaseWL(22dd94f1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  960): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3455 uid=10031 gids={50031, 9997, 3003} abi=arm64-v8a
,D/Process (  960): killProcessQuiet, pid=2702,
I/ActivityManager(  960): Killing 2702:com.htc.sense.browser/u0a9 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 2702
,D/PMS     (  960): acquireWL(3f2008d6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1775 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  960): releaseWL(3f2008d6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(ed92757): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1775 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  960): releaseWL(ed92757): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  960): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3476 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Process (  960): killProcessQuiet, pid=2836
I/ActivityManager(  960): Killing 2836:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  409): Explicit concurrent mark sweep GC freed 8671(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 221us total 28.044ms,
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 178us total 23.272ms
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 168us total 21.624ms
,I/ActivityManager(  960): Recipient 2836
,D/Process (  960): killProcessQuiet, pid=3063
I/ActivityManager(  960): Killing 3063:com.android.settings/1000 (adj 15): empty #17
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  960): acquireWL(bc7244): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1775 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  960): releaseWL(bc7244): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  960): Recipient 3063
,D/Process (  960): killProcessQuiet, pid=3141
I/ActivityManager(  960): Killing 3141:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 3141,
,E/Personalize.BootComple_( 3476): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
E/Personalize.BootComple_( 3476): action android.intent.action.BOOT_COMPLETED
,E/Personalize.Utilities( 3476): SimpleLauncher not found: com.htc.simplelauncher
I/ActivityManager(  960): Killing 3164:com.htc.backup/u0a109 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=3164
I/PackageManager(  960):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=3476, uid=1000, userID:0
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 3164
,E/Personalize.BootComple_( 3476): initialize: false,
E/Personalize.Utilities( 3476): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
I/PackageManager(  960):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=3476, uid=1000, userID:0
,V/BootCompletedReceiver( 2811): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
,D/PeopleYouKnow( 2811): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) },
,I/ActivityManager(  960): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3497 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
D/Process (  960): killProcessQuiet, pid=3248
I/ActivityManager(  960): Killing 3248:com.futuredial/u0a82 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 3248
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 3497): ACTION_BOOT_COMPLETED
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=3497, uid=10040, userID:0,
,V/HtcDataStripWidget.DisableWidgetReceiver( 3497): ACTION_BOOT_COMPLETED,
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=3497, uid=10040, userID:0
,I/ActivityManager(  960): Killing 3218:com.android.keychain/1000 (adj 15): empty #17
,D/Process (  960): killProcessQuiet, pid=3218
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  960): Recipient 3218,
,D/DotMatrix( 1306): [EventReceiver] onReceive, version:1.3
,I/ActivityManager(  960): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3518 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  960): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3540 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a
,I/ActivityManager(  960): Killing 3325:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=3325
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 3540): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.,
,I/ActivityManager(  960): Recipient 3325,
,D/MediaSessionHelper( 3540): Attempting to get helper with context android.app.ReceiverRestrictedContext@353289f2,
,D/MediaSessionService(  960): Created session for package com.htc.music with tag MediaSessionHelper-com.htc.music
,D/MediaSessionHelper( 3540): addMediaButtonListener added PendingIntent{3bb63ec0: android.os.BinderProxy@2fb8a843}
,I/ActivityManager(  960): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3563 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/ActivityManager(  960): Killing 2601:com.htc.calendar/u0a10 (adj 15): empty #17,
D/Process (  960): killProcessQuiet, pid=2601
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 2601
,I/ActivityManager(  960): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3585 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  960): Killing 2934:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=2934
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 2934,
,W/ContextImpl( 3585): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 3585): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 3585): MY_DEBUG = false
W/ContextImpl( 3585): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 3585): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,V/AlarmManager(  960): sending alarm PendingIntent{378f129: PendingIntentRecord{2af5cae com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457423912083, Int=0
,W/ContextImpl( 3585): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:208 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:71 android.app.IntentService$ServiceHandler.handleMessage:65 ,
,I/[PluginManager]RegisterService( 1421): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
,D/HtcAppUPService( 1421): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/HtcAppUPService( 1421): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@20173ed6
,D/AutoSetting( 1421): receiver - intent: android.intent.action.BOOT_COMPLETED
,I/WSP     ( 1421): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
,D/HtcAppUPService( 1421): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
,I/ActivityManager(  960): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3617 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a,
,D/Process (  960): killProcessQuiet, pid=3276
I/ActivityManager(  960): Killing 3276:android.process.media/u0a17 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/WeatherUtility( 1224): Weather sync is On
W/WeatherTimeKeeper( 1224): [refreshWeatherData] no weather data
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/FeatureList( 1421): feature,
D/FeatureList( 1421): type
D/FeatureList( 1421): description
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source),
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:,
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:,
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source),
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): ,	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): ,	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	,at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  960): Recipient 3276
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
,W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/AutoSetting( 1421): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete,
D/AutoSetting( 1421): service - onStartCommand() boot completed, remove cache
D/AutoSetting( 1421): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1421): service - handleMessage() setting current location null
D/AutoSetting( 1421): service - handleMessage() removing cache
D/AutoSetting( 1421): service - AddressCache: clean up all cache
D/HtcAppUPService( 1421): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,D/HtcAppUPService( 1421): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true,
,V/BootReceiver( 3617): onReceive: android.intent.action.BOOT_COMPLETED,
D/BootReceiver( 3617): boot completed:
,D/BootReceiver( 3617): isValid:  isEnabledEasyAccess = true, isEnabledQuickDial = true
,D/BootReceiver( 3617): Valid
,D/BootReceiver( 3617): startService:
,I/ActivityManager(  960): Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3638 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a,
,I/ActivityManager(  960): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3657 uid=10058 gids={50058, 9997, 1028, 1015, 1023} abi=arm64-v8a,
I/ActivityManager(  960): Killing 3370:com.htc.fm/u0a20 (adj 15): empty #17
,D/Process (  960): killProcessQuiet, pid=3370,
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/PluginProvider( 1421): Begin Apply Batch,
,E/PluginProvider( 1421): conflict when insert feature, ignored
,I/ActivityManager(  960): Recipient 3370
,D/NGFService( 3638): onCreate +++,
,D/SettingUtils( 3638): getProcessNormalFlag: true,
D/NGFService( 3638): onCreate last time crash or 1st run=false
D/SettingUtils( 3638): setProcessNormalFlag: false
,D/NGFService( 3638): getAudioStreamType: ScoOn =false,
D/SoundEffects( 3638): init +++ 3
,W/LMW     ( 3657): [3686][ActionDeviceStorageHandler] onActionBootComplete++
,W/LMW     ( 3657): [3686][ActionDeviceStorageHandler] onActionBootComplete--
,I/ActivityManager(  960): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3688 uid=10063 gids={50063, 9997, 1028, 3003} abi=arm64-v8a
,D/Process (  960): killProcessQuiet, pid=3203
I/ActivityManager(  960): Killing 3203:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/AudioCache(  401): Heap size overflow! req size: 1058400, max size: 1048576,
,W/NuPlayerRenderer(  401): AudioSink write short frame count 0 < 9824,
,D/PluginProvider( 1421): apply Batch success
,I/[PluginManager]RegisterService( 1421): Notify Carousel that a new TabPlugin has been installed!,
,W/libutils.threads(  401): Thread (this=0xab092d70): don't call join() from this Thread object's thread. It's a guaranteed deadlock!
W/OMX     (  401): loop count is null and break
,I/ActivityManager(  960): Recipient 3203
,I/art     (  960): Explicit concurrent mark sweep GC freed 14145(767KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.388ms total 129.904ms
,I/ActivityManager(  960): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=3758 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
,I/ActivityManager(  960): Killing 2049:com.htc.bgp/u0a11 (adj 15): empty #17
,D/Process (  960): killProcessQuiet, pid=2049,
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/NGFLanguageMgr( 3638): LanguageFromSystem: language:en  country:gb,
D/NGFLanguageMgr( 3638): language package name = preload_package
,I/HtcModeClient( 3300): handler message = 4011,
E/HtcModeClient( 3300): Check connection and retry 1 times.
,I/NMT     ( 3638): NMT version: 1.6.1-B006 REL,
,D/NGFService( 3638): Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm
,I/ActivityManager(  960): Recipient 2049
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  960): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  960): MONITOR_LOG
V/AlarmManager(  960): sending alarm PendingIntent{6f29c6b: PendingIntentRecord{6b763c8 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=45902, Int=0
,W/Settings:Agent(  960): name: bluetooth_on
I/ActivityManager(  960): Killing 3399:com.google.android.onetimeinitializer/u0a26 (adj 15): empty #17
W/Settings:Agent(  960): value: 0
W/Settings:Agent(  960): >> traceCallingStack()
W/Settings:Agent(  960): Process.myPid(): 960
W/Settings:Agent(  960): Process.myTid(): 986
W/Settings:Agent(  960): Process.myUid(): 1000
W/Settings:Agent(  960): 
W/Settings:Agent(  960): 
W/System.err(  960): java.lang.Throwable: stack dump
D/WifiService(  960): New client listening to asynchronous messages
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  960): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  960): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  960): 	at android.provider.Settings$Global.putString(Settings.java:7403)
D/WifiService(  960): setWifiEnabled: false pid=3098, uid=10374
W/System.err(  960): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
W/System.err(  960): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
I/WifiService(  960): isSprintWifiRestricted(): false
W/System.err(  960): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
I/WifiService(  960): isMdmWifiRestricted(): false
W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  960): 
W/Settings:Agent(  960): << traceCallingStack(): 1(ms)
D/BluetoothManagerService(  960): Message: MESSAGE_DISABLE
D/Process (  960): killProcessQuiet, pid=3399
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/WifiManager( 3098): setWifiEnabled: Base Package Name=com.example.hello, uid=10374
W/Settings:Agent(  960): MONITOR_LOG
W/Settings:Agent(  960): name: wifi_on
W/Settings:Agent(  960): value: 0
W/Settings:Agent(  960): >> traceCallingStack()
W/Settings:Agent(  960): Process.myPid(): 960
W/Settings:Agent(  960): Process.myTid(): 1717
W/Settings:Agent(  960): Process.myUid(): 1000
W/Settings:Agent(  960): 
W/Settings:Agent(  960): 
W/System.err(  960): java.lang.Throwable: stack dump
E/WifiTrafficPoller(  960): ADD_CLIENT: 6
,W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  960): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  960): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  960): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  960): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  960): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  960): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  960): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  960): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  960): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  960): 
W/Settings:Agent(  960): << traceCallingStack(): 10(ms)
,D/WifiController(  960): handleMessage: E msg.what=155656
,D/WifiController(  960): processMsg: ApStaDisabledState
D/WifiController(  960): handleMessage: X
I/jxcore-log( 3098): ****TEST TOOK:  5314  ms ****
I/jxcore-log( 3098): 
I/jxcore-log( 3098): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3098): 
,I/ActivityManager(  960): Recipient 3399
,D/NGFService( 3638): applyCurrentSystemLanguage +++
D/NGFService( 3638): grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish]
D/NGFLanguageMgr( 3638): LanguageFromSystem: language:en  country:gb
D/NGFService( 3638): Elvis language uses the language: 2
D/NGFService( 3638): setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0
D/NGFService( 3638): setCurrentNGFLanguageMgr: set language = British English
D/NGFService( 3638): bluetoothInitialize +++
,W/System.err(  960): java.lang.Throwable: stack dump
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@654e3e0:true
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
,D/NGFService( 3638): cloud_init +++
D/NGFLanguageMgr( 3638): getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
,D/MediaProvider( 3758): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,D/MediaProvider( 3758): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3758): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3758): [MP][DEBUG] Storage State: removed,
D/MediaProvider( 3758): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3758): [MP][DEBUG] Storage State: removed
,D/MediaScannerReceiver( 3758): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,D/MediaProviderUtils( 3758): [startScan]volume:internal, action:android.intent.action.MEDIA_MOUNTED
,E/SQLiteLog( 3758): (283) recovered 48 frames from WAL file /data/user/0/com.android.providers.media/databases/external.db-wal
D/MediaProviderUtils( 3758): [startScan]volume:external, action:android.intent.action.MEDIA_MOUNTED
,D/NGFService( 3638): elvisInitalize +++
,D/NGFService( 3638): elvisInitalize lang = British English
,D/NGFService( 3638): elvisInitalize: Freq Type:16000
D/NGFService( 3638): tts_init +++
D/NGFLanguageMgr( 3638): getVocalizerFolderName: language = 2, folder name = vocalizer_eng
,E/cutils-trace( 3782): Error opening trace file: Permission denied (13),
,D/NGFLanguageMgr( 3638): LanguageFromSystem: language:en  country:gb,
D/NGFLanguageMgr( 3638): language package name = preload_package
,D/NGFService( 3638): load vocalizer language = British English
,E/NGFService( 3638): registerObserver
,D/NGFService( 3638): onCreate: Battery Level Remaining: 100%
,D/NGFService( 3638): onStartCommand(): service start
D/NGFService( 3638): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
,D/NGFService( 3638): QuickCall,
D/CustomizationManager( 3782): ====startRecUseTime====
D/htc.customization.log.level( 3782):  is 
W/CustomizationLogLevel( 3782): Level value is invalid, use default level 2
,W/NMT     ( 3638): Fail to open read-stream for file generic.lst
,W/NMT-OemFile( 3638): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3638): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat,
,D/NGFService( 3638): Elvis is initialization Success
D/NGFService( 3638): bElvisInitializeCompleted = true
D/NGFService( 3638): GrammarState = 0
D/NGFService( 3638): loadGrammar +++,
D/NGFService( 3638): loadGrammar asr_grammar
I/NGFService( 3638): GrammarDepot contains a valid Elvis Grammar0
D/NGFService( 3638): loadGrammar from cache
,W/NMT-OemFile( 3638): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
,D/MediaScannerServiceEx( 3758): Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
D/MediaScannerServiceEx( 3758): Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED,
D/PMS     (  960): acquireWL(23c45fd1): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3758 10017 null
,W/NMT     ( 3638): Fail to open read-stream for file elvisBritish Englishname.lst
,W/NMT-OemFile( 3638): fopen(): Failed to open file sysdct.dat
W/NMT-OemFile( 3638): fopen(): Failed to open file sysdct.dat
,D/MtpReceiver( 3758): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3758): [MTP][handleUsbStateAsync]1:1-
,D/MtpReceiver( 3758): [MTP][handleUsbState]+
,W/NMT     ( 3638): Fail to open read-stream for file elvisBritish Englishartist.lst
W/NMT-OemFile( 3638): fopen(): Failed to open file clm.dat
,W/NMT     ( 3638): Fail to open read-stream for file elvisBritish Englishplaylist.lst
,W/NMT     ( 3638): Fail to open read-stream for file elvisBritish Englishsong.lst
,W/NMT     ( 3638): Fail to open read-stream for file elvisBritish Englishalbum.lst
W/NMT     ( 3638): Fail to open read-stream for file elvisBritish Englishgeneric.lst,
,I/ActivityManager(  960): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3818 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/MediaProvider( 3758): bindService() MTP Service Connection.
,D/MtpReceiver( 3758): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpReceiver( 3758): [MTP][handleUsbState]-
D/MtpReceiver( 3758): [MTP][handleMessage]-
D/CustomizationManager( 3782):  Read ACC file spent 0.036 (s)
W/NMT-OemFile( 3638): fopen(): Failed to open file daniel_userdct_eng.dat
,D/CIDMapFileReader( 3782): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3782): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3782): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3782): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3782): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3782): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3782): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3782): full path : /system/customize/CID/HTC__102.xml
D/MediaScanner( 3758): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
I/CustomizationCIDLoader( 3782): Parsing tag category name = system
,I/CustomizationCIDLoader( 3782): Parsing tag category name = application
,I/CustomizationCIDLoader( 3782): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3782): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3782): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3782): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3782): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3782): add string-array item, value = 42507
I/CustomizationCIDLoader( 3782): add string-array item, value = 21902
I/CustomizationCIDLoader( 3782): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 3782): add string-array item, value = 23420
I/CustomizationCIDLoader( 3782): add string-array item, value = 22299
I/CustomizationCIDLoader( 3782): add string-array item, value = 24002
I/CustomizationCIDLoader( 3782): add string-array item, value = 23210
D/MtpService( 3758): updating state; isCurrentUser=true, mMtpLocked=false
I/CustomizationCIDLoader( 3782): add string-array item, value = 23205
I/CustomizationCIDLoader( 3782): add string-array item, value = 23806
I/CustomizationCIDLoader( 3782): add string-array item, value = 23430
I/CustomizationCIDLoader( 3782): add string-array item, value = 23408
I/CustomizationCIDLoader( 3782): add string-array item, value = 27205
I/CustomizationCIDLoader( 3782): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 3782): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 3782):  Read CID file spent 0.080 (s)
D/CustomizationManager( 3782):  All configurations done spent 0.080 (s)
D/SettingUtils( 3638): setProcessNormalFlag: true
D/NGFService( 3638): RebuildListener constraintList size 17
D/NGFService( 3638): RebuildListener: onComplete0
D/NGFService( 3638): onComplete GRAMMAR_STATE_DEFAULT
D/NGFService( 3638): switchScenario: htc_screen_140_19
D/NGFService( 3638): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3638): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3638): Loading grammar completed.
D/NGFService( 3638): update contact cache completed
D/SettingUtils( 3638): set Updatge Contact Cache: false
,D/MtpService( 3758): addStorageInternal without MtpServer
D/MtpService( 3758): [MTP][onCreate]-
I/ActionCombine( 3758): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
E/SQLiteLog( 3758): (283) recovered 86 frames from WAL file /data/user/0/com.android.providers.media/databases/internal.db-wal
D/MtpService( 3758): [MTP] startForeground
D/MtpService( 3758): updating state; isCurrentUser=true, mMtpLocked=false
,D/Process (  960): killProcessQuiet, pid=3098
D/PMS     (  960): acquireWL(279a0ce6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2137 10024 null
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
D/PackageManager(  960): deletePackageAsUser: pkg=com.example.hello, pid=3782, uid=2000 userid=0
D/MtpDatabase( 3758): TotalSize=1886532,MediaCacheLimit=6000
I/ActivityManager(  960): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
I/ActivityManager(  960): Killing 3098:com.example.hello/u0a374 (adj 0): stop com.example.hello
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
W/HtcWrapAdjustableCursorFactory( 3818): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MessageFrequencyProvider( 3818): onCreate
,W/MediaScanner( 3758): Error opening directory '/oem/media/', skipping: No such file or directory.,
,W/MediaScanner( 3758): Error opening directory '/oem/media/', skipping: No such file or directory.,
,D/MediaScanner( 3758):  prescan time: 92ms,
D/MediaScanner( 3758):     scan time: 28ms
D/MediaScanner( 3758): postscan time: 0ms
D/MediaScanner( 3758):    total time: 120ms
D/MediaScanner( 3758): -----------------------------------------------------------------
D/MediaScanner( 3758): firstscan(media) time: 13ms
D/MediaScanner( 3758): secondscan(non-media) time: 5ms
D/MediaScanner( 3758):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3758):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3758):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3758):  [Total]    File(Image+Video+Audio+Others) in database : 339
,W/PackageSettings(  960): Skipping PackageSetting{4aaf7c6 com.test.thalitest/10366} due to missing metadata,
,I/RemoteViews( 1224): apply : com.android.providers.media 0 9 2 36,
,I/RemoteViews( 1224): apply : com.android.providers.media 1 11 1 51,
,I/ActivityManager(  960): Recipient 3098
I/WindowState(  960): WIN DEATH: Window{1729db19 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  960): Client connection lost with reason: 4
,E/InputEventReceiver( 1354): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2bea17de uid 10374 pid 3098} (c)'
,W/ActivityManager(  960): Force removing ActivityRecord{2a8ca7e8 u0 com.example.hello/.MainActivity t12}: app died, no saved state
,W/ActivityManager(  960): Spurious death for ProcessRecord{2c69c227 3098:com.example.hello/u0a374}, curProc for 3098: null
,D/MtpService( 3758): starting MTP server in MTP mode
,V/GetPrviateResource( 3818): GetPrviateResource
V/GetPrviateResource( 3818): GetPrviateResource
,I/ActivityManager(  960): Force stopping com.example.hello appid=10374 user=0: pkg removed
,D/MessageCustFlag( 3818): sense_version=6.0
,D/BTAccessoryUtil( 3818): createReceiver
,D/DotMatrix( 1306): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1306): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/BTAccessoryUtil( 3818): registerReceiver return intent = null
,D/PMS     (  960): acquireWL(fa659c3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1775 10024 WorkSource{10024 com.google.android.gms}
D/MessageCustFlag( 3818): sku_id=118
,D/MtpService( 3758): addStorageInternal 65537 /storage/emulated/0,
I/FeedHostManager( 1525): [onResume]
I/FeedProviderManager( 1525): onResume
I/SocialFeedProvider( 1525): +onResume
I/SocialFeedProvider( 1525): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1525): -onResume
W/GeofencerStateMachine( 1775): Ignoring removeGeofence because network location is disabled.
D/HtcBuildUtils( 3818): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3818): Cannot find qct_8960_interface, use default value instead
V/MmsSystemEventReceiver( 3818): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) },
I/ConnectivityHelper( 1525): [getCurrentConnectionType] no network connection
D/PMS     (  960): releaseWL(fa659c3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 2811): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/AccTypeManager( 1676): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  960): Cannot find grip_rejection_width, use default value instead
,D/StatusBarManagerService(  960): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
,D/MtpService( 3758): [checkStorageState] Storage state - mounted
D/MtpDatabase( 3758): [MTP][addStorage] iHostType =2
D/MtpService( 3758): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
D/FindExtension( 1525): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1525): Defer allocateBuffers to drawing time
,D/MediaProvider( 3758): [delete][241]
I/InputMethodManagerService(  960): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/MediaProvider( 3758): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/PMS     (  960): acquireWL(2d02ae9c): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 3818 10064 null
D/AccTypeManager( 2811): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ExchangePolicystatus( 3818): onReceive()
D/ExchangePolicystatus( 3818): onReceive(): ACTION_BOOT_COMPLETED
D/MessageUtils( 3818): Text messaging allow status = allow
D/Messaging( 3818): EAS allow SMS !!!
D/ExchangePolicystatus( 3818): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
W/InputMethodManagerService(  960): Got RemoteException sending setActive(false) notification to pid 3098 uid 10374
D/AccTypeManager( 1676): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/StatusBarManagerService(  960): swetImeWindowStatus vis=0 backDisposition=0
D/Messaging( 3818): EAS allow SMS !!!
I/InputMethodManagerService(  960): Enable input method client, pid=1525
,D/MediaProvider( 3758): [recoverParentNodes] - 0
,D/MediaProvider( 3758): [update][24],
D/MediaScannerServiceEx( 3758): [scan] Recover Parent Node is finished!
D/PhoneApp( 1471): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  960): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3857 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
D/PMS     (  960): releaseWL(23c45fd1): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,V/SmsReceiverService( 3818): onStart: #1, @738534872
,V/SmsReceiverService( 3818): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 3818): isCbm: false
D/SmsReceiverService( 3818): isDiscard: false
D/SettingsManager( 3818): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2f2086ec
,V/SmsReceiverService( 3818): handleBootCompleted
E/MediaScannerService( 3758): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3758): [handleMessage] --- Should not be here, ignore request. ----
,E/MediaScannerServiceEx( 3758): [getStorageMaskIdFromPath] path is null,
D/MediaScannerServiceEx( 3758): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
,D/MediaScannerServiceEx( 3758): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 3758): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3758): calcVolumeId: /storage/ext_sd
W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MediaProviderUtils( 3758): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3758): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3758): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3758): [update][9]#0#
,D/AccTypeManager( 2811): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/MediaProvider( 3758): [update][4]#0#
,I/iu.UploadsManager( 2137): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/StatusBarManagerService(  960): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
D/AccFlag ( 1471): sku_id=118
,W/ResourcesManager(  960): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/ExternalAccountType( 2811): Unsupported attribute readOnly
,W/PackageManager(  960): Unable to load service info ResolveInfo{1e46c591 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  960): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  960): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  960): 	,at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  960): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  960): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  960): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  960): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  960): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  960): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  960): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  960): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  960): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/MediaProvider( 3758): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3758): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/AccTypeManager( 1676): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
D/MediaProvider( 3758): [update][33]#1#
,D/SmsReceiverService( 3818): OutBoxSize = 0
,D/SmsReceiverService( 3818): sendFirstQueuedMessage start: 0
D/MessageCustFlag( 3818): sku_id=118
D/MediaScannerServiceEx( 3758): [AliveExtStorageRows]-0, 0
,D/TelephUtils( 1471): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/PMS     (  960): acquireWL(cbf1c0b): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3758 10017 null
,D/AccFlag ( 1471): sku_id=118
,I/art     (  960): Explicit concurrent mark sweep GC freed 16096(1254KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 15MB/23MB, paused 1.859ms total 214.675ms
,D/MessageCustFlag( 3818): sku_id=118
,D/MediaScanner( 3758): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,E/ExternalAccountType( 1676): Unsupported attribute readOnly
,D/SmsReceiverService( 3818): sendFirstQueuedMessage end cnt> 0
,D/SpaceBufferUtil( 3818): > createBufferFile()
D/SpaceBufferUtil( 3818): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
,D/SpaceBufferUtil( 3818): < createBufferFile()
,I/iu.UploadsManager( 2137): End new media; added: 0, uploading: 0, time: 108 ms
,D/PMS     (  960): releaseWL(279a0ce6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,E/cutils-trace( 3885): Error opening trace file: Permission denied (13)
,I/dex2oat ( 3885): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 3885): dex2oat: override thread count:4
,D/JobSchedulerService(  960): Receieved: android.intent.action.PACKAGE_REMOVED
,I/PhoneStatusBar( 1224): setImeWindowStatus(false,false)
D/TaskPersister(  960): removeObsoleteFile: deleting file=12_task.xml
,W/OpenGLRenderer( 1525): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,E/dex2oat ( 3885): Failed to write Failed to write Fai for /data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex: Bad file number
,E/dex2oat ( 3885): Unable to write to file /data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex
E/dex2oat ( 3885): Failed to write ELF file /data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex
,E/dex2oat ( 3885): Failed to create oat file: /data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex,
,I/HtcModeClient( 3300): handler message = 4009,
I/HtcModeClient( 3300): start to setup the connection
,I/dex2oat ( 3885): dex2oat took 789.688ms (threads: 4),
,I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 3857): ApplicationMonitor {2cc91d31}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/ActivityManager(  960): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3895 uid=10076 gids={50076, 9997} abi=arm64-v8a,
,E/SharedPreferencesImpl( 3857): Couldn't rename file /data/data/com.htc.cs.pns/shared_prefs/reg_info.xml to backup file /data/data/com.htc.cs.pns/shared_prefs/reg_info.xml.bak,
,I/PushClient( 3857): String {2b182068}: handleBroadcast(): Schedule update on boot completed.,
E/SharedPreferencesImpl( 3857): Couldn't rename file /data/data/com.htc.cs.pns/shared_prefs/reg_info.xml to backup file /data/data/com.htc.cs.pns/shared_prefs/reg_info.xml.bak
,I/ActivityManager(  960): Killing 3429:com.htc.video/u0a29 (adj 15): empty #17
D/Process (  960): killProcessQuiet, pid=3429
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 3429,
,D/SMSBackup( 3895): Got ACTION_BOOT_COMPLETED event,
,D/MediaScanner( 3758):  prescan time: 664ms
D/MediaScanner( 3758):     scan time: 523ms
D/MediaScanner( 3758): postscan time: 2ms
D/MediaScanner( 3758):    total time: 1189ms
D/MediaScanner( 3758): -----------------------------------------------------------------
D/MediaScanner( 3758): firstscan(media) time: 242ms
D/MediaScanner( 3758): secondscan(non-media) time: 281ms
D/MediaScanner( 3758):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
,D/MediaScanner( 3758):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3758):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3758):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/SMSBackup( 3895): setCheckAlarm,
,D/SMSBackup( 3895): Next check is scheduled at 60s from now,
D/Process (  960): killProcessQuiet, pid=2790
I/ActivityManager(  960): Killing 2790:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  960): Recipient 2790
,I/Prism.ItemManager( 1525): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1525): loadItems() com.htc.launcher.pageview.WidgetManager@1f2bb889 +
I/Prism.WidgetManager( 1525): onLoadItems() +
,W/ResourcesManager( 1525): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/PackageManager(  960):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1471, uid=1001, userID:0
,I/ActivityManager(  960): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3917 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a,

```
