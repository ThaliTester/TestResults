#### Test 50242285e132180_thali08_samsung-SM-A300FU Logs


```
--------- beginning of system
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  ( 2715): MountEmulatedStorage()
E/Zygote  ( 2715): v2
I/SELinux ( 2715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/libpersona( 2715): KNOX_SDCARD checking this for 1000
I/libpersona( 2715): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2715 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false
D/TP/MmsProvider( 1453): Update uri=content://mms, match=0
D/TP/MmsProvider( 1453): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
I/Mms:transaction( 2218): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2218): [start]    nonBlockingUpdateMessageIndicator() consume time = 3448.254165
I/Mms/ReservationManager( 2218): resetAfterConnected()
D/Mms/MessagingNotification( 2218): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2218): isDefault true
D/TP/MmsProvider( 1453): Query uri=content://mms, match=0, calling pid = 2218
I/DrmEventService( 1018): action event :android.intent.action.BOOT_COMPLETED
I/TimaServiceEventReceiver( 1018): TimaServiceEventReceiver : onReceive
D/TP/MmsSmsProvider( 1453): query,matched:7, calling pid = 2218
D/TP/MmsSmsProvider( 1453): match 7:Elapsed time : 2.713 ms
I/ANDROID_DRM_FRWORKS_DrmManager(  283): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1188/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1382/cgroup.procs: No such file or directory
E/SQLiteLog( 1226): (283) recovered 467 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
E/CscReceiver( 1453): onReceive android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/TimaKeyStoreProvider( 2715): TimaSignature is unavailable
D/ActivityThread( 2715): Added TimaKeyStore provider
D/MediaScanner( 1226): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/CscUpdateService( 1453): onStart
E/CscUpdateService( 1453): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1453): set_CSC_version
E/CscParser( 1453): update(): xml file exist
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2734): MountEmulatedStorage()
I/libpersona( 2734): KNOX_SDCARD checking this for 10002
E/Zygote  ( 2734): v2
I/libpersona( 2734): KNOX_SDCARD not a persona
I/SELinux ( 2734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2734 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
I/SELinux ( 2734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2734): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/CscUtil ( 1453): isWifiOnly = false
D/SettingsProvider( 1018): name = next_alarm_formatted
I/Mms/ReservationManager( 2218): getReservedSendMessageCount(): retMessageCount=0
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10081
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
I/System.out( 1453): HandDataNode = null
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
I/CscUpdateService( 1453): PATH_CSCNAME =CustomerDataSet.CSCName
D/TP/MmsSmsProvider( 1453): query,matched:200, calling pid = 2218
W/ContextImpl( 2715): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
D/TP/MmsSmsProvider( 1453): match 200:Elapsed time : 1.298 ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/MediaScanner( 1226): processDirectory :  /system/media
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/CscUpdateService( 1453): This is normal boot : CSC not updated
D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
E/CscParser( 1453): update(): xml file exist
D/TimaKeyStoreProvider( 2734): TimaSignature is unavailable
D/ActivityThread( 2734): Added TimaKeyStore provider
E/Zygote  ( 2752): MountEmulatedStorage()
E/Zygote  ( 2752): v2
I/libpersona( 2752): KNOX_SDCARD checking this for 10043
I/libpersona( 2752): KNOX_SDCARD not a persona
I/SELinux ( 2752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/CscGPS  ( 1453): CSCGPS.updateParameters
D/CscGPS  ( 1453): supl host : null
D/CscGPS  ( 1453): SUPL Host is null or invalid
D/CscGPS  ( 1453): supl_ver : null
D/CscGPS  ( 1453): SUPL Ver is null or invalid
D/CscGPS  ( 1453): supl port : null
D/CscGPS  ( 1453): SUPL PORT is null or invalid
D/CscGPS  ( 1453): LPP : null
D/CscGPS  ( 1453): LPP is null or invalid
D/CscGPS  ( 1453): CSC don't have any AGPS value.
E/SELinux ( 2752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2752 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/MediaScanner( 1226):  prescan time: 110ms (DB items: 138)
V/MediaScanner( 1226):     scan time: 49ms (Caching mode: true), (makeEntry time: 18ms ~36%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1226): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1226):    total time: 159ms
V/MediaScanner( 1226): checked files: 130  directories : 6  (I: 0, U: 0)
I/CscUpdateService( 1453): same CSC Version
D/CscUtil ( 1453): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/MediaScanner( 1226): checkDefaultSounds
D/MediaScanner( 1226): system alarm_alert  : Vwiurug_etwofi5wgg
E/Zygote  ( 2763): MountEmulatedStorage()
E/Zygote  ( 2763): v2
I/libpersona( 2763): KNOX_SDCARD checking this for 10153
I/libpersona( 2763): KNOX_SDCARD not a persona
I/SELinux ( 2763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2763 uid=10153 gids={50153, 9997} abi=armeabi-v7a
E/USB_UICC(  297): Timeout! No signal received. Retry num = 24
I/SELinux ( 2763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2752): TimaSignature is unavailable
D/ActivityThread( 2752): Added TimaKeyStore provider
D/MediaScanner( 1226): OK. alarm_alert is already exist in setting DB.
D/TimaKeyStoreProvider( 2763): TimaSignature is unavailable
D/TP/SmsProvider( 1453): query,matched:0, calling pid = 2218
D/ActivityThread( 2763): Added TimaKeyStore provider
D/MediaScanner( 1226): system notification_sound  : K_Oprkltf5wgg
D/TP/SmsProvider( 1453): match 0:Elapsed time : 2.781 ms
D/MediaScanner( 1226): OK. notification_sound is already exist in setting DB.
W/ResourcesManager( 2752): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2752): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2752): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/Mms/SmsReceiverService( 2218): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/MediaScanner( 1226): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1226): OK. ringtone is already exist in setting DB.
D/Mms/TelephonyPermission( 2218): isDefault true
D/Mms/SmsReceiverService( 2218): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2218): [start]    handleBootCompleted() consume time = 214.75849
W/art     ( 2677): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 124.795ms
W/ResourcesManager( 2763): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/FactoryTestApp( 2508): [DummyFtClient$mBroadcastReceiver](2508) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2508): [DummyFtClient$mBroadcastReceiver](2508) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2508): [DummyFtClient$mBroadcastReceiver](2508) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/MediaScannerService( 1226): !@done scanning volume internal
D/MediaScannerService( 1226): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
E/Zygote  ( 2784): MountEmulatedStorage()
E/Zygote  ( 2784): v2
I/libpersona( 2784): KNOX_SDCARD checking this for 1000
D/TP/MmsSmsProvider( 1453): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1453): deleteConversation threadId: 9223372036854775806
I/libpersona( 2784): KNOX_SDCARD not a persona
I/SELinux ( 2784): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2784): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2784): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2784 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
I/art     (  305): Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 23.611ms
I/art     ( 1453): Explicit concurrent mark sweep GC freed 39370(2MB) AllocSpace objects, 11(176KB) LOS objects, 45% free, 4MB/8MB, paused 1.039ms total 100.757ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1453): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1453): updateThread(), thread_id = 9223372036854775806
D/TP/SmsProvider( 1453): query,matched:51, calling pid = 2218
D/TimaKeyStoreProvider( 2784): TimaSignature is unavailable
D/ActivityThread( 2784): Added TimaKeyStore provider
D/SettingsProvider( 1018): name = block_emergency_message
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10043
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/TP/SmsProvider( 1453): match 51:Elapsed time : 3.394 ms
V/TP/MmsSmsDatabaseHelper( 1453): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 687us total 18.046ms
D/TP/MmsSmsProvider( 1453): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
D/MediaScanner( 1226): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.388ms
V/MediaScanner( 1226): processDirectory :  /storage/emulated/0
E/Zygote  ( 2802): MountEmulatedStorage()
I/libpersona( 2802): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2802): v2
I/libpersona( 2802): KNOX_SDCARD not a persona
I/SELinux ( 2802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/MediaScanner( 1226): Skipping:
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(75ebcf7
I/ActivityManager( 1018): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2802 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
D/TimaKeyStoreProvider( 2802): TimaSignature is unavailable
D/Mms/Conversation( 2218): deleteTempConversation(),deleted=0
D/ActivityThread( 2802): Added TimaKeyStore provider
D/MediaScanner( 1226): Skipping:
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1226): processDirectory :  /storage/extSdCard
W/MediaScanner( 1226): Error opening directory, reason : Permission denied.
W/MediaScanner( 1226): 7klwibgf7fxlKdCbid7
V/MediaScanner( 1226):  prescan time: 50ms (DB items: 26)
V/MediaScanner( 1226):     scan time: 41ms (Caching mode: true), (makeEntry time: 29ms ~70%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1226): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1226):    total time: 93ms
V/MediaScanner( 1226): checked files: 10  directories : 16  (I: 0, U: 0)
D/Mms/MessagingNotification( 2218): isBlockingModeEnabled() = false, Zen mode = 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SmsProvider( 1453): Update uri=content://sms/outbox, match=8
D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
E/Zygote  ( 2818): MountEmulatedStorage()
E/Zygote  ( 2818): v2
I/libpersona( 2818): KNOX_SDCARD checking this for 10155
I/libpersona( 2818): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2818 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 2818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 1398:com.sec.android.provider.emergencymode/u0a92 (adj 15): empty #31
D/MediaScannerService( 1226): !@done scanning volume external
D/FactoryTestApp( 2508): [DummyFtClient$mBroadcastReceiver](2508) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2508): [DummyFtClient$mBroadcastReceiver](2508) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/Mms/SmsReceiverService( 2218): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2218): handle boot completed, sendFirstQueuedMessage()
I/SELinux ( 2818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/Mms/SmsReceiverService( 2218): [SIM-1]sendFirstQueuedMessage()
D/FactoryTestApp( 2508): [DummyFtClient$sendBootCompletedAndFinish](2508) ...
D/FactoryTestApp( 2508): [Support$Values.getString](2508) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2508): [ModuleCommon$isConnectionModeNone](2508) mConnectionMode = gsm
D/FactoryTestApp( 2508): [IPCWriterToSecPhoneService$ResponseWriter](2508) Create IPCWriterToSecPhoneService
E/SELinux ( 2818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/FactoryTestApp( 2508): [IPCWriterToSecPhoneService$connectToSecPhoneService](2508)  
W/ContextImpl( 2508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
D/TimaKeyStoreProvider( 2818): TimaSignature is unavailable
D/ActivityThread( 2818): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/WifiCredService( 1289): onCreate
D/TP/SmsProvider( 1453): query,matched:26, calling pid = 2218
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1453): match 26:Elapsed time : 12.692 ms
E/SQLiteLog( 2802): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
E/Zygote  ( 2839): MountEmulatedStorage()
E/Zygote  ( 2839): v2
I/libpersona( 2839): KNOX_SDCARD checking this for 1000
I/libpersona( 2839): KNOX_SDCARD not a persona
I/SELinux ( 2839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2839): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2839 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ResourcesManager( 2818): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/FactoryTestApp( 2508): [IPCWriterToSecPhoneService$onServiceConnected](2508) connected done
D/FactoryTestApp( 2508): [IPCWriterToSecPhoneService$write](2508) Send Response Message to SecPhone
D/FactoryTestApp( 2508): [IPCWriterToSecPhoneService$write](2508) Response ��
D/AT_Distributor(  309): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 2508): [IPCWriterToSecPhoneService$handleMessage](2508) Send BOOTING COMPLETED done
D/WifiTimerReceiver( 1289): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1289): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1289): Action boot completed received
W/libprocessgroup( 1018): failed to open /acct/uid_10092/pid_1398/cgroup.procs: No such file or directory
D/Mms/SmsReceiver( 2218): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2218): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2218): isDefault true
D/TimaKeyStoreProvider( 2839): TimaSignature is unavailable
D/ActivityThread( 2839): Added TimaKeyStore provider
D/DSM     ( 2802): [Lines:107] Normal booted
D/DSM     ( 2802): [Lines:114] Boot completed
D/TP/MmsProvider( 1453): Query uri=content://mms, match=0, calling pid = 2218
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2839): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/Zygote  ( 2857): MountEmulatedStorage()
E/Zygote  ( 2857): v2
I/libpersona( 2857): KNOX_SDCARD checking this for 1000
I/libpersona( 2857): KNOX_SDCARD not a persona
I/SELinux ( 2857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2857 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 2857): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/iu.UploadsManager( 1848): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
D/NearbySettings( 1289): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1289): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1289): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1289): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
I/art     ( 1018): Explicit concurrent mark sweep GC freed 37919(2MB) AllocSpace objects, 7(226KB) LOS objects, 33% free, 21MB/32MB, paused 2.398ms total 177.985ms
D/SettingsProvider( 1018): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
V/NearbySettings( 1289): MountReceiver.mPrefHandler - 7002
D/AT_Distributor(  309): SetAtdStatus(), 1_1_0
D/AT_Distributor(  309): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/TimaKeyStoreProvider( 2857): TimaSignature is unavailable
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/NearbySettings( 1289): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/NearbySettings( 1289): MountReceiver.onReceive - Internal Path
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 2857): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2877): MountEmulatedStorage()
E/Zygote  ( 2877): v2
I/libpersona( 2877): KNOX_SDCARD checking this for 10082
I/libpersona( 2877): KNOX_SDCARD not a persona
I/SELinux ( 2877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2877): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
I/ActivityManager( 1018): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2877 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 1520:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
D/SettingsProvider( 1018): name = personal_mode_enabled
D/BadgeProvider( 1559): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/TP/MmsSmsProvider( 1453): query,matched:200, calling pid = 2218
W/ResourcesManager( 2857): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2877): TimaSignature is unavailable
D/ActivityThread( 2877): Added TimaKeyStore provider
D/BadgeProvider( 1559): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/Launcher.Model( 1476): reloadBadges entered.
D/BadgeProvider( 1559): sendNotify, [notify] : null
D/BadgeProvider( 1559): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1559): update, [UpdateCount] : 1
D/[0]UMC:Core( 2818): onCreate(): 
D/Mms/MessagingNotification( 2218): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2218): remove alarm
I/ActivityManager( 1018): Killing 1908:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
D/TP/MmsSmsProvider( 1453): match 200:Elapsed time : 27.847 ms
D/TP/SmsProvider( 1453): query,matched:0, calling pid = 2218
D/TP/SmsProvider( 1453): match 0:Elapsed time : 3.450 ms
D/Mms/MessagingNotification( 2218): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 2218): [end]    nonBlockingUpdateMessageIndicator() consume time = 551.884114
I/iu.UploadsManager( 1848): End new media; added: 0, uploading: 0, time: 156 ms
D/TP/SmsProvider( 1453): query,matched:0, calling pid = 2218
D/[0]UMC:DeviceInfo( 2818): USA==US==
D/TP/SmsProvider( 1453): match 0:Elapsed time : 5.436 ms
D/TP/SmsProvider( 1453): query,matched:51, calling pid = 2218
D/TP/SmsProvider( 1453): match 51:Elapsed time : 1.603 ms
D/Mms/MessagingNotification( 2218): isBlockingModeEnabled() = false, Zen mode = 0
W/libprocessgroup( 1018): failed to open /acct/uid_10134/pid_1908/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10052/pid_1520/cgroup.procs: No such file or directory
D/BadgeProvider( 1559): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/USER_AGENT( 2818): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/[0]UMC:AdminManager( 2818): init - start
D/[0]UMC:AdminManager( 2818): loadAdmins
D/Launcher.Model( 1476): reloadBadges entered.
D/BadgeProvider( 1559): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): sendNotify, [notify] : null
D/BadgeProvider( 1559): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1559): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2218): setBadgeCount(), count=0
W/ResourcesManager( 1453): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1453): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1453): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1453): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/[0]UMC:AdminManager( 2818): init - end
D/GSLBManager( 2818): migrateStoredUrlFromOldPref
D/Mms/MessagingNotification( 2218): remove alarm
D/Mms/MessagingNotification( 2218): updateAllHistoryAsRead()
D/GSLBManager( 2818): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 2818): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2818): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2818): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2818): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2818): isContainer : 0
D/TP/SmsProvider( 1453): query,matched:0, calling pid = 2218
D/TP/SmsProvider( 1453): match 0:Elapsed time : 2.084 ms
D/EnterpriseDeviceManagerService( 1018): isManagedProfileUser(): userId = 0
D/Mms/SmsReceiverService( 2218): [end]    handleBootCompleted() consume time = 132.104375
I/ActivityManager( 1018): Killing 2031:com.vlingo.midas/u0a28 (adj 15): empty #31
W/ActivityThread( 2857): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/UpdateRequestReceiver( 2877): ignoring update request
E/UpdateRequestReceiver( 2877): ignoring update request
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
I/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
E/UpdateRequestReceiver( 2877): ignoring update request
E/[0]UMC:UMCAdmin( 2818): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 2818): isContainer : 0
D/[0]UMC:UMCAdmin( 2818): deactivateUMCAdmin - UMC App Admin deactivated
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
I/SmartcardBootCompleteReceiver( 1289): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1289): Received intent with action - android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2818): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2818):  check PreETag 
W/ContextImpl( 1289): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
I/SmartcardBootCompleteReceiver( 1289): Broadcast sent with current lockscreen type
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
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
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2857): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
E/UpdateRequestReceiver( 2877): ignoring update request
,I/LcdtestApp( 2857): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/UpdateRequestReceiver( 2877): ignoring update request
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/[0]UMC:ByodSetupStarter( 2818): Container ID : 0
D/[SBeam] ( 1289): SBeamEnabler.initPreferenceForSbeam : 0
I/libpersona( 2911): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2911): MountEmulatedStorage()
I/libpersona( 2911): KNOX_SDCARD not a persona
E/Zygote  ( 2911): v2
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2911 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 2079:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
I/SELinux ( 2911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2911): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/[0]UMC:Utils( 2818): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2818): shutdown
I/art     ( 2818): System.exit called, status: 0
I/AndroidRuntime( 2818): VM exiting with result code 0, cleanup skipped.
E/UpdateRequestReceiver( 2877): ignoring update request
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2911): TimaSignature is unavailable
D/ActivityThread( 2911): Added TimaKeyStore provider
E/Zygote  ( 2929): MountEmulatedStorage()
E/Zygote  ( 2929): v2
I/libpersona( 2929): KNOX_SDCARD checking this for 10088
I/libpersona( 2929): KNOX_SDCARD not a persona
I/SettingSearch/SearchIntentReceiver( 1289): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1289): search setting db init!!
I/SELinux ( 2929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=2929 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2135:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
I/SELinux ( 2929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2929): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ContextImpl( 1289): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
I/SettingSearch/SearchIntentReceiver( 1289): BOOT_COMPLETED call InitSerachDBThread thread start!
D/TimaKeyStoreProvider( 2929): TimaSignature is unavailable
D/ActivityThread( 2929): Added TimaKeyStore provider
I/ActivityManager( 1018): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2818)(adj 0) has died(66,719)
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1018): failed to open /acct/uid_10028/pid_2031/cgroup.procs: No such file or directory
E/Zygote  ( 2947): MountEmulatedStorage()
I/libpersona( 2947): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2947): v2
I/libpersona( 2947): KNOX_SDCARD not a persona
I/SELinux ( 2947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2947 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1733): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1733): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1733): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1733): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/Zygote  ( 2960): MountEmulatedStorage()
I/libpersona( 2960): KNOX_SDCARD checking this for 10146
E/Zygote  ( 2960): v2
I/libpersona( 2960): KNOX_SDCARD not a persona
I/SELinux ( 2960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2960 uid=10146 gids={50146, 9997} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2947): TimaSignature is unavailable
D/ActivityThread( 2947): Added TimaKeyStore provider
I/SELinux ( 2960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2960): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/SMD     (  289): DCD OFF
D/daemonapp( 1733): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1733): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
W/libprocessgroup( 1018): failed to open /acct/uid_10045/pid_2079/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10110/pid_2135/cgroup.procs: No such file or directory
D/comsamsunglog( 1733): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1733): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1733): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1733): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1733): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1733): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
E/USB_UICC(  297): Timeout! No signal received. Retry num = 25
D/SettingsProvider( 1018): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10157
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/TimaKeyStoreProvider( 2960): TimaSignature is unavailable
D/ActivityThread( 2960): Added TimaKeyStore provider
W/ResourcesManager( 2947): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
D/daemonapp( 1733): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/daemonapp( 1733): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/daemonapp( 1733): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1733): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1733): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1733): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/daemonapp( 1733): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1733): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1733): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1449501102925
D/daemonapp( 1733): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1449522660000
D/daemonapp( 1733): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1733): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/daemonapp( 1733): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449522660000
D/daemonapp( 1733): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 19
D/daemonapp( 1733): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1449522660000
D/AndroidRuntime( 2935): 
D/AndroidRuntime( 2935): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2935): CheckJNI is OFF
D/AndroidRuntime( 2935): readGMSProperty: start
D/AndroidRuntime( 2935): readGMSProperty: already setted!!
D/AndroidRuntime( 2935): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2935): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2935): readGMSProperty: end
D/AndroidRuntime( 2935): addProductProperty: start
D/comdaemonstockapp( 1733): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1733): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2979): MountEmulatedStorage()
E/Zygote  ( 2979): v2
I/libpersona( 2979): KNOX_SDCARD checking this for 10161
I/libpersona( 2979): KNOX_SDCARD not a persona
I/SELinux ( 2979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2979 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2979): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DIAGMON_AGENT( 2911): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
D/TimaKeyStoreProvider( 2979): TimaSignature is unavailable
D/ActivityThread( 2979): Added TimaKeyStore provider
I/FOTA    ( 2947): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
W/ResourcesManager( 2979): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2979): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/DBG_DM  ( 2947): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
I/DBG_DM  ( 2947): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
V/JNIHelp ( 2979): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/DBG_DM  ( 2947): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3008): MountEmulatedStorage()
E/Zygote  ( 3008): v2
I/libpersona( 3008): KNOX_SDCARD checking this for 10088
I/libpersona( 3008): KNOX_SDCARD not a persona
I/SELinux ( 3008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityThread( 2979): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/SELinux ( 3008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/System  ( 2979): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@350a4cd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2979): Installed default security provider GmsCore_OpenSSL
E/SELinux ( 3008): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3008 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3008): TimaSignature is unavailable
D/ActivityThread( 3008): Added TimaKeyStore provider
I/art     (  305): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 950us total 20.117ms
I/DIAGMON_AGENT( 2911): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DBG_DM  ( 2947): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
I/DIAGMON_AGENT( 2911): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
W/ContextImpl( 2947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 4.923ms total 21.114ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DIAGMON_AGENT( 2911): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 2911): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2911): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2911): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.809ms
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 2947): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/DBG_DM  ( 2947): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 2947): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 2947): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 2947): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 2947): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/DBG_DM  ( 2947): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
W/ContextImpl( 2947): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
I/DBG_DM  ( 2947): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 2947): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 2947): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(155/onStartCommand)] 
E/Zygote  ( 3026): MountEmulatedStorage()
E/Zygote  ( 3026): v2
I/libpersona( 3026): KNOX_SDCARD checking this for 1000
I/libpersona( 3026): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3026 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/SELinux ( 3026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/OverheatReceiver( 1175): onReceive() getAction : android.intent.action.BOOT_COMPLETED
I/SELinux ( 3026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3026): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/OverheatReceiver( 1175): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1175): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1175): isSafeMode = false
I/DBG_DM  ( 2947): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
D/BootupListener( 1453): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1018): name = internet_call_settings_visibility
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1001
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/PhoneUtilsCommon( 1453): isSupportVoLTE is false.
D/TimaKeyStoreProvider( 3026): TimaSignature is unavailable
D/ActivityThread( 3026): Added TimaKeyStore provider
I/DBG_DM  ( 2947): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
I/ActivityManager( 1018): Killing 1606:com.google.android.partnersetup/u0a14 (adj 15): empty #31
I/ActivityManager( 1018): Killing 2238:com.sec.tcpdumpservice/1000 (adj 15): empty #31
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2979): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3026): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
E/Zygote  ( 3052): MountEmulatedStorage()
I/DBG_POLICYDM( 3026): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
E/Zygote  ( 3052): v2
I/libpersona( 3052): KNOX_SDCARD checking this for 10008
I/SELinux ( 3052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3052): KNOX_SDCARD not a persona
I/Telecom ( 1427): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
I/SELinux ( 3052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3052): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/com.dropbox.android.service.DropboxNetworkReceiver( 2929): Setting receiver enabled: false
I/DBG_POLICYDM( 3026): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3052 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
D/TimaKeyStoreProvider( 3052): TimaSignature is unavailable
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3052): Added TimaKeyStore provider
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3026): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_1606/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2238/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 3026): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 3026): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
E/Zygote  ( 3069): MountEmulatedStorage()
E/Zygote  ( 3069): v2
I/libpersona( 3069): KNOX_SDCARD checking this for 10052
I/libpersona( 3069): KNOX_SDCARD not a persona
I/SELinux ( 3069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3069): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3069 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/Telecom ( 1427): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
E/ActivityThread( 2929): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
I/DBG_POLICYDM( 3026): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 3026): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
D/TimaKeyStoreProvider( 3069): TimaSignature is unavailable
D/ActivityThread( 3069): Added TimaKeyStore provider
E/USB_UICC(  297): Timeout! No signal received. Retry num = 26
I/DBG_DM  ( 2947): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
I/dbxyzptlk.db240408.D.h( 2929): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
E/AffinityControl( 2935): AffinityControl: registerfunction enter
I/DBG_DM  ( 2947): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/dbxyzptlk.db240408.D.h( 2929): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
I/DBG_DM  ( 2947): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
I/DBG_DM  ( 2947): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
I/dbxyzptlk.db240408.D.h( 2929): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
D/AndroidRuntime( 2935): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/dbxyzptlk.db240408.D.h( 2929): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
I/DBG_POLICYDM( 3026): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
W/ActivityManager( 1018): mDVFSHelper.acquire()
V/audio_hw_primary(  284): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  284): audio_extn_get_parameters: returns 
V/msm8974_platform(  284): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  284): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  284): key: 'call_forwarding' value: ''
V/InCall  ( 1796): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1796): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1796): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
I/DBG_POLICYDM( 3026): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
D/ScoverManager( 1796): serviceVersion : 16908288
I/DBG_POLICYDM( 3026): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/InCall  ( 1796): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
I/Telecom ( 1427): ProximitySensorManager: Proximity wake lock already released
D/InCall  ( 1796): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
E/DBG_POLICYDM( 3026): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
I/InCall  ( 1796): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1796): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1796): InCallPresenter -  - dismissCoverDialog()...
D/breakpad( 2929): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
I/InCall  ( 1796): CallSContextMotion - stopPutDownListening
D/InCall  ( 1796): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
D/FocusedStackFrame( 1018): Set to : 0
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1796): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
D/Launcher.HomeView( 1476): onPause
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1476
D/PhoneStatusBarView( 1175): setCallBackground:0
D/AndroidRuntime( 2935): Shutting down VM
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/com.dropbox.sync.android.a( 2929): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
E/Zygote  ( 3100): MountEmulatedStorage()
I/libpersona( 3100): KNOX_SDCARD checking this for 10333
E/Zygote  ( 3100): v2
I/libpersona( 3100): KNOX_SDCARD not a persona
I/SELinux ( 3100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/SELinux ( 3100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3100): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/VideoCallManager( 1796): Instantiating VideoCallManager
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3100 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/        ( 1796): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/GFX construct_block_size_descriptor_2d second part( 1796): took 3.144895ms for 0*0 texture 0
I/GFX generate_partition_tables( 1796): took 5.234635ms for 0*0 texture 0
V/ActivityThread( 1476): updateVisibility : ActivityRecord{136fa791 token=android.os.BinderProxy@14b1ab81 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/DBG_POLICYDM( 3026): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
I/GFX raster( 1796): took 12.301406ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1796): Bitmap=0xb84d8090 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb84d7960 counterpartCT=4 counterpartW=176 counterparth=144
D/TimaKeyStoreProvider( 3100): TimaSignature is unavailable
D/ActivityThread( 3100): Added TimaKeyStore provider
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3026): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3026): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
E/        ( 1796): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/Adreno-EGL( 1796): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1796): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1796): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1796): Local Branch: 
I/Adreno-EGL( 1796): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1796): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1796):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/Launcher.HomeView( 1476): onStop
V/ActivityThread( 1476): updateVisibility : ActivityRecord{136fa791 token=android.os.BinderProxy@14b1ab81 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1018): [SO] activate (ident=0xb88b47a8, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SensorManager( 1018): unregisterListener ::   
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb88fc188, enabled=1)
D/SensorService( 1018): [SO] AR_init
E/Zygote  ( 3122): MountEmulatedStorage()
I/libpersona( 3122): KNOX_SDCARD checking this for 10014
E/Zygote  ( 3122): v2
I/libpersona( 3122): KNOX_SDCARD not a persona
I/SELinux ( 3122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/ActivityManager( 1018): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3122 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
D/LocationManagerService( 1018): getProviders()=[passive]
I/SELinux ( 3122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3122): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/Launcher( 1476): onTrimMemory. Level: 20
I/com.dropbox.sync.android.ad( 2929): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
D/TimaKeyStoreProvider( 3122): TimaSignature is unavailable
D/ActivityThread( 3122): Added TimaKeyStore provider
D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
W/art     ( 2935): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/GFX GPU raster( 1796): eglCreateImageKHR: EGL_SUCCESS
,E/Zygote  ( 3142): MountEmulatedStorage()
,I/libpersona( 3142): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3142): v2
I/libpersona( 3142): KNOX_SDCARD not a persona
I/SELinux ( 3142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/glCompressedTexImage2D( 1796): took 0.501198ms for 320*61440 texture 37809
,I/SELinux ( 3142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2271:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
I/ActivityManager( 1018): Killing 1491:com.android.printspooler/u0a132 (adj 15): empty #32
I/ActivityManager( 1018): Killing 2252:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #33
,I/ContactAccountLoggerTas( 3069): canRun() : Opted Out
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/draw setup( 1796): took 13.560885ms for 320*240 texture 37809
,E/GFX GPU raster( 1796): drawn
,I/GFX GPU raster ASTC( 1796): took 47.621404ms for 320*240 texture 12
I/GFX raster( 1796): took 47.753800ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1796): Bitmap=0xb84d8010 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb84d7b78 counterpartCT=4 counterpartW=320 counterparth=240
,D/TimaKeyStoreProvider( 3142): TimaSignature is unavailable
,D/ActivityThread( 3142): Added TimaKeyStore provider
,D/SensorService( 1018): [SO] currT = 32781056000, prevT = 32471081000, diff = 309975000, [-0.421 0.019 9.883]
D/SensorService( 1018): [SO] -0.421 0.019 9.883
D/SensorService( 1018): [SO] -0.421 0.019 9.883
D/SensorService( 1018): [SO] [100 -> 255]
,E/        ( 1796): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1796): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1796): took 0.354375ms for 480*122880 texture 37813
I/draw setup( 1796): took 0.841458ms for 480*640 texture 37813
E/GFX GPU raster( 1796): drawn
,I/GFX GPU raster ASTC( 1796): took 8.739842ms for 480*640 texture 12
I/GFX raster( 1796): took 8.806978ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1796): Bitmap=0xb84d7b78 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb87195d0 counterpartCT=4 counterpartW=480 counterparth=640
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/WebViewFactory( 3100): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,E/Tethering( 1018): No numeric data
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 1796): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330,
I/GFX GPU raster( 1796): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1796): took 0.365208ms for 440*116864 texture 37809
I/draw setup( 1796): took 0.709219ms for 440*330 texture 37809
E/GFX GPU raster( 1796): drawn
I/Velvet.VelvetFactory( 3069): refreshing search history.
I/GFX GPU raster ASTC( 1796): took 4.248699ms for 440*330 texture 12
I/GFX raster( 1796): took 4.331719ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1796): Bitmap=0xb87195b0 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8719980 counterpartCT=4 counterpartW=440 counterparth=330
,E/Zygote  ( 3165): MountEmulatedStorage(),
E/Zygote  ( 3165): v2
I/libpersona( 3165): KNOX_SDCARD checking this for 10090
I/libpersona( 3165): KNOX_SDCARD not a persona
,I/SELinux ( 3165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3165 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2316:com.wsomacp/u0a23 (adj 15): empty #31
,E/SELinux ( 3165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,I/LibraryLoader( 3100): Loading: webviewchromium
E/Tethering( 1018): No numeric data
I/LibraryLoader( 3100): Time to load native libraries: 5 ms (timestamps 2892-2897)
I/LibraryLoader( 3100): Expected native library version number "",actual native library version number ""
E/Tethering( 1018): No numeric data
E/Tethering( 1018): No numeric data
E/        ( 1796): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1796): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1796): took 0.479843ms for 480*163840 texture 37811
I/draw setup( 1796): took 1.018854ms for 480*640 texture 37811
E/GFX GPU raster( 1796): drawn
I/GFX GPU raster ASTC( 1796): took 6.405727ms for 480*640 texture 12
I/GFX raster( 1796): took 6.491092ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1796): Bitmap=0xb87193f0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb872c418 counterpartCT=4 counterpartW=480 counterparth=640
,D/TimaKeyStoreProvider( 3165): TimaSignature is unavailable
,D/ActivityThread( 3165): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2271/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10127/pid_2252/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10132/pid_1491/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_2316/cgroup.procs: No such file or directory
,I/DBG_FMMDM( 3142): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/elm:15121( 3165): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 3165): ELMEngine.ELMEngine( context ).
,D/elm:15121( 3165): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 3165): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/DBG_FMMDM( 3142): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3142): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3142): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/elm:15121( 3165): ElmAgentService : onCreate()
,D/elm:15121( 3165): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 3165): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3165): BootCompletedState : startBootCompleted() call
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 1796): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1796): took 2.596094ms for 0*0 texture 0
,V/WebViewChromiumFactoryProvider( 3100): Binding Chromium to main looper Looper (main, tid 1) {1f3aa30d}
,E/Zygote  ( 3189): MountEmulatedStorage()
,E/Zygote  ( 3189): v2
I/libpersona( 3189): KNOX_SDCARD checking this for 1000
I/libpersona( 3189): KNOX_SDCARD not a persona
,I/LibraryLoader( 3100): Expected native library version number "",actual native library version number ""
I/chromium( 3100): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/SELinux ( 3189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3189 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3189): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/GFX generate_partition_tables( 1796): took 8.829582ms for 0*0 texture 0
V/EmergencyMode( 1414): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,I/GFX raster( 1796): took 13.384114ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1796): Bitmap=0xb8709500 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb872c438 counterpartCT=4 counterpartW=176 counterparth=144
,D/[SBeam] ( 1289): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1289): SBeamEnabler.isSBeamSupported : EXIST
,E/        ( 1796): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,D/TimaKeyStoreProvider( 3189): TimaSignature is unavailable
I/GFX construct_block_size_descriptor_2d second part( 1796): took 2.270573ms for 0*0 texture 0
,D/ActivityThread( 3189): Added TimaKeyStore provider
,I/GFX generate_partition_tables( 1796): took 6.147917ms for 0*0 texture 0
,D/elm:15121( 3165): MDMBridge.getAllLicenseInfoFromSDK()
I/GFX raster( 1796): took 10.527708ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1796): Bitmap=0xb8719a60 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb872e128 counterpartCT=4 counterpartW=176 counterparth=144
,I/BrowserStartupController( 3100): Initializing chromium process, renderers=0
,W/art     ( 3100): Attempt to remove local handle scope entry from IRT, ignoring
,D/ScoverManager( 1796): registerListener
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/elm:15121( 3165): Get License : 0
D/elm:15121( 3165): ElmAgentService : onDestroy().
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1018): registerListenerCallback : binder = android.os.BinderProxy@264590ef, pid : 1796, uid : 1001, type : 1
,I/ActivityManager( 1018): Killing 2336:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=7 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=7 Removed Mauncher (-2/8)
,D/InCall  ( 1796): InCallPresenter -  - Finished InCallPresenter.setUp
,E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/Tethering( 1018): No numeric data
W/chromium( 3100): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/chromium( 3100): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 3100): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 3100): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 3069): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/System.out( 2929): Thread-379(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,E/Tethering( 1018): No numeric data
,D/BluetoothAdapter( 3100): 313758402: getState() :  mService = null. Returning STATE_OFF
,I/System.out( 2929): Thread-379(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2929): Thread-379(ApacheHTTPLog):isShipBuild true
I/System.out( 2929): Thread-379(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2929): Thread-379(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/FavoriteContactNamesSup( 3069): get() : Execute runnable (UI thread)
I/ContactLabelSupplier( 3069): get() : Execute runnable (UI thread)
,W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_2336/cgroup.procs: No such file or directory
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10088
,I/System.out( 2929): pool-10-thread-1 calls detatch()
,I/Adreno-EGL( 3100): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3100): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3100): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3100): Local Branch: 
I/Adreno-EGL( 3100): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3100): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3100):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/PCWCLIENTTRACE_LOG( 3189): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 3189): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3189): new DMDBOpenHelper instance
,E/YouTube MDX( 2979): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3223): MountEmulatedStorage(),
E/Zygote  ( 3223): v2
I/libpersona( 3223): KNOX_SDCARD checking this for 10055
I/libpersona( 3223): KNOX_SDCARD not a persona
,I/SELinux ( 3223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
V/VibratorService( 1018): hasVibrator - useVibetonz: true
E/SELinux ( 3223): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3223 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/PCWCLIENTTRACE_DMContentProvider( 3189): [URIMatcher] - result : 2
,I/ActivityManager( 1018): Killing 2366:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3223): TimaSignature is unavailable
,D/ActivityThread( 3223): Added TimaKeyStore provider
,W/NotificationAccessSettings( 1289): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,I/DBG_FMMDM( 3142): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3142): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3142): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1289): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/Zygote  ( 3249): MountEmulatedStorage()
,E/Zygote  ( 3249): v2
I/libpersona( 3249): KNOX_SDCARD checking this for 1000
I/libpersona( 3249): KNOX_SDCARD not a persona
,I/SELinux ( 3249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3249 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2191:com.sec.android.app.mt/1000 (adj 15): empty #31,
I/ActivityManager( 1018): Killing 2382:com.sec.android.app.camera/u0a135 (adj 15): empty #32
,I/SELinux ( 3249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3249): TimaSignature is unavailable
,D/ActivityThread( 3249): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 3223): PlaceProvider onCreate()
,I/WebViewFactory( 3069): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 3069): Loading: webviewchromium
,I/LibraryLoader( 3069): Time to load native libraries: 5 ms (timestamps 3286-3291)
I/LibraryLoader( 3069): Expected native library version number "",actual native library version number ""
,I/DBG_FMMDS( 3249): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 27
,I/DBG_FMMDS( 3249): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/UserAnalysis.SecureDbManager( 3223): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3223): SecurePlaceDbHelper() 
D/UserAnalysis( 3223): Create SecureDbHelper
,W/chromium( 3100): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_2366/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_2382/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2191/cgroup.procs: No such file or directory
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/ServiceManager(  315): Waiting for service AtCmdFwd...
D/PCWCLIENTTRACE_DMContentProvider( 3189): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3249): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
I/DBG_FMMDS( 3249): [50.18.150420][Line:43][xdbDBInit] 
,W/art     ( 3100): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 3100): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/AwContents( 3100): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 3100): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3100): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 3100): CordovaWebView is running on device made by: samsung
,D/ScoverManager( 1289): serviceVersion : 16908288
,W/art     ( 3100): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3100): Attempt to remove local handle scope entry from IRT, ignoring
,D/IntelligenceServiceApplication( 3223): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3223): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/art     ( 3069): Attempt to remove local handle scope entry from IRT, ignoring
,D/IntelligenceServiceApplication( 3223): no applications having user consent for prediction
,E/Zygote  ( 3276): MountEmulatedStorage(),
E/Zygote  ( 3276): v2
I/libpersona( 3276): KNOX_SDCARD checking this for 10056
W/ContextImpl( 2979): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/libpersona( 3276): KNOX_SDCARD not a persona
,I/SELinux ( 3276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3276 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/SELinux ( 3276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3276): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 2979): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2979): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/art     (  305): Explicit concurrent mark sweep GC freed 8767(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 25.124ms
,D/TimaKeyStoreProvider( 3276): TimaSignature is unavailable
D/ActivityThread( 3276): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 18.041ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,V/PlaceDetection v1.0.19 ( 3223): [PlaceDetection::stopService] Service stopped.
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.800ms,
,I/DBG_FMMDS( 3249): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,V/PlaceDetection v1.0.19 ( 3223): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3223): Constructor Preference
,I/DBG_FMMDS( 3249): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3249): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3249): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3249): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/DBG_FMMDS( 3249): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3249): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,I/ActivityManager( 1018): Killing 2474:com.android.calendar/u0a131 (adj 15): empty #31
,I/FOTA_Client( 3052): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3052): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3052): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_2474/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 23037(1234KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 22MB/33MB, paused 2.333ms total 196.225ms
,I/ActivityManager( 1018): Killing 2537:com.android.keychain/1000 (adj 15): empty #31
,I/FactoryTestApp( 2508): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2847)  
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/FOTA_Client( 3052): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3331): MountEmulatedStorage(),
E/Zygote  ( 3331): v2
I/libpersona( 3331): KNOX_SDCARD checking this for 10013
I/libpersona( 3331): KNOX_SDCARD not a persona
,I/SELinux ( 3331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3331 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2603:com.mobeam.barcodeService/1000 (adj 15): empty #31
,E/SELinux ( 3331): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/MessageQueue( 2979): Handler (android.os.Handler) {18061306} sending message to a Handler on a dead thread
W/MessageQueue( 2979): java.lang.IllegalStateException: Handler (android.os.Handler) {18061306} sending message to a Handler on a dead thread
W/MessageQueue( 2979): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 2979): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 2979): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 2979): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 2979): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 2979): 	at ffw.a(SourceFile:327)
W/MessageQueue( 2979): 	at guw.a(SourceFile:120)
W/MessageQueue( 2979): 	at guf.c(SourceFile:26)
W/MessageQueue( 2979): 	at gui.run(SourceFile:297)
W/MessageQueue( 2979): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 2979): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 2979): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 2979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager( 1018): Killing 2489:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3331): TimaSignature is unavailable
,D/ActivityThread( 3331): Added TimaKeyStore provider
,V/OneTimeInitializerReceiver( 3331): OneTimeInitializerReceiver.onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,W/ContextImpl( 1790): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1790): Service started flags 0 startId 1
,D/SecUISvc( 1790): Thread created.
,V/OneTimeService( 3331): OneTimeService.onHandleIntent
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/LockPatternUtils( 1289): isSmartCardAuthenticationAvailable: false
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2537/cgroup.procs: No such file or directory
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10052
,D/Settings_Utils( 1289): isSupportVNFestival SM-A300FU XEO
,E/Zygote  ( 3353): MountEmulatedStorage()
E/Zygote  ( 3353): v2
I/libpersona( 3353): KNOX_SDCARD checking this for 10026
I/libpersona( 3353): KNOX_SDCARD not a persona
,I/SELinux ( 3353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3353): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/NetworkUtils( 3069): OkHttp exception
I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3353 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2489/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2603/cgroup.procs: No such file or directory
,W/ResourceType( 1289): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,W/ResourceType( 1289): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,I/sCloudBackupApp( 3276): sCloudBackupApp Version Info : 4.04.7.KK_APP
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3353): TimaSignature is unavailable
D/ActivityThread( 3353): Added TimaKeyStore provider
W/GAV2    ( 3069): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ContactAccountLoggerTas( 3069): canRun() : Opted Out
,W/GAV2    ( 3069): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/Zygote  ( 3369): MountEmulatedStorage()
I/libpersona( 3369): KNOX_SDCARD checking this for 10058
E/Zygote  ( 3369): v2
I/libpersona( 3369): KNOX_SDCARD not a persona
I/ContactAccountLoggerTas( 3069): canRun() : Opted Out
,I/SELinux ( 3369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3369 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2621:flipboard.boxer.app/u0a97 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/SELinux ( 3369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 3369): TimaSignature is unavailable
,D/ActivityThread( 3369): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/ContactLabelSupplier( 3069): get() : OptedIn = false
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/EmergencyMode( 1414): [EmergencyBase] setBootTime
V/EmergencyMode( 1414): [EmergencyFactory] No Recovery State, kill my self.
,E/Zygote  ( 3390): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3390 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 3390): v2
,I/libpersona( 3390): KNOX_SDCARD checking this for 1000
I/libpersona( 3390): KNOX_SDCARD not a persona
,I/SELinux ( 3390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/OpenGLRenderer( 3100): Render dirty regions requested: true
,E/Zygote  ( 3403): MountEmulatedStorage()
E/Zygote  ( 3403): v2
I/libpersona( 3403): KNOX_SDCARD checking this for 1000
I/libpersona( 3403): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3403 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false,
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,D/PhoneWindow( 3100): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3100): *FMB* isFloatingMenuEnabled return false
,D/TimaKeyStoreProvider( 3390): TimaSignature is unavailable
,D/ActivityThread( 3390): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10097/pid_2621/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
I/SELinux ( 3403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ExternalOEMControlProvider( 3369): onCreate
,E/SELinux ( 3403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3403): TimaSignature is unavailable
D/InputDispatcher( 1018): Focus entered window: 3100
,E/Zygote  ( 3418): MountEmulatedStorage()
E/Zygote  ( 3418): v2
I/libpersona( 3418): KNOX_SDCARD checking this for 1000
I/libpersona( 3418): KNOX_SDCARD not a persona
I/SELinux ( 3418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1018): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3418 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 3403): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 2636:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/SRIB_DCS( 3100): log_dcs ThreadedRenderer::initialize entered! 
,I/SELinux ( 3418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/OpenGLRenderer( 3100): Initialized EGL, version 1.4
E/SELinux ( 3418): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1018): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10058
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/OpenGLRenderer( 3100): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3100): Enabling debug mode 0
,D/SettingsProvider( 1018): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10058
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3418): TimaSignature is unavailable
,D/ActivityThread( 3418): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3390): onCreate
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Hs20UtilService( 3390): Starting #1
E/Zygote  ( 3443): MountEmulatedStorage()
I/libpersona( 3443): KNOX_SDCARD checking this for 10018
E/Zygote  ( 3443): v2
I/libpersona( 3443): KNOX_SDCARD not a persona
I/Hs20UtilService( 3390): Message received 5003
I/ActivityManager( 1018): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3443 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
I/SELinux ( 3443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Timeline( 3100): Timeline: Activity_idle id: android.os.BinderProxy@131a3072 time:34138
,W/ResourcesManager( 3418): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Displayed Component not be shown by security: +1s640ms
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2636/cgroup.procs: No such file or directory
D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1018): mDVFSHelper.release()
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3f4b5f0f u0 com.example.hello/.MainActivity t2} time:34148
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/TimaKeyStoreProvider( 3443): TimaSignature is unavailable
,D/ActivityThread( 3443): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3443): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 16:11:45 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/ServiceMode( 3418): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 3418): setReferenceIsDumpState : 0
,I/KLMS-2.5.123: ( 3443): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3443): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3443): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3443): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3443): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 3462): MountEmulatedStorage()
,E/Zygote  ( 3462): v2
I/libpersona( 3462): KNOX_SDCARD checking this for 10020
I/libpersona( 3462): KNOX_SDCARD not a persona
I/SELinux ( 3462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3462 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,I/SELinux ( 3462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3443): KLMSIntentService(): BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/CameraApp( 3403): CameraApp.onCreate()... mFeature : null
I/testFeature( 3403): Feature.Feature(context)
I/testFeature( 3403): Feature.readInternalDefaultXml()
I/testFeature( 3403): ResetFeatureValue
,D/TimaKeyStoreProvider( 3462): TimaSignature is unavailable
,D/ActivityThread( 3462): Added TimaKeyStore provider
,E/Zygote  ( 3478): MountEmulatedStorage()
E/Zygote  ( 3478): v2
I/libpersona( 3478): KNOX_SDCARD checking this for 1000
I/libpersona( 3478): KNOX_SDCARD not a persona
,I/SELinux ( 3478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/CameraFirmware_broadcast( 3403): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3403): CameraApp.getAppFeature()...
,I/SELinux ( 3478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3478 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2655:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SMD     (  289): DCD OFF
,E/Zygote  ( 3492): MountEmulatedStorage()
I/libpersona( 3492): KNOX_SDCARD checking this for 10095
E/Zygote  ( 3492): v2
I/libpersona( 3492): KNOX_SDCARD not a persona
,I/SELinux ( 3492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3492 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2204:com.sec.modem.settings/1000 (adj 15): empty #31
,I/SELinux ( 3492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,D/TimaKeyStoreProvider( 3478): TimaSignature is unavailable
,D/ActivityThread( 3478): Added TimaKeyStore provider
E/SELinux ( 3492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 28
,I/KLMS-2.5.123: ( 3443): KLMSIntentService(): onDestroy()
,I/chromium( 3100): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3100): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/TimaKeyStoreProvider( 3492): TimaSignature is unavailable
,D/ActivityThread( 3492): Added TimaKeyStore provider
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_2655/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2204/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,D/PreloadFilterInstaller( 3492): uses FILTER_DB_VER_1
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/RlzPingService( 3122): Setting next ping for 1450105905984
,E/SQLiteLog( 3492): (284) automatic index on titles(filter_id)
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,D/NPS_WSSNPS( 3478): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3478): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3478): [] Service onCreate!!
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,E/Zygote  ( 3511): MountEmulatedStorage()
,E/Zygote  ( 3511): v2
I/libpersona( 3511): KNOX_SDCARD checking this for 1000
I/libpersona( 3511): KNOX_SDCARD not a persona
,I/SELinux ( 3511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/JsMessageQueue( 3100): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager( 1018): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3511 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3511): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NPS_WSSNPS( 3478): [50.150321] NpsServiceTask Start
,I/SamsungIME( 1774): getCurrentCandidateView
,I/art     (  305): Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 653us total 26.711ms
,D/NPS_WSSNPS( 3478): [50.150321] smlDBHelper
,I/FilterProviderReceiver( 3492): onReceive in FilterProviderReceiver
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/FilterProviderReceiver( 3492): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3511): TimaSignature is unavailable
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.631ms
,D/ActivityThread( 3511): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 17.237ms
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 3530): MountEmulatedStorage(),
E/Zygote  ( 3530): v2
I/libpersona( 3530): KNOX_SDCARD checking this for 10098
I/libpersona( 3530): KNOX_SDCARD not a persona
,I/SELinux ( 3530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3530 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 3530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 2094:flipboard.app/u0a96 (adj 15): empty #31
,E/SELinux ( 3530): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3478): [50.150321] AsyncBulkFlagCheck
,E/Zygote  ( 3545): MountEmulatedStorage()
E/Zygote  ( 3545): v2
I/libpersona( 3545): KNOX_SDCARD checking this for 1000
I/libpersona( 3545): KNOX_SDCARD not a persona
,I/SELinux ( 3545): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3545 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3545): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 2695:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,E/SELinux ( 3545): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/NPS_WSSNPS( 3478): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3478): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3478): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,D/TimaKeyStoreProvider( 3530): TimaSignature is unavailable
,D/ActivityThread( 3530): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,I/chromium( 3100): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3100): 
,D/NPS_WSSNPS( 3478): [50.150321] Service onDestroy
,D/TimaKeyStoreProvider( 3545): TimaSignature is unavailable
D/ActivityThread( 3545): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 2218:com.android.mms/u0a41 (adj 15): empty #31
,I/NPS_WSSNPS( 3478): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3478): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3478): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3478): [50.150321] cpuBooster release : false
,D/NPS_WSSNPS( 3478): [50.150321] dsServerSocket close
,I/ActivityManager( 1018): Killing 2752:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,D/PackageIntentReceiver( 3530): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3530): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SamsungIME( 1774): Dismiss ExpandCandiate
,D/SettingsProvider( 1018): name = access_control_enabled
,D/jxcore_app_log( 3100): JniHelper::setJavaVM(0xb812c448), pthread_self() = -1200167736
,D/JX-Cordova( 3100): jxcore cordova android initializing
,E/Zygote  ( 3567): MountEmulatedStorage()
E/Zygote  ( 3567): v2
I/libpersona( 3567): KNOX_SDCARD checking this for 10099
I/libpersona( 3567): KNOX_SDCARD not a persona
I/SELinux ( 3567): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3567 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3567): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 2763:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,E/SELinux ( 3567): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/MTPRx   ( 3545): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,E/Zygote  ( 3577): MountEmulatedStorage()
E/Zygote  ( 3577): v2
I/libpersona( 3577): KNOX_SDCARD checking this for 10065
I/libpersona( 3577): KNOX_SDCARD not a persona
,I/SELinux ( 3577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 3577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3577 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2784:com.sec.usbsettings/1000 (adj 15): empty #31
E/SELinux ( 3577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
W/jxcore-log( 3100): Initializing JXcore engine
W/jxcore-log( 3100): JXcore engine is ready
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1018): mCursor = null
,D/TimaKeyStoreProvider( 3567): TimaSignature is unavailable
W/jxcore-log( 3100): Starting JXcore engine
,V/MTPRx   ( 3545): sealedState: false
W/libprocessgroup( 1018): failed to open /acct/uid_1101/pid_2695/cgroup.procs: No such file or directory
V/MTPRx   ( 3545): sealedUsbMassStorageState: false
D/ActivityThread( 3567): Added TimaKeyStore provider
,D/SettingsProvider( 1018): name = mtp_usb_connection_status
,D/TimaKeyStoreProvider( 3577): TimaSignature is unavailable
,D/SettingsProvider( 1018): name = media_player_mode
,D/ActivityThread( 3577): Added TimaKeyStore provider
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = mtp_running_status
,D/SettingsProvider( 1018): name = media_mount_count
,D/SettingsProvider( 1018): name = mtp_sync_alive
,D/SettingsProvider( 1018): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = boot_time_connected
,I/SamsungIME( 1774): getDebugLevel  : 0x4f4c
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/LockPatternUtils( 1289): isSmartCardAuthenticationAvailable: false
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/CountryDetector( 1018): No listener is left
,I/PCWCLIENTTRACE_PushUtil( 3189): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3189): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3189): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3189): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3189): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3189): ACTION_BOOTUP - Push type: [SPP, GCM]
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/libprocessgroup( 1018): failed to open /acct/uid_10096/pid_2094/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10043/pid_2752/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10153/pid_2763/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2784/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_2218/cgroup.procs: No such file or directory
,D/FileShare-Server( 3577): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/PCWCLIENTTRACE_PCWHandler( 3189): [ensureRegistration] - netwrok is not available. action ignored
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/audit   ( 1771): type=1400 msg=audit(1449501106.526:203): avc:  denied  { ioctl } for  pid=3100 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1771):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1771): type=1300 msg=audit(1449501106.526:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bef14d58 items=0 ppid=305 ppcomm=main pid=3100 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1771): type=1320 msg=audit(1449501106.526:203): 
E/Zygote  ( 3600): MountEmulatedStorage()
E/Zygote  ( 3600): v2
I/libpersona( 3600): KNOX_SDCARD checking this for 10028
I/libpersona( 3600): KNOX_SDCARD not a persona
I/SELinux ( 3600): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3600 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2677:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,I/SELinux ( 3600): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3600): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3600): TimaSignature is unavailable
,D/ActivityThread( 3600): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10081/pid_2677/cgroup.procs: No such file or directory
,W/jxcore-log( 3100): Platform android
W/jxcore-log( 3100): 
W/jxcore-log( 3100): Process ARCH arm
W/jxcore-log( 3100): 
,I/System.out( 3600): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 3600): Inside WakeupProvider
,I/jxcore-log( 3100): JXcore Cordova bridge is ready!
I/jxcore-log( 3100): 
,W/jxcore-log( 3100): JXcore engine is started
,I/VlingoApplication( 3600): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,D/Finsky  ( 3353): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/SamsungIME( 1774): getDebugLevel  : 0x4f4c
,D/BluetoothAdapter( 3600): 320483442: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3600): 320483442: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3600): 320483442: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3600): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,E/jxcore-log( 3100): >> samsung-SM-A300FU
E/jxcore-log( 3100): 
,I/jxcore-log( 3100): Total memory 1451114496
I/jxcore-log( 3100): 
,I/jxcore-log( 3100): Free memory 20299776
I/jxcore-log( 3100): 
I/jxcore-log( 3100): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3100): 
I/jxcore-log( 3100): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3100): 
,I/jxcore-log( 3100): userPath [ 'www' ]
I/jxcore-log( 3100): 
,I/jxcore-log( 3100): Size 540 960
I/jxcore-log( 3100): 
,I/jxcore-log( 3100): Screen Brightness 255
I/jxcore-log( 3100): 
,E/jxcore-log( 3100): Dummy Error Log.
E/jxcore-log( 3100): 
,I/SamsungIME( 1774): KeybaordView init() : load resources
,W/ContextImpl( 1289): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ContextImpl( 1289): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1289): InitSerachDBThread thread end!
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/SamsungIME( 1774): getCurrentKeyboard
,I/SamsungIME( 1774): getTextKeyboard
,I/ActivityManager( 1018): Killing 2839:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1018): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 29
,E/Zygote  ( 3634): MountEmulatedStorage()
E/Zygote  ( 3634): v2
I/libpersona( 3634): KNOX_SDCARD checking this for 1000
I/libpersona( 3634): KNOX_SDCARD not a persona
,I/SELinux ( 3634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3634 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 3634): TimaSignature is unavailable
,D/ActivityThread( 3634): Added TimaKeyStore provider
,D/SamsungIME( 1774): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2839/cgroup.procs: No such file or directory
,W/ContextImpl( 3634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/Gmail   ( 3567): getAccountsCursor
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3658): MountEmulatedStorage()
,E/Zygote  ( 3658): v2
I/libpersona( 3658): KNOX_SDCARD checking this for 1000
I/libpersona( 3658): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3658 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3658): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/SELinux ( 3658): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3658): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/VlingoApplication( 3600): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3600): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/TimaKeyStoreProvider( 3658): TimaSignature is unavailable
,D/ActivityThread( 3658): Added TimaKeyStore provider
,W/GAV2    ( 3567): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/DialogFlow( 3600): initQueue()
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ResourcesManager( 3658): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ContextImpl( 3658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,I/Gmail   ( 3567): Observing account changes for notifications
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/F_PHONE ( 3658): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone,
W/ContextImpl( 3658): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,E/Zygote  ( 3683): MountEmulatedStorage(),
E/Zygote  ( 3683): v2
I/libpersona( 3683): KNOX_SDCARD checking this for 1000
I/libpersona( 3683): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3683 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone,
I/SELinux ( 3683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/F_PHONE ( 3658): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3658): default registerAction()
I/F_PHONE ( 3658): [[com.sec.bcservice]] sendPendingMessage()
,I/SELinux ( 3683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3353): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/TimaKeyStoreProvider( 3683): TimaSignature is unavailable
,D/ActivityThread( 3683): Added TimaKeyStore provider
,D/FactoryTestApp( 2508): [DummyFtClient$onDestroy](2508) Destroy DummyFtClient service
,W/Settings( 3353): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3353): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4283, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,D/PowerUI ( 1175): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1175): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/jxcore-log( 3100): getBuffer is called!!!!
I/jxcore-log( 3100): 
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 24188(1298KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 12.545ms total 210.942ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3707): MountEmulatedStorage()
,I/libpersona( 3707): KNOX_SDCARD checking this for 10029
E/Zygote  ( 3707): v2
I/libpersona( 3707): KNOX_SDCARD not a persona
I/SELinux ( 3707): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3707): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3707): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3707 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/FactoryTestApp( 2508): [Support$Values.getString](2508) id=MODEL_COMMUNICATION_MODE, value=gsm
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/FactoryTestApp( 2508): [ModuleCommon$isConnectionModeNone](2508) mConnectionMode = gsm
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,I/FactoryTestApp( 2508): [ModuleCommon$isRunningFtClient](2508) RUNNING_FTCLIENT : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 3707): TimaSignature is unavailable
,D/ActivityThread( 3707): Added TimaKeyStore provider
,D/FactoryTestApp( 2508): [DummyFtClient$onDestroy](2508) kill process
,I/Process ( 2508): Sending signal. PID: 2508 SIG: 9
,W/ResourcesManager( 3683): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/Volley  ( 3353): [461] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3353): [468] DiskBasedCache.clear: Cache cleared.
,E/Gmail   ( 3567): Error finding the version of the Email provider.....
E/Gmail   ( 3567): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3567): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3567): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3567): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3567): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3567): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3567): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3567): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3567): We do not support migrating this version of the Email provider.
,D/BluetoothBDAdrressReceiver( 3683): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3683): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/ActivityManager( 1018): Killing 2802:com.sec.dsm.system/1000 (adj 15): empty #31
,W/ResourcesManager( 1453): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1453): onCreate()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/BluetoothBDTestService( 1453): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1453): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1453): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/Ads     ( 3353): Skipping gmscore version check
,D/Finsky  ( 3353): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3353): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3567): getAccountsCursor
,I/ActivityManager( 1018): Process com.sec.factory (pid 2508)(adj 0) has died(28,687)
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2802/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3353): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3634): Resource data:2131165186
,W/ResourcesManager( 3634): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/AMMetaDataParserService( 3634): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3634): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3738): MountEmulatedStorage(),
E/Zygote  ( 3738): v2
I/libpersona( 3738): KNOX_SDCARD checking this for 10102
I/libpersona( 3738): KNOX_SDCARD not a persona
,I/SELinux ( 3738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3738): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3738 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/Finsky  ( 3353): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GoogleHttpClient( 1618): GMS http client unavailable, use old client,
,I/ActivityManager( 1018): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3750 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 3750): MountEmulatedStorage()
I/ActivityManager( 1018): Killing 2857:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
E/Zygote  ( 3750): v2
I/libpersona( 3750): KNOX_SDCARD checking this for 10030
I/libpersona( 3750): KNOX_SDCARD not a persona
,I/SELinux ( 3750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3567): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@8eb1d21 that was originally bound here
E/ActivityThread( 3567): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@8eb1d21 that was originally bound here
E/ActivityThread( 3567): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3567): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3567): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3567): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3567): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3567): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3567): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3567): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3567): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3567): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3567): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3567): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3567): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3567): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3567): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3567): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@2fd53227
E/SELinux ( 3750): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  305): Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 32.896ms
,I/AMMetaDataParserService( 3634): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,E/SQLiteLog( 3567): (283) recovered 17 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 17.126ms
,D/TimaKeyStoreProvider( 3750): TimaSignature is unavailable
,D/ActivityThread( 3750): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.663ms
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom,.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
D/TimaKeyStoreProvider( 3738): TimaSignature is unavailable
D/ActivityThread( 3738): Added TimaKeyStore provider
W/ContextImpl( 3634): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
E/USB_UICC(  297): Timeout! No signal received. Retry num = 30
W/ResourcesManager( 3738): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131034113
,I/AMMetaDataParserService( 3634): getResourceName:com.android.contacts:xml/assistant_main
W/ResourcesManager( 3634): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
W/ResourcesManager( 3634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2857/cgroup.procs: No such file or directory
,E/USB_UICC(  297): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  297): usb_uicc_init_qmi failed ! ,
I/USB_UICC(  297): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  297): usb_uicc_cleanup, Issuing QMI deinit ... 
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3634): took 2.417812ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3634): took 6.200833ms for 0*0 texture 0
,I/GFX raster( 3634): took 9.835678ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e7738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84e7770 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 1.271459ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e7738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84e7770 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,I/art     ( 1618): Explicit concurrent mark sweep GC freed 9576(706KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 7MB/12MB, paused 980us total 44.827ms
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/ActivityManager( 1018): Killing 1559:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/Babel   ( 3738): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3738): MmsConfig.loadMmsSettings
I/Babel   ( 3738): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3738): MmsConfig.loadFromDatabase
,E/File    ( 3567): fail readDirectory() errno=2
,I/Gmail   ( 3567): getAccountsCursor
,I/Gmail   ( 3567): notifyAccountChanged
,I/Gmail   ( 3567): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3567): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager( 1018): Killing 2877:com.google.android.configupdater/u0a82 (adj 15): empty #31
,E/Babel   ( 3738): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3738): MmsConfig.loadFromResources
,E/Babel   ( 3738): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3738): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/Gmail   ( 3567): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3567): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/VideoCapabilities( 3738): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3738): Unsupported mime audio/evrc
,W/AudioCapabilities( 3738): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3738): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3738): Unsupported mime audio/mpeg-L2
,W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_1559/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10082/pid_2877/cgroup.procs: No such file or directory
,I/Gmail   ( 3567): getAccountsCursor
,W/AudioCapabilities( 3738): Unsupported mime audio/x-ms-wma
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioCapabilities( 3738): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3738): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3738): Unsupported mime audio/evrc
,W/Settings( 3738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3634): took 2.425051ms for 0*0 texture 0
,W/ResourcesManager( 3750): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 3750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3750): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/GFX generate_partition_tables( 3634): took 7.528698ms for 0*0 texture 0
,I/GFX raster( 3634): took 10.883958ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb81338f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8509b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 3750): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3738): Unsupported mime video/wvc1
,W/VideoCapabilities( 3738): Unsupported mime video/x-ms-wmv,
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.589062ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84c5638 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb828c5d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ResourcesManager( 3750): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,W/ResourcesManager( 3750): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3738): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3738): Unsupported mime video/wvc1
,W/VideoCapabilities( 3738): Unsupported mime video/x-ms-wmv
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.817500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb8228180 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb828d000 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3738): Unsupported mime video/x-ms-wmv7
,I/AMMetaDataParserService( 3634): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/VideoCapabilities( 3738): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3738): Unsupported mime video/mp43
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/VideoCapabilities( 3738): Unsupported mime video/sorenson
,I/GFX raster( 3634): took 0.701355ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e6d18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84e82c0 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3738): Unsupported mime video/mp4v-esdp
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.673958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb828c5d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8509b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/art     ( 3738): Suspending all threads took: 8.956ms
,I/VideoCapabilities( 3738): Unsupported profile 4 for video/mp4v-es
,V/Babel   ( 3738): babel boot account: SMS
,V/Babel   ( 3738): babel boot account: thalitester@gmail.com
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/FileApkUtils( 1848): Spent 76ms computing apk sha1.,
,D/FileApkUtils( 1848): Module already staged or being staged:chimera-modules/MapsModule.apk,
,I/art     ( 1848): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,E/Zygote  ( 3794): MountEmulatedStorage()
E/Zygote  ( 3794): v2
I/libpersona( 3794): KNOX_SDCARD checking this for 1000
,I/libpersona( 3794): KNOX_SDCARD not a persona
,I/SELinux ( 3794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3794 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3794): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 2911:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/System.out( 3600): INFO:Resource not found:/Common.properties Using default values
D/DexOptUtils( 1848): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1848): Keeping up-to-date module: module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad
,D/TimaKeyStoreProvider( 3794): TimaSignature is unavailable
,W/art     ( 1848): Suspending all threads took: 9.692ms
D/ActivityThread( 3794): Added TimaKeyStore provider
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.540052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb828d000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8132a28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2911/cgroup.procs: No such file or directory
,E/Zygote  ( 3812): MountEmulatedStorage()
,E/Zygote  ( 3812): v2
I/libpersona( 3812): KNOX_SDCARD checking this for 1000
I/libpersona( 3812): KNOX_SDCARD not a persona
I/SELinux ( 3812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/art     ( 3600): Suspending all threads took: 10.119ms
,I/SELinux ( 3812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3812): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131034113
,I/AMMetaDataParserService( 3634): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3812 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/GFX raster( 3634): took 0.848594ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e7738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8509b00 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1018): Killing 2929:com.dropbox.android/u0a88 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3812): TimaSignature is unavailable
,D/ActivityThread( 3812): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3634): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/GmsModuleFndr( 1848): Beginning GMS chimera module scan
,E/KnoxSetupWizardClient( 3812): isShipMode : 1
I/KnoxSetupWizardClient( 3812): onReceive : android.intent.action.BOOT_COMPLETED
,E/SMD     (  289): DCD OFF
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.996147ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e7738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84e82c0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1018): failed to open /acct/uid_10088/pid_2929/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3634): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/ShortcutReceiver( 3812):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.601250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb81338f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8132a28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/GmsModuleFndr( 1848): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 1848): Beginning module configuration check
,D/ChimeraCfgMgr( 1848): Module APKs unchanged, check complete
,D/KnoxShortcutUtil( 3812): getIsShortcutMigrationFor_2_3_0_Done true
,W/ResourcesManager( 3707): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ShortcutReceiver( 3812):  KnoxContainerVersion 2.3.0
,D/ShortcutReceiver( 3812):  shortcut migration not required 
,W/System.err( 3812): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3812): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3812): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3812): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3812): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3812): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3812): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3844): MountEmulatedStorage()
,E/Zygote  ( 3844): v2
I/libpersona( 3844): KNOX_SDCARD checking this for 1000
I/libpersona( 3844): KNOX_SDCARD not a persona
,I/SELinux ( 3844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3844 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1018): Killing 2960:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/SELinux ( 3844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3844): TimaSignature is unavailable
E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityThread( 3844): Added TimaKeyStore provider
I/GFX raster( 3634): took 0.720938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84c5638 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84e82c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourcesManager( 3707): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3707): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/GFX raster( 3634): took 0.861510ms for 96*96 texture 0
W/ResourcesManager( 3707): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb8228180 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8509b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/StatusChecker( 3844): onReceive : android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1018): failed to open /acct/uid_10146/pid_2960/cgroup.procs: No such file or directory
,I/Icing   ( 1848): Storage manager: low false usage 2.01MB avail 8.51GB capacity 9.90GB
,I/StatusChecker( 3844): onReceive : net.mt.init : DONE
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3634): took 0.638438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e6d18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8132a28 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3865 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,E/Zygote  ( 3865): MountEmulatedStorage()
I/libpersona( 3865): KNOX_SDCARD checking this for 10113
E/Zygote  ( 3865): v2
I/libpersona( 3865): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/SELinux ( 3865): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3865): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 3008:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
E/SELinux ( 3865): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Process ( 3750): Sending signal. PID: 3750 SIG: 9
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.708542ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb828c5d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84e82c0 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3634): took 0.544271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb828d000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8509b00 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3865): TimaSignature is unavailable
,I/AMMetaDataParserService( 3634): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/ActivityThread( 3865): Added TimaKeyStore provider
,I/ActivityManager( 1018): Process com.sec.android.app.sns3 (pid 3750)(adj 0) has died(39,676)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3882): MountEmulatedStorage()
,E/Zygote  ( 3882): v2
I/libpersona( 3882): KNOX_SDCARD checking this for 10031
I/libpersona( 3882): KNOX_SDCARD not a persona
,I/SELinux ( 3882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3882 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/libprocessgroup( 1018): failed to open /acct/uid_10088/pid_3008/cgroup.procs: No such file or directory
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1848): COMPAT: Multi user not supported
I/PageBuddyNotiSvc( 3865): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1618): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3882): TimaSignature is unavailable
,D/ActivityThread( 3882): Added TimaKeyStore provider
I/AMMetaDataParserService( 3634): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3634): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3634): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131034112
,I/AMMetaDataParserService( 3634): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 3865): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/PageBuddyNotiSvc( 3865): onCreate mCpBitFlag=0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GFX raster( 3634): took 0.732863ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84c5638 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84dd8f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1848): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3902 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/AMMetaDataParserService( 3634): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
E/Zygote  ( 3902): MountEmulatedStorage()
E/Zygote  ( 3902): v2
I/libpersona( 3902): KNOX_SDCARD checking this for 10121
I/libpersona( 3902): KNOX_SDCARD not a persona
,I/SELinux ( 3902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1584): DispatchingService.onCreate()
,I/SELinux ( 3902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.680052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84c5638 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8132a28 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3902): TimaSignature is unavailable
,D/ActivityThread( 3902): Added TimaKeyStore provider
,I/CheckinService( 1848): Checkin interval check for package: unspecified last checkin: 1449011761246 min interval config: 0 actual interval: 489348027
,I/AMMetaDataParserService( 3634): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,W/ResourcesManager( 3902): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3902): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3902): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.782500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e82c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8509b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/CheckinService( 1848): Disabling old GoogleServicesFramework version
,I/AMMetaDataParserService( 3634): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.655989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e6d18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84dd8f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 3026): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/DBG_POLICYDM( 3026): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/libpersona( 3923): KNOX_SDCARD checking this for 10032
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/libpersona( 3923): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131034113
I/AMMetaDataParserService( 3634): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3634): took 1.858229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e7738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84dd8f8 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 3923): MountEmulatedStorage()
E/Zygote  ( 3923): v2
I/SELinux ( 3923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3923): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3923 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3142:com.fmm.dm/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3634): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 3923): TimaSignature is unavailable
,D/ActivityThread( 3923): Added TimaKeyStore provider
,D/QuickConnect( 3902): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/CheckinService( 1848): Checking schedule, now: 1449501109458 next: 1449578688177,
I/CheckinService( 1848): active receiver: disabled
,D/SettingsProvider( 1018): name = scon_is_running
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10121
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.817917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e7738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84e1318 counterpartCT=4 counterpartW=96 counterparth=96
,D/QuickConnect( 3902): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 3902): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/AMMetaDataParserService( 3634): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/SystemUpdateService( 1848): onCreate
,I/GCoreUlr( 1584): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/QuickConnect( 3902): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3940): MountEmulatedStorage()
I/libpersona( 3940): KNOX_SDCARD checking this for 10127
E/Zygote  ( 3940): v2
I/libpersona( 3940): KNOX_SDCARD not a persona
,I/SELinux ( 3940): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3940): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3940): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3940 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3165:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3142/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3940): TimaSignature is unavailable
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.601615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb828c5d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb828d000 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 3940): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3634): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/SystemUpdateService( 1848): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/ResourcesManager( 3940): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3940): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3940): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3940): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/AuthZen ( 1848): Handling intent: android.intent.action.BOOT_COMPLETED
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.707448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84c5638 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84e1318 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/libprocessgroup( 1018): failed to open /acct/uid_10090/pid_3165/cgroup.procs: No such file or directory
,D/AuthZenEventHandler( 1848): Handling event: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 1848): cancelUpdate (empty URL)
I/SystemUpdateService( 1848): active receiver: disabled
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 29578(1800KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/33MB, paused 2.616ms total 163.904ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.810677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb828d000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84cce20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3634): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/SBrowserFeatureFlag( 3940): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 3940): onCreate()
,E/SPPClientService( 3923): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 3923): [PushClientApplication] Push log off : This is Ship build version
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3634): took 0.670468ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84c1db0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84e82c0 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 3923): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/NetworkSettingsReceiver( 3940): onReceive: android.intent.action.BOOT_COMPLETED
,D/SPPClientService( 3923): PushLog.txt file is not deleted.
,D/SPPClientService( 3923): PushLog.txt file is not deleted.
,D/SPPClientService( 3923): ============PushLog. stop!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/GFX raster( 3634): took 0.756043ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e1318 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81338f8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/art     ( 1848): Background sticky concurrent mark sweep GC freed 11612(1007KB) AllocSpace objects, 16(256KB) LOS objects, 14% free, 7MB/9MB, paused 8.394ms total 129.035ms
,D/ChimeraCfgMgr( 1848): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/Zygote  ( 3972): MountEmulatedStorage()
E/Zygote  ( 3972): v2
I/libpersona( 3972): KNOX_SDCARD checking this for 10036
I/libpersona( 3972): KNOX_SDCARD not a persona
,I/SELinux ( 3972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=3972 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3972): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 3223:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,W/System.err( 3940): java.lang.NoSuchMethodException: isEnabled []
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/System.err( 3940): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 3940): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 3940): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 3940): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 3940): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 3940): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 3940): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 3940): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 3940): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 3940): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 3940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3940): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3940): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 3940): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3940): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3940): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3940): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/GFX raster( 3634): took 0.532604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84f3cb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84cce20 counterpartCT=4 counterpartW=96 counterparth=96
,W/BaseAppContext( 1848): Using Auth Proxy for data requests.
,E/SBrowserFeatureFlag( 3940): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3e60c93c
,D/TimaKeyStoreProvider( 3972): TimaSignature is unavailable
,D/ActivityThread( 3972): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3634): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SBrowserFeatureFlag( 3940): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3940): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3634): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3991): MountEmulatedStorage()
E/Zygote  ( 3991): v2
I/libpersona( 3991): KNOX_SDCARD checking this for 10131
I/libpersona( 3991): KNOX_SDCARD not a persona
,I/SELinux ( 3991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3991 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
I/ActivityManager( 1018): Killing 3249:com.fmm.ds/1000 (adj 15): empty #31
I/SELinux ( 3991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3991): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3991): TimaSignature is unavailable
,D/ActivityThread( 3991): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SystemUpdateService( 1848): onDestroy
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634,): Resource data:2131165203
W/ResourcesManager( 3634): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX construct_block_size_descriptor_2d second part( 3634): took 3.729062ms for 0*0 texture 0
D/ChimeraCfgMgr( 1848): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ResourcesManager( 3991): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3991): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3991): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GFX generate_partition_tables( 3634): took 19.041876ms for 0*0 texture 0
,I/GFX raster( 3634): took 23.376927ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb86bec98 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb84e68f0 counterpartCT=4 counterpartW=80 counterparth=80
,W/GCoreFlp( 1584): No location to return for getLastLocation()
,W/FusedLocationProvider( 1848): location=null
,I/AMMetaDataParserService( 3634): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,W/libprocessgroup( 1018): failed to open /acct/uid_10055/pid_3223/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3249/cgroup.procs: No such file or directory
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1584): No location to return for getLastLocation()
,W/FusedLocationProvider( 1848): location=null
,W/Kids    ( 1848): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 1848): [KidAccountFixer] No network connection
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3634): took 2.110781ms for 0*0 texture 0
,W/Auth    ( 1618): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/GFX generate_partition_tables( 3634): took 5.267709ms for 0*0 texture 0
,I/GFX raster( 3634): took 8.393803ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e68f0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb88564d0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3634): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1848): Fetching signing key...
,D/daemonapp( 1733): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1848): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PersistentNotificationBroadcastReceiver( 1618): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/GCoreUlr( 1584): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/GCoreUlr( 1584): Unbound from all location providers
,I/AuthZen ( 1848): Signing key fetched successfully!
,W/BaseAppContext( 1848): Using Auth Proxy for data requests.
,I/SA      ( 3972): [SSP] onCreated
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3634): took 0.682917ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e68f0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb88564d0 counterpartCT=4 counterpartW=80 counterparth=80
I/SA      ( 3972): [TPM] There is no property file
I/AMMetaDataParserService( 3634): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/Zygote  ( 4028): MountEmulatedStorage()
E/Zygote  ( 4028): v2
I/libpersona( 4028): KNOX_SDCARD checking this for 10037
I/libpersona( 4028): KNOX_SDCARD not a persona
,I/SELinux ( 4028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4028 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/SA      ( 3972): [SCU] isHaveSA() - false
I/art     ( 1618): Explicit concurrent mark sweep GC freed 7642(428KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/13MB, paused 1.287ms total 62.269ms
E/SELinux ( 4028): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SA      ( 3972): [TPM] getModelProperty : null
I/SA      ( 3972): [TPM] getCSCProperty : null
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SA      ( 3972): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 3972): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 3972): [DM] TFT FEATURE: false
,I/SA      ( 3972): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 3972): [DM] init START
,I/SA      ( 3972): [DM] This device is not a Vodafone
,I/art     (  305): Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 22.986ms
,D/TimaKeyStoreProvider( 4028): TimaSignature is unavailable
,D/ActivityThread( 4028): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 16.752ms
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3634): took 0.764638ms for 80*80 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb84e68f0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb88564d0 counterpartCT=4 counterpartW=80 counterparth=80
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.437ms
,I/AMMetaDataParserService( 3634): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/Zygote  ( 4044): MountEmulatedStorage()
E/Zygote  ( 4044): v2
,I/libpersona( 4044): KNOX_SDCARD checking this for 10135
I/libpersona( 4044): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4044 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/SELinux ( 4044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 3972): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 3972): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 3972): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 3972): No package identifier when getting value for resource number 0x00000000,
W/ResourceType( 3972): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 3972): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 3972): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 3972): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 3972): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75),
W/ResourceType( 3972): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 3972): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 3972): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,W/ResourceType( 3972): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 3972): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/GFX raster( 3634): took 0.619687ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb88564d0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8854f68 counterpartCT=4 counterpartW=80 counterparth=80
,D/a       ( 1848): Opening database auth.proximity.permit_store...
,I/SA      ( 3972): [SCU] isHaveSA() - false
I/SA      ( 3972): support phone number id : false
I/SA      ( 3972): [DM] Supports Ref Jpn : true
I/SA      ( 3972): [DM] init END
,D/TimaKeyStoreProvider( 4044): TimaSignature is unavailable
D/ActivityThread( 4044): Added TimaKeyStore provider
,I/Icing   ( 1848): updateResources: need to parse f{com.google.android.gms}
I/AMMetaDataParserService( 3634): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
I/SA      ( 3972): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 3972): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/AuthZenTransactionCache( 1848): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1848): Clearing transaction cache
W/ResourcesManager( 4028): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 3972): [OR] onReceive END
,W/ResourcesManager( 4044): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4044): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4044): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4044): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4044): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SA      ( 3972): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 3972): [ODM] queryOpenData(key= GEO_IP )
,I/GCoreUlr( 1584): DispatchingService.onDestroy()
I/GCoreUlr( 1584): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1584): Unbound from all location providers
,I/CalendarProvider2( 4028): CalendarProvider2.onCreate() called
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 3276:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,I/SA      ( 3972): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 3972): [LBE] REF_JPN : true
I/SA      ( 3972): [BDC] create
,I/GAV2    ( 3069): Thread[GAThread,5,main]: No campaign data found.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4064): MountEmulatedStorage()
E/Zygote  ( 4064): v2
I/libpersona( 4064): KNOX_SDCARD checking this for 10141
I/libpersona( 4064): KNOX_SDCARD not a persona
,I/SELinux ( 4064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4064 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/SELinux ( 4064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4064): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 3972): [DBMV2] getEmailID
,D/TimaKeyStoreProvider( 4064): TimaSignature is unavailable
,D/ActivityThread( 4064): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10056/pid_3276/cgroup.procs: No such file or directory
,I/SA      ( 3972): [DBMV2] getDataV02ForItems
I/SA      ( 3972): [SSP] query invoked
,I/SA      ( 3972): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 3972): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 3972): [BDC] destroy
,I/ActivityManager( 1018): Killing 3052:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,W/ResourcesManager( 4064): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4064): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4064): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4064): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3634): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3634): took 0.619010ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3634): Bitmap=0xb88564d0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb84e0380 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3634): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,W/libprocessgroup( 1018): failed to open /acct/uid_10008/pid_3052/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 3331:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3634): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131099648
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ResourcesManager( 3634): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 3634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/libprocessgroup( 1018): failed to open /acct/uid_10013/pid_3331/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3634): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3634): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId,
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3634): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1175 (0x0)
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/AMMetaDataParserService( 3634): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131099648
,I/AMMetaDataParserService( 3634): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4091): MountEmulatedStorage()
E/Zygote  ( 4091): v2
I/libpersona( 4091): KNOX_SDCARD checking this for 10068
I/libpersona( 4091): KNOX_SDCARD not a persona
I/SELinux ( 4091): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4091 uid=10068 gids={50068, 9997} abi=armeabi-v7a
I/SELinux ( 4091): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4091): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4091): TimaSignature is unavailable
,D/ActivityThread( 4091): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3634): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 4091): onCreate
D/BadgeProvider( 4091): DatabaseHelper
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 4091): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/Icing   ( 1848): Internal init done: storage state 0
,D/SSRM:n  ( 1018): SIOP:: AP = 410
,D/BadgeProvider( 4091): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4091): sendNotify, [notify] : null
D/BadgeProvider( 4091): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4091): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4091): update, [UpdateCount] : 1
,D/Launcher.Model( 1476): reloadBadges entered.
,I/Icing   ( 1848): Post-init done
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3634): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4114): MountEmulatedStorage(),
,I/libpersona( 4114): KNOX_SDCARD checking this for 10142,
,E/Zygote  ( 4114): v2
I/libpersona( 4114): KNOX_SDCARD not a persona
I/SELinux ( 4114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4114 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3369:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
I/SELinux ( 4114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/AMMetaDataParserService( 3634): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/SELinux ( 4114): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/ActivityManager( 1018): Killing 3403:com.sec.factory.camera/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131099648
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4114): TimaSignature is unavailable
,D/ActivityThread( 4114): Added TimaKeyStore provider
,W/ResourcesManager( 4114): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/AMMetaDataParserService( 3634): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1018): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/Process ( 4064): Sending signal. PID: 4064 SIG: 9,
,I/AMMetaDataParserService( 3634): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3403/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10058/pid_3369/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3634): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4131): MountEmulatedStorage(),
E/Zygote  ( 4131): v2
I/libpersona( 4131): KNOX_SDCARD checking this for 1000
,I/SELinux ( 4131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4131): KNOX_SDCARD not a persona
,I/SELinux ( 4131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4131): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131099648
I/ActivityManager( 1018): Process com.android.email (pid 4064)(adj 9) has died(30,663)
,I/AMMetaDataParserService( 3634): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3634): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/Zygote  ( 4146): MountEmulatedStorage()
,E/Zygote  ( 4146): v2
I/libpersona( 4146): KNOX_SDCARD checking this for 10141
I/libpersona( 4146): KNOX_SDCARD not a persona
,I/SELinux ( 4146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3634): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ActivityManager( 1018): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4146 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4146): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4131): TimaSignature is unavailable
,D/ActivityThread( 4131): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3634): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4146): TimaSignature is unavailable
,D/ActivityThread( 4146): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
I/ActivityManager( 1018): Killing 3418:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3634): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ResourcesManager( 4146): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4146): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4146): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4146): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131099648
,I/AMMetaDataParserService( 3634): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 3462:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3634): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
W/ActivityManager( 1018): userId = 0, bbcId = -10000
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
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131099648
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3634): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3634): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3634): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3634): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 25860(1450KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/33MB, paused 2.214ms total 148.666ms
I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1018): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131165197
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ResourcesManager( 3634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3634): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3634): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1584): callingUid 10011, callindPid: 1584
,E/MDM     ( 1584): [156] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3634): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/LocationInitializer( 1848): Restart initialization of location
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131165197
,I/AMMetaDataParserService( 3634): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,D/BadgeProvider( 4091): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/GCM     ( 1618): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Process ( 4114): Sending signal. PID: 4114 SIG: 9
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 4028): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3634): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/BluetoothAdapter( 3100): disable()
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3634): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/AuthorizationBluetoothService( 1618): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/BluetoothManagerService( 1018): Bluetooth is already disabled. DO NOT disable again.
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
D/BadgeProvider( 4091): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4091): sendNotify, [notify] : null
,D/BadgeProvider( 4091): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4091): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4091): update, [UpdateCount] : 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 3492:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/AlarmManager( 1018): waitForAlarm result :8
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Launcher.Model( 1476): reloadBadges entered.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1584): No location to return for getLastLocation()
,W/FusedLocationProvider( 1618): location=null
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: false pid=3100, uid=10333
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131165197
,D/SettingsProvider( 1018): name = wifi_on
V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3100): ****TEST TOOK:  5073  ms ****
I/jxcore-log( 3100): 
,I/AMMetaDataParserService( 3634): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,I/jxcore-log( 3100): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3100): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SMD     (  289): DCD OFF
I/ActivityManager( 1018): Process com.android.exchange (pid 4114)(adj 11) has died(30,664)
,I/AMMetaDataParserService( 3634): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3418/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3634): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
W/libprocessgroup( 1018): failed to open /acct/uid_10020/pid_3462/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10095/pid_3492/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1848): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity,
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3634): getResourcePackageName:android.wallpaper.preview
W/ContextImpl( 3634): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.wallpaper.preview,
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
I/AMMetaDataParserService( 3634): Resource data:2131099648
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 3634): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ResourcesManager( 3634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3634): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SIP     ( 1453): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1453): fail readDirectory() errno=2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3634): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
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
,I/AMMetaDataParserService( 3634): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/Zygote  ( 4187): MountEmulatedStorage()
,E/Zygote  ( 4187): v2
I/libpersona( 4187): KNOX_SDCARD checking this for 10041
,I/libpersona( 4187): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.widget.MmsWidgetProvider: pid=4187 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
I/SELinux ( 4187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 4187): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
W/ContextImpl( 3634): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/GAV2    ( 3567): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 4187): TimaSignature is unavailable
,D/ActivityThread( 4187): Added TimaKeyStore provider
,I/iu.UploadsManager( 1848): End new media; added: 0, uploading: 0, time: 118 ms,
,D/AndroidRuntime( 4178): 
D/AndroidRuntime( 4178): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,W/ResourcesManager( 4187): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/AndroidRuntime( 4178): CheckJNI is OFF
,D/AndroidRuntime( 4178): readGMSProperty: start
D/AndroidRuntime( 4178): readGMSProperty: already setted!!
D/AndroidRuntime( 4178): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4178): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4178): readGMSProperty: end
D/AndroidRuntime( 4178): addProductProperty: start
W/ResourcesManager( 4187): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4187): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4187): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4187): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.GridSettings
W/ResourcesManager( 3634): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
W/ResourcesManager( 3634): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): getResourcePackageName:assistant
W/ResourcesManager( 3634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): Resource data:2131165220
W/ResourcesManager( 3634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): getResourceName:com.android.settings:xml/assistant
W/ResourcesManager( 3634): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3634): getResourceTypeNamexml
,I/AMMetaDataParserService( 3634): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,D/Mms/MmsApp( 4187): [start]    onCreate() consume time = 0.0
,I/AMMetaDataParserService( 3634): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
,I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ContextImpl( 3634): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
,I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/ActivityManager( 1018): Waited long enough for: ServiceRecord{1db6522c u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings,.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.androi,d.settings.DockSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/PackageManager( 1018): START PACKAGE DELETE: observer{77804524}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/PackageManager( 1018): !@killApplicatoin: 10333, uninstall pkg
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/ActivityManager( 1018): Killing 3100:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3634): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3634): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3634): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
E/AffinityControl( 4178): AffinityControl: registerfunction enter
D/AndroidRuntime( 4178): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
W/art     ( 4187): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 12,8.898ms
,I/WindowState( 1018): WIN DEATH: Window{3cf0717f u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
,W/PackageSettings( 1018): Skipping PackageSetting{16724095 com.test.thalitest/10326} due to missing metadata
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
,D/InputDispatcher( 1018): Focus left window: 3100
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/Mms/ArtClassLoader( 4187): init before art
,D/Mms/TelephonyPermission( 4187): start operation mode monitor
,W/ActivityManager( 1018): Force removing ActivityRecord{3f4b5f0f u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1018): Focused application set to: xxxx
,W/ResourcesManager( 4187): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,W/ActivityManager( 1018): Spurious death for ProcessRecord{7d733b5 3100:com.example.hello/u0a333}, curProc for 3100: null
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=0: pkg removed
,D/Mms/TelephonyPermission( 4187): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4187): isDefault true
,D/Mms/MmsApp( 4187): onCreate() com.android.mms
,D/Launcher( 1476): onRestart, Launcher: 1046530364
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,D/Launcher( 1476): onStart, Launcher: 1046530364
,D/Launcher.HomeView( 1476): onStart
,D/Launcher( 1476): onResume, Launcher: 1046530364
,D/SettingsProvider( 1018): name = kids_home_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10006
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/Launcher.HomeView( 1476): onResume
,D/Mms/MmsApp( 4187): [start]    initCountryIso consume time = 331.635676
,D/CountryDetector( 1018): The first listener is added
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/Mms/MmsApp( 4187): [end]    initCountryIso consume time = 14.411823
,D/Mms/MmsConfig( 4187): [start]    MmsConfig.init() consume time = 0.100157
,W/GeofencerStateMachine( 1584): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 1774): mOCRHelper is null
,W/ResourcesManager( 1453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/MmsConfig( 4187): before partial update
,D/MenuAppsGridFragment( 1476): onResume
,D/ActivityManager( 1018): handle home activity for 0
,I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/Mms/MmsConfig( 4187): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4187): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4187): isAuth is false
,D/Mms/MmsConfig( 4187): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1018): Focus entered window: 1476
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1476): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/TP/MmsSmsProvider( 1453): query,matched:2117, calling pid = 4187
,D/TP/MmsSmsProvider( 1453): match 2117:Elapsed time : 1.758 ms
,D/EasySignUpManager_1.0.1( 4187): isAuth is false
D/EasySignUpManager_1.0.1( 4187): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4187): mps_code.dat does not exist
E/CscParser( 4187): customer_path =/system/csc/customer.xml
E/CscParser( 4187): fileName + /system/csc/customer.xml
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/Mms/ArtClassLoader( 4187): init [DONE] art
,E/CscParser( 4187): mps_code.dat does not exist
E/CscParser( 4187): customer_path =/system/csc/customer.xml
E/CscParser( 4187): fileName + /system/csc/customer.xml
,D/CscParser( 4187): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4187):  enable multiwindow = false
,D/RegisteredServicesCache( 1438): empty dynamic service
,E/Mms/MessageUtils( 4187): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4187): updateCountryIso : update country iso info 
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10333
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,D/Mms/MmsConfig( 4187): [end]    init() consume time = 222.705677
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/Mms/Contact( 4187): [start]    init() consume time = 4.237864
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=2_task.xml
,D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,D/Mms/Contact( 4187): [end]    init consume time = 15.921406
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 3100 uid 10333
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TP/MmsSmsProvider( 1453): query,matched:13, calling pid = 4187
,D/TP/MmsSmsProvider( 1453): match 13:Elapsed time : 1.413 ms
,D/SensorService( 1018): [SO] activate (ident=0xb88fc188, enabled=0)
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SamsungIME( 1774): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/Mms/DraftCache( 4187): [start]    rebuildCache consume time = 19.557709
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb88fc188, enabled=1)
D/SensorService( 1018): [SO] AR_init,
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/Mms/MethodReflector( 4187): getSubId is called
D/Mms/TelephonyUtils( 4187): getLongSubId from simSlot 0, return Value = -1,
D/TP/MmsSmsProvider( 1453): query,matched:12, calling pid = 4187,
D/Mms/MethodReflector( 4187): getTelephonyProperty is called
D/Mms/DownloadManager( 4187): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4187): [NotificationTransaction] getAutoDownloadState simSlot : 0,
D/Mms/DownloadManager( 4187): auto download without roaming -> true
,D/Mms/DownloadManager( 4187): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4187): getSubId is called
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/Mms/MethodReflector( 4187): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 4187): subID is null or 0 length, so get DefaultSubId!!
D/TP/MmsSmsProvider( 1453): match 12:Elapsed time : 4.402 ms
D/Mms/TelephonyUtils( 4187): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4187): getTelephonyProperty is called
,D/Mms/DownloadManager( 4187): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4187): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4187): auto download without roaming -> true
D/Mms/DownloadManager( 4187): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
,D/Mms/DownloadManager( 4187): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4187): mAutoDownload ------> true
D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10333
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms,
D/Mms/DraftCache( 4187): [end]    rebuildCache consume time = 33.235885
,D/ComposerPerformance( 4187): 1449501112879 ms / [DONE] Composer constructor
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,E/CII     ( 4187): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4187): ReservationManager()
I/Mms/ReservationManager( 4187): resetAfterConnected()
,D/Mms/Conversation( 4187): [start]    init() consume time = 20.554323
,D/TP/MmsSmsProvider( 1453): query,matched:7, calling pid = 4187
,D/TP/MmsSmsProvider( 1453): deleteConversation threadId: 9223372036854775807
,W/TextServicesManagerService( 1018): no available spell checker services found
,D/TP/MmsSmsProvider( 1453): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,D/TP/MmsSmsProvider( 1453): match 7:Elapsed time : 15.667 ms
,V/TP/MmsSmsDatabaseHelper( 1453): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1453): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1453): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
,D/Mms/Conversation( 4187): [end]    init consume time = 36.404219
,I/Mms/ReservationManager( 4187): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MessagingNotification( 4187): [start]    init() consume time = 8.637604
,I/ActivityManager( 1018): Displayed Component not be shown by security: +442ms
,D/Mms/MessagingNotification( 4187): [end]    init consume time = 12.709323
,D/TP/MmsSmsProvider( 1453): query,matched:0, calling pid = 4187
,V/TP/MmsSmsProvider( 1453): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1453): match 0:Elapsed time : 1.728 ms
,D/Mms/SpamFilter( 4187): [start]    SpamFilter fill() begin consume time = 6.02
,D/Mms/Synchronizer( 4187): [start]    doSync consume time = 0.972708
,D/TP/MmsSmsProvider( 1453): query,matched:400, calling pid = 4187
,D/TP/MmsSmsProvider( 1453): update, matched:300, calling pid = 4187
V/TP/MmsSmsProvider( 1453): syncDBData start
,D/Mms/SpamFilter( 4187): [end]    SpamFilter fill() finished consume time = 5.961771
V/TP/MmsSmsProvider( 1453): syncDBData sms end
,V/TP/MmsSmsProvider( 1453): syncDBData mms end
,V/TP/MmsSmsProvider( 1453): syncDBData end
,D/Mms/Synchronizer( 4187): [end]    doSync consume time = 7.53776
,D/Mms/MmsApp( 4187): [end]    onCreate() consume time = 4.073959
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/MessagingNotification( 4187): checkBadgeCount unreadCount=0 badgeCount=0
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 32842(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 22MB/33MB, paused 12ms total 352.173ms
,D/TP/SmsProvider( 1453): query,matched:26, calling pid = 4187
,D/TP/SmsProvider( 1453): match 26:Elapsed time : 1.783 ms
,D/Mms/DownloadManager( 4187): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4187): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 4187): getSubId is called
D/Mms/TelephonyUtils( 4187): getLongSubId from simSlot 0, return Value = -1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
D/Mms/MethodReflector( 4187): getTelephonyProperty is called
D/Mms/DownloadManager( 4187): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4187): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4187): auto download without roaming -> true
D/Mms/DownloadManager( 4187): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4187): mAutoDownload ------> true
,I/ActivityManager( 1018): Killing 3122:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): delete codoeFile: 
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
I/AASA_removePackage( 1018): UID=10333 Target=com.example.hello
,W/ActivityManager( 1018): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/PackageManager( 1018): result of delete: 1{77804524}
,D/AndroidRuntime( 4178): Shutting down VM
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/TP/MmsSmsProvider( 1453): query,matched:6, calling pid = 4187
,D/TP/MmsSmsProvider( 1453): match 6:Elapsed time : 4.101 ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,I/DBG_DM  ( 2947): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4233): MountEmulatedStorage()
I/libpersona( 4233): KNOX_SDCARD checking this for 10023
E/Zygote  ( 4233): v2
I/libpersona( 4233): KNOX_SDCARD not a persona
,I/SELinux ( 4233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 4233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4233): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4233 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1018): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4233): TimaSignature is unavailable
,D/ActivityThread( 4233): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1584): [157] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1018): Killing 3478:com.wssnps/1000 (adj 15): empty #31
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 4178): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SensorService( 1018): [SO] currT = 41671041000, prevT = 41181133000, diff = 489908000, [-0.421 0.019 9.883]
,D/SensorService( 1018): [SO] -0.421 0.019 9.883
D/SensorService( 1018): [SO] [100 -> 255]
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1848): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_3122/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3478/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 4233): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,D/GCM     ( 1618): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/FileUtils( 2715): Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
D/AuthorizationBluetoothService( 1618): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{30de5d9f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:41751
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,D/Mms/Omacp( 4187): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
,E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): ,	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SharedPreferencesImpl( 2301): Couldn't rename file /data/data/com.android.contacts/shared_prefs/com.android.contacts_preferences.xml to backup file /data/data/com.android.contacts/shared_prefs/com.android.contacts_preferences.xml.bak
,E/SharedPreferencesImpl( 2301): Couldn't rename file /data/data/com.android.contacts/shared_prefs/com.android.contacts_preferences.xml to backup file /data/data/com.android.contacts/shared_prefs/com.android.contacts_preferences.xml.bak
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
V/GLSActivity( 1618): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,D/Mms/Contact( 4187): sContactsObserver.onChange(),selfUpdate=false
,I/ValidateNoPeople( 1018): mEvictionCount: 0
E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
D/Mms/Contact( 4187): performUpdate:widgetCount=0
I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,D/Mms/ContactsCache( 4187): [start]    invalidate() consume time = 418.78125
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,D/Mms/ContactsCache( 4187): [end]    invalidate() consume time = 2.705364
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
I/OMACP   ( 4233): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1584): No location to return for getLastLocation()
E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,W/FusedLocationProvider( 1618): location=null
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
V/GmsCoreStatsServiceLauncher( 1848): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2715): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2715): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2715): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2715): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2715): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2715): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)

```
