#### Test 50388019b17f598_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/CscGPS  ( 1459): CSCGPS.updateParameters
D/CscGPS  ( 1459): supl host : null
D/CscGPS  ( 1459): SUPL Host is null or invalid
D/CscGPS  ( 1459): supl_ver : null
D/CscGPS  ( 1459): SUPL Ver is null or invalid
D/CscGPS  ( 1459): supl port : null
D/CscGPS  ( 1459): SUPL PORT is null or invalid
D/CscGPS  ( 1459): LPP : null
D/CscGPS  ( 1459): LPP is null or invalid
D/CscGPS  ( 1459): CSC don't have any AGPS value.
D/SensorService( 1017): [SO] 0.211 0.153 10.132
I/CscUpdateService( 1459): same CSC Version
D/CscUtil ( 1459): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
--------- beginning of system
D/MediaScannerService( 1225): !@start scanning volume internal: [/system/media, /oem/media]
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
D/ActivityManager( 1017): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
D/TP/MmsProvider( 1459): Update uri=content://mms, match=0
D/MtpService( 1225): updating state; isCurrentUser=true, mMtpLocked=false
D/TP/MmsProvider( 1459): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2971): MountEmulatedStorage()
I/libpersona( 2971): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2971): v2
I/libpersona( 2971): KNOX_SDCARD not a persona
E/USB_UICC(  297): Timeout! No signal received. Retry num = 27
I/SELinux ( 2971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=2971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2971): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Mms:transaction( 2283): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2283): [start]    nonBlockingUpdateMessageIndicator() consume time = 4073.15328
I/Mms/ReservationManager( 2283): resetAfterConnected()
I/ServiceManager(  314): Waiting for service AtCmdFwd...
I/art     (  305): Explicit concurrent mark sweep GC freed 8762(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 756us total 27.034ms
D/TP/MmsSmsProvider( 1459): query,matched:7, calling pid = 2283
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/TP/MmsSmsProvider( 1459): match 7:Elapsed time : 3.302 ms
D/Mms/MessagingNotification( 2283): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2283): isDefault true
D/TimaService( 1017): TIMA: in getTimaVersion
D/TimaKeyStoreProvider( 2971): TimaSignature is unavailable
D/ActivityThread( 2971): Added TimaKeyStore provider
E/TLC_TZ_KEYSTORE: ( 1017): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1017): TIMA3: KeyStore3_init
I/TLC_TZ_KEYSTORE: ( 1017): creating new keystore context...
D/TimaService( 1017): TIMA: in getTimaVersion
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
D/TP/MmsProvider( 1459): Query uri=content://mms, match=0, calling pid = 2283
I/Mms/ReservationManager( 2283): getReservedSendMessageCount(): retMessageCount=0
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 715us total 19.822ms
E/SQLiteLog( 1225): (283) recovered 363 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/ActivityManager( 1017): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SecureStorage( 2947): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
D/QSEECOMAPI: ( 1017): Loaded image: APP id = 9
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.766ms
I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1017): ctx = 0xb8cdb3f8, comm = 0xb9066178, sendmsg = 0x9d50a000, recvmsg = 0x9d50a440
I/TZ_init: ( 1017): TZ_init: sending initialization request...
E/TZ_init: ( 1017): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1017): trustlet initialization failed
I/TZ_init: ( 1017): TZ_init_START...
E/Zygote  ( 2990): MountEmulatedStorage()
E/Zygote  ( 2990): v2
I/libpersona( 2990): KNOX_SDCARD checking this for 10048
I/libpersona( 2990): KNOX_SDCARD not a persona
I/SELinux ( 2990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecureStorage( 2947): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/ActivityManager( 1017): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2990 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SecureStorage(  334): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2947
I/SecureStorage(  334): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 2947): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2947): [INFO]: SPID(0x00000000)Processing data
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
I/SecureStorage(  334): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2947
I/SecureStorage(  334): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
I/TZ_init: ( 1017): TZ_init_with_data: sending initialization request...
D/SecurityLogAgent( 2971): KnoxConfiguration : Current State = 1
D/TP/MmsSmsProvider( 1459): query,matched:200, calling pid = 2283
I/TZ_init: ( 1017): TZ_init: successful initialization
D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 9
D/TP/MmsSmsProvider( 1459): match 200:Elapsed time : 1.188 ms
E/TLC_TZ_KEYSTORE: ( 1017): Count : 1, Ret : 0
D/TimaKeyStoreProvider( 2990): TimaSignature is unavailable
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
D/SecurityLogAgent( 2971): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 2971): StateMachine : Current State = 1
D/ActivityThread( 2990): Added TimaKeyStore provider
D/SecurityLogAgent( 2971): BootReceiver : completed task. Failed to return wakelock . 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3008): MountEmulatedStorage()
E/Zygote  ( 3008): v2
I/libpersona( 3008): KNOX_SDCARD checking this for 1000
I/libpersona( 3008): KNOX_SDCARD not a persona
D/MediaScanner( 1225): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/SELinux ( 3008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/SmsReceiverService( 2283): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
D/Mms/TelephonyPermission( 2283): isDefault true
D/Mms/SmsReceiverService( 2283): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2283): [start]    handleBootCompleted() consume time = 145.149115
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3008): TimaSignature is unavailable
D/ActivityThread( 3008): Added TimaKeyStore provider
W/ResourcesManager( 2990): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2990): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2990): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
E/Zygote  ( 3023): MountEmulatedStorage()
E/Zygote  ( 3023): v2
I/libpersona( 3023): KNOX_SDCARD checking this for 10152
I/libpersona( 3023): KNOX_SDCARD not a persona
I/SELinux ( 3023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=3023 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 3023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Killing 1402:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
E/SELinux ( 3023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/MediaScanner( 1225): processDirectory :  /system/media
D/TP/SmsProvider( 1459): query,matched:0, calling pid = 2283
D/TP/SmsProvider( 1459): match 0:Elapsed time : 1.667 ms
D/TimaKeyStoreProvider( 3023): TimaSignature is unavailable
D/ActivityThread( 3023): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1459): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1459): deleteConversation threadId: 9223372036854775806
W/ActivityManager( 1017): getTasks: caller 10146 does not hold GET_TASKS; limiting output
D/TP/SmsProvider( 1459): query,matched:51, calling pid = 2283
D/TP/SmsProvider( 1459): match 51:Elapsed time : 1.478 ms
W/ContextImpl( 2914): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
I/Process ( 2928): Sending signal. PID: 2928 SIG: 9
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3040): MountEmulatedStorage()
E/Zygote  ( 3040): v2
I/libpersona( 3040): KNOX_SDCARD checking this for 1000
I/libpersona( 3040): KNOX_SDCARD not a persona
I/SELinux ( 3040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3040 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/SettingsProvider( 1017): name = block_emergency_message
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10048
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/ActivityManager( 1017): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
D/TP/MmsSmsProvider( 1459): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1459): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1459): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1459): (284) automatic index on im_threads(normal_thread_id)
D/TimaKeyStoreProvider( 3040): TimaSignature is unavailable
D/ActivityThread( 3040): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1459): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_1402/cgroup.procs: No such file or directory
D/ActivityManager( 1017): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/Mms/Conversation( 2283): deleteTempConversation(),deleted=0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
W/ResourcesManager( 3040): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/SQLiteLog( 3023): (284) automatic index on shooting_modes(title_id)
E/SQLiteLog( 3008): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
V/MediaScanner( 1225):  prescan time: 223ms (DB items: 141)
V/MediaScanner( 1225):     scan time: 140ms (Caching mode: true), (makeEntry time: 73ms ~52%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 363ms
V/MediaScanner( 1225): checked files: 133  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1225): checkDefaultSounds
D/MediaScanner( 1225): system alarm_alert  : Vwiurug_etwofi5wgg
I/ActivityManager( 1017): Process com.android.exchange (pid 2928)(adj 11) has died(292,989)
I/WifiCredService( 1301): onCreate
I/art     ( 1459): Explicit concurrent mark sweep GC freed 39575(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/13MB, paused 1.008ms total 100.596ms
W/ContextImpl( 3040): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
D/SmsProvider( 1459): Update uri=content://sms/outbox, match=8
D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
D/ActivityManager( 1017): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
D/Mms/SmsReceiverService( 2283): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2283): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2283): [SIM-1]sendFirstQueuedMessage()
D/MediaScanner( 1225): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1225): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1225): OK. notification_sound is already exist in setting DB.
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/SEAMService( 1017):  hashset_to_int_array returning null
D/MediaScanner( 1225): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/DSM     ( 3008): [Lines:107] Normal booted
D/DSM     ( 3008): [Lines:114] Boot completed
D/MediaScanner( 1225): OK. ringtone is already exist in setting DB.
D/WifiTimerReceiver( 1301): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1301): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1301): Action boot completed received
W/SEAMService( 1017):  hashset_to_int_array returning null
I/F_PHONE ( 3040): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
W/ContextImpl( 3040): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
E/SQLiteLog( 2914): (284) automatic index on seams_container_info(seams_container_id)
I/libpersona( 3059): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3059): MountEmulatedStorage()
I/libpersona( 3059): KNOX_SDCARD not a persona
E/Zygote  ( 3059): v2
I/SELinux ( 3059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3059): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SQLiteLog( 2914): (284) automatic index on seams_container_info(sp_id)
D/ActivityManager( 1017): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
D/WifiCredService( 1301): Action received :android.net.wifi.WIFI_STATE_CHANGED
E/WifiStateMachine( 1017): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1017): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1017): invaild command id : 215
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
W/SEAMService( 1017):  hashset_to_int_array returning null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/FactoryTestApp( 2606): [DummyFtClient$mBroadcastReceiver](2606) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2606): [DummyFtClient$mBroadcastReceiver](2606) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2606): [DummyFtClient$mBroadcastReceiver](2606) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/MediaScannerService( 1225): !@done scanning volume internal
D/TP/SmsProvider( 1459): query,matched:26, calling pid = 2283
D/TP/SmsProvider( 1459): match 26:Elapsed time : 3.111 ms
E/Zygote  ( 3079): MountEmulatedStorage()
E/Zygote  ( 3079): v2
I/libpersona( 3079): KNOX_SDCARD checking this for 1000
I/libpersona( 3079): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3079 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3059): TimaSignature is unavailable
D/ActivityThread( 3059): Added TimaKeyStore provider
I/SELinux ( 3079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/MediaScannerService( 1225): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/F_PHONE ( 3040): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3040): default registerAction()
I/F_PHONE ( 3040): [[com.sec.bcservice]] sendPendingMessage()
I/SELinux ( 3079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3079): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MessagingNotification( 2283): isBlockingModeEnabled() = false, Zen mode = 0
D/NearbySettings( 1301): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1301): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1301): MountReceiver.onReceive - Create mPrefHandler
D/TimaKeyStoreProvider( 3079): TimaSignature is unavailable
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/ActivityThread( 3079): Added TimaKeyStore provider
D/SettingsProvider( 1017): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
I/NearbySettings( 1301): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1301): MountReceiver.onReceive - Internal Path
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/art     ( 1017): Explicit concurrent mark sweep GC freed 37012(2033KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 2.310ms total 139.723ms
D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
D/ActivityManager( 1017): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3059): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
E/Zygote  ( 3098): MountEmulatedStorage()
E/Zygote  ( 3098): v2
I/libpersona( 3098): KNOX_SDCARD checking this for 1101
I/libpersona( 3098): KNOX_SDCARD not a persona
I/SELinux ( 3098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3098): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothBDAdrressReceiver( 3059): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 3059): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
I/ActivityManager( 1017): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3098 uid=1101 gids={41101, 9997} abi=armeabi-v7a
D/ActivityManager( 1017): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
D/SettingsProvider( 1017): name = personal_mode_enabled
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
W/ResourcesManager( 1459): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothBDTestService( 1459): onCreate()
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/BluetoothBDTestService( 1459): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1459): bd_address_path: /efs/bluetooth/bt_addr
D/TimaKeyStoreProvider( 3098): TimaSignature is unavailable
E/BluetoothBDTestService( 1459): already exist!( /efs/bluetooth/bt_addr ), file length: 17
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
D/Mms/SmsReceiver( 2283): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2283): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2283): isDefault true
D/ActivityThread( 3098): Added TimaKeyStore provider
W/ResourcesManager( 3079): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/BadgeProvider( 1562): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3098): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
D/TP/MmsProvider( 1459): Query uri=content://mms, match=0, calling pid = 2283
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
V/SmartcardService( 3098): main Received broadcast
V/SmartcardService( 3098): Starting smartcard service after boot completed
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
E/Zygote  ( 3113): MountEmulatedStorage()
E/Zygote  ( 3113): v2
I/libpersona( 3113): KNOX_SDCARD checking this for 1000
I/SELinux ( 3113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3113): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3113 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/MediaScanner( 1225): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/ActivityManager( 1017): Killing 1544:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
E/SELinux ( 3113): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
D/ActivityManager( 1017): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ResourcesManager( 1459): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 1459): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
W/ResourcesManager( 1459): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 1773:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/TimaKeyStoreProvider( 3113): TimaSignature is unavailable
D/ActivityThread( 3113): Added TimaKeyStore provider
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/SmartcardBootCompleteReceiver( 1301): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1301): Received intent with action - android.intent.action.BOOT_COMPLETED
W/ActivityThread( 3079): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
I/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
W/ResourcesManager( 3113): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SecureStorage(  334): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
V/MediaScanner( 1225): processDirectory :  /storage/emulated/0
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
I/ActivityManager( 1017): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3131 uid=10157 gids={50157, 9997} abi=armeabi-v7a
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/MediaScanner( 1225): Skipping:,
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(75ebcf7
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Waited long enough for: ServiceRecord{111b7218 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
E/Zygote  ( 3131): MountEmulatedStorage()
E/Zygote  ( 3131): v2
I/libpersona( 3131): KNOX_SDCARD checking this for 10157
I/libpersona( 3131): KNOX_SDCARD not a persona
D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
I/SELinux ( 3131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3131): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
V/MediaScanner( 1225): processDirectory :  /storage/extSdCard
W/MediaScanner( 1225): Error opening directory, reason : Permission denied.
W/MediaScanner( 1225): 7klwibgf7fxlKdCbid7
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 3079): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/LcdtestApp( 3079): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
D/TP/MmsSmsProvider( 1459): query,matched:200, calling pid = 2283
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
V/MediaScanner( 1225):  prescan time: 95ms (DB items: 27)
V/MediaScanner( 1225):     scan time: 26ms (Caching mode: true), (makeEntry time: 18ms ~69%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 24ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 145ms
V/MediaScanner( 1225): checked files: 10  directories : 17  (I: 0, U: 0)
D/Launcher.Model( 1480): reloadBadges entered.
D/BadgeProvider( 1562): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
D/BadgeProvider( 1562): sendNotify, [notify] : null
D/BadgeProvider( 1562): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1562): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1562): update, [UpdateCount] : 1
D/TP/MmsSmsProvider( 1459): match 200:Elapsed time : 4.892 ms
W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_1544/cgroup.procs: No such file or directory
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3131): TimaSignature is unavailable
D/ActivityThread( 3131): Added TimaKeyStore provider
I/SecureStorage( 2947): [INFO]: SPID(0x00000002)Processing data has been completed
I/SecureStorage( 2947): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
E/Zygote  ( 3149): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3149 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3149): v2
I/libpersona( 3149): KNOX_SDCARD checking this for 1000
I/SELinux ( 3149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3149): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Killing 1615:com.google.android.apps.maps/u0a107 (adj 15): empty #31
I/SELinux ( 3149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SmartcardBootCompleteReceiver( 1301): Broadcast sent with current lockscreen type
D/MediaScannerService( 1225): !@done scanning volume external
D/Mms/MessagingNotification( 2283): setBadgeCount(), count=0
D/FactoryTestApp( 2606): [DummyFtClient$mBroadcastReceiver](2606) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2606): [DummyFtClient$mBroadcastReceiver](2606) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2606): [DummyFtClient$sendBootCompletedAndFinish](2606) ...
D/FactoryTestApp( 2606): [Support$Values.getString](2606) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2606): [ModuleCommon$isConnectionModeNone](2606) mConnectionMode = gsm
D/Mms/MessagingNotification( 2283): remove alarm
D/TimaKeyStoreProvider( 3149): TimaSignature is unavailable
D/ActivityThread( 3149): Added TimaKeyStore provider
I/ActivityManager( 1017): Killing 2099:com.vlingo.midas/u0a31 (adj 15): empty #31
D/FactoryTestApp( 2606): [IPCWriterToSecPhoneService$ResponseWriter](2606) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2606): [IPCWriterToSecPhoneService$connectToSecPhoneService](2606)  
W/ContextImpl( 2606): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/ActivityManager( 1017): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/FactoryTestApp( 2606): [IPCWriterToSecPhoneService$onServiceConnected](2606) connected done
W/ResourcesManager( 3131): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/FactoryTestApp( 2606): [IPCWriterToSecPhoneService$write](2606) Send Response Message to SecPhone
D/FactoryTestApp( 2606): [IPCWriterToSecPhoneService$write](2606) Response ��
E/SMD     (  288): DCD OFF
D/AT_Distributor(  309): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 2606): [IPCWriterToSecPhoneService$handleMessage](2606) Send BOOTING COMPLETED done
D/TP/SmsProvider( 1459): query,matched:0, calling pid = 2283
D/TP/SmsProvider( 1459): match 0:Elapsed time : 1.256 ms
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/Mms/MessagingNotification( 2283): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 2283): [end]    nonBlockingUpdateMessageIndicator() consume time = 825.422343
D/TP/SmsProvider( 1459): query,matched:0, calling pid = 2283
D/TP/SmsProvider( 1459): match 0:Elapsed time : 1.252 ms
D/TP/SmsProvider( 1459): query,matched:51, calling pid = 2283
D/TP/SmsProvider( 1459): match 51:Elapsed time : 1.068 ms
D/Mms/MessagingNotification( 2283): isBlockingModeEnabled() = false, Zen mode = 0
E/USB_UICC(  297): Timeout! No signal received. Retry num = 28
I/KnoxUsageLogPro( 3113): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
I/KnoxUsageLogPro( 3113): savePreference: key = previous_sys_time value = 1448385974210
D/BadgeProvider( 1562): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/KnoxUsageLogPro( 3113): premStatus:2
I/KnoxUsageLogPro( 3113): isEulaShown : false
I/KnoxUsageLogPro( 3113): KnoxUsageReceiver onReceive : not Processible, just return
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3168): MountEmulatedStorage()
W/libprocessgroup( 1017): failed to open /acct/uid_10138/pid_1773/cgroup.procs: No such file or directory
E/Zygote  ( 3168): v2
W/libprocessgroup( 1017): failed to open /acct/uid_10107/pid_1615/cgroup.procs: No such file or directory
I/libpersona( 3168): KNOX_SDCARD checking this for 10085
I/libpersona( 3168): KNOX_SDCARD not a persona
I/SELinux ( 3168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ServiceManager(  314): Waiting for service AtCmdFwd...
I/SELinux ( 3168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3168 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1017): failed to open /acct/uid_10031/pid_2099/cgroup.procs: No such file or directory
I/ActivityManager( 1017): Killing 2123:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/art     (  305): Explicit concurrent mark sweep GC freed 8768(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 22.010ms
D/TimaKeyStoreProvider( 3168): TimaSignature is unavailable
D/ActivityThread( 3168): Added TimaKeyStore provider
D/AT_Distributor(  309): SetAtdStatus(), 1_1_0
D/AT_Distributor(  309): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 16.885ms
D/Launcher.Model( 1480): reloadBadges entered.
D/BadgeProvider( 1562): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1562): sendNotify, [notify] : null
D/BadgeProvider( 1562): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1562): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1562): update, [UpdateCount] : 1
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 593us total 16.519ms
I/iu.UploadsManager( 2052): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
D/[SBeam] ( 1301): SBeamEnabler.initPreferenceForSbeam : 0
E/Zygote  ( 3185): MountEmulatedStorage()
E/Zygote  ( 3185): v2
I/libpersona( 3185): KNOX_SDCARD checking this for 10159
I/libpersona( 3185): KNOX_SDCARD not a persona
I/SELinux ( 3185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3185): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3185 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1496:com.android.printspooler/u0a136 (adj 15): empty #31
D/Mms/MessagingNotification( 2283): setBadgeCount(), count=0
W/ResourcesManager( 3168): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3168): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3168): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3168): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3168): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3168): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
I/ActivityManager( 1017): Killing 2192:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
D/TimaKeyStoreProvider( 3185): TimaSignature is unavailable
D/ActivityThread( 3185): Added TimaKeyStore provider
D/Mms/MessagingNotification( 2283): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 2283): remove alarm
I/SettingSearch/SearchIntentReceiver( 1301): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1301): search setting db init!!
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
I/SettingSearch/SearchIntentReceiver( 1301): BOOT_COMPLETED call InitSerachDBThread thread start!
D/BluetoothMediaBrowser( 2644):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
D/TP/SmsProvider( 1459): query,matched:0, calling pid = 2283
D/TP/SmsProvider( 1459): match 0:Elapsed time : 1.465 ms
I/DIAGMON_AGENT( 3149): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
D/Mms/SmsReceiverService( 2283): [end]    handleBootCompleted() consume time = 215.528073
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_10050/pid_2123/cgroup.procs: No such file or directory
E/Zygote  ( 3203): MountEmulatedStorage()
I/libpersona( 3203): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3203): v2
I/libpersona( 3203): KNOX_SDCARD not a persona
I/SELinux ( 3203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3203 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1646:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/KnoxUsageLogPro( 3113): savePreference: key = previous_elapsed_time value = 34614
D/BluetoothMediaBrowser( 2644): no now playing list
D/BluetoothMediaBrowser( 2644):  getNowPlayingId now playing id : -1
I/Intent to TravelDirActivity( 3185): inside TravelBroadcastReceiver
I/iu.UploadsManager( 2052): End new media; added: 0, uploading: 0, time: 134 ms
D/TimaKeyStoreProvider( 3203): TimaSignature is unavailable
D/ActivityThread( 3203): Added TimaKeyStore provider
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_10136/pid_1496/cgroup.procs: No such file or directory
E/Zygote  ( 3218): MountEmulatedStorage()
E/Zygote  ( 3218): v2
I/libpersona( 3218): KNOX_SDCARD checking this for 1000
I/libpersona( 3218): KNOX_SDCARD not a persona
I/SELinux ( 3218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3218): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3218 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2309:com.sec.android.omc/1000 (adj 15): empty #31
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3218): TimaSignature is unavailable
D/ActivityThread( 3218): Added TimaKeyStore provider
W/ResourcesManager( 3203): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 3234): MountEmulatedStorage()
E/Zygote  ( 3234): v2
I/libpersona( 3234): KNOX_SDCARD checking this for 10150
I/libpersona( 3234): KNOX_SDCARD not a persona
I/SELinux ( 3234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3234 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/SELinux ( 3234): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1017): failed to open /acct/uid_10113/pid_2192/cgroup.procs: No such file or directory
E/BluetoothHeadset( 2947): BTStateChangeCB is registed
D/BluetoothHeadset( 2947): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1017): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 2947): BluetoothHeadset service is binded
D/BluetoothA2dp( 2947): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1017): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
D/TimaKeyStoreProvider( 3234): TimaSignature is unavailable
D/ActivityThread( 3234): Added TimaKeyStore provider
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3249): MountEmulatedStorage()
I/libpersona( 3249): KNOX_SDCARD checking this for 10160
E/Zygote  ( 3249): v2
I/libpersona( 3249): KNOX_SDCARD not a persona
I/SELinux ( 3249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3249 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 3249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2347:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_1646/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 3249): TimaSignature is unavailable
D/ActivityThread( 3249): Added TimaKeyStore provider
I/FOTA    ( 3203): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
W/ResourcesManager( 3249): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2309/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_2347/cgroup.procs: No such file or directory
D/BluetoothA2dp( 2947): Proxy object connected
I/DBG_DM  ( 3203): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
V/AlarmManager( 1017): waitForAlarm result :8
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/DIAGMON_AGENT( 3149): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT( 3149): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
D/[0]UMC:UMCContentProvider( 3249): @onCreate
D/[0]UMC:Core( 3249): onCreate(): 
D/[0]UMC:Core( 3249): @isManagedProfileUser
D/[0]UMC:Core( 3249): userId: 0
D/[0]UMC:Core( 3249): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 3249): userInfo.isManagedProfile() : false
I/DBG_DM  ( 3203): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
I/DBG_DM  ( 3203): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/DIAGMON_AGENT( 3149): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 3149): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 3149): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 3149): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/[0]UMC:DeviceInfo( 3249): USA==US==
D/SettingsProvider( 1017): name = next_alarm_formatted
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10085
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/DBG_DM  ( 3203): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
W/ContextImpl( 3203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
D/ActivityManager( 1017): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
D/OverheatReceiver( 1180): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1180): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1180): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1180): isSafeMode = false
D/BootupListener( 1459): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/PhoneUtilsCommon( 1459): isSupportVoLTE is false.
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 3203): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/DBG_DM  ( 3203): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 3203): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 3203): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/ActivityManager( 1017): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3272 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3272): MountEmulatedStorage()
E/Zygote  ( 3272): v2
I/libpersona( 3272): KNOX_SDCARD checking this for 1000
I/libpersona( 3272): KNOX_SDCARD not a persona
I/SELinux ( 3272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_DM  ( 3203): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/Telecom ( 1434): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
I/SELinux ( 3272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3272): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
I/DBG_DM  ( 3203): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
D/ActivityManager( 1017): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
I/DBG_DM  ( 3203): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3203): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 3203): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
I/DBG_DM  ( 3203): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
D/TimaKeyStoreProvider( 3272): TimaSignature is unavailable
D/ActivityThread( 3272): Added TimaKeyStore provider
W/ContextImpl( 3203): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
E/Zygote  ( 3287): MountEmulatedStorage()
I/libpersona( 3287): KNOX_SDCARD checking this for 10057
E/Zygote  ( 3287): v2
I/libpersona( 3287): KNOX_SDCARD not a persona
I/SELinux ( 3287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3287 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 3287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3287): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(155/onStartCommand)] 
D/ActivityManager( 1017): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/Telecom ( 1434): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
I/DBG_DM  ( 3203): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/TimaKeyStoreProvider( 3287): TimaSignature is unavailable
D/ActivityThread( 3287): Added TimaKeyStore provider
I/DBG_DM  ( 3203): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
D/AndroidRuntime( 3267): 
D/AndroidRuntime( 3267): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager( 1017): Killing 2363:com.sec.tcpdumpservice/1000 (adj 15): empty #31
D/AndroidRuntime( 3267): CheckJNI is OFF
D/AndroidRuntime( 3267): readGMSProperty: start
D/AndroidRuntime( 3267): readGMSProperty: already setted!!
D/AndroidRuntime( 3267): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3267): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3267): readGMSProperty: end
D/AndroidRuntime( 3267): addProductProperty: start
W/art     ( 3168): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 281.404ms
D/USER_AGENT( 3249): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2363/cgroup.procs: No such file or directory
V/audio_hw_primary(  283): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  283): audio_extn_get_parameters: returns 
V/msm8974_platform(  283): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  283): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  283): key: 'call_forwarding' value: ''
V/InCall  ( 1947): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1947): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1947): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
D/ScoverManager( 1947): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1947): InCallUtils - isCoverClosed false
I/Telecom ( 1434): ProximitySensorManager: Proximity wake lock already released
D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1947): InCallUtils - isCoverClosed false
I/InCall  ( 1947): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1947): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1947): InCallPresenter -  - dismissCoverDialog()...
E/USB_UICC(  297): Timeout! No signal received. Retry num = 29
D/[0]UMC:AdminManager( 3249): init - start
I/InCall  ( 1947): CallSContextMotion - stopPutDownListening
D/InCall  ( 1947): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
D/PhoneStatusBarView( 1180): setCallBackground:0
E/AffinityControl( 3267): AffinityControl: registerfunction enter
I/ServiceManager(  314): Waiting for service AtCmdFwd...
E/Tethering( 1017): No numeric data
E/Tethering( 1017): No numeric data
E/Tethering( 1017): No numeric data
E/Tethering( 1017): No numeric data
I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
D/AndroidRuntime( 3267): Calling main entry com.android.commands.am.Am
I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
E/Tethering( 1017): No numeric data
D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
D/InCall  ( 1947): InCallUtils - isCoverClosed false
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Tethering( 1017): No numeric data
D/[0]UMC:AdminManager( 3249): loadAdmins
I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3322 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3322): MountEmulatedStorage()
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
E/Zygote  ( 3322): v2
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SELinux ( 3322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/libpersona( 3322): KNOX_SDCARD checking this for 10009
I/libpersona( 3322): KNOX_SDCARD not a persona
I/SELinux ( 3322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
E/SELinux ( 3322): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/DBG_POLICYDM( 3272): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/ActivityManager( 1017): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3337 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/DBG_POLICYDM( 3272): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 3272): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/[0]UMC:AdminManager( 3249): init - end
D/GSLBManager( 3249): migrateStoredUrlFromOldPref
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
E/Zygote  ( 3337): MountEmulatedStorage()
I/libpersona( 3337): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3337): v2
I/libpersona( 3337): KNOX_SDCARD not a persona
I/SELinux ( 3337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/TimaKeyStoreProvider( 3322): TimaSignature is unavailable
D/ActivityThread( 3322): Added TimaKeyStore provider
I/SELinux ( 3337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3337): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 3272): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/LocationManagerService( 1017): getProviders()=[passive]
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1017): Set to : 0
D/GSLBManager( 3249): migrateStoredUrlFromOldPref : Migration Not Needed
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1480
D/Launcher.HomeView( 1480): onPause
D/AndroidRuntime( 3267): Shutting down VM
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/[0]UMC:UMCAdmin( 3249): deactivateUMCAdminIfNotRequired : -1
I/MotionRecognitionService( 1017): Plugged
E/[0]UMC:Utils( 3249): Admin not found in package com.samsung.knoxpb.mdm
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/PowerUI ( 1180): Cable  true --> true mBootCompleted : true
E/[0]UMC:Utils( 3249): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/PowerUI ( 1180): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
D/[0]UMC:UMCAdmin( 3249): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3249): isContainer : 0
D/TimaKeyStoreProvider( 3337): TimaSignature is unavailable
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
D/ActivityThread( 3337): Added TimaKeyStore provider
D/VideoCallManager( 1947): Instantiating VideoCallManager
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
V/HeadsetService( 2644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2644): Disconnected process message: 10
E/        ( 1947): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
I/GFX construct_block_size_descriptor_2d second part( 1947): took 2.336094ms for 0*0 texture 0
E/[0]UMC:UMCAdmin( 3249): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 3249): isContainer : 0
D/[0]UMC:UMCAdmin( 3249): deactivateUMCAdmin - UMC App Admin deactivated
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/GFX generate_partition_tables( 1947): took 5.289062ms for 0*0 texture 0
I/GFX raster( 1947): took 11.503592ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1947): Bitmap=0xb8a5e740 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8a76950 counterpartCT=4 counterpartW=176 counterparth=144
E/        ( 1947): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/Adreno-EGL( 1947): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1947): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1947): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1947): Local Branch: 
I/Adreno-EGL( 1947): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1947): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1947):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3358): MountEmulatedStorage()
E/Zygote  ( 3358): v2
I/libpersona( 3358): KNOX_SDCARD checking this for 10174
I/libpersona( 3358): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 3272): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3272): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/SELinux ( 3358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3358 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/GFX GPU raster( 1947): eglCreateImageKHR: EGL_SUCCESS
I/SELinux ( 3358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/glCompressedTexImage2D( 1947): took 0.439010ms for 320*61440 texture 37809
E/SELinux ( 3358): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 3272): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
I/draw setup( 1947): took 11.293854ms for 320*240 texture 37809
E/GFX GPU raster( 1947): drawn
I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
D/ActivityManager( 1017): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
I/GFX GPU raster ASTC( 1947): took 42.111094ms for 320*240 texture 12
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
I/GFX raster( 1947): took 42.168749ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1947): Bitmap=0xb8a76950 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8a78c90 counterpartCT=4 counterpartW=320 counterparth=240
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/TimaKeyStoreProvider( 3358): TimaSignature is unavailable
D/ActivityThread( 3358): Added TimaKeyStore provider
I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
E/        ( 1947): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1947): eglCreateImageKHR: EGL_SUCCESS
D/[0]UMC:GuardService( 3249): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
I/glCompressedTexImage2D( 1947): took 0.375573ms for 480*122880 texture 37813
I/draw setup( 1947): took 0.924583ms for 480*640 texture 37813
E/GFX GPU raster( 1947): drawn
D/[0]UMC:CoreReceiver( 3249): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 3249):  check PreETag 
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
I/GFX GPU raster ASTC( 1947): took 7.712866ms for 480*640 texture 12
I/GFX raster( 1947): took 7.812188ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1947): Bitmap=0xb8a78c90 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8ca7120 counterpartCT=4 counterpartW=480 counterparth=640
I/DBG_DM  ( 3203): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1017): [SO] activate (ident=0xb8f7f6e0, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SensorManager( 1017): unregisterListener ::   
E/        ( 1947): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
I/GFX GPU raster( 1947): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1947): took 0.359323ms for 440*116864 texture 37809
I/draw setup( 1947): took 0.839219ms for 440*330 texture 37809
E/GFX GPU raster( 1947): drawn
I/GFX GPU raster ASTC( 1947): took 4.436927ms for 440*330 texture 12
I/GFX raster( 1947): took 4.517240ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1947): Bitmap=0xb8ca7120 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8cbb510 counterpartCT=4 counterpartW=440 counterparth=330
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb8f7f6e0, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
V/ActivityThread( 1480): updateVisibility : ActivityRecord{f7b28c2 token=android.os.BinderProxy@18cc644a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1480): onStop
V/ActivityThread( 1480): updateVisibility : ActivityRecord{f7b28c2 token=android.os.BinderProxy@18cc644a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
W/art     ( 3267): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/        ( 1947): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1947): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1947): took 0.490053ms for 480*163840 texture 37811
I/draw setup( 1947): took 1.099583ms for 480*640 texture 37811
E/GFX GPU raster( 1947): drawn
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/GFX GPU raster ASTC( 1947): took 7.156039ms for 480*640 texture 12
,I/GFX raster( 1947): took 7.234946ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1947): Bitmap=0xb8cab320 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8cbb048 counterpartCT=4 counterpartW=480 counterparth=640
,I/DBG_DM  ( 3203): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,I/WebViewFactory( 3358): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/Launcher( 1480): onTrimMemory. Level: 20
,I/LibraryLoader( 3358): Time to load native libraries: 3 ms (timestamps 6062-6065)
I/LibraryLoader( 3358): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/        ( 1947): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1947): took 2.423593ms for 0*0 texture 0
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1017): [SO] currT = 36100626703, prevT = 35740283578, diff = 360343125, [0.211 0.153 10.151]
,I/GFX generate_partition_tables( 1947): took 7.449531ms for 0*0 texture 0
,D/SensorService( 1017): [SO] 0.211 0.153 10.151
D/SensorService( 1017): [SO] [100 -> 255]
I/GFX raster( 1947): took 11.889478ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1947): Bitmap=0xb8ca49e0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8ca4b00 counterpartCT=4 counterpartW=176 counterparth=144
,I/ActivityManager( 1017): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3383 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2250:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/Zygote  ( 3383): MountEmulatedStorage()
I/libpersona( 3383): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3383): v2
I/libpersona( 3383): KNOX_SDCARD not a persona
I/SELinux ( 3383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 1947): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1947): took 2.142083ms for 0*0 texture 0
I/GFX generate_partition_tables( 1947): took 6.241667ms for 0*0 texture 0
I/art     (  305): Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 31.900ms
I/GFX raster( 1947): took 10.454323ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1947): Bitmap=0xb8ca4d20 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8ca4cc0 counterpartCT=4 counterpartW=176 counterparth=144
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 17.214ms
D/ScoverManager( 1947): registerListener
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1017): registerListenerCallback : binder = android.os.BinderProxy@843f301, pid : 1947, uid : 1001, type : 1
,D/TimaKeyStoreProvider( 3383): TimaSignature is unavailable
D/ActivityThread( 3383): Added TimaKeyStore provider
,V/WebViewChromiumFactoryProvider( 3358): Binding Chromium to main looper Looper (main, tid 1) {3d9df405}
,I/LibraryLoader( 3358): Expected native library version number "",actual native library version number ""
I/chromium( 3358): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.499ms,
,D/InCall  ( 1947): InCallPresenter -  - Finished InCallPresenter.setUp
,W/ResourcesManager( 3383): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 3272): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/BrowserStartupController( 3358): Initializing chromium process, singleProcess=true
,W/art     ( 3358): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3358): ApplicationContext is null in ApplicationStatus
,I/DBG_POLICYDM( 3272): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,W/TRThreadPoolExecutor( 3287): Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,D/[SBeam] ( 1301): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1301): SBeamEnabler.isSBeamSupported : EXIST
,D/[0]UMC:CoreReceiver( 3249): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 3249): Enter loadList
,D/[0]UMC:CoreReceiver( 3249): handleAutoEnrollmentAndUMCAdminDeactivation
,D/[0]UMC:UMCAdmin( 3249): deactivateUMCAdminIfNotRequired : -1
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 9
,I/DBG_POLICYDM( 3272): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 9
,I/SearchServiceFactory( 3287): refreshing search history.
,W/chromium( 3358): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 3358): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 3358): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 9
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/[0]UMC:Utils( 3249): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 3249): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3249): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3249): isContainer : 0
,I/Adreno-EGL( 3358): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3358): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3358): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3358): Local Branch: 
I/Adreno-EGL( 3358): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3358): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3358):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/Zygote  ( 3409): MountEmulatedStorage(),
E/Zygote  ( 3409): v2
I/libpersona( 3409): KNOX_SDCARD checking this for 10086,
I/libpersona( 3409): KNOX_SDCARD not a persona
,D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
,I/SELinux ( 3409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3409 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2399:com.wsomacp/u0a25 (adj 15): empty #31,
E/[0]UMC:UMCAdmin( 3249): No active admin owned by uid 10160,
D/[0]UMC:UMCAdmin( 3249): isContainer : 0
,I/SELinux ( 3409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1017): Killing 2451:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
D/[0]UMC:UMCAdmin( 3249): deactivateUMCAdmin - UMC App Admin deactivated
,E/SELinux ( 3409): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:ByodSetupStarter( 3249): Container ID : 0,
,E/Zygote  ( 3420): MountEmulatedStorage()
E/Zygote  ( 3420): v2,
I/libpersona( 3420): KNOX_SDCARD checking this for 10003
I/libpersona( 3420): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3420 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 3420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
E/SELinux ( 3420): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/[0]UMC:Utils( 3249): checkAppScreen() : com.example.hello
,I/[0]UMC:Core( 3249): shutdown
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/TimaKeyStoreProvider( 3409): TimaSignature is unavailable
D/[0]UMC:GuardService( 3249): @GuardService - stopService Result = true
D/ActivityThread( 3409): Added TimaKeyStore provider
,I/art     ( 3249): System.exit called, status: 0
I/AndroidRuntime( 3249): VM exiting with result code 0, cleanup skipped.
,E/Tethering( 1017): No numeric data
E/Tethering( 1017): No numeric data
I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/Tethering( 1017): No numeric data
D/TimaKeyStoreProvider( 3420): TimaSignature is unavailable
,D/ActivityThread( 3420): Added TimaKeyStore provider
,I/SurfaceFlinger(  258): id=7 Removed Mauncher (5/8)
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0,
I/DBG_POLICYDM( 3272): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
E/Tethering( 1017): No numeric data,
I/DBG_POLICYDM( 3272): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 3272): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 3272): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 3272): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2015/11/27/14:10:13
,I/DBG_POLICYDM( 3272): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2015/11/24/18:26:15
,I/DBG_POLICYDM( 3272): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2250/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_2399/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3272): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 3272): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_2451/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3272): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 3272): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 3272): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] ,
,I/DBG_POLICYDM( 3272): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0,
,I/ActivityManager( 1017): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3249)(adj 0) has died(249,1018)
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/daemonapp( 1313): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1313): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1313): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/UserAnalysis.PlaceProvider( 3420): PlaceProvider onCreate()
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,W/NotificationAccessSettings( 1301): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/UserAnalysis.SecureDbManager( 3420): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3420): SecurePlaceDbHelper() 
D/UserAnalysis( 3420): Create SecureDbHelper
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,I/DBG_POLICYDM( 3272): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,W/ResourcesManager( 1301): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 22811(1177KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.345ms total 141.423ms
,D/IntelligenceServiceApplication( 3420): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3420): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,D/daemonapp( 1313): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,D/daemonapp( 1313): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
E/USB_UICC(  297): Timeout! No signal received. Retry num = 30
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1313): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/comsamsunglog( 1313): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1313): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1313): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1313): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1313): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1313): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/IntelligenceServiceApplication( 3420): no applications having user consent for prediction
,E/Zygote  ( 3461): MountEmulatedStorage()
E/Zygote  ( 3461): v2
I/libpersona( 3461): KNOX_SDCARD checking this for 10060
I/libpersona( 3461): KNOX_SDCARD not a persona
,I/SELinux ( 3461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3461 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 2465:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,E/UpdateRequestReceiver( 3409): ignoring update request
I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/SELinux ( 3461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/SettingsProvider( 1017): name = aw_daemon_service_key_version_check
,E/SELinux ( 3461): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10162
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,E/UpdateRequestReceiver( 3409): ignoring update request
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3461): TimaSignature is unavailable
,D/ActivityThread( 3461): Added TimaKeyStore provider,
,E/Zygote  ( 3480): MountEmulatedStorage()
E/Zygote  ( 3480): v2
I/libpersona( 3480): KNOX_SDCARD checking this for 1000
I/libpersona( 3480): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3480 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Killing 2662:com.android.keychain/1000 (adj 15): empty #31
I/ActivityManager( 1017): Killing 2622:com.android.calendar/u0a135 (adj 15): empty #32
I/ActivityManager( 1017): Killing 2496:com.sec.android.app.camera/u0a139 (adj 15): empty #33
,I/SELinux ( 3480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,W/chromium( 3358): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
E/USB_UICC(  297): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  297): usb_uicc_init_qmi failed ! 
I/USB_UICC(  297): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  297): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/daemonapp( 1313): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,V/PlaceDetection v1.0.19 ( 3420): [PlaceDetection::stopService] Service stopped.
,D/daemonapp( 1313): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/ScoverManager( 1301): serviceVersion : 16908288
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/DBG_POLICYDM( 3272): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/daemonapp( 1313): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1313): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1313): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1313): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/UpdateRequestReceiver( 3409): ignoring update request
,D/TimaKeyStoreProvider( 3480): TimaSignature is unavailable
,I/DBG_POLICYDM( 3272): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/ActivityThread( 3480): Added TimaKeyStore provider
,I/WebViewFactory( 3287): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,E/UpdateRequestReceiver( 3409): ignoring update request
,E/daemonapp( 1313): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1313): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1313): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1448385976377
,D/daemonapp( 1313): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1448404500000
D/daemonapp( 1313): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
W/art     ( 3358): Attempt to remove local handle scope entry from IRT, ignoring
D/daemonapp( 1313): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/daemonapp( 1313): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448404500000
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_2465/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_2496/cgroup.procs: No such file or directory,
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2662/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_2622/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 3409): ignoring update request
,E/UpdateRequestReceiver( 3409): ignoring update request
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 3287): Time to load native libraries: 2 ms (timestamps 6824-6826)
,I/LibraryLoader( 3287): Expected native library version number "",actual native library version number ""
,I/DBG_FMMDM( 3480): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,E/Zygote  ( 3512): MountEmulatedStorage()
,E/Zygote  ( 3512): v2
I/libpersona( 3512): KNOX_SDCARD checking this for 10092
I/libpersona( 3512): KNOX_SDCARD not a persona
,I/DBG_FMMDM( 3480): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
I/DBG_FMMDM( 3480): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
I/SELinux ( 3512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_FMMDM( 3480): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
I/SELinux ( 3512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3512): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/art     ( 3287): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager( 1017): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3512 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2775:com.android.email/u0a145 (adj 15): empty #31
,W/TRThreadPoolExecutor( 3287): Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3512): TimaSignature is unavailable
D/ActivityThread( 3512): Added TimaKeyStore provider
E/Zygote  ( 3530): MountEmulatedStorage()
,E/Zygote  ( 3530): v2
I/libpersona( 3530): KNOX_SDCARD checking this for 1000
I/libpersona( 3530): KNOX_SDCARD not a persona
I/SELinux ( 3530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3530 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3530): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 3420): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3420): Constructor Preference
,D/TimaKeyStoreProvider( 3530): TimaSignature is unavailable
,D/ActivityThread( 3530): Added TimaKeyStore provider
,D/daemonapp( 1313): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 125
,D/daemonapp( 1313): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1448404500000
,I/PCWCLIENTTRACE_LOG( 3530): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3530): DEFAULT_LOGLEVEL : 3
,W/libprocessgroup( 1017): failed to open /acct/uid_10145/pid_2775/cgroup.procs: No such file or directory
,W/AwContents( 3358): onDetachedFromWindow called when already detached. Ignoring
,I/LockPatternUtils( 1301): isSmartCardAuthenticationAvailable: false
,D/PhoneWindow( 3358): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 3358): *FMB* installDecor flags : 8456448
,D/Settings_Utils( 1301): isSupportVNFestival SM-A500FU XEO
,D/SystemWebViewEngine( 3358): CordovaWebView is running on device made by: samsung
,W/art     ( 3358): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3358): Attempt to remove local handle scope entry from IRT, ignoring
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3530): new DMDBOpenHelper instance
,I/sCloudBackupApp( 3461): sCloudBackupApp Version Info : 4.04.8.KK_APP
,D/PCWCLIENTTRACE_DMContentProvider( 3530): [URIMatcher] - result : 2
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,E/Zygote  ( 3550): MountEmulatedStorage()
I/libpersona( 3550): KNOX_SDCARD checking this for 10062
E/Zygote  ( 3550): v2
I/libpersona( 3550): KNOX_SDCARD not a persona
I/SELinux ( 3550): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3550): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3550): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3550 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2757:com.samsung.android.sm/1000 (adj 15): empty #31
,I/DBG_FMMDM( 3480): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3480): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3480): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3550): TimaSignature is unavailable
D/ActivityThread( 3550): Added TimaKeyStore provider
E/Zygote  ( 3565): MountEmulatedStorage()
E/Zygote  ( 3565): v2
I/libpersona( 3565): KNOX_SDCARD checking this for 1000
I/libpersona( 3565): KNOX_SDCARD not a persona
I/SELinux ( 3565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3565 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2887:flipboard.boxer.app/u0a99 (adj 15): empty #31
I/ActivityManager( 1017): Killing 2435:com.sec.android.gallery3d/u0a44 (adj 15): empty #32
I/SELinux ( 3565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3565): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/comdaemonstockapp( 1313): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1313): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3565): TimaSignature is unavailable
,D/ActivityThread( 3565): Added TimaKeyStore provider
,E/Zygote  ( 3580): MountEmulatedStorage()
,E/Zygote  ( 3580): v2
I/libpersona( 3580): KNOX_SDCARD checking this for 10166
I/libpersona( 3580): KNOX_SDCARD not a persona
,I/SELinux ( 3580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3580): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3580 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1017): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/TimaKeyStoreProvider( 3580): TimaSignature is unavailable
,E/Zygote  ( 3596): MountEmulatedStorage()
I/libpersona( 3596): KNOX_SDCARD checking this for 10092
E/Zygote  ( 3596): v2
I/libpersona( 3596): KNOX_SDCARD not a persona
D/ActivityThread( 3580): Added TimaKeyStore provider
,I/SELinux ( 3596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3596): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3596 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2757/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_2887/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_2435/cgroup.procs: No such file or directory
,I/dhcpcd  ( 2168): wlan0: sending IPv6 Router Solicitation
D/TimaKeyStoreProvider( 3596): TimaSignature is unavailable
,I/dhcpcd  ( 2168): wlan0: no IPv6 Routers available
,D/ActivityThread( 3596): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,I/DBG_FMMDS( 3565): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3565): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/PCWCLIENTTRACE_DMContentProvider( 3530): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3565): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_FMMDS( 3565): [50.18.150420][Line:43][xdbDBInit] 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ExternalOEMControlProvider( 3550): onCreate
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/OpenGLRenderer( 3358): Render dirty regions requested: true
,W/art     ( 3287): Attempt to remove local handle scope entry from IRT, ignoring
,E/Zygote  ( 3618): MountEmulatedStorage()
E/Zygote  ( 3618): v2
I/libpersona( 3618): KNOX_SDCARD checking this for 1000
I/libpersona( 3618): KNOX_SDCARD not a persona
,I/SELinux ( 3618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3618 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3618): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PhoneWindow( 3358): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3358): *FMB* isFloatingMenuEnabled return false
D/SettingsProvider( 1017): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/art     (  305): Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 21.988ms
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/TimaKeyStoreProvider( 3618): TimaSignature is unavailable
,D/ActivityThread( 3618): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.237ms
,D/InputDispatcher( 1017): Focus entered window: 3358
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3358): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3358): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3358): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
W/ResourcesManager( 3618): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/OpenGLRenderer( 3358): Enabling debug mode 0
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.862ms
,I/ActivityManager( 1017): Killing 2138:flipboard.app/u0a98 (adj 15): empty #31
,I/ServiceMode( 3618): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 3618): setReferenceIsDumpState : 0
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3642): MountEmulatedStorage(),
E/Zygote  ( 3642): v2
I/libpersona( 3642): KNOX_SDCARD checking this for 1000
I/libpersona( 3642): KNOX_SDCARD not a persona
,I/SELinux ( 3642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3642 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 2258:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/SELinux ( 3642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3642): TimaSignature is unavailable
,D/ActivityThread( 3642): Added TimaKeyStore provider
,W/ResourcesManager( 3580): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3580): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_2138/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2258/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
I/FactoryTestApp( 2606): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3165)  
,V/JNIHelp ( 3580): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/NPS_WSSNPS( 3642): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3642): [] Service onCreate!!
,E/Zygote  ( 3661): MountEmulatedStorage()
W/ActivityThread( 3580): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/Zygote  ( 3661): v2
I/libpersona( 3661): KNOX_SDCARD checking this for 1000
W/System  ( 3580): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e9b0f10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/libpersona( 3661): KNOX_SDCARD not a persona
I/ProviderInstaller( 3580): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 1017): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3661 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3661): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NPS_WSSNPS( 3642): [] NpsServiceTask Start
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1017): name = PREVIOUS_ELAPSED_TIME
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3512): Setting receiver enabled: false
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3661): TimaSignature is unavailable
,D/ActivityThread( 3661): Added TimaKeyStore provider
,I/DBG_FMMDS( 3565): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,D/EnterpriseController(  278): uids 10057
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10057
,W/ResourcesManager( 3661): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/NPS_WSSNPS( 3642): [50.150621] smlDBHelper
,I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s878ms
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
I/SamsungIME( 1792): getCurrentCandidateView
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/ActivityManager( 1017): mDVFSHelper.release()
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{15010e2a u0 com.example.hello/.MainActivity t2} time:37720
,I/Timeline( 3358): Timeline: Activity_idle id: android.os.BinderProxy@16d7d07b time:37722
,I/LockPatternUtils( 1301): isSmartCardAuthenticationAvailable: false
,I/DBG_FMMDS( 3565): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3565): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3565): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3565): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3565): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3565): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/ActivityManager( 1017): Killing 2971:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/FOTA_Client( 3322): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3322): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3322): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,I/NPS_WSSNPS( 3642): [50.150621] AsyncBulkFlagCheck
,W/FOTA_Client( 3322): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3642): [50.150621] IsRemain_AsyncBulkCheck
,E/Zygote  ( 3692): MountEmulatedStorage()
I/libpersona( 3692): KNOX_SDCARD checking this for 10014
E/Zygote  ( 3692): v2
I/libpersona( 3692): KNOX_SDCARD not a persona
,I/SELinux ( 3692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3692): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3692 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2283:com.android.mms/u0a46 (adj 15): empty #31
,I/NPS_WSSNPS( 3642): [50.150621] IsRemain_Asyncing nothing
E/ActivityThread( 3512): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ContextImpl( 3642): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3642): [50.150621] Service onDestroy
,D/TimaKeyStoreProvider( 3692): TimaSignature is unavailable
,D/ActivityThread( 3692): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3642): [50.150621] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3642): [50.150621] smlBRMessageDelete
,I/NPS_WSSNPS( 3642): [50.150621] smlBREmailDelete
,I/NPS_WSSNPS( 3642): [50.150621] smlBRNetworkDelete
,I/NPS_WSSNPS( 3642): [50.150621] smlBRCallLogDelete
,I/NPS_WSSNPS( 3642): [50.150621] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3642): [50.150621] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3642): [50.150621] smlBRSMemoDelete
I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,I/NPS_WSSNPS( 3642): [50.150621] verifier installed? false
,I/NPS_WSSNPS( 3642): [50.150621] cpuBooster release : false
,D/NPS_WSSNPS( 3642): [50.150621] dsServerSocket close
,I/ActivityManager( 1017): Killing 2990:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,D/SamsungIME( 1792): Dismiss ExpandCandiate
,D/CountryDetector( 1017): No listener is left
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2971/cgroup.procs: No such file or directory
,I/dbxyzptlk.db240408.D.h( 3512): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,W/BindingManager( 3358): Cannot call determinedVisibility() - never saw a connection for the pid: 3358
,I/dbxyzptlk.db240408.D.h( 3512): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/dbxyzptlk.db240408.D.h( 3512): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_2283/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_2990/cgroup.procs: No such file or directory
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,I/dbxyzptlk.db240408.D.h( 3512): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/chromium( 3358): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,V/OneTimeInitializerReceiver( 3692): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,V/OneTimeService( 3692): OneTimeService.onHandleIntent
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/breakpad( 3512): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/com.dropbox.sync.android.a( 3512): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Zygote  ( 3723): MountEmulatedStorage(),
E/Zygote  ( 3723): v2
I/libpersona( 3723): KNOX_SDCARD checking this for 1000
,I/libpersona( 3723): KNOX_SDCARD not a persona
,I/SELinux ( 3723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3723 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Killing 2914:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,D/JsMessageQueue( 3358): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager( 1017): Killing 3008:com.sec.dsm.system/1000 (adj 15): empty #31
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
E/SELinux ( 3723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/AndroidProtocolHandler( 3358): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/SettingSearch/SearchIntentReceiver( 1301): InitSerachDBThread thread end!
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3740): MountEmulatedStorage(),
I/libpersona( 3740): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3740): v2
I/libpersona( 3740): KNOX_SDCARD not a persona,
I/SELinux ( 3740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3740 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3740): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/com.dropbox.sync.android.ad( 3512): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,D/TimaKeyStoreProvider( 3723): TimaSignature is unavailable
,D/ActivityThread( 3723): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3740): TimaSignature is unavailable
,D/ActivityThread( 3740): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3008/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2914/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3740): onCreate
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1792): getDebugLevel  : 0x4f4c
,E/Zygote  ( 3762): MountEmulatedStorage()
E/Zygote  ( 3762): v2
I/libpersona( 3762): KNOX_SDCARD checking this for 10019
I/libpersona( 3762): KNOX_SDCARD not a persona
,I/SELinux ( 3762): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3762 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3762): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/SELinux ( 3762): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Hs20UtilService( 3740): Starting #1
,I/Hs20UtilService( 3740): Message received 5003
,D/jxcore_app_log( 3358): JniHelper::setJavaVM(0xb8695450), pthread_self() = -1195452776
D/JX-Cordova( 3358): jxcore cordova android initializing
,D/SettingsProvider( 1017): name = access_control_enabled
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3776): MountEmulatedStorage()
I/libpersona( 3776): KNOX_SDCARD checking this for 10069
E/Zygote  ( 3776): v2
I/libpersona( 3776): KNOX_SDCARD not a persona
I/SELinux ( 3776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3776 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3023:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3762): TimaSignature is unavailable
,D/ActivityThread( 3762): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3776): TimaSignature is unavailable
,D/ActivityThread( 3776): Added TimaKeyStore provider
,W/jxcore-log( 3358): Initializing JXcore engine
W/jxcore-log( 3358): JXcore engine is ready
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,W/jxcore-log( 3358): Starting JXcore engine
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SamsungIME( 1792): getDebugLevel  : 0x4f4c
,E/Zygote  ( 3796): MountEmulatedStorage(),
E/Zygote  ( 3796): v2
I/libpersona( 3796): KNOX_SDCARD checking this for 10094
I/libpersona( 3796): KNOX_SDCARD not a persona
,I/SELinux ( 3796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3796): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3796 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2327:com.sec.modem.settings/1000 (adj 15): empty #31
,E/audit   ( 1912): type=1400 msg=audit(1448385978.199:205): avc:  denied  { ioctl } for  pid=3358 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1912):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1912): type=1300 msg=audit(1448385978.199:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=beccad58 items=0 ppid=305 ppcomm=main pid=3358 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1912): type=1320 msg=audit(1448385978.199:205): 
,I/SamsungIME( 1792): KeybaordView init() : load resources
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,I/KLMS-2.5.183: ( 3762): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 24 18:26:18 GMT+01:00 2015
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/TimaKeyStoreProvider( 3796): TimaSignature is unavailable
,D/ActivityThread( 3796): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3762): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3814 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,E/Zygote  ( 3814): MountEmulatedStorage()
E/Zygote  ( 3814): v2
I/libpersona( 3814): KNOX_SDCARD checking this for 10022
I/libpersona( 3814): KNOX_SDCARD not a persona
,I/RlzPingService( 3337): Setting next ping for 1448990778296
,I/SELinux ( 3814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3814): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1792): getCurrentKeyboard
I/SamsungIME( 1792): getTextKeyboard
,W/jxcore-log( 3358): Platform android
W/jxcore-log( 3358): 
,W/jxcore-log( 3358): Process ARCH arm
W/jxcore-log( 3358): 
,I/KLMS-2.5.183: ( 3762): KLMSIntentService(): onCreate()
,I/ActivityManager( 1017): Killing 3059:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3762): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/TimaKeyStoreProvider( 3814): TimaSignature is unavailable
,D/ActivityThread( 3814): Added TimaKeyStore provider
,D/elm:15183( 3796): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3796): ELMEngine.ELMEngine( context ).
,I/KLMS-2.5.183: ( 3762): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ResourcesManager( 3580): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3580): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/elm:15183( 3796): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1017): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/KLMS-2.5.183: ( 3762): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 22243(1218KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 26MB/40MB, paused 2.444ms total 159.266ms
,D/SamsungIME( 1792): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/jxcore-log( 3358): JXcore Cordova bridge is ready!
I/jxcore-log( 3358): 
,W/jxcore-log( 3358): JXcore engine is started
,I/System.out( 3512): Thread-479(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3512): Thread-479(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3512): Thread-479(ApacheHTTPLog):isShipBuild true
I/System.out( 3512): Thread-479(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3512): Thread-479(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10092
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10092
,D/elm:15183( 3796): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/FileShare-Server( 3776): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/KLMS-2.5.183: ( 3762): KLMSIntentService(): BOOT_COMPLETED
,V/EmergencyMode( 1419): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,V/EmergencyMode( 1419): [EmergencyBase] setBootTime
,V/EmergencyMode( 1419): [EmergencyFactory] No Recovery State, kill my self.
,E/jxcore-log( 3358): >> samsung-SM-A500FU
E/jxcore-log( 3358): 
,I/jxcore-log( 3358): Total memory 1983791104
I/jxcore-log( 3358): 
,I/jxcore-log( 3358): Free memory 160874496
I/jxcore-log( 3358): 
I/jxcore-log( 3358): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3358): 
,I/jxcore-log( 3358): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3358): 
W/art     ( 1792): Suspending all threads took: 38.784ms
,D/btif_config_util( 2644): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3358): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3358): 
,I/jxcore-log( 3358): Size 720 1280
I/jxcore-log( 3358): 
,I/jxcore-log( 3358): Screen Brightness 5
I/jxcore-log( 3358): 
,E/jxcore-log( 3358): Dummy Error Log.
E/jxcore-log( 3358): 
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 3796): ElmAgentService : onCreate()
,D/elm:15183( 3796): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 3796): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15183( 3796): BootCompletedState : startBootCompleted() call
,E/Zygote  ( 3839): MountEmulatedStorage()
,E/Zygote  ( 3839): v2,
I/libpersona( 3839): KNOX_SDCARD checking this for 1000,
,I/libpersona( 3839): KNOX_SDCARD not a persona
,I/SELinux ( 3839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3839 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 3839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3839): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:15183( 3796): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.183: ( 3762): KLMSIntentService(): onDestroy()
I/elm:15183( 3796): Get License : 0
D/elm:15183( 3796): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 3079:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3839): TimaSignature is unavailable
,D/ActivityThread( 3839): Added TimaKeyStore provider
,I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3856 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/ActivityManager( 1017): Killing 3098:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,E/Zygote  ( 3856): MountEmulatedStorage()
E/Zygote  ( 3856): v2
I/libpersona( 3856): KNOX_SDCARD checking this for 1000
I/libpersona( 3856): KNOX_SDCARD not a persona
,I/SELinux ( 3856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/art     (  305): Explicit concurrent mark sweep GC freed 8758(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 694us total 28.533ms
E/SELinux ( 3856): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 18.975ms
,D/TimaKeyStoreProvider( 3856): TimaSignature is unavailable
D/ActivityThread( 3856): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 18.204ms
,I/CameraApp( 3839): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3839): Feature.Feature(context)
I/testFeature( 3839): Feature.readInternalDefaultXml()
I/testFeature( 3839): ResetFeatureValue
,I/CameraFirmware_broadcast( 3839): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3839): CameraApp.getAppFeature()...
W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_3023/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2327/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3059/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/MTPRx   ( 3856): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3079/cgroup.procs: No such file or directory
,E/Zygote  ( 3876): MountEmulatedStorage()
E/Zygote  ( 3876): v2
I/libpersona( 3876): KNOX_SDCARD checking this for 10100
I/libpersona( 3876): KNOX_SDCARD not a persona
,I/SELinux ( 3876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3876 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3131:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,I/SELinux ( 3876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
,I/ActivityManager( 1017): Killing 3149:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1017): mCursor = null
,V/MTPRx   ( 3856): sealedState: false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
V/MTPRx   ( 3856): sealedUsbMassStorageState: false
W/ContextImpl( 1017): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3876): TimaSignature is unavailable,
,D/ActivityThread( 3876): Added TimaKeyStore provider
,E/Zygote  ( 3891): MountEmulatedStorage(),
E/Zygote  ( 3891): v2
,I/libpersona( 3891): KNOX_SDCARD checking this for 1000
I/libpersona( 3891): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3891 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3891): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ProcessCpuTracker( 1017): Skipping unknown process pid 3131
,W/libprocessgroup( 1017): failed to open /acct/uid_1101/pid_3098/cgroup.procs: No such file or directory
,D/SettingsProvider( 1017): name = mtp_usb_connection_status
,D/TimaKeyStoreProvider( 3891): TimaSignature is unavailable
,D/ActivityThread( 3891): Added TimaKeyStore provider
,D/SettingsProvider( 1017): name = media_player_mode
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/PackageIntentReceiver( 3876): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3876): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1017): name = mtp_running_status
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = media_mount_count
,W/libprocessgroup( 1017): failed to open /acct/uid_10157/pid_3131/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3149/cgroup.procs: No such file or directory
,E/Zygote  ( 3910): MountEmulatedStorage()
,E/Zygote  ( 3910): v2,
I/libpersona( 3910): KNOX_SDCARD checking this for 10101
I/libpersona( 3910): KNOX_SDCARD not a persona
,I/SELinux ( 3910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/SettingsProvider( 1017): name = mtp_sync_alive
I/SELinux ( 3910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3910): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3910 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3113:com.sec.knox.bridge/1000 (adj 15): empty #31
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/ActivityManager( 1017): Killing 2711:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3910): TimaSignature is unavailable
,D/ActivityThread( 3910): Added TimaKeyStore provider
,W/System.err( 3580): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/SettingsProvider( 1017): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/System.out( 3580): YouTube MDX: MDX video stage moved to NEW
,I/System.out( 3580): YouTube MDX: MDX video player state moved to UNSTARTED
,I/System.out( 3580): YouTube MDX: MDX ad player state moved to UNSTARTED
,I/dex2oat ( 3908): ----------------------------------------------------
I/dex2oat ( 3908): <SS>: S T A R T I N G . . .
I/dex2oat ( 3908): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3908): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1935369377.jar --oat-fd=33 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1935369377.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/SettingsProvider( 1017): name = mtp_open_session
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/ActivityManager( 1017): Killing 1562:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/jxcore-log( 3358): getBuffer is called!!!!
I/jxcore-log( 3358): 
W/ContextImpl( 3891): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3113/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/PCWCLIENTTRACE_PushUtil( 3530): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3530): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3530): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3530): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3530): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3530): ACTION_BOOTUP - Push type: [SPP, GCM]
,D/FactoryTestApp( 2606): [DummyFtClient$onDestroy](2606) Destroy DummyFtClient service
,D/FactoryTestApp( 2606): [Support$Values.getString](2606) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2606): [ModuleCommon$isConnectionModeNone](2606) mConnectionMode = gsm
I/FactoryTestApp( 2606): [ModuleCommon$isRunningFtClient](2606) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2606): [DummyFtClient$onDestroy](2606) kill process
I/Process ( 2606): Sending signal. PID: 2606 SIG: 9
,I/dex2oat ( 3908): dex2oat took 121.691ms (threads: 4)
,W/PCWCLIENTTRACE_AccountUtil( 3530): [hasSamungAccount] - No Samsung Account
,W/libprocessgroup( 1017): failed to open /acct/uid_10120/pid_2711/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1562/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3530): [GetString-S]
,I/ReactiveServiceManager( 3530): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,I/ActivityManager( 1017): Process com.sec.factory (pid 2606)(adj 0) has died(140,1089)
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 10
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 10
E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 3530): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3530): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 3530): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3530): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3530): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 3530): [ensureRegistration] - No Samsung account
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3946): MountEmulatedStorage(),
I/libpersona( 3946): KNOX_SDCARD checking this for 10031
E/Zygote  ( 3946): v2
I/libpersona( 3946): KNOX_SDCARD not a persona
I/SELinux ( 3946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3946): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3946 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3185:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3946): TimaSignature is unavailable
,D/ActivityThread( 3946): Added TimaKeyStore provider
,W/art     ( 3580): Suspending all threads took: 7.501ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3946): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/art     ( 3272): Suspending all threads took: 15.716ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/DBG_POLICYDM( 3272): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/System.out( 3512): pool-10-thread-1 calls detatch()
,I/DBG_POLICYDM( 3272): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3580): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3891): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3891): Resource data:2131165186
,W/ResourcesManager( 3891): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3891): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3891): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3891): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,D/SamsungIME( 1792): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,I/AMMetaDataParserService( 3891): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,W/libprocessgroup( 1017): failed to open /acct/uid_10159/pid_3185/cgroup.procs: No such file or directory
,I/Gmail   ( 3910): getAccountsCursor
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 3910): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/AMMetaDataParserService( 3891): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/AMMetaDataParserService( 3891): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
W/ContextImpl( 3891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131034113
,W/ResourcesManager( 3891): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3891): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,I/VlingoApplication( 3946): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3891): took 2.382605ms for 0*0 texture 0
,I/VlingoAndroidCore( 3946): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/GFX generate_partition_tables( 3891): took 6.304894ms for 0*0 texture 0
,I/GFX raster( 3891): took 10.093907ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a692a8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3891): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/Gmail   ( 3910): Error finding the version of the Email provider.....
E/Gmail   ( 3910): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3910): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3910): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3910): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3910): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3910): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3910): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3910): We do not support migrating this version of the Email provider.
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 3910): getAccountsCursor
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AudioService( 1017): getStreamVolume 3 index 0
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3989): MountEmulatedStorage()
E/Zygote  ( 3989): v2
I/libpersona( 3989): KNOX_SDCARD checking this for 10104
I/libpersona( 3989): KNOX_SDCARD not a persona
I/SELinux ( 3989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3989 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 3989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3989): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GoogleHttpClient( 1630): GMS http client unavailable, use old client
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.911823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a71338 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 3989): TimaSignature is unavailable
,D/ActivityThread( 3989): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ResourcesManager( 3989): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3910): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@28b33f9d that was originally bound here
E/ActivityThread( 3910): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@28b33f9d that was originally bound here
E/ActivityThread( 3910): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3910): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3910): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3910): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3910): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3910): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3910): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3910): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3910): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3910): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3910): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3910): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3910): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3910): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3910): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1017): Unbind failed: could not find connection for android.os.BinderProxy@33b3a74f
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3891): took 2.382188ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3891): took 8.503855ms for 0*0 texture 0
,I/GFX raster( 3891): took 11.824427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6db40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6dca8 counterpartCT=4 counterpartW=96 counterparth=96
,D/VlingoApplication( 3946): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3946): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/AMMetaDataParserService( 3891): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/Gmail   ( 3910): Observing account changes for notifications
,D/DialogFlow( 3946): initQueue()
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3580): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,E/SQLiteLog( 3910): (283) recovered 38 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ContextImpl( 3580): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3580): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4016): MountEmulatedStorage()
E/Zygote  ( 4016): v2
I/libpersona( 4016): KNOX_SDCARD checking this for 10032
I/libpersona( 4016): KNOX_SDCARD not a persona
,I/SELinux ( 4016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4016 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 4016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
E/SELinux ( 4016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4016): TimaSignature is unavailable
,D/ActivityThread( 4016): Added TimaKeyStore provider
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.725000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a72510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a72678 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/SMD     (  288): DCD OFF,
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.989844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6f010 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6f178 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/File    ( 3910): fail readDirectory() errno=2
,I/Gmail   ( 3910): notifyAccountChanged
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.687291ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6e318 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6e480 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3910): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/AndroidHttpClient( 3580): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
,D/AndroidHttpClient( 3580): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 3580): Thread-550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3580): Thread-550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3580): Thread-550(ApacheHTTPLog):isShipBuild true
I/System.out( 3580): Thread-550(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3580): Thread-550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10166
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10166
,I/art     ( 1630): Explicit concurrent mark sweep GC freed 7725(417KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 10MB/18MB, paused 1.008ms total 58.839ms
,W/ContextImpl( 1930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1930): Service started flags 0 startId 1
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,D/SecUISvc( 1930): Thread created.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,I/Gmail   ( 3910): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4068): MountEmulatedStorage()
E/Zygote  ( 4068): v2
I/libpersona( 4068): KNOX_SDCARD checking this for 10033
I/libpersona( 4068): KNOX_SDCARD not a persona
,I/SELinux ( 4068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4068 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Killing 3218:com.sec.usbsettings/1000 (adj 15): empty #31
,E/SELinux ( 4068): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 3234:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3272:com.policydm/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4068): TimaSignature is unavailable
,D/ActivityThread( 4068): Added TimaKeyStore provider
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.690000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6d9a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6d858 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3910): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3910): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1180 (0x0)
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3218/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_3234/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3272/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.524895ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a72168 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6c0c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131034113
,I/AMMetaDataParserService( 3891): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.809270ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a6ef98 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4068): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4068): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4068): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3891): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.813334ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a6ec90 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4068): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4068): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4068): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3891): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 4068): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4068): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4068): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.605885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6db40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6ec90 counterpartCT=4 counterpartW=96 counterparth=96
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3891): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/Gmail   ( 3910): getAccountsCursor
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.613020ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a72510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6ec90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/Gmail   ( 3910): getAccountsCursor
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.831407ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6f010 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6ec90 counterpartCT=4 counterpartW=96 counterparth=96
,W/art     ( 3946): Suspending all threads took: 12.135ms
,I/AMMetaDataParserService( 3891): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.630625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6e318 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6ec90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.834375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6d9a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6ec90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/Babel   ( 3989): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3989): MmsConfig.loadMmsSettings
,I/Babel   ( 3989): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3989): MmsConfig.loadFromDatabase
I/GFX raster( 3891): took 0.535208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a72168 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6ec90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3891): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3891): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3891): Resource data:Loop for running activityalias.DialShortcut
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131034112
,I/AMMetaDataParserService( 3891): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.595520ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6ec90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c1d388 counterpartCT=4 counterpartW=96 counterparth=96
,E/Babel   ( 3989): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3989): MmsConfig.loadFromResources
,E/Babel   ( 3989): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3989): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/FileApkUtils( 2052): Spent 60ms computing apk sha1.
,D/FileApkUtils( 2052): Module already staged or being staged:chimera-modules/MapsModule.apk
I/AMMetaDataParserService( 3891): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,I/art     ( 2052): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 2052): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk appears to be unoptimized.
,D/DexOptUtils( 2052): Lollipop platform, using <isa> directory.
,I/System.out( 3580): Thread-550 calls detatch()
,D/DexOptUtils( 2052): Instantiating DexClassLoader to force creation of odex.
,D/DexOptUtils( 2052): Primary ABI of odexing process is armeabi-v7a
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 25176(1455KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 2.345ms total 166.697ms
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.605313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6ec90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a34608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/dex2oat ( 4096): ----------------------------------------------------
I/dex2oat ( 4096): <SS>: S T A R T I N G . . .
I/dex2oat ( 4096): <SS>: Zip is absent. Canceled.
I/GFX raster( 3891): took 0.666197ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50eb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a50b68 counterpartCT=4 counterpartW=96 counterparth=96
,I/dex2oat ( 4096): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/Settings( 3989): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AMMetaDataParserService( 3891): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.622813ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb869bc70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a34608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel_StickerModule( 3989): App launched.
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131034113
I/AMMetaDataParserService( 3891): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.805938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50b68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb87a1af8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3891): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.837917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50b68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb87a1af8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 2052): COMPAT: Multi user not supported
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1630): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,V/Babel   ( 3989): babel boot account: SMS
,I/Process ( 4068): Sending signal. PID: 4068 SIG: 9
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/GFX raster( 3891): took 0.593750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8c1d388 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a34608 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Babel   ( 3989): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,I/AMMetaDataParserService( 3891): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,W/Babel   ( 3989): java.lang.Exception
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3989): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3989): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3989): 	at ckh.a(SourceFile:67)
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3989): 	at bhn.a(SourceFile:301)
W/Babel   ( 3989): 	at bhn.a(SourceFile:137)
W/Babel   ( 3989): 	at bhn.a(SourceFile:126)
W/Babel   ( 3989): 	at bhn.a(SourceFile:159)
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3989): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3989): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3989): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3989): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3989): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3989): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3989): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3989): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3989): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/Babel   ( 3989): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 3989): java.lang.Exception
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3989): 	at aes.a(SourceFile:145)
W/Babel   ( 3989): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3989): 	at ckh.a(SourceFile:67)
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3989): 	at bhn.a(SourceFile:301)
W/Babel   ( 3989): 	at bhn.a(SourceFile:137)
W/Babel   ( 3989): 	at bhn.a(SourceFile:126)
W/Babel   ( 3989): 	at bhn.a(SourceFile:159)
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3989): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3989): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3989): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3989): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3989): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3989): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3989): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3989): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3989): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 2052): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/CheckinService( 2052): Checkin interval check for package: unspecified last checkin: 1448204549172 min interval config: 0 actual interval: 181432082
,I/GFX raster( 3891): took 0.629896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6ec90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb87a1af8 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1825): DispatchingService.onCreate()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3891): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 4068)(adj 0) has died(84,1122)
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,I/CheckinService( 2052): Disabling old GoogleServicesFramework version
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.847552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a34608 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb87a1af8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4128): MountEmulatedStorage(),
E/Zygote  ( 4128): v2
I/libpersona( 4128): KNOX_SDCARD checking this for 10034
,I/libpersona( 4128): KNOX_SDCARD not a persona
,I/SELinux ( 4128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4128 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 4128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,E/SELinux ( 4128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3891): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.649427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb869bc70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a48d78 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 3989): babel boot account: thalitester@gmail.com
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/TimaKeyStoreProvider( 4128): TimaSignature is unavailable
,D/ActivityThread( 4128): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Babel   ( 3989): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 3989): java.lang.Exception
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3989): 	at aes.a(SourceFile:145)
W/Babel   ( 3989): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3989): 	at ckh.a(SourceFile:67)
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3989): 	at bhn.a(SourceFile:301)
W/Babel   ( 3989): 	at bhn.a(SourceFile:137)
W/Babel   ( 3989): 	at bhn.a(SourceFile:126)
W/Babel   ( 3989): 	at bhn.a(SourceFile:159)
W/Babel   ( 3989): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3989): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3989): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3989): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3989): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3989): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3989): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3989): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3989): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3989): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/SystemUpdateService( 2052): onCreate
,I/GFX raster( 3891): took 0.695886ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a6d9a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb87a1af8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.522240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a72168 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a48d78 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/SystemUpdateService( 2052): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 2052): Handling intent: android.intent.action.BOOT_COMPLETED
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
W/ContextImpl( 3891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,D/AuthZenEventHandler( 2052): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891,): Resource data:2131165203
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourcesManager( 3891): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/ResourcesManager( 3891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ResourcesManager( 3891): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3891): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3530): unregister AuthInfo UpdateReceiver v2.0
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX construct_block_size_descriptor_2d second part( 3891): took 2.633333ms for 0*0 texture 0
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/GFX generate_partition_tables( 3891): took 10.098647ms for 0*0 texture 0
,I/GFX raster( 3891): took 13.561720ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a356f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a69f10 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4151): MountEmulatedStorage()
E/Zygote  ( 4151): v2
I/libpersona( 4151): KNOX_SDCARD checking this for 1000
I/libpersona( 4151): KNOX_SDCARD not a persona
,I/SELinux ( 4151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
I/AMMetaDataParserService( 3891): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4151 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/CheckinService( 2052): Checking schedule, now: 1448385981600 next: 1448743812129
I/CheckinService( 2052): active receiver: disabled
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.771250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8c1cf20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8dc9828 counterpartCT=4 counterpartW=96 counterparth=96
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,I/AMMetaDataParserService( 3891): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,D/TimaKeyStoreProvider( 4151): TimaSignature is unavailable
,D/ActivityThread( 4151): Added TimaKeyStore provider
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.775468ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8c1cf20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8dcac78 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,W/VideoCapabilities( 3989): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3891): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/AudioCapabilities( 3989): Unsupported mime audio/evrc
,E/Zygote  ( 4168): MountEmulatedStorage(),
E/Zygote  ( 4168): v2
I/libpersona( 4168): KNOX_SDCARD checking this for 1000
I/libpersona( 4168): KNOX_SDCARD not a persona
I/SELinux ( 4168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4168 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.765729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8c1cf20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8dcc090 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Killing 3168:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/AMMetaDataParserService( 3891): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/AudioCapabilities( 3989): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3989): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3989): Unsupported mime audio/mpeg-L2
,D/TimaKeyStoreProvider( 4168): TimaSignature is unavailable
,D/ActivityThread( 4168): Added TimaKeyStore provider
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.608385ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8dcd538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8dcd670 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 3989): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3989): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3989): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3989): Unsupported mime audio/evrc
,I/AMMetaDataParserService( 3891): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/art     ( 2052): Explicit concurrent mark sweep GC freed 24942(1908KB) AllocSpace objects, 27(432KB) LOS objects, 39% free, 10MB/18MB, paused 1.552ms total 154.016ms
,I/art     ( 1825): Explicit concurrent mark sweep GC freed 15721(1005KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 10MB/17MB, paused 1.088ms total 225.841ms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/libprocessgroup( 1017): failed to open /acct/uid_10085/pid_3168/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,W/VideoCapabilities( 3989): Unsupported mime video/wvc1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/BaseAppContext( 2052): Using Auth Proxy for data requests.,
,I/SystemUpdateService( 2052): cancelUpdate (empty URL),
I/SystemUpdateService( 2052): active receiver: disabled
,W/VideoCapabilities( 3989): Unsupported mime video/x-ms-wmv,
,I/GFX raster( 3891): took 0.740729ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8dcd538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8dce948 counterpartCT=4 counterpartW=96 counterparth=96
I/libpersona( 4183): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4183): MountEmulatedStorage()
I/libpersona( 4183): KNOX_SDCARD not a persona,
E/Zygote  ( 4183): v2
I/SELinux ( 4183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4183): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/SSRM:n  ( 1017): SIOP:: AP = 380,
,I/AMMetaDataParserService( 3891): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577,
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1017): Killing 3287:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
,I/art     (  305): Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 24.624ms total 54.820ms,
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature,
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/ContextImpl( 3891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 18.956ms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 16.898ms
,D/TimaKeyStoreProvider( 4183): TimaSignature is unavailable
,D/ActivityThread( 4183): Added TimaKeyStore provider
,W/VideoCapabilities( 3989): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/VideoCapabilities( 3989): Unsupported mime video/wvc1
,W/VideoCapabilities( 3989): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131099648
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3891): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3891): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.840468ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68c70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a71060 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3989): Unsupported mime video/x-ms-wmv7
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3989): Unsupported mime video/x-ms-wmv8
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/KnoxSetupWizardDbHelper( 4183): dbMigrationFlag : false
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3891): took 2.777657ms for 0*0 texture 0
W/VideoCapabilities( 3989): Unsupported mime video/mp43
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/ChimeraCfgMgr( 2052): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ShortcutReceiver( 4183):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3891): took 8.994325ms for 0*0 texture 0
,W/VideoCapabilities( 3989): Unsupported mime video/sorenson
,I/GFX raster( 3891): took 12.944274ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a729c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a696e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/KnoxShortcutUtil( 4183): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4183):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 4183):  shortcut migration not required 
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/DBG_POLICYDM( 4168): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/AuthZen ( 2052): Fetching signing key...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3989): Unsupported mime video/mp4v-esdp
,I/DBG_POLICYDM( 4168): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/AMMetaDataParserService( 3891): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/Zygote  ( 4217): MountEmulatedStorage(),
E/Zygote  ( 4217): v2
I/libpersona( 4217): KNOX_SDCARD checking this for 1000,
I/libpersona( 4217): KNOX_SDCARD not a persona
,I/SELinux ( 4217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4217 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3383:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AuthZen ( 2052): Signing key fetched successfully!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4168): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4217): TimaSignature is unavailable
,D/ActivityThread( 4217): Added TimaKeyStore provider
,W/BaseAppContext( 2052): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 2052): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 2052): onDestroy
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.739323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a507f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4168): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1825): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/GCoreFlp( 1825): No location to return for getLastLocation()
,W/Kids    ( 2052): [AbstractKidsOperation] Invalid device state 3
,W/FusedLocationProvider( 2052): location=null
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/a       ( 2052): Opening database auth.proximity.permit_store...
I/AMMetaDataParserService( 3891): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthZenTransactionCache( 2052): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2052): Clearing transaction cache
,I/VideoCapabilities( 3989): Unsupported profile 4 for video/mp4v-es
,W/ResourcesManager( 4016): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 4168): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/GCoreFlp( 1825): No location to return for getLastLocation()
,W/FusedLocationProvider( 2052): location=null
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/KnoxSetupWizardClient( 4217): isShipMode : 1
,I/KnoxSetupWizardClient( 4217): onReceive : android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.769635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8f6f7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f6f850 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/Auth    ( 1630): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4168): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4168): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4241): MountEmulatedStorage()
I/libpersona( 4241): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4241): v2
I/libpersona( 4241): KNOX_SDCARD not a persona
,I/SELinux ( 4241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4241 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3420:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/SELinux ( 4241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4241): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/TimaKeyStoreProvider( 4241): TimaSignature is unavailable
,D/ActivityThread( 4241): Added TimaKeyStore provider
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.738855ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb86e7ba0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86e7c48 counterpartCT=4 counterpartW=96 counterparth=96
,V/GmsCoreStatsServiceLauncher( 2052): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4257 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3461:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,E/Zygote  ( 4257): MountEmulatedStorage()
I/libpersona( 4257): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4257): v2
I/libpersona( 4257): KNOX_SDCARD not a persona
I/SELinux ( 4257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/System.err( 4217): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 4217): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4217): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4217): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4217): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
I/SecDataIO(  257): Write to block
W/System.err( 4217): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4217): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
E/SELinux ( 4257): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/PersistentNotificationBroadcastReceiver( 1630): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/ContextImpl( 2588): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 3203): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3203): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
D/TimaKeyStoreProvider( 4257): TimaSignature is unavailable
E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/Process ( 2588): Sending signal. PID: 2588 SIG: 9
,I/GFX raster( 3891): took 0.718125ms for 96*96 texture 0
D/ActivityThread( 4257): Added TimaKeyStore provider
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a106a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f6f578 counterpartCT=4 counterpartW=96 counterparth=96
,E/DBG_DM  ( 3203): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/AMMetaDataParserService( 3891): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131099648
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3891): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.682240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68c70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a71740 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4274): MountEmulatedStorage()
E/Zygote  ( 4274): v2
I/libpersona( 4274): KNOX_SDCARD checking this for 10028
I/libpersona( 4274): KNOX_SDCARD not a persona
,I/SELinux ( 4274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4274 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4274): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Process com.sec.android.app.sysscope (pid 2588)(adj 0) has died(77,1129)
,I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4274): TimaSignature is unavailable
,D/ActivityThread( 4274): Added TimaKeyStore provider
,I/art     ( 1630): Explicit concurrent mark sweep GC freed 7534(444KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/18MB, paused 1.090ms total 201.511ms
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/DBG_DM  ( 3203): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/DBG_POLICYDM( 4168): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_DM  ( 3203): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.743749ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a729c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a71740 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3989): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3891): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/SPPClientService( 4257): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4257): [PushClientApplication] Push log off : This is Ship build version
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.617969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a68e88 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/AMMetaDataParserService( 3891): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SPPClientService( 4257): PushLog.txt file is not deleted.
,D/SPPClientService( 4257): PushLog.txt file is not deleted.
,D/SPPClientService( 4257): ============PushLog. stop!
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,E/SPPClientService( 4257): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
I/DBG_POLICYDM( 4168): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.719532ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8f6f7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a71740 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 9
,I/DBG_POLICYDM( 4168): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 9
,I/AMMetaDataParserService( 3891): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_DM  ( 3203): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 3203): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3203): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 9
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 3989): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString,
,E/Zygote  ( 4297): MountEmulatedStorage(),
,E/Zygote  ( 4297): v2,
I/libpersona( 4297): KNOX_SDCARD checking this for 10041,
,I/libpersona( 4297): KNOX_SDCARD not a persona
,I/SELinux ( 4297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4297): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4297): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4297 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3480:com.fmm.dm/1000 (adj 15): empty #31
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/SQLiteLog( 3989): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4168): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 4168): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,D/TimaKeyStoreProvider( 4297): TimaSignature is unavailable
,D/ActivityThread( 4297): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4168): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_DM  ( 3203): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3203): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3203): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_POLICYDM( 4168): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_DM  ( 3203): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.681771ms for 96*96 texture 0
,I/DBG_POLICYDM( 4168): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2015/11/27/14:10:13
,I/DBG_POLICYDM( 4168): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2015/11/24/18:26:22
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb86e7ba0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a68e88 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 4168): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_DM  ( 3203): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 3203): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,I/DBG_POLICYDM( 4168): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4168): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4168): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4168): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4168): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_POLICYDM( 4168): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500,
,E/SQLiteLog( 3989): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_POLICYDM( 4168): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,E/SQLiteLog( 3989): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.855260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a106a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a71740 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Killing 3409:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/AMMetaDataParserService( 3891): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_3287/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,I/DBG_DM  ( 3203): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
I/DBG_DM  ( 3203): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3383/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131099648
,W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_3420/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10060/pid_3461/cgroup.procs: No such file or directory
,E/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3be6de4b
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3480/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3891): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.697709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68c70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a68e88 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/System.out( 3512): Thread-478(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3512): Thread-478(ApacheHTTPLog):isShipBuild true
I/System.out( 3512): Thread-478(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3512): Thread-478(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10092
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10092
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,I/SA      ( 4297): [SSP] onCreated
,E/SMD     (  288): DCD OFF
,W/libprocessgroup( 1017): failed to open /acct/uid_10086/pid_3409/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4168): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 4168): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 3203): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ContextImpl( 3203): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,D/SettingsProvider( 1017): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,I/SA      ( 4297): [TPM] There is no property file
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.838958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a729c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a68e88 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
D/GCMRegistrar( 3512): resetting backoff for com.dropbox.android
,V/GCMRegistrar( 3512): Registering app com.dropbox.android of senders 735665981150
,I/DBG_DM  ( 3203): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.747760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a71740 counterpartCT=4 counterpartW=96 counterparth=96
,D/StrictMode( 4241): StrictMode policy violation; ~duration=657 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4241): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4241): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4241): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4241): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4241): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4241): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4241): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4241): StrictMode policy violation; ~duration=613 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4241): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4241): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4241): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4241): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4241): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4241): StrictMode policy violation; ~duration=444 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4241): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4241): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4241): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4241): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4241): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4241): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4241): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4241): StrictMode policy violation; ~duration=443 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4241): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4241): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4241): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4241): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4241): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4241): StrictMode policy violation; ~duration=443 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4241): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4241): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4241): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4241): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4241): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	,at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4241): StrictMode policy violation; ~duration=441 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4241): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4241): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4241): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4241): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4241): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4241): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4241): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4241): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4241): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4241): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4241): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4241): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4241): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4241): StrictMode policy violation; ~duration=438 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4241): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4241): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4241): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4241): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4241): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4241): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4241): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4241): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4241): 	,at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4241): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4241): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4241): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4241): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4241): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4241): ,	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4241): StrictMode policy violation; ~duration=379 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4241): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4241): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4241): 	,at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4241): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4241): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4241): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4241): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4241): 	,at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/Stric,tMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4241): StrictMode policy violation; ~duration=378 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 4241): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4241): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4241): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4241): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4241): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4241): 	,at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4241): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4241): 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4241): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
,D/StrictMode( 4241): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4241): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 4241): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:6145),
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/AMMetaDataParserService( 3891): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,I/SA      ( 4297): [SCU] isHaveSA() - false
,I/SA      ( 4297): [TPM] getModelProperty : null
I/SA      ( 4297): [TPM] getCSCProperty : null
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
,I/SA      ( 4297): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4297): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4297): [DM] TFT FEATURE: false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4297): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4297): [DM] init START
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.630000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8f6f7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a71740 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4327): MountEmulatedStorage()
E/Zygote  ( 4327): v2
I/libpersona( 4327): KNOX_SDCARD checking this for 1000
I/libpersona( 4327): KNOX_SDCARD not a persona
,I/SELinux ( 4327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/AMMetaDataParserService( 3891): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
I/SELinux ( 4327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4327): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4327 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3512:com.dropbox.android/u0a92 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SA      ( 4297): [DM] This device is not a Vodafone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
I/GFX raster( 3891): took 0.742137ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb86e7ba0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a712f0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1017): showStatusBarByNotification() mOpenByNotification=false
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3203): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/GCM     ( 1630): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1017): mCursor = null
,W/ResourceType( 4297): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4297): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4297): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/TimaKeyStoreProvider( 4327): TimaSignature is unavailable
,D/ActivityThread( 4327): Added TimaKeyStore provider
,W/ResourcesManager( 1180): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 1.002969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a106a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a712f0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1017): failed to open /acct/uid_10092/pid_3512/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
,I/SA      ( 4297): [SCU] isHaveSA() - false
I/SA      ( 4297): support phone number id : false
I/SA      ( 4297): [DM] Supports Ref Jpn : true
,I/SA      ( 4297): [DM] init END
D/SecContentProvider2( 1017): mCursor = null
,I/SA      ( 4297): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4297): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,I/GCoreUlr( 1825): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AMMetaDataParserService( 3891): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/DBG_DM  ( 3203): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3203): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 3203): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/KnoxNotification( 1180): ----- inflateViews : modified publicViewLocal -----
,D/Finsky  ( 4274): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/KnoxNotification( 1180): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1180): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/BluetoothAdapter( 3358): disable()
,D/SettingsProvider( 1017): name = bluetooth_on
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/dex2oat ( 4096): Verification of void com.google.maps.api.android.lib6.gmm6.n.cj.g() took 128.568ms
,D/BluetoothAdapterState( 2644): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/BluetoothAdapterProperties( 2644): Setting state to 13
I/BluetoothAdapterState( 2644): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2644): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2644): updateAdapterState state is 13
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: false pid=3358, uid=10174
D/SettingsProvider( 1017): name = wifi_on
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131099648
,E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state,
I/wpa_supplicant( 2009): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2009): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 2009): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2009): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 3358): ****TEST TOOK:  5096  ms ****
I/jxcore-log( 3358): 
,I/jxcore-log( 3358): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3358): 
,I/AMMetaDataParserService( 3891): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3891): took 0.707865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68c70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a712f0 counterpartCT=4 counterpartW=96 counterparth=96
E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  278): Clearing all IP addresses on wlan0,
,I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
V/NativeCrypto( 1630): Read error: ssl=0xb8c1aaf8: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/WifiP2pService( 1017): InactiveState{ what=131204 }
,I/DBG_POLICYDM( 4168): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/WifiP2pService( 1017): P2pEnabledState{ what=131204 }
,D/WifiP2pService( 1017): sending p2p connection changed broadcast: FAILED,
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.892552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a729c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a68e88 counterpartCT=4 counterpartW=96 counterparth=96
,D/WifiScanningService( 1017): SCAN_AVAILABLE : 1,
D/WifiScanningService( 1017): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/RttService( 1017): SCAN_AVAILABLE : 1
,D/RttService( 1017): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService( 1017): P2pDisablingState
,D/WifiP2pService( 1017): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1017): p2p socket connection lost
,D/WifiP2pService( 1017): P2pDisabledState,
D/WifiP2pService( 1017): P2pDisabledState{ what=143375 }
D/WifiP2pService( 1017): DefaultState{ what=143375 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
E/WifiStateMachine( 1017): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer,
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
D/WifiDisplayController( 1017): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1017): disconnect
D/WifiDisplayController( 1017): updateConnection,
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1180): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
I/art     ( 1017): Explicit concurrent mark sweep GC freed 38292(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 27MB/40MB, paused 8.326ms total 213.522ms
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
D/AllShareCastTile( 1180): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/SecContentProvider2( 1017): mCursor = null,
V/NativeCrypto( 1630): SSL shutdown failed: ssl=0xb8c1aaf8: I/O error during system call, Broken pipe
D/ActivityManager( 1017): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
,I/qtaguid ( 1017): Untagging socket 360,
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin,
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1017): mCursor = null
I/SA      ( 4297): [OR] onReceive END
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2644): Autoconnection is available 
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/BluetoothPbapService( 2644): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothAdapterService( 2644): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 2644): terminating service from this receiver
D/EnterpriseController(  278): uids 1000,
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524292
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityManager.CallbackHandler( 2052): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothSocket( 2644): close() in, this: android.bluetooth.BluetoothSocket@2e9b0f10, channel: 19, state: LISTENING
D/BluetoothSocket( 2644): close() this: android.bluetooth.BluetoothSocket@2e9b0f10, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2825adc2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@cfc7a09mSocket: android.net.LocalSocket@20a4e40e impl:android.net.LocalSocketImpl@14858e2f fd:FileDescriptor[74]
D/BluetoothSocket( 2644): Closing mSocket: android.net.LocalSocket@20a4e40e impl:android.net.LocalSocketImpl@14858e2f fd:FileDescriptor[74]
,I/AMMetaDataParserService( 3891): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1459): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/Zygote  ( 4362): MountEmulatedStorage()
E/Zygote  ( 4362): v2
I/libpersona( 4362): KNOX_SDCARD checking this for 10042
,I/libpersona( 4362): KNOX_SDCARD not a persona
,I/SELinux ( 4362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4362 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4362): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3891): took 0.624896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a71740 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/BluetoothAdapterProperties( 2644): onBluetoothDisable()
,D/BluetoothAdapterProperties( 2644): mDiscovering is false
I/wpa_supplicant( 2009): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
W/art     ( 4274): Verification of android.content.Intent com.google.android.finsky.utils.NotificationManager.createDefaultClickIntent(android.content.Context, java.lang.String, java.lang.String, java.lang.String, java.lang.String) took 169.131ms
,I/BluetoothAdapterState( 2644): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/SecContentProvider2( 1017): mCursor = null
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,I/SA      ( 4297): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4297): [ODM] queryOpenData(key= GEO_IP )
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 7ms
,D/StatusBar.NetworkController( 1180): EthernetConnected: false,
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.637448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8f6f7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a50a88 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4362): TimaSignature is unavailable
,D/ActivityThread( 4362): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
I/InputMethodManagerService( 1017): [BT Setting State] State =13
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/BluetoothTile( 1180):  onBluetoothStateChange:
,I/SA      ( 4297): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4297): [LBE] REF_JPN : true
,I/SA      ( 4297): [BDC] create
,D/BluetoothTile( 1180):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1180): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1180):  getBluetoothState : 13
,D/BluetoothTile( 1180):  handleUpdatestate:false name:null
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
,D/BluetoothTile( 1180):  handleUpdatestate:false name:null
,I/SamsungIME( 1792): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/PhoneStatusBar( 1180): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/STATUSBAR-QSTileView( 1180): onStateChanged: Bluetooth
,I/AMMetaDataParserService( 3891): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1180): Wifi onReceive(0)
D/HotspotTile( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1180): onStateChanged: Wi-Fi
,D/HotspotTile( 1180): onReceive : 0, 0
,D/AndroidRuntime( 4358): 
D/AndroidRuntime( 4358): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/AndroidRuntime( 4358): CheckJNI is OFF
,D/AndroidRuntime( 4358): readGMSProperty: start
D/AndroidRuntime( 4358): readGMSProperty: already setted!!
D/AndroidRuntime( 4358): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4358): readGMSProperty: could not set the property(default)!!
,D/AndroidRuntime( 4358): readGMSProperty: end
D/AndroidRuntime( 4358): addProductProperty: start
,I/GFX raster( 3891): took 1.182864ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb86e7ba0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a712f0 counterpartCT=4 counterpartW=96 counterparth=96
,D/WifiCredService( 1301): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/StatusChecker( 4327): onReceive : android.intent.action.BOOT_COMPLETED
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/wpa_supplicant( 2009): Blacklist: Clear (all) 
,V/AlarmManager( 1017): waitForAlarm result :4
,I/StatusChecker( 4327): onReceive : net.mt.init : DONE
,D/BluetoothUtils( 2644): getBtEnabledContainers(): btContainers = [],
D/BluetoothAdapterProperties( 2644): Scan Mode:20
,I/GCoreUlr( 1825): Unbound from all location providers
D/BluetoothAdapterState( 2644): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2644): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2644): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 2644): cmd socket is not created
,E/bt-btm  ( 2644): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2644): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2644): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x001b not found for deregistration
,D/btif_config_util( 2644): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/wpa_supplicant( 2009): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1017): interfaceLinkStateChanged p2p0, false
D/Tethering( 1017): interfaceStatusChanged p2p0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged p2p0, false
,I/SA      ( 4297): [DBMV2] getEmailID
,D/BluetoothSocket( 2644): close() in, this: android.bluetooth.BluetoothSocket@2de9adc5, channel: 5, state: LISTENING
D/BluetoothSocket( 2644): close() this: android.bluetooth.BluetoothSocket@2de9adc5, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@390847d3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2acf331amSocket: android.net.LocalSocket@3be6de4b impl:android.net.LocalSocketImpl@1209b028 fd:FileDescriptor[76]
D/BluetoothSocket( 2644): Closing mSocket: android.net.LocalSocket@3be6de4b impl:android.net.LocalSocketImpl@1209b028 fd:FileDescriptor[76]
,I/SA      ( 4297): [DBMV2] getDataV02ForItems
,I/SA      ( 4297): [SSP] query invoked
,I/wpa_supplicant( 2009): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 2009): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2009): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 2009): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2009): wlan0: State: DISCONNECTED -> DISCONNECTED
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): InitialState.processMessage what=4
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
W/ResourcesManager( 4362): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1017): No numeric data
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Tethering( 1017): interfaceStatusChanged wlan0, false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,I/SA      ( 4297): [SCU] get signed id from samsung account2.0 DB.
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3891): took 0.738906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68e88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a50a88 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4391): MountEmulatedStorage()
E/Zygote  ( 4391): v2
I/libpersona( 4391): KNOX_SDCARD checking this for 10116
I/libpersona( 4391): KNOX_SDCARD not a persona
,I/SA      ( 4297): [SCU] get signed id from samsung account1.0 DB.
,I/SELinux ( 4391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4391 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 3550:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
I/AMMetaDataParserService( 3891): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
I/SELinux ( 4391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/OpenGLRenderer( 3203): Render dirty regions requested: true
,E/AffinityControl( 4358): AffinityControl: registerfunction enter
,E/SELinux ( 4391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,I/System.out( 1630): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1630): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1630): (HTTPLog)-Static: isShipBuild true
I/System.out( 1630): (HTTPLog)-Thread-181-717023319: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1630): (HTTPLog)-Static: isSBSettingEnabled false
,D/HotspotTile( 1180): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1180): updateTetherState():false, false
,I/SA      ( 4297): [BDC] destroy
,I/ActivityManager( 1017): Killing 3565:com.fmm.ds/1000 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=4, Uoast
,D/AndroidRuntime( 4358): Calling main entry com.android.commands.pm.Pm
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,V/NetworkStats( 1017): performPollLocked() took 4ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
D/TimaKeyStoreProvider( 4391): TimaSignature is unavailable
,D/ActivityThread( 4391): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131099648
,D/PackageManager( 1017): START PACKAGE DELETE: observer{308207553}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
,I/AMMetaDataParserService( 3891): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.678593ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8dcc2c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c1c6f8 counterpartCT=4 counterpartW=96 counterparth=96
,D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
I/dex2oat ( 4096): dex2oat took 3.160s (threads: 4)
,I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/PackageManager( 1017): !@killApplicatoin: 10174, uninstall pkg
,W/com.google.a.a.b.d.a( 4241): Application name is not set. Call Builder#setApplicationName.
,D/SRIB_DCS( 3203): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3203): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3203): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3203): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3203): Local Branch: 
I/Adreno-EGL( 3203): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3203): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3203):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 3203): Initialized EGL, version 1.4,
W/bt-l2cap( 2644): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2644): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2644): ag scb idx 1 not allocated
W/bt-btif ( 2644): ag scb idx 2 not allocated,
E/bt-btif ( 2644): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 2644): exiting userial_read_thread
D/bt_userial_mct( 2644): Leaving userial_evt_read_thread()
,D/bt_userial_mct( 2644): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2644): hw_epilog_process
D/bt_userial_mct( 2644): userial_close
I/bt_vendor( 2644): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,I/CalendarProvider2( 4362): CalendarProvider2.onCreate() called
,D/DexOptUtils( 2052): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex
D/DexOptUtils( 2052): Set odex to world readable.
,D/DexOptUtils( 2052): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.odex
,D/FileApkUtils( 2052): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/OpenGLRenderer( 3203): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3203): Enabling debug mode 0
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.656875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb86e7970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a15778 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/wpa_supplicant( 2009): Blacklist: Clear (all) 
,I/System.out( 3946): INFO:Resource not found:/Common.properties Using default values
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.615521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50a88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8c1c6f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/PackageSettings( 1017): Skipping PackageSetting{3854358c com.test.thalitest/10175} due to missing metadata
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.796198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8dcc690 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a15778 counterpartCT=4 counterpartW=96 counterparth=96
,I/wpa_supplicant( 2009): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,I/AMMetaDataParserService( 3891): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.625208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb86e7ba0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a68e28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3565/cgroup.procs: No such file or directory
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/GFX raster( 3891): took 0.762032ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68e88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c1c6f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 3358:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1017): Force removing ActivityRecord{15010e2a u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 3358
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/8)
,I/AMMetaDataParserService( 3891): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/PageBuddyNotiSvc( 4391): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131099648
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,I/AMMetaDataParserService( 3891): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): mDVFSHelper.acquire()
I/GFX raster( 3891): took 0.684896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8dcc2c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8dcc9b0 counterpartCT=4 counterpartW=96 counterparth=96
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,I/bt_vendor( 2644): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2644): bluetooth satus is on
I/bt_vendor( 2644): bt-vendor : resetting BT status
I/bt_vendor( 2644): Starting hciattach daemon
I/bt_vendor( 2644): try to set false
,I/bt_vendor( 2644): Starting hciattach daemon
I/bt_vendor( 2644): try to set false
I/bt_vendor( 2644): cleanup
I/GKI_LINUX( 2644): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2644): GKI_exit_task 0 done
I/GKI_LINUX( 2644): GKI_shutdown(): task [BTU] terminated
,I/AMMetaDataParserService( 3891): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/art     ( 3946): WaitForGcToComplete blocked for 37.699ms for cause HomogeneousSpaceCompact
,W/ContextImpl( 4391): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=0: pkg removed
,D/Finsky  ( 4274): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.650208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb86e7970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a15778 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/Launcher( 1480): onRestart, Launcher: 887735828
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.644792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a50a88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8c1c6f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3891): took 0.642813ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8dcc690 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8dcc9b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3891): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/art     ( 4016): Explicit concurrent mark sweep GC freed 18644(1035KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 6MB/9MB, paused 735us total 36.984ms
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/Settings( 4274): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/GFX raster( 3891): took 0.755833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb86e7ba0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a15778 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1017): failed to open /acct/uid_10062/pid_3550/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/        ( 3891): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/Settings( 4274): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/GFX raster( 3891): took 0.741198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3891): Bitmap=0xb8a68e88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c1c6f8 counterpartCT=4 counterpartW=96 counterparth=96
,D/Launcher( 1480): onStart, Launcher: 887735828
,D/Launcher.HomeView( 1480): onStart
,D/Launcher( 1480): onResume, Launcher: 887735828
,I/AMMetaDataParserService( 3891): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/SettingsProvider( 1017): name = kids_home_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/Launcher.HomeView( 1480): onResume
,E/WifiStateMachine( 1017): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [21]
,E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3891): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity,
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity,
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,D/BluetoothAdapterState( 2644): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2644): isSecureModeOn:false
,D/BluetoothAdapterService( 2644): mProfilesStarted : true supportedProfileServices.length : 12
,W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,I/PageBuddyNotiSvc( 4391): onCreate mCpBitFlag=0
,W/BluetoothAdapterService( 2644): Not skipping com.android.bluetooth.gatt.GattService
,I/GCoreUlr( 1825): DispatchingService.onDestroy()
I/GCoreUlr( 1825): Stopping handler for UlrDispSvcFast
,D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1792): mOCRHelper is null
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3203): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/Settings( 3989): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1180): Wifi onReceive(1)
D/HotspotTile( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1180): onStateChanged: Wi-Fi
,D/HotspotTile( 1180): onReceive : 1, 0
,D/WifiCredService( 1301): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/Settings( 1825): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.DebugUtils( 2644): handleDebugAction() action=null
,D/BtGatt.GattService( 2644): Received stop request...Stopping profile...
,W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 2644): stop()
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 2644): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
D/BtGatt.AdvertiseManager( 2644): advertise clients cleared
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED,
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,E/Zygote  ( 4430): MountEmulatedStorage()
I/libpersona( 4430): KNOX_SDCARD checking this for 10125
E/Zygote  ( 4430): v2
I/libpersona( 4430): KNOX_SDCARD not a persona
,I/SELinux ( 4430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4430 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,E/SELinux ( 4430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/AlarmManagerEXT( 1017): com.example.hello(10174) is removed.
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1017): [SO] activate (ident=0xb8f7f6e0, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2644): Not skipping com.android.bluetooth.a2dp.A2dpService
D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000],
D/SensorService( 1017): [SO] activate (ident=0xb9053320, enabled=1)
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/SensorService( 1017): [SO] AR_init
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2644): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d565b68
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  ,
,D/GmsModuleFndr( 2052): Beginning GMS chimera module scan
,D/MenuAppsGridFragment( 1480): onResume
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,D/HeadsetService( 2644): Received stop request...Stopping profile...
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2644): Not skipping com.android.bluetooth.hdp.HealthService
,D/TimaKeyStoreProvider( 4430): TimaSignature is unavailable
,D/ActivityThread( 4430): Added TimaKeyStore provider
,I/ApplicationPolicy( 1017): updateDataUsageMap
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131165197
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 39588(2MB) AllocSpace objects, 6(144KB) LOS objects, 33% free, 27MB/40MB, paused 6.288ms total 290.135ms
,D/GmsModuleFndr( 2052): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 2052): Beginning module configuration check
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=2_task.xml
,D/ChimeraCfgMgr( 2052): Module APKs unchanged, check complete
,D/ActivityManager( 1017): handle home activity for 0
,I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
,D/KnoxTimeoutHandler( 1017): post home show event for user 0
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,D/RegisteredComponentCache( 1445): Collect Tech packages for Knox
,I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/PersonaManager( 1445): isKioskContainerExistOnDevice
,W/ResourcesManager( 3891): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3891): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3891): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  258): id=13 createSurf (720x1280),1 flag=4, Mauncher
I/AMMetaDataParserService( 3891): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
D/PackageManager( 1017): delete codoeFile: 
D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,I/GAV2    ( 3910): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/AMMetaDataParserService( 3891): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
,I/AASA_removePackage( 1017): UID=10174 Target=com.example.hello
,D/PackageManager( 1017): result of delete: 1{308207553}
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2644): Not skipping com.android.bluetooth.pan.PanService
,D/InputDispatcher( 1017): Focus entered window: 1480
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3891): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/AndroidRuntime( 4358): Shutting down VM,
,D/SRIB_DCS( 1480): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2644): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 3358 uid 10174
,I/AMMetaDataParserService( 3891): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/SamsungIME( 1792): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager( 4430): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4430): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4430): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d565b68
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,I/GCoreUlr( 1825): Unbound from all location providers
W/BluetoothAdapterService( 2644): Not skipping com.broadcom.bt.service.sap.SapService
,W/GeofencerStateMachine( 1825): Ignoring removeGeofence because network location is disabled.
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1017): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/A2dpService( 2644): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2644): Exit Disconnected: -1
,W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,W/BluetoothAdapterService( 2644): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d565b68
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,W/BluetoothAdapterService( 2644): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,D/PersonaManager( 1445): isKioskContainerExistOnDevice
,W/BluetoothAdapterService( 2644): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2644): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/BluetoothAdapterService( 2644): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,D/BluetoothAdapterState( 2644): Stopping profile services that were post enabled
,D/BluetoothA2dp( 2947): Proxy object disconnected
,E/BluetoothAdapterService(492198760)( 2644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131165197
,D/HidService( 2644): Received stop request...Stopping profile...
,D/HidService( 2644): Stopping Bluetooth HidService,
,W/BluetoothHidServiceJni( 2644): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2644): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2644): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d565b68
,I/AMMetaDataParserService( 3891): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
,D/RegisteredServicesCache( 1445): empty dynamic service
,I/AMMetaDataParserService( 3891): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/ActivityManager( 1017): Displayed Component not be shown by security: +611ms
,D/HealthService( 2644): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d565b68
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,D/Tethering( 1017): interfaceRemoved wlan0
,E/Tethering( 1017): attempting to remove unknown iface (wlan0), ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/QuickConnect( 4430): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4430): Util.setSCRunningSetting - [value]0
,D/PanService( 2644): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d565b68
,E/BluetoothAdapterService(492198760)( 2644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2644): Profile still running: com.android.bluetooth.hid.HidService
,D/BluetoothMapService( 2644): Received stop request...Stopping profile...
,D/Volley  ( 4274): [643] DiskBasedCache.clear: Cache cleared.
,W/art     ( 4358): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/ActivityManager( 1017): Killing 3596:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,I/AMMetaDataParserService( 3891): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/Ads     ( 4274): Skipping gmscore version check
,D/Finsky  ( 4274): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4274): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Volley  ( 4274): [636] DiskBasedCache.clear: Cache cleared.
,I/AMMetaDataParserService( 3891): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/SettingsProvider( 1017): name = scon_is_running
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10125
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 2052): End new media; added: 0, uploading: 0, time: 1084 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d565b68
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/Tethering( 1017): interfaceRemoved p2p0
E/Tethering( 1017): attempting to remove unknown iface (p2p0), ignoring
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/SensorService( 1017): [SO] currT = 45530102533, prevT = 45060072533, diff = 470030000, [0.230 0.153 10.151]
,D/SensorService( 1017): [SO] 0.230 0.153 10.151
D/SensorService( 1017): [SO] [100 -> 255]
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/QuickConnect( 4430): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/AMMetaDataParserService( 3891): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
I/QuickConnect( 4430): PeriphStartReceiver.onReceive - no need to start
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/SQLiteLog( 3891): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3891): (3850) statement aborts at 19: [INSERT INTO AMData(actname,amicon,appname,id,amtitle,amstate,amintent,amlabel) VALUES (?,?,?,?,?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 3891): Error inserting actname=com.sec.android.gallery3d.app.GalleryActivity amicon=[B@30d16fbb appname=com.sec.android.gallery3d id=1448385985154 amtitle=Delete amstate=1 amintent=android.intent.action.delete amlabel=2131624002
E/SQLiteDatabase( 3891): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
E/SQLiteDatabase( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3891): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3891): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3891): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3891): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3891): getResourcePackageName:assistant
I/AMMetaDataParserService( 3891): Resource data:2131165197
,I/AMMetaDataParserService( 3891): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3891): getResourceTypeNamexml
I/AMMetaDataParserService( 3891): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,E/SQLiteLog( 3891): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3891): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3891): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3891): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3891): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3891): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3891): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3891): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/System.err( 3891): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3891): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3891): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3891): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3891): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3891): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/System.err( 3891): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3891): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3891): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3891): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3891): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3891): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1017): no available spell checker services found
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,W/BluetoothHeadsetServiceJni( 2644): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2644): Cleaning up Bluetooth Handsfree callback object
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/SapService( 2644): Received stop request...Stopping profile...
D/SapService( 2644): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2644): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d565b68
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,D/Finsky  ( 4274): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/Zygote  ( 4465): MountEmulatedStorage()
E/Zygote  ( 4465): v2
I/libpersona( 4465): KNOX_SDCARD checking this for 10131
I/libpersona( 4465): KNOX_SDCARD not a persona
,I/SELinux ( 4465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothA2dp( 1017): Proxy object disconnected
D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothPan( 1017): BluetoothPAN Proxy object disconnected
,I/SELinux ( 4465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4465): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/StatusBar( 1180): Icon Only
I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4465 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
D/PanelView( 1180): There is/are notification(s) 
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/BluetoothAdapterService(492198760)( 2644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 2644): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2644): Proxy object disconnected
D/BluetoothAdapterService( 2644): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 2644): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2644): GKI_exit_task 2 done
I/GKI_LINUX( 2644): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/BluetoothAdapterService(492198760)( 2644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 2644): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/BluetoothAdapterService(492198760)( 2644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2644): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2644): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2644): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(492198760)( 2644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2644): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothPanServiceJni( 2644): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2644): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(492198760)( 2644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2644): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 2644): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(492198760)( 2644): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 2644): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2644): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##

```
