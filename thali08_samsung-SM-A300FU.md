#### Test 503880194bce128_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
D/TP/MmsProvider( 1449): Update uri=content://mms, match=0
D/TP/MmsProvider( 1449): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
--------- beginning of system
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
D/TimaKeyStoreProvider( 2709): TimaSignature is unavailable
D/ActivityThread( 2709): Added TimaKeyStore provider
D/MtpService( 1223): updating state; isCurrentUser=true, mMtpLocked=false
I/Mms:transaction( 2216): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2216): [start]    nonBlockingUpdateMessageIndicator() consume time = 3424.056457
I/Mms/ReservationManager( 2216): resetAfterConnected()
D/Mms/MessagingNotification( 2216): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2216): isDefault true
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/WVMDrmPlugIn(  283): WVMDrmPlugin::onInitialize : 3944
D/WVMDrmPlugIn(  283): WVMDrmPlugin::onSetOnInfoListener : add 3944
D/TP/MmsProvider( 1449): Query uri=content://mms, match=0, calling pid = 2216
D/TP/MmsSmsProvider( 1449): query,matched:7, calling pid = 2216
D/TP/MmsSmsProvider( 1449): match 7:Elapsed time : 2.579 ms
I/Mms/ReservationManager( 2216): getReservedSendMessageCount(): retMessageCount=0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_1189/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_1413/cgroup.procs: No such file or directory
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2732): MountEmulatedStorage()
E/Zygote  ( 2732): v2
I/SELinux ( 2732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ContextImpl( 2709): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
I/libpersona( 2732): KNOX_SDCARD checking this for 10043
I/libpersona( 2732): KNOX_SDCARD not a persona
E/SELinux ( 2732): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DrmEventService( 1020): action event :android.intent.action.BOOT_COMPLETED
I/TimaServiceEventReceiver( 1020): TimaServiceEventReceiver : onReceive
I/ActivityManager( 1020): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2732 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TP/MmsSmsProvider( 1449): query,matched:200, calling pid = 2216
E/SQLiteLog( 1223): (283) recovered 403 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/TP/MmsSmsProvider( 1449): match 200:Elapsed time : 1.599 ms
I/ANDROID_DRM_FRWORKS_DrmManager(  283): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
D/Mms/SmsReceiverService( 2216): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2216
D/Mms/TelephonyPermission( 2216): isDefault true
D/Mms/SmsReceiverService( 2216): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/TP/SmsProvider( 1449): match 0:Elapsed time : 1.147 ms
D/Mms/SmsReceiverService( 2216): [start]    handleBootCompleted() consume time = 92.381615
D/TimaKeyStoreProvider( 2732): TimaSignature is unavailable
D/SSRM:a  ( 1020): DeviceInfo:: 000000000000
D/ActivityThread( 2732): Added TimaKeyStore provider
D/SSRM:a  ( 1020): SettingsAirViewInfo:: 000000000
E/CscReceiver( 1449): onReceive android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1223): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2750): MountEmulatedStorage()
E/Zygote  ( 2750): v2
I/libpersona( 2750): KNOX_SDCARD checking this for 10153
I/libpersona( 2750): KNOX_SDCARD not a persona
I/SELinux ( 2750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2750 uid=10153 gids={50153, 9997} abi=armeabi-v7a
E/USB_UICC(  302): Timeout! No signal received. Retry num = 24
I/SELinux ( 2750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/art     ( 2672): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 131.422ms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 1449): onStart
E/CscUpdateService( 1449): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1449): set_CSC_version
E/CscParser( 1449): update(): xml file exist
E/Zygote  ( 2765): MountEmulatedStorage()
E/Zygote  ( 2765): v2
I/libpersona( 2765): KNOX_SDCARD checking this for 10002
I/libpersona( 2765): KNOX_SDCARD not a persona
I/SELinux ( 2765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 2750): TimaSignature is unavailable
W/ResourcesManager( 2732): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
D/ActivityThread( 2750): Added TimaKeyStore provider
I/SELinux ( 2765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2765): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2765 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
W/ResourcesManager( 2732): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2732): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
I/CscUtil ( 1449): isWifiOnly = false
I/System.out( 1449): HandDataNode = null
I/CscUpdateService( 1449): PATH_CSCNAME =CustomerDataSet.CSCName
V/MediaScanner( 1223): processDirectory :  /system/media
D/TimaKeyStoreProvider( 2765): TimaSignature is unavailable
W/ResourcesManager( 2750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 2765): Added TimaKeyStore provider
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1020): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2781 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 2781): MountEmulatedStorage()
I/libpersona( 2781): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2781): v2
I/libpersona( 2781): KNOX_SDCARD not a persona
I/SELinux ( 2781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/SettingsProvider( 1020): name = block_emergency_message
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/SELinux ( 2781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10043
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
E/SELinux ( 2781): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1020): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
I/art     (  316): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 28.576ms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
I/CscUpdateService( 1449): This is normal boot : CSC not updated
E/CscParser( 1449): update(): xml file exist
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 836us total 18.311ms
V/MediaScanner( 1223):  prescan time: 180ms (DB items: 138)
V/MediaScanner( 1223):     scan time: 121ms (Caching mode: true), (makeEntry time: 17ms ~14%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1223): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 301ms
V/MediaScanner( 1223): checked files: 130  directories : 6  (I: 0, U: 0)
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1223): checkDefaultSounds
D/MediaScanner( 1223): system alarm_alert  : Vwiurug_etwofi5wgg
D/TP/MmsSmsProvider( 1449): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1449): deleteConversation threadId: 9223372036854775806
D/CscGPS  ( 1449): CSCGPS.updateParameters
D/CscGPS  ( 1449): supl host : null
D/CscGPS  ( 1449): SUPL Host is null or invalid
D/CscGPS  ( 1449): supl_ver : null
D/CscGPS  ( 1449): SUPL Ver is null or invalid
D/CscGPS  ( 1449): supl port : null
D/CscGPS  ( 1449): SUPL PORT is null or invalid
D/CscGPS  ( 1449): LPP : null
D/CscGPS  ( 1449): LPP is null or invalid
D/CscGPS  ( 1449): CSC don't have any AGPS value.
D/TimaKeyStoreProvider( 2781): TimaSignature is unavailable
D/ActivityThread( 2781): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1449): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1449): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1449): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 17.012ms
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1449): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
E/Zygote  ( 2799): MountEmulatedStorage()
E/Zygote  ( 2799): v2
I/libpersona( 2799): KNOX_SDCARD checking this for 1000
I/libpersona( 2799): KNOX_SDCARD not a persona
I/SELinux ( 2799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2799 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/CscUpdateService( 1449): same CSC Version
D/CscUtil ( 1449): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/MediaScanner( 1223): OK. alarm_alert is already exist in setting DB.
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
I/SELinux ( 2799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/Conversation( 2216): deleteTempConversation(),deleted=0
I/WifiCredService( 1296): onCreate
I/art     ( 1449): Explicit concurrent mark sweep GC freed 39283(2MB) AllocSpace objects, 9(144KB) LOS objects, 45% free, 4MB/8MB, paused 1.125ms total 163.473ms
D/MediaScanner( 1223): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1223): OK. notification_sound is already exist in setting DB.
D/TP/SmsProvider( 1449): query,matched:51, calling pid = 2216
D/MediaScanner( 1223): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1223): OK. ringtone is already exist in setting DB.
D/TP/SmsProvider( 1449): match 51:Elapsed time : 9.410 ms
D/TimaKeyStoreProvider( 2799): TimaSignature is unavailable
D/SmsProvider( 1449): Update uri=content://sms/outbox, match=8
D/ActivityThread( 2799): Added TimaKeyStore provider
D/MediaScannerService( 1223): !@done scanning volume internal
D/FactoryTestApp( 2507): [DummyFtClient$mBroadcastReceiver](2507) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2507): [DummyFtClient$mBroadcastReceiver](2507) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2507): [DummyFtClient$mBroadcastReceiver](2507) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/Mms/MessagingNotification( 2216): isBlockingModeEnabled() = false, Zen mode = 0
D/WifiTimerReceiver( 1296): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1296): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1296): Action boot completed received
D/MediaScannerService( 1223): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
D/Mms/SmsReceiverService( 2216): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2216): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2216): [SIM-1]sendFirstQueuedMessage()
D/TP/SmsProvider( 1449): query,matched:26, calling pid = 2216
D/TP/SmsProvider( 1449): match 26:Elapsed time : 2.948 ms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
E/Zygote  ( 2818): MountEmulatedStorage()
E/Zygote  ( 2818): v2
I/libpersona( 2818): KNOX_SDCARD checking this for 10155
I/libpersona( 2818): KNOX_SDCARD not a persona
I/SELinux ( 2818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2818 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
E/SELinux ( 2818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 1383:com.sec.android.provider.emergencymode/u0a92 (adj 15): empty #31
D/MediaScanner( 1223): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/NearbySettings( 1296): MountReceiver.onReceive - Create HandlerThread
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/NearbySettings( 1296): MountReceiver.onReceive - Start HandlerThread
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/NearbySettings( 1296): MountReceiver.onReceive - Create mPrefHandler
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2818): TimaSignature is unavailable
D/ActivityThread( 2818): Added TimaKeyStore provider
D/BadgeProvider( 1559): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1020): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
E/Zygote  ( 2834): MountEmulatedStorage()
I/libpersona( 2834): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2834): v2
I/libpersona( 2834): KNOX_SDCARD not a persona
I/SELinux ( 2834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
V/NearbySettings( 1296): MountReceiver.mPrefHandler - 7002
E/SELinux ( 2834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2834 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/Mms/SmsReceiver( 2216): unregisterForServiceStateChanges, already unregistered
W/libprocessgroup( 1020): failed to open /acct/uid_10092/pid_1383/cgroup.procs: No such file or directory
D/Mms/MessagingNotification( 2216): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2216): isDefault true
D/TimaKeyStoreProvider( 2834): TimaSignature is unavailable
D/ActivityThread( 2834): Added TimaKeyStore provider
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/NearbySettings( 1296): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1296): MountReceiver.onReceive - Internal Path
D/BadgeProvider( 1559): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/Launcher.Model( 1480): reloadBadges entered.
D/BadgeProvider( 1559): sendNotify, [notify] : null
D/BadgeProvider( 1559): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1559): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2216): setBadgeCount(), count=0
I/ActivityManager( 1020): Killing 1525:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
D/Mms/MessagingNotification( 2216): remove alarm
I/art     ( 1020): Explicit concurrent mark sweep GC freed 35607(1996KB) AllocSpace objects, 7(226KB) LOS objects, 33% free, 21MB/32MB, paused 2.075ms total 183.923ms
V/MediaScanner( 1223): processDirectory :  /storage/emulated/0
D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2216
D/TP/MmsProvider( 1449): Query uri=content://mms, match=0, calling pid = 2216
D/TP/SmsProvider( 1449): match 0:Elapsed time : 2.198 ms
W/ResourcesManager( 2818): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/SettingsProvider( 1020): name = personal_mode_enabled
D/Mms/MessagingNotification( 2216): [end]    nonBlockingUpdateMessageIndicator() consume time = 585.849062
D/MediaScanner( 1223): Skipping:
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(75ebcf7
D/Mms/MessagingNotification( 2216): updateAllHistoryAsRead()
W/ResourcesManager( 2834): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/MediaScanner( 1223): Skipping:
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1223): processDirectory :  /storage/extSdCard
W/MediaScanner( 1223): Error opening directory, reason : Permission denied.
W/MediaScanner( 1223): 7klwibgf7fxlKdCbid7
V/MediaScanner( 1223):  prescan time: 237ms (DB items: 26)
V/MediaScanner( 1223):     scan time: 68ms (Caching mode: true), (makeEntry time: 46ms ~67%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1223): postscan time: 5ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 310ms
V/MediaScanner( 1223): checked files: 10  directories : 16  (I: 0, U: 0)
D/TP/MmsSmsProvider( 1449): query,matched:200, calling pid = 2216
D/FactoryTestApp( 2507): [DummyFtClient$mBroadcastReceiver](2507) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2507): [DummyFtClient$mBroadcastReceiver](2507) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2507): [DummyFtClient$sendBootCompletedAndFinish](2507) ...
D/MediaScannerService( 1223): !@done scanning volume external
D/FactoryTestApp( 2507): [Support$Values.getString](2507) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2507): [ModuleCommon$isConnectionModeNone](2507) mConnectionMode = gsm
D/FactoryTestApp( 2507): [IPCWriterToSecPhoneService$ResponseWriter](2507) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2507): [IPCWriterToSecPhoneService$connectToSecPhoneService](2507)  
D/TP/MmsSmsProvider( 1449): match 200:Elapsed time : 6.271 ms
D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2216
D/TP/SmsProvider( 1449): match 0:Elapsed time : 1.596 ms
W/libprocessgroup( 1020): failed to open /acct/uid_10052/pid_1525/cgroup.procs: No such file or directory
D/TP/SmsProvider( 1449): query,matched:51, calling pid = 2216
D/TP/SmsProvider( 1449): match 51:Elapsed time : 1.527 ms
D/[0]UMC:Core( 2818): onCreate(): 
D/Mms/MessagingNotification( 2216): isBlockingModeEnabled() = false, Zen mode = 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1559): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
E/Zygote  ( 2856): MountEmulatedStorage()
E/Zygote  ( 2856): v2
I/ActivityManager( 1020): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2856 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
I/libpersona( 2856): KNOX_SDCARD checking this for 10082
I/libpersona( 2856): KNOX_SDCARD not a persona
I/SELinux ( 2856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/SELinux ( 2856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2856): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/[0]UMC:DeviceInfo( 2818): USA==US==
D/TimaKeyStoreProvider( 2856): TimaSignature is unavailable
D/ActivityThread( 2856): Added TimaKeyStore provider
I/FactoryTestApp( 2507): [IPCWriterToSecPhoneService$onServiceConnected](2507) connected done
D/FactoryTestApp( 2507): [IPCWriterToSecPhoneService$write](2507) Send Response Message to SecPhone
D/FactoryTestApp( 2507): [IPCWriterToSecPhoneService$write](2507) Response ��
W/ResourcesManager( 1449): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/AT_Distributor(  331): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 2507): [IPCWriterToSecPhoneService$handleMessage](2507) Send BOOTING COMPLETED done
D/USER_AGENT( 2818): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/[0]UMC:AdminManager( 2818): init - start
D/[0]UMC:AdminManager( 2818): loadAdmins
E/SQLiteLog( 2799): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
D/Launcher.Model( 1480): reloadBadges entered.
D/BadgeProvider( 1559): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): sendNotify, [notify] : null
D/BadgeProvider( 1559): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1559): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2216): setBadgeCount(), count=0
D/[0]UMC:AdminManager( 2818): init - end
D/GSLBManager( 2818): migrateStoredUrlFromOldPref
D/Mms/MessagingNotification( 2216): remove alarm
I/SmartcardBootCompleteReceiver( 1296): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1296): Received intent with action - android.intent.action.BOOT_COMPLETED
D/DSM     ( 2799): [Lines:107] Normal booted
D/DSM     ( 2799): [Lines:114] Boot completed
I/iu.UploadsManager( 1801): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
D/GSLBManager( 2818): migrateStoredUrlFromOldPref : Migration Not Needed
D/Mms/MessagingNotification( 2216): updateAllHistoryAsRead()
D/[0]UMC:UMCAdmin( 2818): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2818): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2818): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2818): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2818): isContainer : 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2216
D/EnterpriseDeviceManagerService( 1020): isManagedProfileUser(): userId = 0
D/TP/SmsProvider( 1449): match 0:Elapsed time : 2.591 ms
D/AT_Distributor(  331): SetAtdStatus(), 1_1_0
D/AT_Distributor(  331): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
E/Zygote  ( 2882): MountEmulatedStorage()
E/Zygote  ( 2882): v2
I/libpersona( 2882): KNOX_SDCARD checking this for 1000
I/libpersona( 2882): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/[0]UMC:UMCAdmin( 2818): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 2818): isContainer : 0
I/ActivityManager( 1020): Killing 1785:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
I/SELinux ( 2882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/UpdateRequestReceiver( 2856): ignoring update request
I/SmartcardBootCompleteReceiver( 1296): Broadcast sent with current lockscreen type
D/[0]UMC:UMCAdmin( 2818): deactivateUMCAdmin - UMC App Admin deactivated
D/[0]UMC:CoreReceiver( 2818): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2818):  check PreETag 
D/Mms/SmsReceiverService( 2216): [end]    handleBootCompleted() consume time = 273.104531
E/UpdateRequestReceiver( 2856): ignoring update request
D/[0]UMC:ByodSetupStarter( 2818): Container ID : 0
V/[0]UMC:Utils( 2818): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2818): shutdown
I/art     ( 2818): System.exit called, status: 0
I/AndroidRuntime( 2818): VM exiting with result code 0, cleanup skipped.
I/ActivityManager( 1020): Killing 2030:com.vlingo.midas/u0a28 (adj 15): empty #31
D/TimaKeyStoreProvider( 2882): TimaSignature is unavailable
D/ActivityThread( 2882): Added TimaKeyStore provider
E/UpdateRequestReceiver( 2856): ignoring update request
W/ResourcesManager( 2882): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/[SBeam] ( 1296): SBeamEnabler.initPreferenceForSbeam : 0
E/UpdateRequestReceiver( 2856): ignoring update request
I/SettingSearch/SearchIntentReceiver( 1296): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1296): search setting db init!!
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
I/SettingSearch/SearchIntentReceiver( 1296): BOOT_COMPLETED call InitSerachDBThread thread start!
E/UpdateRequestReceiver( 2856): ignoring update request
I/iu.UploadsManager( 1801): End new media; added: 0, uploading: 0, time: 106 ms
E/UpdateRequestReceiver( 2856): ignoring update request
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/ActivityThread( 2882): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/Zygote  ( 2913): MountEmulatedStorage()
I/libpersona( 2913): KNOX_SDCARD checking this for 10088
E/Zygote  ( 2913): v2
I/libpersona( 2913): KNOX_SDCARD not a persona
I/SELinux ( 2913): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2913): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=2913 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 2913): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2074:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
I/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
D/TimaKeyStoreProvider( 2913): TimaSignature is unavailable
E/Zygote  ( 2928): MountEmulatedStorage()
E/Zygote  ( 2928): v2
I/libpersona( 2928): KNOX_SDCARD checking this for 10146
I/libpersona( 2928): KNOX_SDCARD not a persona
I/SELinux ( 2928): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/ActivityThread( 2913): Added TimaKeyStore provider
I/SELinux ( 2928): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
E/SELinux ( 2928): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2928 uid=10146 gids={50146, 9997} abi=armeabi-v7a
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
E/Zygote  ( 2937): MountEmulatedStorage()
E/Zygote  ( 2937): v2
I/libpersona( 2937): KNOX_SDCARD checking this for 1000
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
I/libpersona( 2937): KNOX_SDCARD not a persona
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
I/SELinux ( 2937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
I/ActivityManager( 1020): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2937 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
I/SELinux ( 2937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
E/SELinux ( 2937): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2882): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/ActivityManager( 1020): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2818)(adj 0) has died(38,733)
I/LcdtestApp( 2882): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
E/SMD     (  289): DCD OFF
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2928): TimaSignature is unavailable
D/ActivityThread( 2928): Added TimaKeyStore provider
D/daemonapp( 1726): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1726): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1726): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1726): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/Zygote  ( 2958): MountEmulatedStorage()
I/libpersona( 2958): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2958): v2
I/libpersona( 2958): KNOX_SDCARD not a persona
E/USB_UICC(  302): Timeout! No signal received. Retry num = 25
I/ActivityManager( 1020): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2958 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Killing 2131:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
I/SELinux ( 2958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2958): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1726): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/TimaKeyStoreProvider( 2937): TimaSignature is unavailable
D/ActivityThread( 2937): Added TimaKeyStore provider
D/daemonapp( 1726): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1726): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1726): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1726): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1726): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1726): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1726): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/SettingsProvider( 1020): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10157
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
D/TimaKeyStoreProvider( 2958): TimaSignature is unavailable
D/ActivityThread( 2958): Added TimaKeyStore provider
W/ResourcesManager( 2937): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/libprocessgroup( 1020): failed to open /acct/uid_10134/pid_1785/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10028/pid_2030/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10045/pid_2074/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10110/pid_2131/cgroup.procs: No such file or directory
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
D/daemonapp( 1726): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1726): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/daemonapp( 1726): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1726): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1726): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1726): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/daemonapp( 1726): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1726): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1726): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1448461015897
D/daemonapp( 1726): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1448482560000
I/FOTA    ( 2937): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
D/daemonapp( 1726): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1726): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/daemonapp( 1726): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448482560000
D/AndroidRuntime( 2953): 
D/AndroidRuntime( 2953): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2953): CheckJNI is OFF
D/AndroidRuntime( 2953): readGMSProperty: start
D/AndroidRuntime( 2953): readGMSProperty: already setted!!
D/AndroidRuntime( 2953): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2953): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2953): readGMSProperty: end
D/AndroidRuntime( 2953): addProductProperty: start
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DIAGMON_AGENT( 2958): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
E/Zygote  ( 2978): MountEmulatedStorage()
E/Zygote  ( 2978): v2
I/libpersona( 2978): KNOX_SDCARD checking this for 10088
I/libpersona( 2978): KNOX_SDCARD not a persona
I/SELinux ( 2978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=2978 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2978): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/daemonapp( 1726): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 88
D/daemonapp( 1726): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1448482560000
D/TimaKeyStoreProvider( 2978): TimaSignature is unavailable
D/ActivityThread( 2978): Added TimaKeyStore provider
I/DBG_DM  ( 2937): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
I/DBG_DM  ( 2937): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
I/DBG_DM  ( 2937): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
D/comdaemonstockapp( 1726): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1726): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/com.dropbox.android.service.DropboxNetworkReceiver( 2913): Setting receiver enabled: false
E/Zygote  ( 3004): MountEmulatedStorage()
E/Zygote  ( 3004): v2
I/ActivityManager( 1020): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3004 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 3004): KNOX_SDCARD checking this for 10161
I/libpersona( 3004): KNOX_SDCARD not a persona
I/SELinux ( 3004): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3004): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3004): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 2937): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
W/ContextImpl( 2937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/art     (  316): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 31.663ms
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
E/ActivityThread( 2913): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
D/TimaKeyStoreProvider( 3004): TimaSignature is unavailable
D/ActivityThread( 3004): Added TimaKeyStore provider
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.901ms
I/ActivityManager( 1020): Killing 1587:com.google.android.partnersetup/u0a14 (adj 15): empty #31
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 2937): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/DBG_DM  ( 2937): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 2937): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 2937): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DIAGMON_AGENT( 2958): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DBG_DM  ( 2937): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/DBG_DM  ( 2937): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 24.365ms
I/DBG_DM  ( 2937): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
I/DBG_DM  ( 2937): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
W/ContextImpl( 2937): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
I/DIAGMON_AGENT( 2958): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_DM  ( 2937): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 2937): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(155/onStartCommand)] 
D/OverheatReceiver( 1180): onReceive() getAction : android.intent.action.BOOT_COMPLETED
W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_1587/cgroup.procs: No such file or directory
I/DIAGMON_AGENT( 2958): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 2958): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2958): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2958): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/OverheatReceiver( 1180): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1180): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1180): isSafeMode = false
I/DBG_DM  ( 2937): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
I/dbxyzptlk.db240408.D.h( 2913): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
D/BootupListener( 1449): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1020): name = internet_call_settings_visibility
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1001
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
D/PhoneUtilsCommon( 1449): isSupportVoLTE is false.
I/dbxyzptlk.db240408.D.h( 2913): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
I/dbxyzptlk.db240408.D.h( 2913): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3022): MountEmulatedStorage()
E/Zygote  ( 3022): v2
I/libpersona( 3022): KNOX_SDCARD checking this for 1000
I/libpersona( 3022): KNOX_SDCARD not a persona
I/SELinux ( 3022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3022): TimaSignature is unavailable
D/ActivityThread( 3022): Added TimaKeyStore provider
I/DBG_DM  ( 2937): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
I/Telecom ( 1425): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
I/dbxyzptlk.db240408.D.h( 2913): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1020): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3037 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/Zygote  ( 3037): MountEmulatedStorage()
I/libpersona( 3037): KNOX_SDCARD checking this for 10052
E/Zygote  ( 3037): v2
I/libpersona( 3037): KNOX_SDCARD not a persona
I/SELinux ( 3037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3037): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2235:com.sec.tcpdumpservice/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3037): TimaSignature is unavailable
D/ActivityThread( 3037): Added TimaKeyStore provider
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2235/cgroup.procs: No such file or directory
W/ResourcesManager( 3004): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3004): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Telecom ( 1425): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
V/JNIHelp ( 3004): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/breakpad( 2913): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
I/com.dropbox.sync.android.a( 2913): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
W/ActivityThread( 3004): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3004): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@161171a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3004): Installed default security provider GmsCore_OpenSSL
V/audio_hw_primary(  284): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  284): audio_extn_get_parameters: returns 
V/msm8974_platform(  284): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  284): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  284): key: 'call_forwarding' value: ''
V/InCall  ( 1840): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1840): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1840): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
D/ScoverManager( 1840): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1840): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
E/AffinityControl( 2953): AffinityControl: registerfunction enter
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1840): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/Telecom ( 1425): ProximitySensorManager: Proximity wake lock already released
I/InCall  ( 1840): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1840): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1840): InCallPresenter -  - dismissCoverDialog()...
I/InCall  ( 1840): CallSContextMotion - stopPutDownListening
D/InCall  ( 1840): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
D/PhoneStatusBarView( 1180): setCallBackground:0
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1840): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
D/AndroidRuntime( 2953): Calling main entry com.android.commands.am.Am
D/VideoCallManager( 1840): Instantiating VideoCallManager
E/        ( 1840): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
E/USB_UICC(  302): Timeout! No signal received. Retry num = 26
I/GFX construct_block_size_descriptor_2d second part( 1840): took 2.599427ms for 0*0 texture 0
I/GFX generate_partition_tables( 1840): took 5.954271ms for 0*0 texture 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/GFX raster( 1840): took 12.761823ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1840): Bitmap=0xb81fe078 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb81fd948 counterpartCT=4 counterpartW=176 counterparth=144
E/Zygote  ( 3067): MountEmulatedStorage()
E/Zygote  ( 3067): v2
I/libpersona( 3067): KNOX_SDCARD checking this for 10008
I/libpersona( 3067): KNOX_SDCARD not a persona
I/SELinux ( 3067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3067 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3067): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3067): TimaSignature is unavailable
D/ActivityThread( 3067): Added TimaKeyStore provider
I/DBG_POLICYDM( 3022): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3022): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 3022): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
E/Zygote  ( 3088): MountEmulatedStorage()
I/libpersona( 3088): KNOX_SDCARD checking this for 10014
E/Zygote  ( 3088): v2
I/libpersona( 3088): KNOX_SDCARD not a persona
I/SELinux ( 3088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3088 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3088): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 3022): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_DM  ( 2937): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
I/DBG_POLICYDM( 3022): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
E/        ( 1840): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
D/LocationManagerService( 1020): getProviders()=[passive]
I/Adreno-EGL( 1840): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1840): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1840): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1840): Local Branch: 
I/Adreno-EGL( 1840): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1840): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1840):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3022): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 3022): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
D/TimaKeyStoreProvider( 3088): TimaSignature is unavailable
D/ActivityThread( 3088): Added TimaKeyStore provider
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
I/DBG_POLICYDM( 3022): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
W/ActivityManager( 1020): mDVFSHelper.acquire()
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1020): Set to : 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1480
D/AndroidRuntime( 2953): Shutting down VM
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
I/ContactAccountLoggerTas( 3037): canRun() : Opted Out
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Launcher.HomeView( 1480): onPause
D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3119): MountEmulatedStorage()
I/libpersona( 3119): KNOX_SDCARD checking this for 10333
E/Zygote  ( 3119): v2
I/libpersona( 3119): KNOX_SDCARD not a persona
I/SELinux ( 3119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3119): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/GFX GPU raster( 1840): eglCreateImageKHR: EGL_SUCCESS
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3119 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/glCompressedTexImage2D( 1840): took 0.352240ms for 320*61440 texture 37809
I/DBG_DM  ( 2937): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/draw setup( 1840): took 11.316251ms for 320*240 texture 37809
E/GFX GPU raster( 1840): drawn
I/GFX GPU raster ASTC( 1840): took 47.005262ms for 320*240 texture 12
I/GFX raster( 1840): took 47.080106ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1840): Bitmap=0xb81f92f8 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb81fd9d0 counterpartCT=4 counterpartW=320 counterparth=240
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
V/ActivityThread( 1480): updateVisibility : ActivityRecord{341789e7 token=android.os.BinderProxy@27b7ee12 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/        ( 1840): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/DBG_DM  ( 2937): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
I/GFX GPU raster( 1840): eglCreateImageKHR: EGL_SUCCESS
D/TimaKeyStoreProvider( 3119): TimaSignature is unavailable
I/DBG_DM  ( 2937): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
D/ActivityThread( 3119): Added TimaKeyStore provider
I/glCompressedTexImage2D( 1840): took 0.505000ms for 480*122880 texture 37813
I/draw setup( 1840): took 0.997865ms for 480*640 texture 37813
E/GFX GPU raster( 1840): drawn
I/GFX GPU raster ASTC( 1840): took 8.479479ms for 480*640 texture 12
I/GFX raster( 1840): took 8.555364ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1840): Bitmap=0xb843f310 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb843f688 counterpartCT=4 counterpartW=480 counterparth=640
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
I/com.dropbox.sync.android.ad( 2913): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
D/Launcher.HomeView( 1480): onStop
V/ActivityThread( 1480): updateVisibility : ActivityRecord{341789e7 token=android.os.BinderProxy@27b7ee12 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3004): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
D/PersonaManager( 1020): isKioskContainerExistOnDevice
W/art     ( 2953): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/        ( 1840): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1840): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1840): took 0.349270ms for 440*116864 texture 37809
I/draw setup( 1840): took 0.842864ms for 440*330 texture 37809
E/GFX GPU raster( 1840): drawn
I/GFX GPU raster ASTC( 1840): took 4.668593ms for 440*330 texture 12
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/GFX raster( 1840): took 4.751771ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1840): Bitmap=0xb84540f0 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8454148 counterpartCT=4 counterpartW=440 counterparth=330
D/SensorService( 1020): [SO] activate (ident=0xb8590660, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/Launcher( 1480): onTrimMemory. Level: 20
,D/SensorManager( 1020): unregisterListener ::   
,I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1020): [SO] changed settle time [1]
D/SensorService( 1020): [SO] setDelay [66000000]
D/SensorService( 1020): [SO] activate (ident=0xb8662d98, enabled=1)
D/SensorService( 1020): [SO] AR_init
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,E/        ( 1840): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1840): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1840): took 0.448542ms for 480*163840 texture 37811
I/draw setup( 1840): took 0.958438ms for 480*640 texture 37811
E/GFX GPU raster( 1840): drawn
,I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/GFX GPU raster ASTC( 1840): took 5.862083ms for 480*640 texture 12
I/GFX raster( 1840): took 5.953854ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1840): Bitmap=0xb842a508 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb843f4e8 counterpartCT=4 counterpartW=480 counterparth=640
,I/DBG_POLICYDM( 3022): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3022): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3022): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3022): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3022): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3022): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3022): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
,E/        ( 1840): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/GFX construct_block_size_descriptor_2d second part( 1840): took 2.632708ms for 0*0 texture 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/GFX generate_partition_tables( 1840): took 8.629011ms for 0*0 texture 0
I/GFX raster( 1840): took 13.326042ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1840): Bitmap=0xb842f590 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb842f4f8 counterpartCT=4 counterpartW=176 counterparth=144
E/        ( 1840): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1840): took 2.525625ms for 0*0 texture 0
,I/ActivityManager( 1020): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3147 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/GFX generate_partition_tables( 1840): took 6.213177ms for 0*0 texture 0
E/Zygote  ( 3147): MountEmulatedStorage()
E/Zygote  ( 3147): v2
I/libpersona( 3147): KNOX_SDCARD checking this for 1000,
I/libpersona( 3147): KNOX_SDCARD not a persona
,I/GFX raster( 1840): took 10.942813ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1840): Bitmap=0xb843f958 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb842f4f8 counterpartCT=4 counterpartW=176 counterparth=144
,I/SELinux ( 3147): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Killing 2268:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 1495:com.android.printspooler/u0a132 (adj 15): empty #32
I/ActivityManager( 1020): Killing 2246:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #33
D/ScoverManager( 1840): registerListener
I/SELinux ( 3147): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
E/SELinux ( 3147): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1020): registerListenerCallback : binder = android.os.BinderProxy@140dd9e8, pid : 1840, uid : 1001, type : 1
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1020): [SO] -0.421 -0.019 9.883
,D/SensorService( 1020): [SO] [100 -> 255]
,E/Zygote  ( 3156): MountEmulatedStorage()
E/Zygote  ( 3156): v2
I/libpersona( 3156): KNOX_SDCARD checking this for 10090
I/libpersona( 3156): KNOX_SDCARD not a persona
,I/SELinux ( 3156): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3156 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2315:com.wsomacp/u0a23 (adj 15): empty #31
,I/SELinux ( 3156): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3156): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InCall  ( 1840): InCallPresenter -  - Finished InCallPresenter.setUp
,D/TimaKeyStoreProvider( 3147): TimaSignature is unavailable
,W/GAV2    ( 3037): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityThread( 3147): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3156): TimaSignature is unavailable
W/GAV2    ( 3037): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/ActivityThread( 3156): Added TimaKeyStore provider
,I/ContactAccountLoggerTas( 3037): canRun() : Opted Out
,I/WebViewFactory( 3119): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/SensorService( 1020): [SO] -0.421 -0.019 9.883
,I/LibraryLoader( 3119): Loading: webviewchromium
,I/LibraryLoader( 3119): Time to load native libraries: 4 ms (timestamps 2827-2831)
I/LibraryLoader( 3119): Expected native library version number "",actual native library version number ""
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1020): getStreamVolume 3 index 70
,I/MediaRouter( 3037): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/FavoriteContactNamesSup( 3037): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3037): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3037): get() : OptedIn = false
,W/libprocessgroup( 1020): failed to open /acct/uid_10132/pid_1495/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2268/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10023/pid_2315/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10127/pid_2246/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Killing 2334:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDM( 3147): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/elm:15121( 3156): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 3156): ELMEngine.ELMEngine( context ).
,D/elm:15121( 3156): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 3156): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 3156): ElmAgentService : onCreate()
,D/elm:15121( 3156): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 3156): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3156): BootCompletedState : startBootCompleted() call
,D/elm:15121( 3156): MDMBridge.getAllLicenseInfoFromSDK()
,I/DBG_FMMDM( 3147): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
I/DBG_FMMDM( 3147): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
I/DBG_FMMDM( 3147): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
I/elm:15121( 3156): Get License : 0
D/elm:15121( 3156): ElmAgentService : onDestroy().
,I/System.out( 2913): Thread-374(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/WebViewChromiumFactoryProvider( 3119): Binding Chromium to main looper Looper (main, tid 1) {89133e9}
,I/System.out( 2913): Thread-374(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2913): Thread-374(ApacheHTTPLog):isShipBuild true
I/System.out( 2913): Thread-374(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2913): Thread-374(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 3119): Expected native library version number "",actual native library version number ""
I/chromium( 3119): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10088
,E/Zygote  ( 3189): MountEmulatedStorage()
E/Zygote  ( 3189): v2
I/libpersona( 3189): KNOX_SDCARD checking this for 1000
I/libpersona( 3189): KNOX_SDCARD not a persona
,I/SELinux ( 3189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3189 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SELinux ( 3189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 3189): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  258): id=7 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=7 Removed Mauncher (-2/8)
,V/EmergencyMode( 1401): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,E/Zygote  ( 3201): MountEmulatedStorage()
,E/Zygote  ( 3201): v2
I/libpersona( 3201): KNOX_SDCARD checking this for 10055
I/libpersona( 3201): KNOX_SDCARD not a persona
,I/SELinux ( 3201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/BrowserStartupController( 3119): Initializing chromium process, renderers=0
I/SELinux ( 3201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/art     ( 3119): Attempt to remove local handle scope entry from IRT, ignoring
,E/SELinux ( 3201): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3201 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,W/libprocessgroup( 1020): failed to open /acct/uid_10039/pid_2334/cgroup.procs: No such file or directory
,I/System.out( 2913): pool-10-thread-1 calls detatch()
W/chromium( 3119): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,D/TimaKeyStoreProvider( 3189): TimaSignature is unavailable
,D/ActivityThread( 3189): Added TimaKeyStore provider
,W/chromium( 3119): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 3119): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 3119): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/TimaKeyStoreProvider( 3201): TimaSignature is unavailable
,D/BluetoothAdapter( 3119): 853166190: getState() :  mService = null. Returning STATE_OFF
,D/ActivityThread( 3201): Added TimaKeyStore provider
,V/EmergencyMode( 1401): [EmergencyBase] setBootTime
,V/EmergencyMode( 1401): [EmergencyFactory] No Recovery State, kill my self.
,I/Adreno-EGL( 3119): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3119): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3119): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3119): Local Branch: 
I/Adreno-EGL( 3119): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3119): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3119):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/ActivityManager( 1020): Killing 2363:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3231): MountEmulatedStorage()
E/Zygote  ( 3231): v2
,I/libpersona( 3231): KNOX_SDCARD checking this for 1000
I/libpersona( 3231): KNOX_SDCARD not a persona
,I/SELinux ( 3231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3231): TimaSignature is unavailable
,I/PCWCLIENTTRACE_LOG( 3189): DEFAULT_LOGON : true
D/ActivityThread( 3231): Added TimaKeyStore provider
I/PCWCLIENTTRACE_LOG( 3189): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3189): new DMDBOpenHelper instance
,I/CameraApp( 3231): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3231): Feature.Feature(context)
I/testFeature( 3231): Feature.readInternalDefaultXml()
,I/testFeature( 3231): ResetFeatureValue
,I/CameraFirmware_broadcast( 3231): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3231): CameraApp.getAppFeature()...
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3255): MountEmulatedStorage()
E/Zygote  ( 3255): v2
I/libpersona( 3255): KNOX_SDCARD checking this for 10095
,I/libpersona( 3255): KNOX_SDCARD not a persona
,I/SELinux ( 3255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3255 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2381:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10139/pid_2363/cgroup.procs: No such file or directory
,I/art     (  316): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 22.865ms
,E/USB_UICC(  302): Timeout! No signal received. Retry num = 27
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 16.183ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 645us total 17.170ms
,D/TimaKeyStoreProvider( 3255): TimaSignature is unavailable
,D/UserAnalysis.PlaceProvider( 3201): PlaceProvider onCreate()
D/ActivityThread( 3255): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_10135/pid_2381/cgroup.procs: No such file or directory
,W/chromium( 3119): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 3119): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 3119): Attempt to remove local handle scope entry from IRT, ignoring
,D/UserAnalysis.SecureDbManager( 3201): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3201): SecurePlaceDbHelper() 
D/UserAnalysis( 3201): Create SecureDbHelper
,W/AwContents( 3119): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 3119): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 3119): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 3119): CordovaWebView is running on device made by: samsung
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 21143(1132KB) AllocSpace objects, 4(70KB) LOS objects, 33% free, 21MB/32MB, paused 2.105ms total 162.198ms
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,D/IntelligenceServiceApplication( 3201): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3201): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,W/art     ( 3119): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3119): Attempt to remove local handle scope entry from IRT, ignoring
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,D/PCWCLIENTTRACE_DMContentProvider( 3189): [URIMatcher] - result : 2
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/IntelligenceServiceApplication( 3201): no applications having user consent for prediction
,E/Zygote  ( 3274): MountEmulatedStorage()
E/Zygote  ( 3274): v2
I/libpersona( 3274): KNOX_SDCARD checking this for 10056
I/libpersona( 3274): KNOX_SDCARD not a persona
I/SELinux ( 3274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3274 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 3274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 2188:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/PreloadFilterInstaller( 3255): uses FILTER_DB_VER_1
,I/DBG_FMMDM( 3147): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,D/TimaKeyStoreProvider( 3274): TimaSignature is unavailable
,D/ActivityThread( 3274): Added TimaKeyStore provider
,I/DBG_FMMDM( 3147): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,V/PlaceDetection v1.0.19 ( 3201): [PlaceDetection::stopService] Service stopped.
,D/OpenGLRenderer( 3119): Render dirty regions requested: true
,I/DBG_FMMDM( 3147): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,E/SQLiteLog( 3255): (284) automatic index on titles(filter_id)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 3119): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3119): *FMB* isFloatingMenuEnabled return false
,E/Zygote  ( 3294): MountEmulatedStorage()
E/Zygote  ( 3294): v2
I/libpersona( 3294): KNOX_SDCARD checking this for 1000
I/libpersona( 3294): KNOX_SDCARD not a persona
,I/SELinux ( 3294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
I/ActivityManager( 1020): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3294 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2535:com.android.keychain/1000 (adj 15): empty #31
I/SELinux ( 3294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Killing 2473:com.android.calendar/u0a131 (adj 15): empty #32
E/SELinux ( 3294): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputDispatcher( 1020): Focus entered window: 3119
,D/[SBeam] ( 1296): SBeamEnabler.isSBeamSupported : [-1]
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3119): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3119): Initialized EGL, version 1.4
D/[SBeam] ( 1296): SBeamEnabler.isSBeamSupported : EXIST
,D/OpenGLRenderer( 3119): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
,D/OpenGLRenderer( 3119): Enabling debug mode 0
,D/TimaKeyStoreProvider( 3294): TimaSignature is unavailable
,D/ActivityThread( 3294): Added TimaKeyStore provider
,I/DBG_FMMDS( 3294): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3294): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,V/PlaceDetection v1.0.19 ( 3201): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3201): Constructor Preference
,I/FilterProviderReceiver( 3255): onReceive in FilterProviderReceiver
I/FilterProviderReceiver( 3255): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data,
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2188/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2535/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,E/Zygote  ( 3316): MountEmulatedStorage()
E/Zygote  ( 3316): v2
I/libpersona( 3316): KNOX_SDCARD checking this for 10098
I/libpersona( 3316): KNOX_SDCARD not a persona
,I/SELinux ( 3316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3316 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
I/ActivityManager( 1020): Killing 2601:com.mobeam.barcodeService/1000 (adj 15): empty #31
,D/PCWCLIENTTRACE_DMContentProvider( 3189): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3294): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,E/YouTube MDX( 3004): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/TimaKeyStoreProvider( 3316): TimaSignature is unavailable
,D/ActivityThread( 3316): Added TimaKeyStore provider
,I/DBG_FMMDS( 3294): [50.18.150420][Line:43][xdbDBInit] 
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,I/ActivityManager( 1020): Displayed Component not be shown by security: +1s200ms
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 3119): Timeline: Activity_idle id: android.os.BinderProxy@b1fa91e time:33632
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{39b650a3 u0 com.example.hello/.MainActivity t2} time:33633
W/ActivityManager( 1020): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/libprocessgroup( 1020): failed to open /acct/uid_10131/pid_2473/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2601/cgroup.procs: No such file or directory
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageIntentReceiver( 3316): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3316): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Tethering( 1020): No numeric data
E/Zygote  ( 3344): MountEmulatedStorage()
E/Zygote  ( 3344): v2
I/libpersona( 3344): KNOX_SDCARD checking this for 10099
I/libpersona( 3344): KNOX_SDCARD not a persona
I/SELinux ( 3344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3344): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3344): TimaSignature is unavailable
D/ActivityThread( 3344): Added TimaKeyStore provider
,I/ActivityManager( 1020): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3344 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1020): getStreamVolume 3 index 70
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,I/DBG_FMMDS( 3294): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/sCloudBackupApp( 3274): sCloudBackupApp Version Info : 4.04.7.KK_APP
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1773): getCurrentCandidateView
,I/DBG_FMMDS( 3294): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3294): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,E/Zygote  ( 3369): MountEmulatedStorage()
E/Zygote  ( 3369): v2
I/libpersona( 3369): KNOX_SDCARD checking this for 10058
I/libpersona( 3369): KNOX_SDCARD not a persona
,I/DBG_FMMDS( 3294): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W,
I/DBG_FMMDS( 3294): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/SELinux ( 3369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_FMMDS( 3294): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3294): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/SELinux ( 3369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3369 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2488:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,W/NotificationAccessSettings( 1296): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,D/TimaKeyStoreProvider( 3369): TimaSignature is unavailable,
,D/ActivityThread( 3369): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 2622:flipboard.boxer.app/u0a97 (adj 15): empty #31
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,I/FactoryTestApp( 2507): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2873)  
,I/ActivityManager( 1020): Killing 2636:com.sec.knox.bridge/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/FOTA_Client( 3067): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
W/ResourcesManager( 1296): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/FOTA_Client( 3067): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3067): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3004): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3004): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3004): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2488/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10097/pid_2622/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2636/cgroup.procs: No such file or directory
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/ActivityManager( 1020): Killing 2653:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/FOTA_Client( 3067): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3406 uid=10013 gids={50013, 9997} abi=armeabi-v7a,
E/Zygote  ( 3406): MountEmulatedStorage()
I/libpersona( 3406): KNOX_SDCARD checking this for 10013
E/Zygote  ( 3406): v2
I/libpersona( 3406): KNOX_SDCARD not a persona
,I/SELinux ( 3406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Killing 2197:com.sec.modem.settings/1000 (adj 15): empty #31
,I/SELinux ( 3406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3406): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3406): TimaSignature is unavailable
,D/ActivityThread( 3406): Added TimaKeyStore provider
,I/ExternalOEMControlProvider( 3369): onCreate
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3425 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2693:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
E/Zygote  ( 3425): MountEmulatedStorage()
E/Zygote  ( 3425): v2
I/libpersona( 3425): KNOX_SDCARD checking this for 1000
,I/libpersona( 3425): KNOX_SDCARD not a persona
,I/SELinux ( 3425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/SettingsProvider( 1020): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10058
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,I/SELinux ( 3425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3425): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3425): TimaSignature is unavailable
,D/ActivityThread( 3425): Added TimaKeyStore provider
,V/OneTimeInitializerReceiver( 3406): OneTimeInitializerReceiver.onReceive
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/SettingsProvider( 1020): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10058
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/ResourcesManager( 3425): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/libprocessgroup( 1020): failed to open /acct/uid_10148/pid_2653/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2197/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1101/pid_2693/cgroup.procs: No such file or directory
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,V/OneTimeService( 3406): OneTimeService.onHandleIntent
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,I/ServiceMode( 3425): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3425): setReferenceIsDumpState : 0
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/chromium( 3119): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/AndroidProtocolHandler( 3119): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Zygote  ( 3444): MountEmulatedStorage()
,I/libpersona( 3444): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3444): v2
I/libpersona( 3444): KNOX_SDCARD not a persona
I/SELinux ( 3444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2090:flipboard.app/u0a96 (adj 15): empty #31
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/USB_UICC(  302): Timeout! No signal received. Retry num = 28
,D/TimaKeyStoreProvider( 3444): TimaSignature is unavailable
,D/ActivityThread( 3444): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/MessageQueue( 3004): Handler (android.os.Handler) {2f09ccf9} sending message to a Handler on a dead thread
W/MessageQueue( 3004): java.lang.IllegalStateException: Handler (android.os.Handler) {2f09ccf9} sending message to a Handler on a dead thread
W/MessageQueue( 3004): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 3004): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 3004): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 3004): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 3004): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 3004): 	at ffw.a(SourceFile:327)
W/MessageQueue( 3004): 	at guw.a(SourceFile:120)
W/MessageQueue( 3004): 	at guf.c(SourceFile:26)
W/MessageQueue( 3004): 	at gui.run(SourceFile:297)
W/MessageQueue( 3004): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 3004): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 3004): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 3004): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3467): MountEmulatedStorage()
,E/Zygote  ( 3467): v2
I/libpersona( 3467): KNOX_SDCARD checking this for 1000,
,I/libpersona( 3467): KNOX_SDCARD not a persona
,I/SELinux ( 3467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3467 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/SamsungIME( 1773): Dismiss ExpandCandiate
,I/SELinux ( 3467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3467): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NPS_WSSNPS( 3444): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3444): [] Service onCreate!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_10096/pid_2090/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3467): TimaSignature is unavailable,
,D/ActivityThread( 3467): Added TimaKeyStore provider
,E/Zygote  ( 3482): MountEmulatedStorage()
E/Zygote  ( 3482): v2
I/libpersona( 3482): KNOX_SDCARD checking this for 1000
I/libpersona( 3482): KNOX_SDCARD not a persona
,I/SELinux ( 3482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3482 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3482): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ScoverManager( 1296): serviceVersion : 16908288
,W/ContextImpl( 1830): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/SecUISvc( 1830): Service started flags 0 startId 1
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/SecUISvc( 1830): Thread created.
,D/JsMessageQueue( 3119): Set native->JS mode to OnlineEventsBridgeMode
,D/TimaKeyStoreProvider( 3482): TimaSignature is unavailable
D/ActivityThread( 3482): Added TimaKeyStore provider
,D/NPS_WSSNPS( 3444): [50.150321] NpsServiceTask Start
,E/Zygote  ( 3501): MountEmulatedStorage()
E/Zygote  ( 3501): v2
I/libpersona( 3501): KNOX_SDCARD checking this for 10026
I/libpersona( 3501): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3501 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/art     ( 1640): Explicit concurrent mark sweep GC freed 23437(1532KB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/12MB, paused 1.055ms total 91.300ms
,D/NPS_WSSNPS( 3444): [50.150321] smlDBHelper
,I/SELinux ( 3501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3501): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/art     (  316): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 37.835ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.761ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3467): onCreate
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 16.866ms
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 3501): TimaSignature is unavailable
,D/ActivityThread( 3501): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3444): [50.150321] AsyncBulkFlagCheck
,E/Zygote  ( 3520): MountEmulatedStorage(),
E/Zygote  ( 3520): v2
I/libpersona( 3520): KNOX_SDCARD checking this for 10018
I/libpersona( 3520): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3520 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/RlzPingService( 3088): Setting next ping for 1449065818978
,E/SELinux ( 3520): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/NPS_WSSNPS( 3444): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3444): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3444): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,I/Hs20UtilService( 3467): Starting #1
,I/Hs20UtilService( 3467): Message received 5003
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3444): [50.150321] Service onDestroy
,I/SamsungIME( 1773): getDebugLevel  : 0x4f4c
D/SettingsProvider( 1020): name = access_control_enabled
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3444): [50.150321] smlBRConfigurationDelete
I/NPS_WSSNPS( 3444): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3444): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3444): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3444): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3444): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3444): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3444): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3444): [50.150321] cpuBooster release : false
,D/TimaKeyStoreProvider( 3520): TimaSignature is unavailable
D/ActivityThread( 3520): Added TimaKeyStore provider
,I/chromium( 3119): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3119): 
,E/Zygote  ( 3539): MountEmulatedStorage()
I/libpersona( 3539): KNOX_SDCARD checking this for 10065
E/Zygote  ( 3539): v2
I/libpersona( 3539): KNOX_SDCARD not a persona
,I/SELinux ( 3539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3539 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2216:com.android.mms/u0a41 (adj 15): empty #31
I/SELinux ( 3539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/SELinux ( 3539): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NPS_WSSNPS( 3444): [50.150321] dsServerSocket close
,I/ActivityManager( 1020): Killing 2732:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3539): TimaSignature is unavailable
,D/ActivityThread( 3539): Added TimaKeyStore provider
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/CountryDetector( 1020): No listener is left
,D/jxcore_app_log( 3119): JniHelper::setJavaVM(0xb7e51448), pthread_self() = -1202196536
,D/JX-Cordova( 3119): jxcore cordova android initializing
,D/FileShare-Server( 3539): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/libprocessgroup( 1020): failed to open /acct/uid_10043/pid_2732/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_2216/cgroup.procs: No such file or directory
,I/LockPatternUtils( 1296): isSmartCardAuthenticationAvailable: false
,I/KLMS-2.5.123: ( 3520): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Nov 25 15:16:59 GMT+01:00 2015
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/jxcore-log( 3119): Initializing JXcore engine
W/jxcore-log( 3119): JXcore engine is ready
,I/KLMS-2.5.123: ( 3520): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 3119): Starting JXcore engine
,I/KLMS-2.5.123: ( 3520): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3520): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3520): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3520): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 3559): MountEmulatedStorage()
E/Zygote  ( 3559): v2
I/libpersona( 3559): KNOX_SDCARD checking this for 10020
I/libpersona( 3559): KNOX_SDCARD not a persona
,I/SELinux ( 3559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3559 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3520): KLMSIntentService(): BOOT_COMPLETED,
,I/SELinux ( 3559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3559): TimaSignature is unavailable
,D/ActivityThread( 3559): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3520): KLMSIntentService(): onDestroy(),
,D/Settings_Utils( 1296): isSupportVNFestival SM-A300FU XEO
,E/audit   ( 1772): type=1400 msg=audit(1448461019.243:203): avc:  denied  { ioctl } for  pid=3119 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1772):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1772): type=1300 msg=audit(1448461019.243:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=be8e6d58 items=0 ppid=316 ppcomm=main pid=3119 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1772): type=1320 msg=audit(1448461019.243:203): 
,I/ActivityManager( 1020): Killing 2750:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,W/ResourceType( 1296): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,W/ResourceType( 1296): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/SamsungIME( 1773): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1773): KeybaordView init() : load resources
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3581): MountEmulatedStorage()
E/Zygote  ( 3581): v2
I/libpersona( 3581): KNOX_SDCARD checking this for 1000
I/libpersona( 3581): KNOX_SDCARD not a persona
,I/SELinux ( 3581): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3581): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3581 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 3119): Platform android
W/jxcore-log( 3119): 
,W/jxcore-log( 3119): Process ARCH arm
W/jxcore-log( 3119): 
I/ActivityManager( 1020): Killing 2672:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10153/pid_2750/cgroup.procs: No such file or directory
,E/SELinux ( 3581): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 3581): TimaSignature is unavailable
,D/ActivityThread( 3581): Added TimaKeyStore provider
,I/SamsungIME( 1773): getCurrentKeyboard
I/SamsungIME( 1773): getTextKeyboard
,I/jxcore-log( 3119): JXcore Cordova bridge is ready!
I/jxcore-log( 3119): 
,W/jxcore-log( 3119): JXcore engine is started
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/GAV2    ( 3344): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 3344): getAccountsCursor
,E/MTPRx   ( 3581): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1020): mCursor = null
,V/MTPRx   ( 3581): sealedState: false
V/MTPRx   ( 3581): sealedUsbMassStorageState: false
,D/SettingsProvider( 1020): name = mtp_usb_connection_status
,D/SamsungIME( 1773): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SettingsProvider( 1020): name = media_player_mode
,W/libprocessgroup( 1020): failed to open /acct/uid_10081/pid_2672/cgroup.procs: No such file or directory
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,D/SettingsProvider( 1020): name = mtp_running_status
,E/jxcore-log( 3119): >> samsung-SM-A300FU
E/jxcore-log( 3119): 
,I/jxcore-log( 3119): Total memory 1451114496
I/jxcore-log( 3119): 
,I/jxcore-log( 3119): Free memory 26910720
I/jxcore-log( 3119): 
I/jxcore-log( 3119): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3119): 
I/jxcore-log( 3119): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3119): 
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = media_mount_count
I/jxcore-log( 3119): userPath [ 'www' ]
I/jxcore-log( 3119): 
,I/jxcore-log( 3119): Size 540 960
I/jxcore-log( 3119): 
,I/jxcore-log( 3119): Screen Brightness 255
I/jxcore-log( 3119): 
,E/jxcore-log( 3119): Dummy Error Log.
E/jxcore-log( 3119): 
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = mtp_sync_alive
,D/SettingsProvider( 1020): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = mtp_open_session
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 19755(1040KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 5.230ms total 199.882ms,
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/ActivityManager( 1020): Killing 2781:com.sec.usbsettings/1000 (adj 15): empty #31
,E/USB_UICC(  302): Timeout! No signal received. Retry num = 29
,I/ActivityManager( 1020): Killing 2834:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1020): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PCWCLIENTTRACE_PushUtil( 3189): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3189): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3189): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3189): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3189): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3189): ACTION_BOOTUP - Push type: [SPP, GCM]
,E/Zygote  ( 3609): MountEmulatedStorage()
,E/Zygote  ( 3609): v2
I/libpersona( 3609): KNOX_SDCARD checking this for 1000
I/libpersona( 3609): KNOX_SDCARD not a persona
,I/SELinux ( 3609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3609 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/Gmail   ( 3344): Observing account changes for notifications
,E/SELinux ( 3609): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/PCWCLIENTTRACE_PCWHandler( 3189): [ensureRegistration] - netwrok is not available. action ignored
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3622): MountEmulatedStorage()
E/Zygote  ( 3622): v2
I/libpersona( 3622): KNOX_SDCARD checking this for 10028
I/libpersona( 3622): KNOX_SDCARD not a persona
,I/SELinux ( 3622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3622): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3622 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3609): TimaSignature is unavailable
,D/ActivityThread( 3609): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3622): TimaSignature is unavailable
,D/ActivityThread( 3622): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2834/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2781/cgroup.procs: No such file or directory
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ContextImpl( 3609): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/Finsky  ( 3501): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3644): MountEmulatedStorage()
,I/libpersona( 3644): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3644): v2
I/libpersona( 3644): KNOX_SDCARD not a persona
I/SELinux ( 3644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3644 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3644): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3644): TimaSignature is unavailable
,E/Gmail   ( 3344): Error finding the version of the Email provider.....
E/Gmail   ( 3344): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3344): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3344): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3344): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3344): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3344): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3344): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3344): We do not support migrating this version of the Email provider.
D/ActivityThread( 3644): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/LockPatternUtils( 1296): isSmartCardAuthenticationAvailable: false
,I/Gmail   ( 3344): getAccountsCursor
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
V/AlarmManager( 1020): waitForAlarm result :8
,W/ResourcesManager( 3644): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3668): MountEmulatedStorage(),
,E/Zygote  ( 3668): v2
I/libpersona( 3668): KNOX_SDCARD checking this for 1000
I/libpersona( 3668): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3668 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3344): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@29a01132 that was originally bound here
E/ActivityThread( 3344): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@29a01132 that was originally bound here
E/ActivityThread( 3344): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3344): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3344): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3344): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3344): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3344): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3344): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3344): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3344): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3344): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3344): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3344): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3344): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3344): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3344): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1020): Unbind failed: could not find connection for android.os.BinderProxy@382f0f5e
,I/F_PHONE ( 3644): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/SELinux ( 3668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
E/SELinux ( 3668): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,E/Zygote  ( 3684): MountEmulatedStorage()
,E/Zygote  ( 3684): v2
I/libpersona( 3684): KNOX_SDCARD checking this for 10102
I/libpersona( 3684): KNOX_SDCARD not a persona
,I/SELinux ( 3684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3684 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux ( 3684): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/F_PHONE ( 3644): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3644): default registerAction()
I/F_PHONE ( 3644): [[com.sec.bcservice]] sendPendingMessage()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 3668): TimaSignature is unavailable
,D/ActivityThread( 3668): Added TimaKeyStore provider
I/System.out( 3622): Inside onCreate() of WakeupTriggerProvide
I/System.out( 3622): Inside WakeupProvider
,I/GoogleHttpClient( 1605): GMS http client unavailable, use old client
,W/art     ( 1296): Suspending all threads took: 47.446ms
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 3684): TimaSignature is unavailable
,D/ActivityThread( 3684): Added TimaKeyStore provider
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/jxcore-log( 3119): getBuffer is called!!!!
I/jxcore-log( 3119): 
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,E/SQLiteLog( 3344): (283) recovered 21 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ResourcesManager( 3668): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/accuweather( 1688): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
D/accuweather( 1688): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1688): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,D/accuweather( 1688): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1688): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,E/accuweather( 1688): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 17
,W/ResourcesManager( 3684): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BluetoothBDAdrressReceiver( 3668): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/ResourcesManager( 1449): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1449): onCreate()
,E/BluetoothBDTestService( 1449): onStart(), extra_type: BOOT_COMPLETED
,E/BluetoothBDTestService( 1449): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1449): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4293, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/PowerUI ( 1180): Cable  true --> true mBootCompleted : true
V/EmergencyMode( 1401): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1401): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1180): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/FactoryTestApp( 2507): [DummyFtClient$onDestroy](2507) Destroy DummyFtClient service
,D/FactoryTestApp( 2507): [Support$Values.getString](2507) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2507): [ModuleCommon$isConnectionModeNone](2507) mConnectionMode = gsm
I/FactoryTestApp( 2507): [ModuleCommon$isRunningFtClient](2507) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2507): [DummyFtClient$onDestroy](2507) kill process
I/Process ( 2507): Sending signal. PID: 2507 SIG: 9
,I/VlingoApplication( 3622): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Process com.sec.factory (pid 2507)(adj 0) has died(22,683)
,D/BluetoothAdapter( 3622): 186624286: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3622): 186624286: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3622): 186624286: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3622): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,D/Finsky  ( 3501): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3609): Resource data:2131165186
,W/ResourcesManager( 3609): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3609): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,W/Settings( 3501): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/AMMetaDataParserService( 3609): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,W/Settings( 3501): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/AMMetaDataParserService( 3609): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,E/USB_UICC(  302): Timeout! No signal received. Retry num = 30
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCr,eateAccountActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/ContextImpl( 3609): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/VlingoApplication( 3622): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3622): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/Volley  ( 3501): [506] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3501): [513] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3501): Skipping gmscore version check
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131034113
,W/ResourcesManager( 3609): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3609): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3609): took 2.565938ms for 0*0 texture 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  302): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  302): usb_uicc_init_qmi failed ! 
I/USB_UICC(  302): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  302): usb_uicc_cleanup, Issuing QMI deinit ... 
I/GFX generate_partition_tables( 3609): took 6.129219ms for 0*0 texture 0
I/GFX raster( 3609): took 9.958750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb821ecc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb821ea10 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 3501): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3501): [1] Libraries$2.run: Finished loading 1 libraries.
,D/DialogFlow( 3622): initQueue()
,I/AMMetaDataParserService( 3609): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/Babel   ( 3684): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3684): MmsConfig.loadMmsSettings
,I/GFX raster( 3609): took 0.834062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb821ecc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb822c968 counterpartCT=4 counterpartW=96 counterparth=96
,I/Babel   ( 3684): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3684): MmsConfig.loadFromDatabase
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/art     ( 3684): Suspending all threads took: 33.235ms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3748): MountEmulatedStorage()
I/libpersona( 3748): KNOX_SDCARD checking this for 10029
E/Zygote  ( 3748): v2
I/libpersona( 3748): KNOX_SDCARD not a persona
,I/SELinux ( 3748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Finsky  ( 3501): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3748 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 3748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3748): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/Icing   ( 1801): Storage manager: low false usage 2.07MB avail 8.51GB capacity 9.90GB
,E/Babel   ( 3684): canonicalizeMccMnc: invalid mccmnc 
D/TimaKeyStoreProvider( 3748): TimaSignature is unavailable
,I/Babel   ( 3684): MmsConfig.loadFromResources
,D/ActivityThread( 3748): Added TimaKeyStore provider
,E/Babel   ( 3684): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3684): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/Settings( 3684): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/VideoCapabilities( 3684): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3684): Unsupported mime audio/evrc
,W/AudioCapabilities( 3684): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3684): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3684): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3684): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3684): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3684): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3684): Unsupported mime audio/evrc
,W/VideoCapabilities( 3684): Unsupported mime video/wvc1
,W/VideoCapabilities( 3684): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3684): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3684): Unsupported mime video/wvc1
,W/VideoCapabilities( 3684): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3684): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3684): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3684): Unsupported mime video/mp43
,W/VideoCapabilities( 3684): Unsupported mime video/sorenson
,W/VideoCapabilities( 3684): Unsupported mime video/mp4v-esdp
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,I/VideoCapabilities( 3684): Unsupported profile 4 for video/mp4v-es
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3770): MountEmulatedStorage()
E/Zygote  ( 3770): v2
I/libpersona( 3770): KNOX_SDCARD checking this for 10030
I/libpersona( 3770): KNOX_SDCARD not a persona
,I/SELinux ( 3770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3770 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3770): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3770): TimaSignature is unavailable
,D/ActivityThread( 3770): Added TimaKeyStore provider
,I/art     (  316): Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 697us total 27.522ms
,V/Babel   ( 3684): babel boot account: SMS
V/Babel   ( 3684): babel boot account: thalitester@gmail.com
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 19.769ms
,D/Finsky  ( 3501): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/File    ( 3344): fail readDirectory() errno=2
,D/PackageManager( 1020): [MSG] MCS_UNBIND
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 648us total 18.697ms
,I/Gmail   ( 3344): notifyAccountChanged
,I/Gmail   ( 3344): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/Zygote  ( 3789): MountEmulatedStorage(),
E/Zygote  ( 3789): v2
I/libpersona( 3789): KNOX_SDCARD checking this for 1000
I/libpersona( 3789): KNOX_SDCARD not a persona,
I/SELinux ( 3789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/Gmail   ( 3344): getAccountsCursor,
I/SELinux ( 3789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3789 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3789): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 1559:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,V/AlarmManager( 1020): waitForAlarm result :4
,I/Gmail   ( 3344): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager( 1020): Killing 2799:com.sec.dsm.system/1000 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 2882:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,D/TimaKeyStoreProvider( 3789): TimaSignature is unavailable
I/ActivityManager( 1020): Killing 2856:com.google.android.configupdater/u0a82 (adj 15): empty #31
W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,D/ActivityThread( 3789): Added TimaKeyStore provider
,I/SettingSearch/SearchIntentReceiver( 1296): InitSerachDBThread thread end!
,I/Gmail   ( 3344): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3344): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/art     ( 1605): Explicit concurrent mark sweep GC freed 10140(713KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 7MB/12MB, paused 1.012ms total 80.287ms
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1020): Killing 2913:com.dropbox.android/u0a88 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2799/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10068/pid_1559/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2882/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10082/pid_2856/cgroup.procs: No such file or directory
,E/Zygote  ( 3810): MountEmulatedStorage()
E/Zygote  ( 3810): v2
I/libpersona( 3810): KNOX_SDCARD checking this for 1000
I/libpersona( 3810): KNOX_SDCARD not a persona
,I/SELinux ( 3810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3810 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2928:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 3810): TimaSignature is unavailable
,D/ActivityThread( 3810): Added TimaKeyStore provider
,I/GFX construct_block_size_descriptor_2d second part( 3609): took 5.490361ms for 0*0 texture 0
,W/ResourcesManager( 3770): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3770): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3770): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/GFX generate_partition_tables( 3609): took 8.990103ms for 0*0 texture 0
,I/GFX raster( 3609): took 16.415986ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb822c598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb822c6f0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1020): failed to open /acct/uid_10088/pid_2913/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10146/pid_2928/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3609): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531,
,W/ResourcesManager( 3770): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3770): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/Gmail   ( 3344): getAccountsCursor
,I/GFX raster( 3609): took 0.995261ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb83dabd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83db338 counterpartCT=4 counterpartW=96 counterparth=96
E/KnoxSetupWizardClient( 3810): isShipMode : 1
,I/KnoxSetupWizardClient( 3810): onReceive : android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3770): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3770): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3609): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.829948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb81ebb28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f60cd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3609): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.624896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb820d088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,D/ShortcutReceiver( 3810):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3609): took 0.715573ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb820c508 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f60cd0 counterpartCT=4 counterpartW=96 counterparth=96
D/KnoxShortcutUtil( 3810): getIsShortcutMigrationFor_2_3_0_Done true
D/ShortcutReceiver( 3810):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 3810):  shortcut migration not required 
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3830): MountEmulatedStorage()
E/Zygote  ( 3830): v2
I/libpersona( 3830): KNOX_SDCARD checking this for 1000
I/libpersona( 3830): KNOX_SDCARD not a persona
I/SELinux ( 3830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3830 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/ActivityManager( 1020): Killing 2958:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/GFX raster( 3609): took 0.522396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7f98e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,W/System.err( 3810): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3810): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3810): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3810): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3810): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3810): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3810): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/AMMetaDataParserService( 3609): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/FileApkUtils( 1801): Spent 52ms computing apk sha1.
,D/FileApkUtils( 1801): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1801): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/TimaKeyStoreProvider( 3830): TimaSignature is unavailable
,D/ActivityThread( 3830): Added TimaKeyStore provider
,D/DexOptUtils( 1801): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1801): Keeping up-to-date module: module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad
,E/SMD     (  289): DCD OFF
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131034113
,I/AMMetaDataParserService( 3609): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.815417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7f60cd0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3609): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/GmsModuleFndr( 1801): Beginning GMS chimera module scan
,D/StatusChecker( 3830): onReceive : android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GmsModuleFndr( 1801): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 1801): Beginning module configuration check
,D/ChimeraCfgMgr( 1801): Module APKs unchanged, check complete
,I/StatusChecker( 3830): onReceive : net.mt.init : DONE
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 1.195938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7f60cd0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2958/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3609): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/Zygote  ( 3850): MountEmulatedStorage(),
E/Zygote  ( 3850): v2
I/libpersona( 3850): KNOX_SDCARD checking this for 10113
I/libpersona( 3850): KNOX_SDCARD not a persona
,I/SELinux ( 3850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3850): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1020): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3850 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2978:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GFX raster( 3609): took 0.739062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb822c598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3850): TimaSignature is unavailable
,D/ActivityThread( 3850): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3609): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/PageBuddyNotiSvc( 3850): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3850): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 3850): onCreate mCpBitFlag=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.610209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb83dabd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3609): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/Zygote  ( 3881): MountEmulatedStorage()
I/libpersona( 3881): KNOX_SDCARD checking this for 10121
E/Zygote  ( 3881): v2
I/libpersona( 3881): KNOX_SDCARD not a persona
,I/SELinux ( 3881): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3881): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3881): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.867135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb81ebb28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3609): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/ActivityManager( 1020): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3881 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1020): failed to open /acct/uid_10088/pid_2978/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3881): TimaSignature is unavailable
,D/ActivityThread( 3881): Added TimaKeyStore provider
,D/GCM     ( 1801): COMPAT: Multi user not supported
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 1801): Checkin interval check for package: unspecified last checkin: 1448443211930 min interval config: 0 actual interval: 17810027
,D/GCM     ( 1605): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.669947ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb820d088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.929167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb820c508 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ResourcesManager( 3881): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GCoreUlr( 1801): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/ResourcesManager( 3881): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3881): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1640): DispatchingService.onCreate()
,I/Process ( 3770): Sending signal. PID: 3770 SIG: 9
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 1801): Disabling old GoogleServicesFramework version
,D/QuickConnect( 3881): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1020): name = scon_is_running
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed,
,D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10121
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 3881): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 3881): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1801): onCreate
,I/QuickConnect( 3881): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,E/Zygote  ( 3905): MountEmulatedStorage(),
I/libpersona( 3905): KNOX_SDCARD checking this for 10127
E/Zygote  ( 3905): v2,
I/libpersona( 3905): KNOX_SDCARD not a persona
I/SELinux ( 3905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/System.out( 3622): INFO:Resource not found:/Common.properties Using default values
E/SELinux ( 3905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3905 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3022:com.policydm/1000 (adj 15): empty #31
,I/ActivityManager( 1020): Process com.sec.android.app.sns3 (pid 3770)(adj 0) has died(32,687)
,D/SystemUpdateService( 1801): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/AuthZen ( 1801): Handling intent: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3905): TimaSignature is unavailable
,D/ActivityThread( 3905): Added TimaKeyStore provider
,D/AuthZenEventHandler( 1801): Handling event: android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 3924): MountEmulatedStorage(),
E/Zygote  ( 3924): v2
I/libpersona( 3924): KNOX_SDCARD checking this for 10031
I/libpersona( 3924): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3924 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,I/SELinux ( 3924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SELinux ( 3924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/GFX raster( 3609): took 0.576459ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7f98e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 3924): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3609): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3609): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3609): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131034112
,D/TimaKeyStoreProvider( 3924): TimaSignature is unavailable
,D/ActivityThread( 3924): Added TimaKeyStore provider
,W/ResourcesManager( 3748): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3609): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.611615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb83dabd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3022/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3609): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/CheckinService( 1801): Checking schedule, now: 1448461022294 next: 1449010138595
I/CheckinService( 1801): active receiver: disabled
,I/GFX raster( 3609): took 0.671301ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb83dabd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e59b88 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3609): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,W/BaseAppContext( 1801): Using Auth Proxy for data requests.
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.642552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7e59b88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb821edd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3609): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.639115ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb820d088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82042a0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3748): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3748): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3748): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/SystemUpdateService( 1801): cancelUpdate (empty URL)
,I/SystemUpdateService( 1801): active receiver: disabled
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 34254(1988KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 2.866ms total 183.481ms
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131034113
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
I/GAV2    ( 3037): Thread[GAThread,5,main]: No campaign data found.
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 7.493335ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7f60cd0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb822bf48 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3905): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3905): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3905): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3905): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3609): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.853228ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7f60cd0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81f0e00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3609): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/art     ( 3622): Suspending all threads took: 18.179ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.605885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7f98e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb820d088 counterpartCT=4 counterpartW=96 counterparth=96
,I/AuthZen ( 1801): Fetching signing key...
,I/AMMetaDataParserService( 3609): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/SBrowserFeatureFlag( 3905): initialized in static block : loadCscFeatureValue() succeed! 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/ManifestProvider( 3905): onCreate()
,E/Zygote  ( 3957): MountEmulatedStorage()
E/Zygote  ( 3957): v2
I/libpersona( 3957): KNOX_SDCARD checking this for 1000
I/libpersona( 3957): KNOX_SDCARD not a persona
,I/SELinux ( 3957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3957 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Killing 3147:com.fmm.dm/1000 (adj 15): empty #31
,E/SELinux ( 3957): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.596458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb8217570 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81ebb28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AuthZen ( 1801): Signing key fetched successfully!
,W/BaseAppContext( 1801): Using Auth Proxy for data requests.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 3957): TimaSignature is unavailable
,D/ActivityThread( 3957): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,I/GCoreUlr( 1640): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1801): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/art     ( 1801): Background sticky concurrent mark sweep GC freed 10298(940KB) AllocSpace objects, 14(224KB) LOS objects, 15% free, 7MB/9MB, paused 13.049ms total 83.343ms
,E/NetworkSettingsReceiver( 3905): onReceive: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3609): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3147/cgroup.procs: No such file or directory
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.833698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb7e59b88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81f0e00 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/a       ( 1801): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 1801): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1801): Clearing transaction cache
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/System.err( 3905): java.lang.NoSuchMethodException: isEnabled []
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/System.err( 3905): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 3905): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 3905): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 3905): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 3905): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 3905): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 3905): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 3905): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 3905): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 3905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 3905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3905): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3905): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 3905): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3905): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 3905): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@f94f188
,D/SBrowserFeatureFlag( 3905): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3905): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3957): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3957): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3957): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3957): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 3957): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,E/Zygote  ( 3985): MountEmulatedStorage()
I/libpersona( 3985): KNOX_SDCARD checking this for 10131
E/Zygote  ( 3985): v2
I/libpersona( 3985): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3985 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3156:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,I/SELinux ( 3985): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3985): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/SELinux ( 3985): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3609): took 0.660312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb83dabd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb820d088 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 1801): onDestroy
I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/DBG_POLICYDM( 3957): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ChimeraCfgMgr( 1801): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/DBG_POLICYDM( 3957): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,D/TimaKeyStoreProvider( 3985): TimaSignature is unavailable
,I/DBG_POLICYDM( 3957): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,D/ActivityThread( 3985): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3957): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3957): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3957): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 3957): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3957): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3957): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3957): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.685885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb81ebb28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81f0e00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_POLICYDM( 3957): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 3957): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 3957): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3609): took 0.531198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb820d088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81f0e00 counterpartCT=4 counterpartW=96 counterparth=96
,W/GCoreFlp( 1640): No location to return for getLastLocation()
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/FusedLocationProvider( 1801): location=null
,I/AMMetaDataParserService( 3609): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
W/ContextImpl( 3609): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
W/libprocessgroup( 1020): failed to open /acct/uid_10090/pid_3156/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,E/Zygote  ( 4004): MountEmulatedStorage()
,I/libpersona( 4004): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4004): v2
I/libpersona( 4004): KNOX_SDCARD not a persona
I/SELinux ( 4004): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ResourcesManager( 3985): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3985): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3985): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SELinux ( 4004): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4004): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4004 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1020): Killing 3201:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,W/Kids    ( 1801): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 1801): [KidAccountFixer] No network connection
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Auth    ( 1605): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/DBG_POLICYDM( 3957): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3957): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity,
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts,
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions,
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings,
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange,
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
W/ResourcesManager( 3609): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
W/ResourcesManager( 3609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
W/ResourcesManager( 3609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering,
W/ResourcesManager( 3609): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131165203
I/DBG_POLICYDM( 3957): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3609): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
W/GCoreFlp( 1640): No location to return for getLastLocation()
,W/FusedLocationProvider( 1801): location=null
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,E/DBG_POLICYDM( 3957): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/TimaKeyStoreProvider( 4004): TimaSignature is unavailable
D/ActivityThread( 4004): Added TimaKeyStore provider
,I/GFX construct_block_size_descriptor_2d second part( 3609): took 3.635469ms for 0*0 texture 0
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,V/GmsCoreStatsServiceLauncher( 1801): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3609): took 17.355053ms for 0*0 texture 0
I/GFX raster( 3609): took 21.605106ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb83d5800 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb83d64c0 counterpartCT=4 counterpartW=80 counterparth=80
,D/daemonapp( 1726): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup( 1020): failed to open /acct/uid_10055/pid_3201/cgroup.procs: No such file or directory
,I/Icing   ( 1801): updateResources: need to parse f{com.google.android.gms}
,D/PersistentNotificationBroadcastReceiver( 1605): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3609): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,E/Zygote  ( 4030): MountEmulatedStorage(),
I/libpersona( 4030): KNOX_SDCARD checking this for 10037
E/Zygote  ( 4030): v2
I/libpersona( 4030): KNOX_SDCARD not a persona
I/SELinux ( 4030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4030): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/GFX construct_block_size_descriptor_2d second part( 3609): took 2.974743ms for 0*0 texture 0
I/ActivityManager( 1020): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4030 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/GFX generate_partition_tables( 3609): took 5.672813ms for 0*0 texture 0
I/GFX raster( 3609): took 9.805057ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb81fda50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb81fdaf8 counterpartCT=4 counterpartW=80 counterparth=80
,I/art     (  316): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 637us total 23.069ms
,I/AMMetaDataParserService( 3609): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 17.014ms
,D/TimaKeyStoreProvider( 4030): TimaSignature is unavailable
,D/ActivityThread( 4030): Added TimaKeyStore provider
,E/SPPClientService( 4004): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4004): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 4004): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.643ms
,E/Zygote  ( 4048): MountEmulatedStorage()
,E/Zygote  ( 4048): v2
I/libpersona( 4048): KNOX_SDCARD checking this for 10135
I/libpersona( 4048): KNOX_SDCARD not a persona
,I/SELinux ( 4048): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4048 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
D/SPPClientService( 4004): PushLog.txt file is not deleted.
D/SPPClientService( 4004): PushLog.txt file is not deleted.
D/SPPClientService( 4004): ============PushLog. stop!
,I/SELinux ( 4048): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4048): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
W/ResourcesManager( 4030): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4048): TimaSignature is unavailable
,D/ActivityThread( 4048): Added TimaKeyStore provider
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3609): took 0.807344ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb81fda50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb81fbfd0 counterpartCT=4 counterpartW=80 counterparth=80
,E/Zygote  ( 4063): MountEmulatedStorage()
,E/Zygote  ( 4063): v2
I/libpersona( 4063): KNOX_SDCARD checking this for 10036
I/libpersona( 4063): KNOX_SDCARD not a persona
,I/SELinux ( 4063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AMMetaDataParserService( 3609): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/SELinux ( 4063): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4063 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 3231:com.sec.factory.camera/1000 (adj 15): empty #31
,I/art     ( 1605): Explicit concurrent mark sweep GC freed 7710(457KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 7MB/13MB, paused 1.015ms total 45.166ms
,D/TimaKeyStoreProvider( 4063): TimaSignature is unavailable
,D/ActivityThread( 4063): Added TimaKeyStore provider
,W/ResourcesManager( 4048): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4048): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4048): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4048): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4048): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SQLiteLog( 1605): (10) POSIX Error : 11 SQLite Error : 3850
,I/CalendarProvider2( 4030): CalendarProvider2.onCreate() called
,I/ActivityManager( 1020): Killing 3255:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3609): took 0.703333ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb81fda50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb83d5b60 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3609): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3231/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4063): [SSP] onCreated,
,E/Zygote  ( 4080): MountEmulatedStorage(),
E/Zygote  ( 4080): v2
I/libpersona( 4080): KNOX_SDCARD checking this for 10141
I/SELinux ( 4080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/libpersona( 4080): KNOX_SDCARD not a persona
,I/SELinux ( 4080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4080 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/GCoreUlr( 1640): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1640): Unbound from all location providers
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3609): took 0.646302ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb8722fa0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb87231b0 counterpartCT=4 counterpartW=80 counterparth=80
,D/TimaKeyStoreProvider( 4080): TimaSignature is unavailable
,D/ActivityThread( 4080): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3609): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,W/ResourcesManager( 4080): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4080): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4080): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/GCoreUlr( 1640): DispatchingService.onDestroy()
I/GCoreUlr( 1640): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1640): Unbound from all location providers
,W/libprocessgroup( 1020): failed to open /acct/uid_10095/pid_3255/cgroup.procs: No such file or directory
,I/SA      ( 4063): [TPM] There is no property file
,I/SA      ( 4063): [SCU] isHaveSA() - false
,I/SA      ( 4063): [TPM] getModelProperty : null
,I/SA      ( 4063): [TPM] getCSCProperty : null
,I/SA      ( 4063): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 4063): [DM] PRODUCT AMOLED FEATURE: false
,I/SA      ( 4063): [DM] TFT FEATURE: false
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/SA      ( 4063): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4063): [DM] init START
,I/SA      ( 4063): [DM] This device is not a Vodafone
,W/ResourceType( 4063): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4063): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4063): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75),
,W/ResourceType( 4063): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4063): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4063): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/SA      ( 4063): [SCU] isHaveSA() - false
I/SA      ( 4063): support phone number id : false
I/SA      ( 4063): [DM] Supports Ref Jpn : true
,I/SA      ( 4063): [DM] init END
,I/SA      ( 4063): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4063): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4063): [OR] onReceive END
,I/SA      ( 4063): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4063): [ODM] queryOpenData(key= GEO_IP )
,I/SA      ( 4063): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4063): [LBE] REF_JPN : true
I/SA      ( 4063): [BDC] create
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/SA      ( 4063): [DBMV2] getEmailID
,I/SA      ( 4063): [DBMV2] getDataV02ForItems
I/SA      ( 4063): [SSP] query invoked
,I/SA      ( 4063): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4063): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4063): [BDC] destroy
,I/ActivityManager( 1020): Killing 3274:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,E/        ( 3609): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3609): took 0.867552ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3609): Bitmap=0xb8722fa0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb87244c0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3609): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/PowerManagerService( 1020): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1180 (0x0)
,I/Icing   ( 1801): Internal init done: storage state 0
,I/Icing   ( 1801): Post-init done
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.spellscroll
W/ContextImpl( 3609): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4110): MountEmulatedStorage()
,E/Zygote  ( 4110): v2
I/libpersona( 4110): KNOX_SDCARD checking this for 10068
I/libpersona( 4110): KNOX_SDCARD not a persona
,I/SELinux ( 4110): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4110 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,W/libprocessgroup( 1020): failed to open /acct/uid_10056/pid_3274/cgroup.procs: No such file or directory
,I/SELinux ( 4110): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4110): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/SSRM:n  ( 1020): SIOP:: AP = 430
,D/TimaKeyStoreProvider( 4110): TimaSignature is unavailable
,D/ActivityThread( 4110): Added TimaKeyStore provider
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131099648
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager( 3609): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 3609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3609): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/BadgeProvider( 4110): onCreate
D/BadgeProvider( 4110): DatabaseHelper
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4133): MountEmulatedStorage()
,E/Zygote  ( 4133): v2
I/libpersona( 4133): KNOX_SDCARD checking this for 10142
I/libpersona( 4133): KNOX_SDCARD not a persona
,I/SELinux ( 4133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4133 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
I/SELinux ( 4133): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4133): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 3316:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 3294:com.fmm.ds/1000 (adj 15): empty #32
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/TimaKeyStoreProvider( 4133): TimaSignature is unavailable
,D/ActivityThread( 4133): Added TimaKeyStore provider
,D/BadgeProvider( 4110): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,W/ResourcesManager( 4133): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3609): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/libprocessgroup( 1020): failed to open /acct/uid_10098/pid_3316/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3294/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3609): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3609): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4151): MountEmulatedStorage(),
E/Zygote  ( 4151): v2
,I/libpersona( 4151): KNOX_SDCARD checking this for 1000
I/libpersona( 4151): KNOX_SDCARD not a persona
,I/SELinux ( 4151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4151 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3609): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/ActivityManager( 1020): Killing 3369:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131099648
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 24848(1417KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 22MB/33MB, paused 2.872ms total 163.387ms
,I/AMMetaDataParserService( 3609): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,D/Launcher.Model( 1480): reloadBadges entered.
,D/BadgeProvider( 4110): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4110): sendNotify, [notify] : null
D/BadgeProvider( 4110): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4110): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4110): update, [UpdateCount] : 1
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4151): TimaSignature is unavailable
,D/ActivityThread( 4151): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3609): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3609): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1020): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,I/Process ( 4133): Sending signal. PID: 4133 SIG: 9
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/AMMetaDataParserService( 3609): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 1020): Killing 3067:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1020): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/Process ( 4080): Sending signal. PID: 4080 SIG: 9
,I/AMMetaDataParserService( 3609): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131099648
,I/AMMetaDataParserService( 3609): getResourceName:com.android.mms:xml/assistant_messaging
,I/splitIntent( 1020): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
I/ActivityManager( 1020): Killing 3406:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
E/lowmemorykiller(  255): Error writing /proc/4080/oom_score_adj; errno=22
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3609): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3609): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3609): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/AMMetaDataParserService( 3609): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/ActivityManager( 1020): Process com.android.exchange (pid 4133)(adj 9) has died(47,651)
,E/lowmemorykiller(  255): Error writing /proc/4080/oom_score_adj; errno=22
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3609): Resource data:2131099648
,I/AMMetaDataParserService( 3609): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1020): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Process com.android.email (pid 4080)(adj 9) has died(48,651)
,I/AMMetaDataParserService( 3609): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SIP     ( 1449): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1449): fail readDirectory() errno=2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_10058/pid_3369/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1640): callingUid 10011, callindPid: 1640
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,I/GAV2    ( 3344): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1640): [172] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131099648
,I/AMMetaDataParserService( 3609): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/LocationInitializer( 1801): Restart initialization of location
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3609): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/GCM     ( 1605): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1605): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3609): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131099648
,I/AMMetaDataParserService( 3609): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,V/GmsCoreStatsServiceLauncher( 1801): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1640): No location to return for getLastLocation()
,W/FusedLocationProvider( 1605): location=null
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3609): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3609): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3609): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/BluetoothAdapter( 3119): disable()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/BluetoothManagerService( 1020): Bluetooth is already disabled. DO NOT disable again.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1020): mCursor = null
,I/AMMetaDataParserService( 3609): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/WifiService( 1020): setWifiEnabled: false pid=3119, uid=10333
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SettingsProvider( 1020): name = wifi_on
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
W/ContextImpl( 3609): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3609): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector,
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/jxcore-log( 3119): ****TEST TOOK:  5061  ms ****
I/jxcore-log( 3119): 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/jxcore-log( 3119): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3119): 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131165197
,W/ResourcesManager( 3609): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3609): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3609): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/AlarmManager( 1020): waitForAlarm result :8,
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.widget.MmsWidgetProvider: pid=4183 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/Zygote  ( 4183): MountEmulatedStorage(),
I/libpersona( 4183): KNOX_SDCARD checking this for 10041
E/Zygote  ( 4183): v2,
I/libpersona( 4183): KNOX_SDCARD not a persona
I/SELinux ( 4183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3609): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
E/SMD     (  289): DCD OFF
,I/SELinux ( 4183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4183): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3609): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/libprocessgroup( 1020): failed to open /acct/uid_10008/pid_3067/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10013/pid_3406/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3609): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131165197
,I/AMMetaDataParserService( 3609): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4183): TimaSignature is unavailable
,D/ActivityThread( 4183): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3609): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ResourcesManager( 4183): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4183): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4183): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4183): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4183): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3609): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/ValidateNoPeople( 1020): mEvictionCount: 0
,I/AMMetaDataParserService( 3609): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/AndroidRuntime( 4191): 
D/AndroidRuntime( 4191): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4191): CheckJNI is OFF
,D/AndroidRuntime( 4191): readGMSProperty: start
D/AndroidRuntime( 4191): readGMSProperty: already setted!!
D/AndroidRuntime( 4191): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4191): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4191): readGMSProperty: end
,D/AndroidRuntime( 4191): addProductProperty: start
D/Mms/MmsApp( 4183): [start]    onCreate() consume time = 0.0
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.cooliris.media.Gallery,
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131165197
,I/AMMetaDataParserService( 3609): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,I/AMMetaDataParserService( 3609): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625,
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{25bb9a63 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService},
,I/AMMetaDataParserService( 3609): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623,
,I/CalendarProvider2( 4030): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,V/AlarmManager( 1020): waitForAlarm result :4
,I/AMMetaDataParserService( 3609): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/iu.UploadsManager( 1801): End new media; added: 0, uploading: 0, time: 47 ms
,I/AMMetaDataParserService( 3609): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3609): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,W/art     ( 4183): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 128.527ms
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131099648
,W/ResourcesManager( 3609): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3609): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,E/AffinityControl( 4191): AffinityControl: registerfunction enter
,I/AMMetaDataParserService( 3609): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,D/AndroidRuntime( 4191): Calling main entry com.android.commands.pm.Pm
,I/AMMetaDataParserService( 3609): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/PackageManager( 1020): START PACKAGE DELETE: observer{960764922}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER,
,D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10333, uninstall pkg
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 3119:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1020): Force removing ActivityRecord{39b650a3 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1020): Set to : 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1020): Focused application set to: xxxx,
D/InputDispatcher( 1020): Focus left window: 3119
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3609): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/Mms/ArtClassLoader( 4183): init before art
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,D/Mms/TelephonyPermission( 4183): start operation mode monitor
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,W/PackageSettings( 1020): Skipping PackageSetting{166bf4fe com.test.thalitest/10326} due to missing metadata
,V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,W/ResourcesManager( 4183): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10333 user=0: pkg removed
,D/Mms/TelephonyPermission( 4183): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4183): isDefault true
,D/Launcher( 1480): onRestart, Launcher: 261419400
,D/Mms/MmsApp( 4183): onCreate() com.android.mms
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,D/Launcher( 1480): onStart, Launcher: 261419400
,D/Launcher.HomeView( 1480): onStart
,D/Launcher( 1480): onResume, Launcher: 261419400
,D/SettingsProvider( 1020): name = kids_home_mode
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10006
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,D/Launcher.HomeView( 1480): onResume
,D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/art     ( 3748): Explicit concurrent mark sweep GC freed 21071(1121KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 3MB/5MB, paused 694us total 37.262ms
,E/SamsungIME( 1773): mOCRHelper is null
,W/GeofencerStateMachine( 1640): Ignoring removeGeofence because network location is disabled.
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MenuAppsGridFragment( 1480): onResume
,D/Mms/MmsApp( 4183): [start]    initCountryIso consume time = 500.114115
,D/CountryDetector( 1020): The first listener is added
,D/Mms/MmsApp( 4183): [end]    initCountryIso consume time = 15.979531
,D/Mms/MmsConfig( 4183): [start]    MmsConfig.init() consume time = 0.411458
,D/Mms/MmsConfig( 4183): before partial update
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:assistant
I/AMMetaDataParserService( 3609): Resource data:2131165220
,D/Mms/MmsConfig( 4183): Load Resize quality : 80
,W/ResourcesManager( 3609): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3609): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3609): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3609): getResourceTypeNamexml
,D/EasySignUpManager_1.0.1( 4183): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4183): isAuth is false
,D/Mms/MmsConfig( 4183): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/ActivityManager( 1020): handle home activity for 0
,D/Mms/ArtClassLoader( 4183): init [DONE] art
I/WallpaperManagerService( 1020): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1020): post home show event for user 0
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,I/AMMetaDataParserService( 3609): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,D/TP/MmsSmsProvider( 1449): query,matched:2117, calling pid = 4183
,I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=4, Mauncher
,D/TP/MmsSmsProvider( 1449): match 2117:Elapsed time : 4.388 ms
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/RegisteredServicesCache( 1436): empty dynamic service
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1020): Focus entered window: 1480
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1480): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/EasySignUpManager_1.0.1( 4183): isAuth is false
D/EasySignUpManager_1.0.1( 4183): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4183): mps_code.dat does not exist
E/CscParser( 4183): customer_path =/system/csc/customer.xml
E/CscParser( 4183): fileName + /system/csc/customer.xml
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10333
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,E/CscParser( 4183): mps_code.dat does not exist
E/CscParser( 4183): customer_path =/system/csc/customer.xml
E/CscParser( 4183): fileName + /system/csc/customer.xml
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
,I/AMMetaDataParserService( 3609): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/TaskPersister( 1020): removeObsoleteFile: deleting file=2_task.xml
,D/CscParser( 4183): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4183):  enable multiwindow = false
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
,E/Mms/MessageUtils( 4183): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4183): updateCountryIso : update country iso info 
,W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 3119 uid 10333
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.set,tings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
W/ContextImpl( 3609): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.DockSettings
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ManageApplications
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
D/SensorService( 1020): [SO] activate (ident=0xb8662d98, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
W/ActivityManager( 1020): mDVFSHelper.release()
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
,I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
D/SamsungIME( 1773): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/SensorManager( 1020): unregisterListener ::   
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 200000000(ns)
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3609): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3609): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3609): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/SensorService( 1020): [SO] changed settle time [0]
D/SensorService( 1020): [SO] setDelay [200000000]
D/SensorService( 1020): [SO] activate (ident=0xb8662d98, enabled=1)
D/SensorService( 1020): [SO] AR_init
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10333
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
D/WallpaperManagerService( 1020):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1020): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/Mms/MmsConfig( 4183): [end]    init() consume time = 180.634636
W/OpenGLRenderer( 1480): SFEffectCache::get: create texture(0xa187e724): name, size, mSize = 34, 82320, 217556
D/Mms/Contact( 4183): [start]    init() consume time = 60.589947
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/Mms/Contact( 4183): [end]    init consume time = 36.21849
D/TP/MmsSmsProvider( 1449): query,matched:13, calling pid = 4183
D/TP/MmsSmsProvider( 1449): match 13:Elapsed time : 1.389 ms
D/Mms/DraftCache( 4183): [start]    rebuildCache consume time = 21.896875
D/Mms/MethodReflector( 4183): getSubId is called
D/Mms/TelephonyUtils( 4183): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 4183): getTelephonyProperty is called
D/Mms/DownloadManager( 4183): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4183): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4183): auto download without roaming -> true
D/Mms/DownloadManager( 4183): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4183): getSubId is called
D/Mms/MethodReflector( 4183): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4183): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4183): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4183): getTelephonyProperty is called
D/Mms/DownloadManager( 4183): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4183): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4183): auto download without roaming -> true
D/Mms/DownloadManager( 4183): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4183): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4183): mAutoDownload ------> true
D/TP/MmsSmsProvider( 1449): query,matched:12, calling pid = 4183
D/TP/MmsSmsProvider( 1449): match 12:Elapsed time : 1.729 ms
,D/Mms/DraftCache( 4183): [end]    rebuildCache consume time = 27.737917
,D/ComposerPerformance( 4183): 1448461025781 ms / [DONE] Composer constructor
,E/CII     ( 4183): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 4183): ReservationManager()
,I/Mms/ReservationManager( 4183): resetAfterConnected()
,D/TP/MmsSmsProvider( 1449): query,matched:7, calling pid = 4183
,D/TP/MmsSmsProvider( 1449): match 7:Elapsed time : 4.435 ms
,D/Mms/Conversation( 4183): [start]    init() consume time = 21.166406
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 35487(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 22MB/33MB, paused 2.488ms total 304.710ms
,I/Mms/ReservationManager( 4183): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1449): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1449): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1449): updateThread(), thread_id = 9223372036854775807
,D/Mms/MmsApp( 4183): [end]    onCreate() consume time = 8.865156
,D/Mms/DownloadManager( 4183): Service state changed: Bundle[mParcelledData.dataSize=744]
W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/Mms/DownloadManager( 4183): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 4183): getSubId is called
D/Mms/TelephonyUtils( 4183): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4183): getTelephonyProperty is called
D/Mms/DownloadManager( 4183): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4183): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4183): auto download without roaming -> true
D/Mms/DownloadManager( 4183): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4183): mAutoDownload ------> true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/TP/MmsSmsDatabaseHelper( 1449): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,D/PackageManager( 1020): delete codoeFile: 
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,I/ActivityManager( 1020): Killing 3425:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/ActivityManager( 1020): Displayed Component not be shown by security: +518ms
,D/TP/MmsSmsProvider( 1449): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
,D/Mms/Conversation( 4183): [end]    init consume time = 34.196927
,D/Mms/MessagingNotification( 4183): [start]    init() consume time = 3.498334
,D/Mms/MessagingNotification( 4183): [end]    init consume time = 2.993541
,D/Mms/Synchronizer( 4183): [start]    doSync consume time = 3.890781
,D/Mms/SpamFilter( 4183): [start]    SpamFilter fill() begin consume time = 2.482605
D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
I/AASA_removePackage( 1020): UID=10333 Target=com.example.hello
,D/TP/MmsSmsProvider( 1449): update, matched:300, calling pid = 4183
D/PackageManager( 1020): result of delete: 1{960764922}
V/TP/MmsSmsProvider( 1449): syncDBData start
,D/TP/MmsSmsProvider( 1449): query,matched:0, calling pid = 4183
,V/TP/MmsSmsProvider( 1449): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1449): query,matched:400, calling pid = 4183
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/TP/MmsSmsProvider( 1449): syncDBData sms end
,D/TP/MmsSmsProvider( 1449): match 0:Elapsed time : 3.842 ms
V/TP/MmsSmsProvider( 1449): syncDBData mms end
,V/TP/MmsSmsProvider( 1449): syncDBData end
,D/Mms/Synchronizer( 4183): [end]    doSync consume time = 17.225729
D/AndroidRuntime( 4191): Shutting down VM
D/Mms/SpamFilter( 4183): [end]    SpamFilter fill() finished consume time = 1.712031
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/MessagingNotification( 4183): checkBadgeCount unreadCount=0 badgeCount=0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1020): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1449): query,matched:26, calling pid = 4183
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TP/SmsProvider( 1449): match 26:Elapsed time : 3.916 ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1640): [173] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1449): query,matched:6, calling pid = 4183
,D/TP/MmsSmsProvider( 1449): match 6:Elapsed time : 1.489 ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/Zygote  ( 4233): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4233 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,E/Zygote  ( 4233): v2
I/libpersona( 4233): KNOX_SDCARD checking this for 10023
I/SELinux ( 4233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4233): KNOX_SDCARD not a persona
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 4233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4233): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/CrashAnrDetector( 1020): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 1020): clearDefaults: com.example.hello
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4233): TimaSignature is unavailable
,D/ActivityThread( 4233): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1605): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3425/cgroup.procs: No such file or directory
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1020): [SO] currT = 41531370000, prevT = 41091052000, diff = 440318000, [-0.421 -0.019 9.902]
,D/SensorService( 1020): [SO] -0.421 -0.019 9.902
D/SensorService( 1020): [SO] [100 -> 255]
,I/ActivityManager( 1020): Killing 3444:com.wssnps/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1605): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1801): Restart initialization of location
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 4191): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2937): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
V/GmsCoreStatsServiceLauncher( 1801): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1640): No location to return for getLastLocation()
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3444/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/FusedLocationProvider( 1605): location=null
,I/OMACP   ( 4233): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 4183): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,E/SQLiteLog( 1605): (10) unixWrite() File Descriptor : 57 gets errno : 9
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,E/SQLiteDatabase( 1605): Error inserting runtime=1448461026163 retry_strategy={"maximum_backoff_seconds":{"3600":0},"initial_backoff_seconds":{"30":0},"retry_policy":{"0":0}} tag=upload_periodic requires_charging=0 target_package=com.google.android.gms required_network_type=0 last_runtime=0 flex_time=3540000 period=3600000 task_type=1 target_class=com.google.android.gms.playlog.uploader.UploaderService user_id=0
E/SQLiteDatabase( 1605): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 1605): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 1605): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 1605): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 1605): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 1605): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 1605): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 1605): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:201)
E/SQLiteDatabase( 1605): 	at com.google.android.gms.gcm.nts.h.a(SourceFile:481)
E/SQLiteDatabase( 1605): 	at com.google.android.gms.gcm.nts.h.a(SourceFile:462)
E/SQLiteDatabase( 1605): 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:178)
E/SQLiteDatabase( 1605): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
E/SQLiteDatabase( 1605): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
E/SQLiteDatabase( 1605): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
E/SQLiteDatabase( 1605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1605): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 1605): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 1605): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 1605): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 1605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 1605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/NetworkScheduler( 1605): Error persisting task.
I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/FileUtils( 2709): Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/MTPRx   ( 3581): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.j,ava:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
D/SecContentProvider2( 1020): uri = 14 selection = getSealedState
D/SecContentProvider2( 1020): mCursor = null
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/SecContentProvider2( 1020): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1020): mCursor = null
E/SQLiteDatabase( 2709): Failed to ope,n database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
V/MTPRx   ( 3581): sealedState: false
V/MTPRx   ( 3581): sealedUsbMassStorageState: false
E/MTPRx   ( 3581): check value of boot_completed is1
E/MTPRx   ( 3581): check booting is completed_sys.boot_completed
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/MTPRx   ( 3581): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3581): Status for mount/Unmount :removed
E/MTPRx   ( 3581): SDcard is not available
W/MTPRx   ( 3581): value of connected istrue
W/MTPRx   ( 3581): value of configured istrue
W/MTPRx   ( 3581): value of mtpEnabled istrue
W/MTPRx   ( 3581): value of ptpEnabled isfalse
E/MTPRx   ( 3581): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 3581): mFirstTime: false
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{10316623 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:41721
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512),
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/        ( 3581): MTP: reading debug level property
I/Choreographer( 1480): Skipped 39 frames!  The application may be doing too much work on its main thread.
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/WallpaperManager( 1480): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
D/WallpaperManager( 1480): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
E/MTPJNIInterface( 3581): Getting CryptionKey from JAVA
E/MTPRx   ( 3581): currentUserId is 0
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/MTPRx   ( 3581): Start observing USB_STATE_MATCH 
E/MTPRx   ( 3581): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 3581): is_Privatemode is NOT 1
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
D/SettingsProvider( 1020): name = boot_time_connected
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2709): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2709): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2709): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2709): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2709): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2709): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2709): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2709): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2709): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2709): 
```
