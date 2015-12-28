#### Test 503880191ec81a5_thali08_samsung-SM-A300FU Logs


```
--------- beginning of system
I/ActivityManager( 1015): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3023 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
--------- beginning of main
I/CscUpdateService( 1455): same CSC Version
D/CscUtil ( 1455): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
I/SELinux ( 3023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TP/SmsProvider( 1455): query,matched:0, calling pid = 2346
D/TimaKeyStoreProvider( 3005): TimaSignature is unavailable
D/ActivityThread( 3005): Added TimaKeyStore provider
D/TP/SmsProvider( 1455): match 0:Elapsed time : 0.849 ms
D/TimaKeyStoreProvider( 3023): TimaSignature is unavailable
D/ActivityThread( 3023): Added TimaKeyStore provider
D/Mms/SmsReceiverService( 2346): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2346): isDefault true
D/Mms/SmsReceiverService( 2346): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2346): [start]    handleBootCompleted() consume time = 157.392552
W/ResourcesManager( 3023): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3023): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3023): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
V/MediaScanner( 1227):  prescan time: 120ms (DB items: 138)
V/MediaScanner( 1227):     scan time: 110ms (Caching mode: true), (makeEntry time: 58ms ~52%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 230ms
V/MediaScanner( 1227): checked files: 130  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1227): checkDefaultSounds
D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
D/[0]UMC:Core( 2986): onCreate(): 
D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
D/MediaScannerService( 1227): !@done scanning volume internal
D/FactoryTestApp( 2614): [DummyFtClient$mBroadcastReceiver](2614) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2614): [DummyFtClient$mBroadcastReceiver](2614) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/FactoryTestApp( 2614): [DummyFtClient$mBroadcastReceiver](2614) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/TP/MmsSmsProvider( 1455): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1455): deleteConversation threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1455): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1455): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1455): sUpgradeVersion = 0, db.getVersion() = 81
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1455): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
D/Mms/Conversation( 2346): deleteTempConversation(),deleted=0
D/SmsProvider( 1455): Update uri=content://sms/outbox, match=8
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
D/Mms/SmsReceiverService( 2346): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2346): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2346): [SIM-1]sendFirstQueuedMessage()
D/[0]UMC:DeviceInfo( 2986): USA==US==
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/SettingsProvider( 1015): name = block_emergency_message
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10043
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/ActivityManager( 1015): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
I/art     ( 1455): Explicit concurrent mark sweep GC freed 39742(2MB) AllocSpace objects, 11(176KB) LOS objects, 45% free, 4MB/8MB, paused 984us total 146.876ms
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/TP/SmsProvider( 1455): query,matched:51, calling pid = 2346
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/TP/SmsProvider( 1455): match 51:Elapsed time : 6.189 ms
D/TP/SmsProvider( 1455): query,matched:26, calling pid = 2346
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1455): match 26:Elapsed time : 2.979 ms
D/MediaScanner( 1227): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/Zygote  ( 3058): MountEmulatedStorage()
E/Zygote  ( 3058): v2
I/libpersona( 3058): KNOX_SDCARD checking this for 1000
I/libpersona( 3058): KNOX_SDCARD not a persona
I/SELinux ( 3058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3058 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
I/WifiCredService( 1306): onCreate
D/TimaKeyStoreProvider( 3058): TimaSignature is unavailable
D/ActivityThread( 3058): Added TimaKeyStore provider
W/DriveInitializer( 1817): Background init thread ended
D/USER_AGENT( 2986): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/[0]UMC:AdminManager( 2986): init - start
D/[0]UMC:AdminManager( 2986): loadAdmins
D/[0]UMC:AdminManager( 2986): init - end
D/GSLBManager( 2986): migrateStoredUrlFromOldPref
D/GSLBManager( 2986): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 2986): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2986): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2986): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2986): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2986): isContainer : 0
D/EnterpriseDeviceManagerService( 1015): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2986): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 2986): isContainer : 0
D/[0]UMC:UMCAdmin( 2986): deactivateUMCAdmin - UMC App Admin deactivated
D/[0]UMC:CoreReceiver( 2986): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2986):  check PreETag 
D/[0]UMC:ByodSetupStarter( 2986): Container ID : 0
V/[0]UMC:Utils( 2986): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2986): shutdown
I/art     ( 2986): System.exit called, status: 0
I/AndroidRuntime( 2986): VM exiting with result code 0, cleanup skipped.
I/dhcpcd  ( 1778): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 1778): wlan0: no IPv6 Routers available
I/art     ( 1015): Explicit concurrent mark sweep GC freed 27569(1379KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 2.194ms total 135.161ms
D/Mms/MessagingNotification( 2346): isBlockingModeEnabled() = false, Zen mode = 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3086): MountEmulatedStorage()
E/Zygote  ( 3086): v2
I/libpersona( 3086): KNOX_SDCARD checking this for 1000
I/libpersona( 3086): KNOX_SDCARD not a persona
I/SELinux ( 3086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
E/SELinux ( 3086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MediaScanner( 1227): Skipping:
I/ActivityManager( 1015): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3086 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
D/Mms/SmsReceiver( 2346): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2346): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2346): isDefault true
D/WifiTimerReceiver( 1306): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1306): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1306): Action boot completed received
D/TimaKeyStoreProvider( 3086): TimaSignature is unavailable
D/ActivityThread( 3086): Added TimaKeyStore provider
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
V/MediaScanner( 1227):  prescan time: 185ms (DB items: 26)
V/MediaScanner( 1227):     scan time: 21ms (Caching mode: true), (makeEntry time: 13ms ~61%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 4ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 210ms
V/MediaScanner( 1227): checked files: 10  directories : 16  (I: 0, U: 0)
D/TP/MmsProvider( 1455): Query uri=content://mms, match=0, calling pid = 2346
D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
E/WifiStateMachine( 1015): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1015): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1015): invaild command id : 215
D/BadgeProvider( 1579): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/ActivityManager( 1015): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2986)(adj 0) has died(33,680)
D/MediaScannerService( 1227): !@done scanning volume external
W/ResourcesManager( 3086): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/FactoryTestApp( 2614): [DummyFtClient$mBroadcastReceiver](2614) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2614): [DummyFtClient$mBroadcastReceiver](2614) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2614): [DummyFtClient$sendBootCompletedAndFinish](2614) ...
D/FactoryTestApp( 2614): [Support$Values.getString](2614) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2614): [ModuleCommon$isConnectionModeNone](2614) mConnectionMode = gsm
D/FactoryTestApp( 2614): [IPCWriterToSecPhoneService$ResponseWriter](2614) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2614): [IPCWriterToSecPhoneService$connectToSecPhoneService](2614)  
D/daemonapp( 1762): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1762): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1762): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 2614): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/SettingsProvider( 1015): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
D/daemonapp( 1762): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1762): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1762): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1762): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1762): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1762): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1762): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1762): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1762): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/SettingsProvider( 1015): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10157
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/daemonapp( 1762): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/TP/MmsSmsProvider( 1455): query,matched:200, calling pid = 2346
D/daemonapp( 1762): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/TP/MmsSmsProvider( 1455): match 200:Elapsed time : 6.187 ms
D/daemonapp( 1762): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1762): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1762): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
D/daemonapp( 1762): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/daemonapp( 1762): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1762): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1762): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1451341435469
D/daemonapp( 1762): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1451362980000
D/daemonapp( 1762): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1762): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/Launcher.Model( 1478): reloadBadges entered.
D/BadgeProvider( 1579): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1579): sendNotify, [notify] : null
D/BadgeProvider( 1579): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1579): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1579): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2346): setBadgeCount(), count=0
D/daemonapp( 1762): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1451362980000
D/TP/SmsProvider( 1455): query,matched:0, calling pid = 2346
D/TP/SmsProvider( 1455): match 0:Elapsed time : 2.652 ms
D/Mms/MessagingNotification( 2346): remove alarm
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3108): MountEmulatedStorage()
E/Zygote  ( 3108): v2
I/libpersona( 3108): KNOX_SDCARD checking this for 10082
I/libpersona( 3108): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3108 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3108): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/Mms/MessagingNotification( 2346): updateAllHistoryAsRead()
I/SELinux ( 3108): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3108): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 3058): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
I/ActivityManager( 1015): Killing 2159:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
I/NearbySettings( 1306): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1306): MountReceiver.onReceive - Internal Path
D/TP/SmsProvider( 1455): query,matched:0, calling pid = 2346
D/daemonapp( 1762): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 47
D/TP/SmsProvider( 1455): match 0:Elapsed time : 1.515 ms
D/daemonapp( 1762): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1451362980000
D/SettingsProvider( 1015): name = personal_mode_enabled
I/FactoryTestApp( 2614): [IPCWriterToSecPhoneService$onServiceConnected](2614) connected done
D/FactoryTestApp( 2614): [IPCWriterToSecPhoneService$write](2614) Send Response Message to SecPhone
D/FactoryTestApp( 2614): [IPCWriterToSecPhoneService$write](2614) Response ��
D/Mms/MessagingNotification( 2346): [end]    nonBlockingUpdateMessageIndicator() consume time = 537.728541
D/TimaKeyStoreProvider( 3108): TimaSignature is unavailable
D/ActivityThread( 3108): Added TimaKeyStore provider
D/TP/SmsProvider( 1455): query,matched:51, calling pid = 2346
D/TP/SmsProvider( 1455): match 51:Elapsed time : 2.345 ms
D/AT_Distributor(  311): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 2614): [IPCWriterToSecPhoneService$handleMessage](2614) Send BOOTING COMPLETED done
D/Mms/MessagingNotification( 2346): isBlockingModeEnabled() = false, Zen mode = 0
D/BluetoothMediaBrowser( 2632):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/DSM     ( 3058): [Lines:107] Normal booted
D/DSM     ( 3058): [Lines:114] Boot completed
I/iu.UploadsManager( 1817): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1579): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
E/Zygote  ( 3132): MountEmulatedStorage()
E/Zygote  ( 3132): v2
I/libpersona( 3132): KNOX_SDCARD checking this for 1000
I/libpersona( 3132): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/BluetoothMediaBrowser( 2632): no now playing list
D/BluetoothMediaBrowser( 2632):  getNowPlayingId now playing id : -1
I/SELinux ( 3132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3132): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1015): failed to open /acct/uid_10065/pid_2159/cgroup.procs: No such file or directory
D/AT_Distributor(  311): SetAtdStatus(), 1_1_0
D/AT_Distributor(  311): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/TimaKeyStoreProvider( 3132): TimaSignature is unavailable
D/ActivityThread( 3132): Added TimaKeyStore provider
E/UpdateRequestReceiver( 3108): ignoring update request
W/ResourcesManager( 3132): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/UpdateRequestReceiver( 3108): ignoring update request
D/BadgeProvider( 1579): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1579): sendNotify, [notify] : null
D/BadgeProvider( 1579): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1579): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1579): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2346): setBadgeCount(), count=0
D/Launcher.Model( 1478): reloadBadges entered.
D/Mms/MessagingNotification( 2346): remove alarm
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/UpdateRequestReceiver( 3108): ignoring update request
D/comdaemonstockapp( 1762): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1762): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/TP/SmsProvider( 1455): query,matched:0, calling pid = 2346
I/ActivityManager( 1015): Killing 2176:com.vlingo.midas/u0a28 (adj 15): empty #31
D/TP/SmsProvider( 1455): match 0:Elapsed time : 4.054 ms
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3154): MountEmulatedStorage()
I/libpersona( 3154): KNOX_SDCARD checking this for 10161
E/Zygote  ( 3154): v2
I/libpersona( 3154): KNOX_SDCARD not a persona
I/SELinux ( 3154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3154): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityThread( 3132): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1015): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3154 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
I/art     ( 1817): Explicit concurrent mark sweep GC freed 21502(1608KB) AllocSpace objects, 24(384KB) LOS objects, 25% free, 7MB/10MB, paused 1.148ms total 102.834ms
I/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
E/UpdateRequestReceiver( 3108): ignoring update request
D/Mms/MessagingNotification( 2346): updateAllHistoryAsRead()
D/TimaKeyStoreProvider( 3154): TimaSignature is unavailable
D/ActivityThread( 3154): Added TimaKeyStore provider
I/art     (  305): Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 777us total 30.572ms
D/Mms/SmsReceiverService( 2346): [end]    handleBootCompleted() consume time = 257.080365
E/UpdateRequestReceiver( 3108): ignoring update request
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
I/iu.UploadsManager( 1817): End new media; added: 0, uploading: 0, time: 219 ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 703us total 18.992ms
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 697us total 17.734ms
W/ResourcesManager( 1455): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1455): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1455): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
W/ResourcesManager( 1455): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
W/ResourcesManager( 1455): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
W/ResourcesManager( 1455): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
W/libprocessgroup( 1015): failed to open /acct/uid_10028/pid_2176/cgroup.procs: No such file or directory
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
I/ActivityManager( 1015): Killing 2201:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 3132): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/ActivityManager( 1015): Killing 2258:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
I/LcdtestApp( 3132): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/UpdateRequestReceiver( 3108): ignoring update request
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3176): MountEmulatedStorage()
I/libpersona( 3176): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3176): v2
I/libpersona( 3176): KNOX_SDCARD not a persona
I/SELinux ( 3176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3176): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3176 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 1493:com.android.printspooler/u0a132 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3176): TimaSignature is unavailable
D/ActivityThread( 3176): Added TimaKeyStore provider
E/Zygote  ( 3192): MountEmulatedStorage()
E/Zygote  ( 3192): v2
I/libpersona( 3192): KNOX_SDCARD checking this for 10088
I/SELinux ( 3192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3192): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3192 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3192): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 1645:com.google.android.partnersetup/u0a14 (adj 15): empty #31
I/SmartcardBootCompleteReceiver( 1306): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1306): Received intent with action - android.intent.action.BOOT_COMPLETED
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
D/TimaKeyStoreProvider( 3192): TimaSignature is unavailable
D/ActivityThread( 3192): Added TimaKeyStore provider
I/SmartcardBootCompleteReceiver( 1306): Broadcast sent with current lockscreen type
E/USB_UICC(  297): Timeout! No signal received. Retry num = 27
W/libprocessgroup( 1015): failed to open /acct/uid_10045/pid_2201/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10110/pid_2258/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10132/pid_1493/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10014/pid_1645/cgroup.procs: No such file or directory
W/ResourcesManager( 3154): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3154): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3154): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3207): 
D/AndroidRuntime( 3207): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3207): CheckJNI is OFF
D/AndroidRuntime( 3207): readGMSProperty: start
D/AndroidRuntime( 3207): readGMSProperty: already setted!!
D/AndroidRuntime( 3207): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3207): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3207): readGMSProperty: end
D/AndroidRuntime( 3207): addProductProperty: start
W/ActivityThread( 3154): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3154): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@382ea3e7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3154): Installed default security provider GmsCore_OpenSSL
D/[SBeam] ( 1306): SBeamEnabler.initPreferenceForSbeam : 0
I/DIAGMON_AGENT( 3176): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/SettingSearch/SearchIntentReceiver( 1306): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1306): search setting db init!!
I/ActivityManager( 1015): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3223 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
E/Zygote  ( 3223): MountEmulatedStorage()
E/Zygote  ( 3223): v2
I/libpersona( 3223): KNOX_SDCARD checking this for 10088
I/libpersona( 3223): KNOX_SDCARD not a persona
I/SELinux ( 3223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SettingSearch/SearchIntentReceiver( 1306): BOOT_COMPLETED call InitSerachDBThread thread start!
I/SELinux ( 3223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3223): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3223): TimaSignature is unavailable
D/ActivityThread( 3223): Added TimaKeyStore provider
E/Zygote  ( 3241): MountEmulatedStorage()
E/Zygote  ( 3241): v2
I/libpersona( 3241): KNOX_SDCARD checking this for 1000
I/libpersona( 3241): KNOX_SDCARD not a persona
I/SELinux ( 3241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3241 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3241): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3256): MountEmulatedStorage()
D/TimaKeyStoreProvider( 3241): TimaSignature is unavailable
E/Zygote  ( 3256): v2
D/ActivityThread( 3241): Added TimaKeyStore provider
I/libpersona( 3256): KNOX_SDCARD checking this for 10146
I/libpersona( 3256): KNOX_SDCARD not a persona
I/SELinux ( 3256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3256 uid=10146 gids={50146, 9997} abi=armeabi-v7a
E/SELinux ( 3256): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3256): TimaSignature is unavailable
D/ActivityThread( 3256): Added TimaKeyStore provider
W/ResourcesManager( 3241): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DIAGMON_AGENT( 3176): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT( 3176): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/ServiceManager(  315): Waiting for service AtCmdFwd...
I/FOTA    ( 3241): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
I/com.dropbox.android.service.DropboxNetworkReceiver( 3192): Setting receiver enabled: false
I/DIAGMON_AGENT( 3176): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 3176): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 3176): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 3176): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3154): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3241): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
E/Zygote  ( 3279): MountEmulatedStorage()
E/Zygote  ( 3279): v2
I/libpersona( 3279): KNOX_SDCARD checking this for 1000
I/SELinux ( 3279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3279): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3279 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityThread( 3192): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
I/SELinux ( 3279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3241): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
D/TimaKeyStoreProvider( 3279): TimaSignature is unavailable
I/DBG_DM  ( 3241): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
D/ActivityThread( 3279): Added TimaKeyStore provider
I/dbxyzptlk.db240408.D.h( 3192): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
E/Zygote  ( 3301): MountEmulatedStorage()
E/Zygote  ( 3301): v2
I/libpersona( 3301): KNOX_SDCARD checking this for 10008
I/libpersona( 3301): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3301 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/SELinux ( 3301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/DBG_POLICYDM( 3279): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/SELinux ( 3301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3301): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/dbxyzptlk.db240408.D.h( 3192): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/dbxyzptlk.db240408.D.h( 3192): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_DM  ( 3241): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
W/ContextImpl( 3241): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
E/AffinityControl( 3207): AffinityControl: registerfunction enter
I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 3241): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
D/OverheatReceiver( 1172): onReceive() getAction : android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
D/TimaKeyStoreProvider( 3301): TimaSignature is unavailable
I/DBG_DM  ( 3241): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
D/ActivityThread( 3301): Added TimaKeyStore provider
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 3241): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 3241): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 3241): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3241): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3279): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_DM  ( 3241): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 3279): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_DM  ( 3241): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 3241): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(155/onStartCommand)] 
I/DBG_DM  ( 3241): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
W/ContextImpl( 3241): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
I/DBG_DM  ( 3241): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
D/AndroidRuntime( 3207): Calling main entry com.android.commands.am.Am
D/OverheatReceiver( 1172): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1172): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1172): isSafeMode = false
I/dbxyzptlk.db240408.D.h( 3192): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
E/USB_UICC(  297): Timeout! No signal received. Retry num = 28
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/breakpad( 3192): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1015): mDVFSHelper.acquire()
E/SMD     (  289): DCD OFF
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
I/DBG_POLICYDM( 3279): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/FocusedStackFrame( 1015): Set to : 0
I/DBG_POLICYDM( 3279): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 1478
D/AndroidRuntime( 3207): Shutting down VM
D/Launcher.HomeView( 1478): onPause
D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 3279): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
I/art     ( 1015): Explicit concurrent mark sweep GC freed 15039(736KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 14.295ms total 180.830ms
I/ActivityManager( 1015): Killing 2328:com.sec.modem.settings/1000 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/BootupListener( 1455): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1015): name = internet_call_settings_visibility
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1001
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
I/DBG_POLICYDM( 3279): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
D/PhoneUtilsCommon( 1455): isSupportVoLTE is false.
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (540x960),1 flag=404, iello
I/com.dropbox.sync.android.a( 3192): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
E/Zygote  ( 3331): MountEmulatedStorage()
E/Zygote  ( 3331): v2
I/libpersona( 3331): KNOX_SDCARD checking this for 10334
I/libpersona( 3331): KNOX_SDCARD not a persona
I/SELinux ( 3331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3331 uid=10334 gids={50334, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 3331): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 3279): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 3279): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
I/DBG_POLICYDM( 3279): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 3279): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/31/10:27:55
I/DBG_DM  ( 3241): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
I/DBG_POLICYDM( 3279): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/28/23:23:57
V/ActivityThread( 1478): updateVisibility : ActivityRecord{3ca11464 token=android.os.BinderProxy@28a3cbb2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/DBG_POLICYDM( 3279): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2328/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 3279): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/Telecom ( 1427): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
D/TimaKeyStoreProvider( 3331): TimaSignature is unavailable
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
D/ActivityThread( 3331): Added TimaKeyStore provider
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1478): onStop
V/ActivityThread( 1478): updateVisibility : ActivityRecord{3ca11464 token=android.os.BinderProxy@28a3cbb2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/DBG_POLICYDM( 3279): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 3279): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 3279): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/DBG_POLICYDM( 3279): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 3279): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 3279): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
D/PersonaManager( 1015): isKioskContainerExistOnDevice
I/DBG_POLICYDM( 3279): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
E/Tethering( 1015): No numeric data
E/Tethering( 1015): No numeric data
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Tethering( 1015): No numeric data
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3279): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
E/Tethering( 1015): No numeric data
E/Zygote  ( 3355): MountEmulatedStorage()
E/Zygote  ( 3355): v2
I/libpersona( 3355): KNOX_SDCARD checking this for 10052
I/libpersona( 3355): KNOX_SDCARD not a persona
I/SELinux ( 3355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3355 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/Tethering( 1015): No numeric data
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/SELinux ( 3355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3355): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/Tethering( 1015): No numeric data
I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
I/Telecom ( 1427): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1015): [SO] activate (ident=0xb954f0f8, enabled=0)
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
W/art     ( 3207): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/SensorManager( 1015): unregisterListener ::   
I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1015): [SO] changed settle time [1]
D/SensorService( 1015): [SO] setDelay [66000000]
D/SensorService( 1015): [SO] activate (ident=0xb954f0f8, enabled=1)
D/SensorService( 1015): [SO] AR_init
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/DBG_DM  ( 3241): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/TimaKeyStoreProvider( 3355): TimaSignature is unavailable
D/Launcher( 1478): onTrimMemory. Level: 20
,D/ActivityThread( 3355): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
D/[SBeam] ( 1306): SBeamEnabler.isSBeamSupported : [-1]
I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
D/[SBeam] ( 1306): SBeamEnabler.isSBeamSupported : EXIST
I/DBG_POLICYDM( 3279): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
I/DBG_POLICYDM( 3279): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
,I/com.dropbox.sync.android.ad( 3192): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,I/DBG_POLICYDM( 3279): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3279): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1015): No numeric data
,E/Zygote  ( 3372): MountEmulatedStorage()
,E/Zygote  ( 3372): v2
I/libpersona( 3372): KNOX_SDCARD checking this for 1000
I/libpersona( 3372): KNOX_SDCARD not a persona
,E/Tethering( 1015): No numeric data
,I/ActivityManager( 1015): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3372 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Killing 2378:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 2363:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #32
E/Tethering( 1015): No numeric data
I/SELinux ( 3372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3372): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SensorService( 1015): [SO] currT = 34581082000, prevT = 34271084000, diff = 309998000, [-0.402 -0.019 9.883]
D/SensorService( 1015): [SO] -0.402 -0.019 9.883
D/SensorService( 1015): [SO] [100 -> 255]
,V/audio_hw_primary(  284): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  284): audio_extn_get_parameters: returns 
V/msm8974_platform(  284): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  284): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  284): key: 'call_forwarding' value: ''
V/InCall  ( 1852): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1852): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1852): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1852): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1852): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,I/Telecom ( 1427): ProximitySensorManager: Proximity wake lock already released
,D/InCall  ( 1852): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,I/InCall  ( 1852): InCallPresenter -  - InCallState = NO_CALLS
,E/Tethering( 1015): No numeric data
,I/InCall  ( 1852): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1852): InCallPresenter -  - dismissCoverDialog()...
,D/TimaKeyStoreProvider( 3372): TimaSignature is unavailable
,D/ActivityThread( 3372): Added TimaKeyStore provider
,I/InCall  ( 1852): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1852): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,D/PhoneStatusBarView( 1172): setCallBackground:0
,I/DBG_DM  ( 3241): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/YouTube MDX( 3154): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1852): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
V/VibratorService( 1015): hasVibrator - useVibetonz: true
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2378/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10127/pid_2363/cgroup.procs: No such file or directory
,I/WebViewFactory( 3331): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,W/NotificationAccessSettings( 1306): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,I/DBG_DM  ( 3241): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,V/VibratorService( 1015): hasVibrator - useVibetonz: true
,V/VibratorService( 1015): hasVibrator - useVibetonz: true
,I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3241): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/VideoCallManager( 1852): Instantiating VideoCallManager
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 3331): Loading: webviewchromium
,I/LibraryLoader( 3331): Time to load native libraries: 5 ms (timestamps 4706-4711)
I/LibraryLoader( 3331): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 3398): MountEmulatedStorage(),
I/libpersona( 3398): KNOX_SDCARD checking this for 10090
E/Zygote  ( 3398): v2
I/libpersona( 3398): KNOX_SDCARD not a persona
I/SELinux ( 3398): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3398 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 2395:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/SELinux ( 3398): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ResourcesManager( 1306): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/SELinux ( 3398): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/        ( 1852): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/GFX construct_block_size_descriptor_2d second part( 1852): took 2.458073ms for 0*0 texture 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
I/GFX generate_partition_tables( 1852): took 6.298438ms for 0*0 texture 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/art     (  305): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 631us total 26.722ms
,I/GFX raster( 1852): took 12.682397ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1852): Bitmap=0xb928b4c8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb928b928 counterpartCT=4 counterpartW=176 counterparth=144
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 17.629ms
D/TimaKeyStoreProvider( 3398): TimaSignature is unavailable
,D/ActivityThread( 3398): Added TimaKeyStore provider
,E/        ( 1852): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1852): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
I/Adreno-EGL( 1852): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1852): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1852): Local Branch: 
I/Adreno-EGL( 1852): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1852): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1852):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,V/WebViewChromiumFactoryProvider( 3331): Binding Chromium to main looper Looper (main, tid 1) {1fad6310}
,I/LibraryLoader( 3331): Expected native library version number "",actual native library version number ""
I/chromium( 3331): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 17.546ms
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
I/BrowserStartupController( 3331): Initializing chromium process, renderers=0,
E/Zygote  ( 3415): MountEmulatedStorage()
E/Zygote  ( 3415): v2
I/libpersona( 3415): KNOX_SDCARD checking this for 10014
I/libpersona( 3415): KNOX_SDCARD not a persona
,W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
,I/SELinux ( 3415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3415): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3415 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,I/SurfaceFlinger(  258): id=7 Removed Mauncher (5/8)
,D/TimaKeyStoreProvider( 3415): TimaSignature is unavailable
D/ActivityThread( 3415): Added TimaKeyStore provider
,D/LocationManagerService( 1015): getProviders()=[passive]
,I/GFX GPU raster( 1852): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1852): took 0.322500ms for 320*61440 texture 37809
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2395/cgroup.procs: No such file or directory
,W/chromium( 3331): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 3331): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 3331): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/draw setup( 1852): took 10.847919ms for 320*240 texture 37809
E/GFX GPU raster( 1852): drawn
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/GFX GPU raster ASTC( 1852): took 44.882140ms for 320*240 texture 12
I/GFX raster( 1852): took 44.960056ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1852): Bitmap=0xb928b928 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb9287648 counterpartCT=4 counterpartW=320 counterparth=240
,I/Adreno-EGL( 3331): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3331): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3331): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3331): Local Branch: 
I/Adreno-EGL( 3331): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3331): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3331):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/        ( 1852): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1852): eglCreateImageKHR: EGL_SUCCESS
I/AudioService( 1015): getStreamVolume 3 index 70
,I/glCompressedTexImage2D( 1852): took 0.345937ms for 480*122880 texture 37813
I/draw setup( 1852): took 0.849792ms for 480*640 texture 37813
E/GFX GPU raster( 1852): drawn
I/GFX GPU raster ASTC( 1852): took 7.580313ms for 480*640 texture 12
I/GFX raster( 1852): took 7.682448ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1852): Bitmap=0xb9287648 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb94ccc08 counterpartCT=4 counterpartW=480 counterparth=640
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_FMMDM( 3372): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/elm:15121( 3398): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,E/        ( 1852): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,D/elm:15121( 3398): ELMEngine.ELMEngine( context ).
I/GFX GPU raster( 1852): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1852): took 0.427292ms for 440*116864 texture 37809
I/draw setup( 1852): took 1.083906ms for 440*330 texture 37809
E/GFX GPU raster( 1852): drawn
,D/elm:15121( 3398): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/GFX GPU raster ASTC( 1852): took 4.623177ms for 440*330 texture 12
I/GFX raster( 1852): took 4.694531ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1852): Bitmap=0xb94ccc08 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb94e1720 counterpartCT=4 counterpartW=440 counterparth=330
,D/elm:15121( 3398): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/Velvet.VelvetFactory( 3355): refreshing internal icing corpora
I/ContactAccountLoggerTas( 3355): canRun() : Opted Out
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/elm:15121( 3398): ElmAgentService : onCreate()
,D/elm:15121( 3398): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 3398): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3398): BootCompletedState : startBootCompleted() call
,D/elm:15121( 3398): MDMBridge.getAllLicenseInfoFromSDK()
,V/EmergencyMode( 1415): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
I/elm:15121( 3398): Get License : 0
D/elm:15121( 3398): ElmAgentService : onDestroy().
,I/ActivityManager( 1015): Killing 2444:com.wsomacp/u0a23 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/DBG_FMMDM( 3372): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/        ( 1852): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1852): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1852): took 0.447344ms for 480*163840 texture 37811
I/draw setup( 1852): took 0.930468ms for 480*640 texture 37811
E/GFX GPU raster( 1852): drawn
,V/EmergencyMode( 1415): [EmergencyBase] setBootTime
V/EmergencyMode( 1415): [EmergencyFactory] No Recovery State, kill my self.
,I/DBG_FMMDM( 3372): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/GFX GPU raster ASTC( 1852): took 5.905624ms for 480*640 texture 12
I/GFX raster( 1852): took 5.984270ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1852): Bitmap=0xb94e1720 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb94cca10 counterpartCT=4 counterpartW=480 counterparth=640
,I/DBG_FMMDM( 3372): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/ScoverManager( 1306): serviceVersion : 16908288
,I/Velvet.VelvetFactory( 3355): refreshing search history.
,W/chromium( 3331): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/chromium( 3331): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3471): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3471 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 3471): v2
I/libpersona( 3471): KNOX_SDCARD checking this for 1000
I/libpersona( 3471): KNOX_SDCARD not a persona
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/        ( 1852): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
I/GFX construct_block_size_descriptor_2d second part( 1852): took 2.393750ms for 0*0 texture 0
,I/SELinux ( 3471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX generate_partition_tables( 1852): took 7.496668ms for 0*0 texture 0
,I/GFX raster( 1852): took 11.840886ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1852): Bitmap=0xb94b49c8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb94b4ae8 counterpartCT=4 counterpartW=176 counterparth=144
,E/Zygote  ( 3478): MountEmulatedStorage()
E/Zygote  ( 3478): v2
I/libpersona( 3478): KNOX_SDCARD checking this for 1000
I/libpersona( 3478): KNOX_SDCARD not a persona
,I/SELinux ( 3478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/        ( 1852): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1852): took 2.513854ms for 0*0 texture 0
,E/SELinux ( 3478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
I/GFX generate_partition_tables( 1852): took 6.249584ms for 0*0 texture 0
I/ActivityManager( 1015): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3478 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/GFX raster( 1852): took 10.976563ms for 176*144 texture 0
I/ActivityManager( 1015): Killing 2486:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1852): Bitmap=0xb94b4c20 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb94b4f20 counterpartCT=4 counterpartW=176 counterparth=144
,W/AwContents( 3331): onDetachedFromWindow called when already detached. Ignoring
D/ScoverManager( 1852): registerListener
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
I/System.out( 3192): Thread-409(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1015): registerListenerCallback : binder = android.os.BinderProxy@30216b7a, pid : 1852, uid : 1001, type : 1
D/TimaKeyStoreProvider( 3471): TimaSignature is unavailable
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3471): Added TimaKeyStore provider
,I/System.out( 3192): Thread-409(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3192): Thread-409(ApacheHTTPLog):isShipBuild true
I/System.out( 3192): Thread-409(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3192): Thread-409(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/PhoneWindow( 3331): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3331): *FMB* installDecor flags : 8456448
,D/TimaKeyStoreProvider( 3478): TimaSignature is unavailable
D/ActivityThread( 3478): Added TimaKeyStore provider
D/InCall  ( 1852): InCallPresenter -  - Finished InCallPresenter.setUp
,D/SystemWebViewEngine( 3331): CordovaWebView is running on device made by: samsung
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3154): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 3154): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10088
E/USB_UICC(  297): Timeout! No signal received. Retry num = 29
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3154): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,I/CameraApp( 3471): CameraApp.onCreate()... mFeature : null
I/testFeature( 3471): Feature.Feature(context)
I/testFeature( 3471): Feature.readInternalDefaultXml()
I/testFeature( 3471): ResetFeatureValue
,I/CameraFirmware_broadcast( 3471): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3471): CameraApp.getAppFeature()...
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PCWCLIENTTRACE_LOG( 3478): DEFAULT_LOGON : true
,E/Zygote  ( 3507): MountEmulatedStorage()
,I/libpersona( 3507): KNOX_SDCARD checking this for 10095
E/Zygote  ( 3507): v2
I/libpersona( 3507): KNOX_SDCARD not a persona
I/SELinux ( 3507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3507 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 3507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 2506:com.sec.android.app.camera/u0a135 (adj 15): empty #31
I/PCWCLIENTTRACE_LOG( 3478): DEFAULT_LOGLEVEL : 3
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3478): new DMDBOpenHelper instance
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 70
,W/libprocessgroup( 1015): failed to open /acct/uid_10023/pid_2444/cgroup.procs: No such file or directory
I/MediaRouter( 3355): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PCWCLIENTTRACE_DMContentProvider( 3478): [URIMatcher] - result : 2
,D/TimaKeyStoreProvider( 3507): TimaSignature is unavailable
,D/ActivityThread( 3507): Added TimaKeyStore provider
,I/FavoriteContactNamesSup( 3355): get() : Execute runnable (UI thread)
I/ContactLabelSupplier( 3355): get() : Execute runnable (UI thread)
,W/libprocessgroup( 1015): failed to open /acct/uid_10139/pid_2486/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_2506/cgroup.procs: No such file or directory
,I/LockPatternUtils( 1306): isSmartCardAuthenticationAvailable: false
,I/DBG_FMMDM( 3372): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3372): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
I/DBG_FMMDM( 3372): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PreloadFilterInstaller( 3507): uses FILTER_DB_VER_1
,D/Settings_Utils( 1306): isSupportVNFestival SM-A300FU XEO
,E/Zygote  ( 3540): MountEmulatedStorage(),
I/libpersona( 3540): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3540): v2
I/libpersona( 3540): KNOX_SDCARD not a persona
I/SELinux ( 3540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3540 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 2093:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
I/ActivityManager( 1015): Killing 2316:com.sec.android.app.mt/1000 (adj 15): empty #32
,E/SELinux ( 3540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 3507): (284) automatic index on titles(filter_id)
,D/TimaKeyStoreProvider( 3540): TimaSignature is unavailable,
E/Zygote  ( 3556): MountEmulatedStorage()
I/libpersona( 3556): KNOX_SDCARD checking this for 10055
E/Zygote  ( 3556): v2
I/libpersona( 3556): KNOX_SDCARD not a persona
D/ActivityThread( 3540): Added TimaKeyStore provider,
I/SELinux ( 3556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3556 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,E/SELinux ( 3556): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ActivityManager( 1015): Killing 2595:com.android.calendar/u0a131 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3556): TimaSignature is unavailable
,D/ActivityThread( 3556): Added TimaKeyStore provider
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 ,
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2316/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2093/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10131/pid_2595/cgroup.procs: No such file or directory
,D/UserAnalysis.PlaceProvider( 3556): PlaceProvider onCreate(),
,W/ResourceType( 1306): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,W/ResourceType( 1306): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,D/UserAnalysis.SecureDbManager( 3556): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3556): SecurePlaceDbHelper() 
D/UserAnalysis( 3556): Create SecureDbHelper
,I/DBG_FMMDS( 3540): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3540): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/IntelligenceServiceApplication( 3556): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3556): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3586): MountEmulatedStorage()
E/Zygote  ( 3586): v2
I/libpersona( 3586): KNOX_SDCARD checking this for 10056
I/libpersona( 3586): KNOX_SDCARD not a persona
,I/SELinux ( 3586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 3586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3586 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 3586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FilterProviderReceiver( 3507): onReceive in FilterProviderReceiver
I/FilterProviderReceiver( 3507): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,D/PCWCLIENTTRACE_DMContentProvider( 3478): [URIMatcher] - result : 2
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/OpenGLRenderer( 3331): Render dirty regions requested: true
,E/Zygote  ( 3604): MountEmulatedStorage()
E/Zygote  ( 3604): v2
I/libpersona( 3604): KNOX_SDCARD checking this for 10098
I/libpersona( 3604): KNOX_SDCARD not a persona
I/SELinux ( 3604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 3586): TimaSignature is unavailable
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3604 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 3604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/ActivityThread( 3586): Added TimaKeyStore provider
,E/SELinux ( 3604): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GAV2    ( 2721): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,I/ContactAccountLoggerTas( 3355): canRun() : Opted Out
,D/PhoneWindow( 3331): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3331): *FMB* isFloatingMenuEnabled return false
,E/DBG_FMMDS( 3540): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/ContactAccountLoggerTas( 3355): canRun() : Opted Out
,I/UpdateIcingCorporaServi( 3355): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/DBG_FMMDS( 3540): [50.18.150420][Line:43][xdbDBInit] 
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/TimaKeyStoreProvider( 3604): TimaSignature is unavailable
,D/ActivityThread( 3604): Added TimaKeyStore provider
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,I/WebViewFactory( 3355): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/PowerUI ( 1172): Cable  true --> true mBootCompleted : true
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/PowerUI ( 1172): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
D/InputDispatcher( 1015): Focus entered window: 3331
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 3331): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3331): Initialized EGL, version 1.4
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,I/LibraryLoader( 3355): Loading: webviewchromium
,D/SViewCoverView( 1172): level :100 plugged : 2
,I/LibraryLoader( 3355): Time to load native libraries: 5 ms (timestamps 5677-5682)
I/LibraryLoader( 3355): Expected native library version number "",actual native library version number ""
,D/OpenGLRenderer( 3331): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3331): Enabling debug mode 0
,D/PackageIntentReceiver( 3604): ACTION_BOOT_COMPLETED,
,D/PackageIntentReceiver( 3604): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/IntelligenceServiceApplication( 3556): no applications having user consent for prediction,
,I/FactoryTestApp( 2614): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3126)  
,E/Zygote  ( 3623): MountEmulatedStorage()
E/Zygote  ( 3623): v2
I/libpersona( 3623): KNOX_SDCARD checking this for 10099
I/libpersona( 3623): KNOX_SDCARD not a persona
,I/SELinux ( 3623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/ActivityManager( 1015): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3623 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ServiceManager(  315): Waiting for service AtCmdFwd...,
I/ActivityManager( 1015): Killing 2651:com.android.keychain/1000 (adj 15): empty #31
I/SELinux ( 3623): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3623): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1015): Killing 2688:com.android.chrome/u0a77 (adj 15): empty #31
,D/PanelView( 1172): There is/are notification(s) 
,I/ActivityManager( 1015): Displayed Component not be shown by security: +1s495ms
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{1d93b50a u0 com.example.hello/.MainActivity t2} time:35765
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
W/ActivityManager( 1015): mDVFSHelper.release()
,D/TimaKeyStoreProvider( 3623): TimaSignature is unavailable
,D/ActivityThread( 3623): Added TimaKeyStore provider
,I/Timeline( 3331): Timeline: Activity_idle id: android.os.BinderProxy@fa7b040 time:35786
,I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,V/PlaceDetection v1.0.19 ( 3556): [PlaceDetection::stopService] Service stopped.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 3355): Attempt to remove local handle scope entry from IRT, ignoring
,I/sCloudBackupApp( 3586): sCloudBackupApp Version Info : 4.04.7.KK_APP
,I/DBG_FMMDS( 3540): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,W/libprocessgroup( 1015): failed to open /acct/uid_10077/pid_2688/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2651/cgroup.procs: No such file or directory
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3645): MountEmulatedStorage()
E/Zygote  ( 3645): v2
I/libpersona( 3645): KNOX_SDCARD checking this for 10058
I/libpersona( 3645): KNOX_SDCARD not a persona
,I/SELinux ( 3645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3645): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1015): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3645 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 2456:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 3645): TimaSignature is unavailable
,D/ActivityThread( 3645): Added TimaKeyStore provider
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,V/PlaceDetection v1.0.19 ( 3556): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3556): Constructor Preference
,I/DBG_FMMDS( 3540): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3540): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/ExternalOEMControlProvider( 3645): onCreate,
I/DBG_FMMDS( 3540): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3540): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3540): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3540): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,W/libprocessgroup( 1015): failed to open /acct/uid_10039/pid_2456/cgroup.procs: No such file or directory
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3668): MountEmulatedStorage()
,E/Zygote  ( 3668): v2
I/libpersona( 3668): KNOX_SDCARD checking this for 1000
I/libpersona( 3668): KNOX_SDCARD not a persona
,I/SELinux ( 3668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3668 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 2764:com.android.email/u0a141 (adj 15): empty #31
,I/SamsungIME( 1795): getCurrentCandidateView
E/SELinux ( 3668): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
I/chromium( 3331): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager( 1015): Killing 2848:com.mobeam.barcodeService/1000 (adj 15): empty #31
E/AndroidProtocolHandler( 3331): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/art     (  305): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 24.460ms
D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@11
D/SettingsProvider( 1015): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10058
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/TimaKeyStoreProvider( 3668): TimaSignature is unavailable
,D/ActivityThread( 3668): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 29.650ms
,I/FOTA_Client( 3301): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/SettingsProvider( 1015): name = PREVIOUS_ELAPSED_TIME
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,I/FOTA_Client( 3301): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 18.090ms
,D/SettingsProvider( 1015): selectionArgs: 10058,
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
W/ResourcesManager( 3668): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/SettingsProvider( 1015): ret = -1
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/FOTA_Client( 3301): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1015): Killing 2870:flipboard.boxer.app/u0a97 (adj 15): empty #31
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 30
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 2667(109KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 727us total 33.343ms
,V/VibratorService( 1015): hasVibrator - useVibetonz: true
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2848/cgroup.procs: No such file or directory
,I/ServiceMode( 3668): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3668): setReferenceIsDumpState : 0
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,W/FOTA_Client( 3301): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10141/pid_2764/cgroup.procs: No such file or directory
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10097/pid_2870/cgroup.procs: No such file or directory
,E/Zygote  ( 3689): MountEmulatedStorage()
E/Zygote  ( 3689): v2
I/libpersona( 3689): KNOX_SDCARD checking this for 10013
I/libpersona( 3689): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3689 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,I/SELinux ( 3689): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Killing 2901:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3689): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3689): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/JsMessageQueue( 3331): Set native->JS mode to OnlineEventsBridgeMode
,E/USB_UICC(  297): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  297): usb_uicc_init_qmi failed ! 
I/USB_UICC(  297): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  297): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/TimaKeyStoreProvider( 3689): TimaSignature is unavailable,
,D/ActivityThread( 3689): Added TimaKeyStore provider
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 22734(1259KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/33MB, paused 2.509ms total 155.298ms
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3714): MountEmulatedStorage(),
E/Zygote  ( 3714): v2
I/libpersona( 3714): KNOX_SDCARD checking this for 1000
I/libpersona( 3714): KNOX_SDCARD not a persona
,I/SELinux ( 3714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3714): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/chromium( 3331): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3331): 
,I/ActivityManager( 1015): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3714 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 2944:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/MessageQueue( 3154): Handler (android.os.Handler) {30864e60} sending message to a Handler on a dead thread
W/MessageQueue( 3154): java.lang.IllegalStateException: Handler (android.os.Handler) {30864e60} sending message to a Handler on a dead thread
W/MessageQueue( 3154): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 3154): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 3154): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 3154): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 3154): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 3154): 	at ffw.a(SourceFile:327)
W/MessageQueue( 3154): 	at guw.a(SourceFile:120)
W/MessageQueue( 3154): 	at guf.c(SourceFile:26)
W/MessageQueue( 3154): 	at gui.run(SourceFile:297)
W/MessageQueue( 3154): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 3154): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 3154): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 3154): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/ActivityManager( 1015): Killing 2217:flipboard.app/u0a96 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3714): TimaSignature is unavailable
,D/ActivityThread( 3714): Added TimaKeyStore provider
,D/SamsungIME( 1795): Dismiss ExpandCandiate
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10052
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/AndroidHttpClient( 3154): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
D/AndroidHttpClient( 3154): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 3154): Thread-443(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3154): Thread-443(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 3154): Thread-443(ApacheHTTPLog):isShipBuild true
I/System.out( 3154): Thread-443(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3154): Thread-443(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10161
,D/jxcore_app_log( 3331): JniHelper::setJavaVM(0xb8edf448), pthread_self() = -1184856480
,D/JX-Cordova( 3331): jxcore cordova android initializing
,V/OneTimeInitializerReceiver( 3689): OneTimeInitializerReceiver.onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,V/OneTimeService( 3689): OneTimeService.onHandleIntent
,W/jxcore-log( 3331): Initializing JXcore engine
D/NPS_WSSNPS( 3714): [] android.intent.action.BOOT_COMPLETED
W/jxcore-log( 3331): JXcore engine is ready
,W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/jxcore-log( 3331): Starting JXcore engine
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3714): [] Service onCreate!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/LockPatternUtils( 1306): isSmartCardAuthenticationAvailable: false
,I/qtaguid ( 3355): Tagging socket 34 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
,E/Zygote  ( 3742): MountEmulatedStorage(),
E/Zygote  ( 3742): v2,
I/ActivityManager( 1015): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3742 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/libpersona( 3742): KNOX_SDCARD checking this for 1000
I/libpersona( 3742): KNOX_SDCARD not a persona
,I/SELinux ( 3742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3742): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup( 1015): failed to open /acct/uid_1101/pid_2901/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10153/pid_2944/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10096/pid_2217/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/audit   ( 1812): type=1400 msg=audit(1451341439.384:205): avc:  denied  { ioctl } for  pid=3331 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1812):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1812): type=1300 msg=audit(1451341439.384:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=be8fad58 items=0 ppid=305 ppcomm=main pid=3331 auid=4294967295 uid=10334 gid=10334 euid=10334 suid=10334 fsuid=10334 egid=10334 sgid=10334 fsgid=10334 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1812): type=1320 msg=audit(1451341439.384:205): 
,D/TimaKeyStoreProvider( 3742): TimaSignature is unavailable
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityThread( 3742): Added TimaKeyStore provider
,W/ContextImpl( 1840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/NPS_WSSNPS( 3714): [50.150321] smlDBHelper
,D/NPS_WSSNPS( 3714): [50.150321] NpsServiceTask Start
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1840): Service started flags 0 startId 1
,D/SecUISvc( 1840): Thread created.
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 19124(1461KB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 9MB/15MB, paused 1.181ms total 218.952ms
,I/NPS_WSSNPS( 3714): [50.150321] AsyncBulkFlagCheck
,I/System.out( 3192): pool-10-thread-1 calls detatch()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SamsungIME( 1795): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NPS_WSSNPS( 3714): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3714): [50.150321] IsRemain_Asyncing nothing,
,W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3714): [50.150321] Service onDestroy
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/jxcore-log( 3331): Platform android
W/jxcore-log( 3331): 
,W/jxcore-log( 3331): Process ARCH arm
W/jxcore-log( 3331): 
,I/Hs20UtilService( 2072): Starting #4
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/Hs20UtilService( 2072): Message received 5003
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/Zygote  ( 3774): MountEmulatedStorage()
,I/libpersona( 3774): KNOX_SDCARD checking this for 10018
E/Zygote  ( 3774): v2
I/libpersona( 3774): KNOX_SDCARD not a persona
I/SELinux ( 3774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/Icing   ( 1817): Storage manager: low false usage 2.09MB avail 10.00GB capacity 11.63GB
I/SELinux ( 3774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3774): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3774 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 3331): JXcore Cordova bridge is ready!
I/jxcore-log( 3331): 
,W/jxcore-log( 3331): JXcore engine is started
D/TimaKeyStoreProvider( 3774): TimaSignature is unavailable
D/ActivityThread( 3774): Added TimaKeyStore provider
I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,I/NPS_WSSNPS( 3714): [50.150321] smlBRConfigurationDelete
I/NPS_WSSNPS( 3714): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3714): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3714): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3714): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3714): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3714): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3714): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3714): [50.150321] cpuBooster release : false
,D/NPS_WSSNPS( 3714): [50.150321] dsServerSocket close
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{c1b02bd u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,D/SettingsProvider( 1015): name = access_control_enabled
,E/jxcore-log( 3331): >> samsung-SM-A300FU
E/jxcore-log( 3331): 
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 3331): Total memory 1451114496
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): Free memory 29687808
I/jxcore-log( 3331): 
I/jxcore-log( 3331): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3331): 
I/jxcore-log( 3331): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): userPath [ 'www' ]
I/jxcore-log( 3331): 
,I/Gmail   ( 3623): getAccountsCursor
,I/jxcore-log( 3331): Size 540 960
I/jxcore-log( 3331): 
,E/Zygote  ( 3794): MountEmulatedStorage(),
E/Zygote  ( 3794): v2
I/libpersona( 3794): KNOX_SDCARD checking this for 10065
I/libpersona( 3794): KNOX_SDCARD not a persona
I/jxcore-log( 3331): Screen Brightness 255
I/jxcore-log( 3331): ,
E/jxcore-log( 3331): Dummy Error Log.
E/jxcore-log( 3331): 
,I/SELinux ( 3794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3794): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3794 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
,I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
,I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
,I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
I/qtaguid ( 3355): Untagging socket 46
I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
,I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
,I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
,I/qtaguid ( 3355): Untagging socket 46
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
I/qtaguid ( 3355): Untagging socket 46
,D/TimaKeyStoreProvider( 3794): TimaSignature is unavailable
,D/ActivityThread( 3794): Added TimaKeyStore provider
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/KLMS-2.5.123: ( 3774): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 28 23:23:59 GMT+01:00 2015
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/System.out( 3154): Thread-443 calls detatch()
,I/System.out( 1676): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1676): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1676): (HTTPLog)-Static: isShipBuild true
I/System.out( 1676): (HTTPLog)-Thread-135-799301268: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1676): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/KLMS-2.5.123: ( 3774): KLMSAbstractReciever(): onReceive().END.
,I/SamsungIME( 1795): getDebugLevel  : 0x4f4c
,I/qtaguid ( 3355): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3355, getuid(): 10052
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3774): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3774): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/System.out( 1676): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1676): Tagging socket 68 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1676, getuid(): 10011
,I/KLMS-2.5.123: ( 3774): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3774): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SamsungIME( 1795): KeybaordView init() : load resources
,W/GAV2    ( 3623): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 3817): MountEmulatedStorage()
I/libpersona( 3817): KNOX_SDCARD checking this for 10020
E/Zygote  ( 3817): v2
I/libpersona( 3817): KNOX_SDCARD not a persona
I/SELinux ( 3817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3817): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3817 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3774): KLMSIntentService(): BOOT_COMPLETED
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,I/ActivityManager( 1015): Killing 2966:com.sec.usbsettings/1000 (adj 15): empty #31
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1306): InitSerachDBThread thread end!
,D/FileShare-Server( 3794): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/RlzPingService( 3415): Setting next ping for 1451946239915
,D/TimaKeyStoreProvider( 3817): TimaSignature is unavailable
D/ActivityThread( 3817): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3774): KLMSIntentService(): onDestroy()
,I/SamsungIME( 1795): getCurrentKeyboard
I/SamsungIME( 1795): getTextKeyboard
,I/qtaguid ( 1676): Tagging socket 71 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1676, getuid(): 10011
,W/GAV2    ( 3355): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 3355): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 3355): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3355): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3355): canRun() : Opted Out
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 3623): Observing account changes for notifications
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2966/cgroup.procs: No such file or directory
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3843): MountEmulatedStorage(),
E/Zygote  ( 3843): v2
I/libpersona( 3843): KNOX_SDCARD checking this for 1000
I/libpersona( 3843): KNOX_SDCARD not a persona
I/SELinux ( 3843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3843 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3843): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 2346:com.android.mms/u0a41 (adj 15): empty #31
,D/SamsungIME( 1795): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/ContactLabelSupplier( 3355): get() : OptedIn = false
D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 3843): TimaSignature is unavailable
,D/ActivityThread( 3843): Added TimaKeyStore provider
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,E/Gmail   ( 3623): Error finding the version of the Email provider.....
E/Gmail   ( 3623): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3623): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3623): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3623): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3623): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3623): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3623): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3623): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 3623): We do not support migrating this version of the Email provider.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 3623): getAccountsCursor
,I/ActivityManager( 1015): Killing 2887:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/CountryDetector( 1015): No listener is left
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/MTPRx   ( 3843): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_2346/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10081/pid_2887/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1015): mCursor = null
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1015): mCursor = null
V/MTPRx   ( 3843): sealedState: false
V/MTPRx   ( 3843): sealedUsbMassStorageState: false
,E/Zygote  ( 3866): MountEmulatedStorage()
,E/Zygote  ( 3866): v2
I/libpersona( 3866): KNOX_SDCARD checking this for 10102
I/libpersona( 3866): KNOX_SDCARD not a persona
,I/SELinux ( 3866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3866 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/SELinux ( 3866): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3623): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@12ccd55d that was originally bound here
E/ActivityThread( 3623): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@12ccd55d that was originally bound here
E/ActivityThread( 3623): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3623): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3623): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3623): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3623): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3623): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3623): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3623): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3623): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3623): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3623): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3623): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3623): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3623): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3623): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3623): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@349c34aa
,D/accuweather( 1734): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/SettingsProvider( 1015): name = mtp_usb_connection_status
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1734): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/btif_config_util( 2632): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/SQLiteLog( 3623): (283) recovered 100 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1734): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1734): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,D/accuweather( 1734): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1734): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,D/TimaKeyStoreProvider( 3866): TimaSignature is unavailable
,D/ActivityThread( 3866): Added TimaKeyStore provider
,E/accuweather( 1734): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 23 24
,D/SettingsProvider( 1015): name = media_player_mode
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/GoogleHttpClient( 1629): GMS http client unavailable, use old client
,I/ActivityManager( 1015): Killing 3023:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,D/GCM     ( 1676): COMPAT: Multi user not supported
,W/ResourcesManager( 3866): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1015): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/Zygote  ( 3885): MountEmulatedStorage()
,E/Zygote  ( 3885): v2
I/libpersona( 3885): KNOX_SDCARD checking this for 1000
I/libpersona( 3885): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3885 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/jxcore-log( 3331): getBuffer is called!!!!
I/jxcore-log( 3331): 
,E/SELinux ( 3885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_10043/pid_3023/cgroup.procs: No such file or directory
,D/SettingsProvider( 1015): name = mtp_running_status
,D/TimaKeyStoreProvider( 3885): TimaSignature is unavailable
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/ActivityThread( 3885): Added TimaKeyStore provider
,D/SettingsProvider( 1015): name = media_mount_count
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = mtp_sync_alive
,D/FactoryTestApp( 2614): [DummyFtClient$onDestroy](2614) Destroy DummyFtClient service
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/FactoryTestApp( 2614): [Support$Values.getString](2614) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2614): [ModuleCommon$isConnectionModeNone](2614) mConnectionMode = gsm
,I/FactoryTestApp( 2614): [ModuleCommon$isRunningFtClient](2614) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2614): [DummyFtClient$onDestroy](2614) kill process
I/Process ( 2614): Sending signal. PID: 2614 SIG: 9
,D/SettingsProvider( 1015): name = sdcard_launch
,I/DBG_POLICYDM( 3279): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/SettingsProvider( 1015): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/ActivityManager( 1015): Process com.sec.factory (pid 2614)(adj 0) has died(27,662)
,D/SettingsProvider( 1015): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/PCWCLIENTTRACE_PushUtil( 3478): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3478): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3478): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3478): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3478): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3478): ACTION_BOOTUP - Push type: [SPP, GCM]
,I/DBG_POLICYDM( 3279): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 3279): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 3086:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,W/ContextImpl( 3885): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3907): MountEmulatedStorage()
I/libpersona( 3907): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3907): v2
I/libpersona( 3907): KNOX_SDCARD not a persona
,I/SELinux ( 3907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3907): TimaSignature is unavailable
,D/ActivityThread( 3907): Added TimaKeyStore provider
,W/ResourcesManager( 3907): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 3907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3086/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3926): MountEmulatedStorage(),
E/Zygote  ( 3926): v2
I/libpersona( 3926): KNOX_SDCARD checking this for 1000
,I/libpersona( 3926): KNOX_SDCARD not a persona
,I/SELinux ( 3926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3926): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1015): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3926 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3926): TimaSignature is unavailable,
I/F_PHONE ( 3907): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,D/ActivityThread( 3926): Added TimaKeyStore provider
W/ContextImpl( 3907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/art     (  305): Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 25.125ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,W/ResourcesManager( 3926): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.748ms
,D/F_PHONE ( 3907): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3907): default registerAction()
I/F_PHONE ( 3907): [[com.sec.bcservice]] sendPendingMessage()
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.921ms
,D/BluetoothBDAdrressReceiver( 3926): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/PCWCLIENTTRACE_AccountUtil( 3478): [hasSamungAccount] - No Samsung Account
,E/File    ( 3623): fail readDirectory() errno=2
,W/art     ( 3866): Suspending all threads took: 8.908ms
,I/Gmail   ( 3623): notifyAccountChanged
,D/FileApkUtils( 1817): Spent 165ms computing apk sha1.
,D/FileApkUtils( 1817): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/Gmail   ( 3623): getAccountsCursor
,I/art     ( 1817): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-cf053f76526e84be2388d3f24ecde21377d895e5@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/Gmail   ( 3623): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/DexOptUtils( 1817): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1817): Keeping up-to-date module: module-cf053f76526e84be2388d3f24ecde21377d895e5
,D/ChimeraCfgMgr( 1817): Reading stored module config
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3478): [GetString-S]
,I/ReactiveServiceManager( 3478): Supported : 1
,I/Gmail   ( 3623): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,I/Babel   ( 3866): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3866): MmsConfig.loadMmsSettings
I/Babel   ( 3866): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3866): MmsConfig.loadFromDatabase
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 9
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 9
,E/terrier ( 1015): handleString: Failed to handle string(-4)
E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 3478): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3478): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 3478): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3478): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3478): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3478): [ensureRegistration] - No Samsung account
,W/InstanceID/Rpc( 1817): Found 10011
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 21271(1097KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.540ms total 183.137ms
,I/Gmail   ( 3623): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/Gmail   ( 3623): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1455): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1455): onCreate()
,E/BluetoothBDTestService( 1455): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1455): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1455): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/ContactAccountLoggerTas( 3355): canRun() : Opted Out
,E/Zygote  ( 3952): MountEmulatedStorage()
E/Zygote  ( 3952): v2
I/libpersona( 3952): KNOX_SDCARD checking this for 10028
I/libpersona( 3952): KNOX_SDCARD not a persona
,I/SELinux ( 3952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3952): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 3866): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1015): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3952 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,W/AudioCapabilities( 3866): Unsupported mime audio/evrc
,W/AudioCapabilities( 3866): Unsupported mime audio/qcelp
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GmsModuleFndr( 1817): Beginning GMS chimera module scan
,I/ActivityManager( 1015): Killing 2721:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,E/Babel   ( 3866): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3866): MmsConfig.loadFromResources
,E/Babel   ( 3866): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3866): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,D/GmsModuleFndr( 1817): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/ChimeraCfgMgr( 1817): Beginning module configuration check
,D/ChimeraCfgMgr( 1817): Module APKs unchanged, check complete
,D/TimaKeyStoreProvider( 3952): TimaSignature is unavailable
,D/ActivityThread( 3952): Added TimaKeyStore provider
,W/AudioCapabilities( 3866): Unsupported mime audio/mpeg-L1,
,W/AudioCapabilities( 3866): Unsupported mime audio/mpeg-L2
,I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3967 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 3967): MountEmulatedStorage()
E/Zygote  ( 3967): v2
I/libpersona( 3967): KNOX_SDCARD checking this for 1000
I/libpersona( 3967): KNOX_SDCARD not a persona
,I/SELinux ( 3967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3967): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3058:com.sec.dsm.system/1000 (adj 15): empty #31
,W/Settings( 3866): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TimaKeyStoreProvider( 3967): TimaSignature is unavailable
,D/ActivityThread( 3967): Added TimaKeyStore provider
,W/AudioCapabilities( 3866): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3866): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3866): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3866): Unsupported mime audio/evrc
,W/ResourcesManager( 3967): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3866): Unsupported mime video/wvc1
,W/VideoCapabilities( 3866): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3866): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3866): Unsupported mime video/wvc1
,W/VideoCapabilities( 3866): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3866): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3866): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3866): Unsupported mime video/mp43
,W/VideoCapabilities( 3866): Unsupported mime video/sorenson
,W/VideoCapabilities( 3866): Unsupported mime video/mp4v-esdp
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3885): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3885): Resource data:2131165186
,I/Gmail   ( 3623): getAccountsCursor
,I/VideoCapabilities( 3866): Unsupported profile 4 for video/mp4v-es
,W/ResourcesManager( 3885): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3885): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 3967): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 3967): savePreference: key = previous_sys_time value = 1451341441301
,I/KnoxUsageLogPro( 3967): premStatus:2
,I/KnoxUsageLogPro( 3967): isEulaShown : false
I/KnoxUsageLogPro( 3967): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1015): Killing 3132:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3058/cgroup.procs: No such file or directory
,I/System.out( 3952): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 3952): Inside WakeupProvider
,I/AMMetaDataParserService( 3885): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3885): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,I/KnoxUsageLogPro( 3967): savePreference: key = previous_elapsed_time value = 38479
,W/libprocessgroup( 1015): failed to open /acct/uid_10117/pid_2721/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3132/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/Babel   ( 3866): babel boot account: SMS
,I/AMMetaDataParserService( 3885): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,V/Babel   ( 3866): babel boot account: thalitester@gmail.com
,I/ActivityManager( 1015): Killing 1579:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3992): MountEmulatedStorage()
E/Zygote  ( 3992): v2
,I/libpersona( 3992): KNOX_SDCARD checking this for 1000
I/libpersona( 3992): KNOX_SDCARD not a persona
,I/SELinux ( 3992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3885): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/SELinux ( 3992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3992 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.f,irefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
V/AlarmManager( 1015): waitForAlarm result :4
I/VlingoApplication( 3952): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 3108:com.google.android.configupdater/u0a82 (adj 15): empty #31
D/TimaKeyStoreProvider( 3992): TimaSignature is unavailable
D/ActivityThread( 3992): Added TimaKeyStore provider
W/ContextImpl( 3885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,V/AlarmManager( 1015): waitForAlarm result :4
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131034113
,I/VlingoAndroidCore( 3952): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ResourcesManager( 3885): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3885): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3885): took 2.304271ms for 0*0 texture 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3885): took 6.072969ms for 0*0 texture 0
,I/GFX raster( 3885): took 9.651302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb92775c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb927a540 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 1817): COMPAT: Multi user not supported
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3885): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10068/pid_1579/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10082/pid_3108/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1817): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3885): took 0.888644ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb92775c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb929bb98 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3885): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/Zygote  ( 4016): MountEmulatedStorage()
,E/Zygote  ( 4016): v2
I/libpersona( 4016): KNOX_SDCARD checking this for 1000
I/libpersona( 4016): KNOX_SDCARD not a persona
,I/SELinux ( 4016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4016 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/Icing   ( 1817): updateResources: need to parse f{com.google.android.gms}
,I/CheckinService( 1817): Checkin interval check for package: unspecified last checkin: 1451292302959 min interval config: 0 actual interval: 49138764
,D/TimaKeyStoreProvider( 4016): TimaSignature is unavailable
D/ActivityThread( 4016): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/VlingoApplication( 3952): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3952): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/CheckinService( 1817): Disabling old GoogleServicesFramework version
,E/KnoxSetupWizardClient( 4016): isShipMode : 1
I/KnoxSetupWizardClient( 4016): onReceive : android.intent.action.BOOT_COMPLETED
,D/DialogFlow( 3952): initQueue()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3885): took 2.267136ms for 0*0 texture 0
,D/SystemUpdateService( 1817): onCreate
,D/ShortcutReceiver( 4016):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/GFX generate_partition_tables( 3885): took 7.562343ms for 0*0 texture 0
,I/GFX raster( 3885): took 10.766457ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb927a540 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb929b018 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4040): MountEmulatedStorage(),
E/Zygote  ( 4040): v2
I/libpersona( 4040): KNOX_SDCARD checking this for 10029
I/libpersona( 4040): KNOX_SDCARD not a persona,
D/KnoxShortcutUtil( 4016): getIsShortcutMigrationFor_2_3_0_Done true
D/ShortcutReceiver( 4016):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4016):  shortcut migration not required 
,I/SELinux ( 4040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4040 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 3176:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/SELinux ( 4040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 4040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3885): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/Zygote  ( 4048): MountEmulatedStorage()
E/Zygote  ( 4048): v2
I/libpersona( 4048): KNOX_SDCARD checking this for 1000
I/libpersona( 4048): KNOX_SDCARD not a persona
I/SELinux ( 4048): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4048 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3192:com.dropbox.android/u0a88 (adj 15): empty #31
,I/SELinux ( 4048): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4048): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/System.err( 4016): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4016): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4016): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4016): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4016): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4016): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4016): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/GFX raster( 3885): took 0.726563ms for 96*96 texture 0
D/TimaKeyStoreProvider( 4040): TimaSignature is unavailable
,D/ActivityThread( 4040): Added TimaKeyStore provider
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929bb98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb929b018 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4048): TimaSignature is unavailable
,D/ActivityThread( 4048): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3885): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.826719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929b018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9292f90 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 1817): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/AMMetaDataParserService( 3885): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/CheckinService( 1817): Checking schedule, now: 1451341441974 next: 1451859229870
,I/CheckinService( 1817): active receiver: disabled
,D/StatusChecker( 4048): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4048): onReceive : net.mt.init : DONE
,V/AuthZen ( 1817): Handling intent: android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4076): MountEmulatedStorage()
E/Zygote  ( 4076): v2
I/libpersona( 4076): KNOX_SDCARD checking this for 10113
I/libpersona( 4076): KNOX_SDCARD not a persona
,I/SELinux ( 4076): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4076 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3223:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
I/SELinux ( 4076): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 4076): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4076): TimaSignature is unavailable
,D/ActivityThread( 4076): Added TimaKeyStore provider
,I/SystemUpdateService( 1817): cancelUpdate (empty URL)
,I/SystemUpdateService( 1817): active receiver: disabled
,D/AuthZenEventHandler( 1817): Handling event: android.intent.action.BOOT_COMPLETED
,D/ChimeraCfgMgr( 1817): Loading module com.google.android.gms.gass from APK com.google.android.gms
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.710520ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9283bf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9292f90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/BootCompletedReceiver( 1817): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1817): Got an BootCompleted event.
,W/BaseAppContext( 1817): Using Auth Proxy for data requests.
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.685313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9292f90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9280418 counterpartCT=4 counterpartW=96 counterparth=96
,D/BootCompletedReceiver( 1817): Will NOT schedule AdAttestation signal task because it's disabled.
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/art     ( 3952): Suspending all threads took: 9.942ms
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.544427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb928fe70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb928ffc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/PageBuddyNotiSvc( 4076): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3885): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131034113
,I/AMMetaDataParserService( 3885): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.820677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb92775c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9283490 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3885): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533,
,W/ContextImpl( 4076): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,E/BaseAppContext( 1817): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/Zygote  ( 4094): MountEmulatedStorage()
E/Zygote  ( 4094): v2
I/libpersona( 4094): KNOX_SDCARD checking this for 10030
I/libpersona( 4094): KNOX_SDCARD not a persona
,I/SELinux ( 4094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4094 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3256:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,E/SELinux ( 4094): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PageBuddyNotiSvc( 4076): onCreate mCpBitFlag=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4094): TimaSignature is unavailable
,D/ActivityThread( 4094): Added TimaKeyStore provider
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3885): took 0.831458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb92775c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9280068 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4114): MountEmulatedStorage()
E/Zygote  ( 4114): v2
I/libpersona( 4114): KNOX_SDCARD checking this for 10121
I/libpersona( 4114): KNOX_SDCARD not a persona
I/SELinux ( 4114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4114): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3885): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4114 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3176/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10088/pid_3192/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10088/pid_3223/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4114): TimaSignature is unavailable
,D/ActivityThread( 4114): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10146/pid_3256/cgroup.procs: No such file or directory
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.612188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb927a540 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9283c48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3885): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 4114): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4114): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4114): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SystemUpdateService( 1817): onDestroy
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.626094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929bb98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb929beb8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3885): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1817): Fetching signing key...
,D/QuickConnect( 4114): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1015): name = scon_is_running
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10121
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.823750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929b018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9269658 counterpartCT=4 counterpartW=96 counterparth=96
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4114): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4114): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/AMMetaDataParserService( 3885): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/QuickConnect( 4114): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 4930(203KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 859us total 36.559ms
,E/Zygote  ( 4133): MountEmulatedStorage()
I/libpersona( 4133): KNOX_SDCARD checking this for 10127
E/Zygote  ( 4133): v2
I/libpersona( 4133): KNOX_SDCARD not a persona
,I/SELinux ( 4133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4133 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 4133): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4133): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3279:com.policydm/1000 (adj 15): empty #31
,W/SQLiteConnectionPool( 1629): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/TimaKeyStoreProvider( 4133): TimaSignature is unavailable
,D/ActivityThread( 4133): Added TimaKeyStore provider
,I/AuthZen ( 1817): Signing key fetched successfully!
,W/BaseAppContext( 1817): Using Auth Proxy for data requests.
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 4133): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4133): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4133): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4133): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/GFX raster( 3885): took 0.732240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9283bf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9269658 counterpartCT=4 counterpartW=96 counterparth=96
,D/a       ( 1817): Opening database auth.proximity.permit_store...,
I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/AuthZenTransactionCache( 1817): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1817): Clearing transaction cache
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.686719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9292f90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb927fb50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ResourcesManager( 4094): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4094): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4094): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3279/cgroup.procs: No such file or directory
,W/ResourcesManager( 4094): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4094): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4094): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/GCM     ( 1676): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/GCoreUlr( 1676): DispatchingService.onCreate()
,W/ResourcesManager( 4094): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4094): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.550105ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb928fe70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb928b1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SBrowserFeatureFlag( 4133): initialized in static block : loadCscFeatureValue() succeed! 
,I/AMMetaDataParserService( 3885): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3885): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3885): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3885): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131034112
I/AMMetaDataParserService( 3885): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3885): took 0.589740ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929bb98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9293150 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3885): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/ManifestProvider( 4133): onCreate()
,E/NetworkSettingsReceiver( 4133): onReceive: android.intent.action.BOOT_COMPLETED
,I/System.out( 3952): INFO:Resource not found:/Common.properties Using default values
,W/System.err( 4133): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4133): 	at java.lang.Class.getMethod(Class.java:665)
,W/System.err( 4133): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4133): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4133): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4133): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
,W/System.err( 4133): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4133): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
,W/System.err( 4133): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4133): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
,W/System.err( 4133): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4133): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 4133): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4133): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 4133): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4133): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4133): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4133): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@67e824b
,D/SBrowserFeatureFlag( 4133): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4133): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4161): MountEmulatedStorage()
E/Zygote  ( 4161): v2
I/libpersona( 4161): KNOX_SDCARD checking this for 10131
I/libpersona( 4161): KNOX_SDCARD not a persona
,I/SELinux ( 4161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4161 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 4161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4161): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 3372:com.fmm.dm/1000 (adj 15): empty #31
I/GCM     ( 1676): GCM config loaded
,I/art     (  305): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 26.879ms
,D/TimaKeyStoreProvider( 4161): TimaSignature is unavailable
,D/ActivityThread( 4161): Added TimaKeyStore provider
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 17.397ms
E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3885): took 0.602187ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929bb98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92aaaa8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3885): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 19.525ms
,E/SMD     (  289): DCD OFF
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3372/cgroup.procs: No such file or directory
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PCWCLIENTTRACE_AccountAppFacade2_0( 3478): unregister AuthInfo UpdateReceiver v2.0
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 4161): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4161): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4161): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.662553ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb92931e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9293290 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1676): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3885): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 1.305521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9293290 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92900b8 counterpartCT=4 counterpartW=96 counterparth=96
W/art     ( 3952): Suspending all threads took: 6.809ms
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/ActivityManager( 1015): Killing 3398:com.sec.esdk.elm/u0a90 (adj 15): empty #31
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupLis,tActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131034113
I/AMMetaDataParserService( 3885): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3885): took 0.817031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929b018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb929bb98 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3885): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3885): took 0.827240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929b018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9283988 counterpartCT=4 counterpartW=96 counterparth=96
,W/Auth    ( 1676): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AMMetaDataParserService( 3885): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 39282(2MB) AllocSpace objects, 18(480KB) LOS objects, 40% free, 9MB/16MB, paused 1.521ms total 119.999ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.614427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb92a9778 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9040d48 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3885): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/daemonapp( 1762): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.603646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb929bb98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb927a540 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3885): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.915989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb8ffbd28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9283988 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1015): failed to open /acct/uid_10090/pid_3398/cgroup.procs: No such file or directory
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/AMMetaDataParserService( 3885): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.640781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9293290 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92775c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/SSRM:n  ( 1015): SIOP:: AP = 410
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.680469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9040d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb927a540 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3885): took 0.519479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9283988 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92775c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3885): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4040): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4040): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 36338(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 22MB/34MB, paused 25.639ms total 179.035ms
,W/GCoreFlp( 1676): No location to return for getLastLocation()
,W/FusedLocationProvider( 1676): location=null
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 4204): MountEmulatedStorage()
,E/Zygote  ( 4204): v2
I/libpersona( 4204): KNOX_SDCARD checking this for 10037
I/libpersona( 4204): KNOX_SDCARD not a persona
,I/SELinux ( 4204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4204 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 4204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4204): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/Process ( 4094): Sending signal. PID: 4094 SIG: 9
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/GCoreFlp( 1676): No location to return for getLastLocation()
W/FusedLocationProvider( 1676): location=null
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4204): TimaSignature is unavailable
,D/ActivityThread( 4204): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard,
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131165203
,W/ResourcesManager( 3885): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3885): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3885): took 3.902656ms for 0*0 texture 0,
I/ActivityManager( 1015): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4219 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/Zygote  ( 4219): MountEmulatedStorage()
E/Zygote  ( 4219): v2
,I/libpersona( 4219): KNOX_SDCARD checking this for 10135
I/libpersona( 4219): KNOX_SDCARD not a persona
,I/SELinux ( 4219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/GCoreUlr( 1676): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/SELinux ( 4219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 4204): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PersistentNotificationBroadcastReceiver( 1676): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/GFX generate_partition_tables( 3885): took 17.171303ms for 0*0 texture 0
,I/GFX raster( 3885): took 21.661199ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9600ca8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb9601968 counterpartCT=4 counterpartW=80 counterparth=80
,D/TimaKeyStoreProvider( 4219): TimaSignature is unavailable
,D/ActivityThread( 4219): Added TimaKeyStore provider
,I/ActivityManager( 1015): Process com.sec.android.app.sns3 (pid 4094)(adj 0) has died(21,664)
,I/GCoreUlr( 1676): Unbound from all location providers
I/GCoreUlr( 1676): Place inference reporting - stopped
,I/AMMetaDataParserService( 3885): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3885): took 2.347136ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3885): took 5.090574ms for 0*0 texture 0,
W/ResourcesManager( 4219): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,I/GFX raster( 3885): took 8.516199ms for 80*80 texture 0
W/ResourcesManager( 4219): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb960b4d0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb960b578 counterpartCT=4 counterpartW=80 counterparth=80
W/ResourcesManager( 4219): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.,
W/ResourcesManager( 4219): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4219): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4238): MountEmulatedStorage(),
E/Zygote  ( 4238): v2
I/libpersona( 4238): KNOX_SDCARD checking this for 10031
I/SELinux ( 4238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4238): KNOX_SDCARD not a persona,
I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4238 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 4238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/Icing   ( 1817): Internal init done: storage state 0
,I/CalendarProvider2( 4204): CalendarProvider2.onCreate() called
,I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec,
D/TimaKeyStoreProvider( 4238): TimaSignature is unavailable
D/ActivityThread( 4238): Added TimaKeyStore provider,
,I/AMMetaDataParserService( 3885): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/art     ( 3952): Suspending all threads took: 14.914ms
,I/GCoreUlr( 1676): DispatchingService.onDestroy()
I/GCoreUlr( 1676): Stopping handler for UlrDispSvcFast
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1817): Post-init done
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4256): MountEmulatedStorage()
E/Zygote  ( 4256): v2
I/libpersona( 4256): KNOX_SDCARD checking this for 10026
I/libpersona( 4256): KNOX_SDCARD not a persona
,I/SELinux ( 4256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4256 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4256): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4256): TimaSignature is unavailable
,D/ActivityThread( 4256): Added TimaKeyStore provider
,I/GCoreUlr( 1676): Unbound from all location providers
I/GCoreUlr( 1676): Place inference reporting - stopped
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4272): MountEmulatedStorage()
E/Zygote  ( 4272): v2
I/libpersona( 4272): KNOX_SDCARD checking this for 10141
I/libpersona( 4272): KNOX_SDCARD not a persona
,I/SELinux ( 4272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4272): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4272 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 3471:com.sec.factory.camera/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4272): TimaSignature is unavailable
,D/ActivityThread( 4272): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4272): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4272): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4272): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4272): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3471/cgroup.procs: No such file or directory
,E/Zygote  ( 4289): MountEmulatedStorage(),
,E/Zygote  ( 4289): v2
I/libpersona( 4289): KNOX_SDCARD checking this for 1000
I/libpersona( 4289): KNOX_SDCARD not a persona
I/SELinux ( 4289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4289 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3507:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4289): TimaSignature is unavailable
,D/ActivityThread( 4289): Added TimaKeyStore provider
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/libprocessgroup( 1015): failed to open /acct/uid_10095/pid_3507/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4312): MountEmulatedStorage()
E/Zygote  ( 4312): v2
I/libpersona( 4312): KNOX_SDCARD checking this for 10068
I/libpersona( 4312): KNOX_SDCARD not a persona
,I/SELinux ( 4312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4312 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,I/SELinux ( 4312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4312): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4289): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4289): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4289): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4289): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 4289): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,D/TimaKeyStoreProvider( 4312): TimaSignature is unavailable
,I/DBG_POLICYDM( 4289): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
D/ActivityThread( 4312): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4289): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 4289): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 4289): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4289): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4289): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4289): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4337): MountEmulatedStorage()
E/Zygote  ( 4337): v2
I/libpersona( 4337): KNOX_SDCARD checking this for 10032
I/libpersona( 4337): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4337 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 4337): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 4312): onCreate
,D/BadgeProvider( 4312): DatabaseHelper
,E/Zygote  ( 4352): MountEmulatedStorage()
E/Zygote  ( 4352): v2
I/libpersona( 4352): KNOX_SDCARD checking this for 10142
I/libpersona( 4352): KNOX_SDCARD not a persona
,I/SELinux ( 4352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 4337): TimaSignature is unavailable
D/ActivityThread( 4337): Added TimaKeyStore provider
,I/SELinux ( 4352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4352 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3556:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
I/ActivityManager( 1015): Killing 3540:com.fmm.ds/1000 (adj 15): empty #32
,D/TimaKeyStoreProvider( 4352): TimaSignature is unavailable
,D/ActivityThread( 4352): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4289): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4289): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,W/ResourcesManager( 4352): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4289): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,D/BadgeProvider( 4312): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider( 4312): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4312): sendNotify, [notify] : null
D/BadgeProvider( 4312): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4312): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4312): update, [UpdateCount] : 1
,D/Launcher.Model( 1478): reloadBadges entered.
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4289): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4289): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4289): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,W/ActivityManager( 1015): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/DBG_POLICYDM( 4289): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/31/10:27:55
,I/DBG_POLICYDM( 4289): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/28/23:24:04
,I/DBG_POLICYDM( 4289): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4289): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/Process ( 4272): Sending signal. PID: 4272 SIG: 9
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3885): took 0.691771ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb960b4d0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb96081f8 counterpartCT=4 counterpartW=80 counterparth=80
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4289): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/AMMetaDataParserService( 3885): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/DBG_POLICYDM( 4289): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4289): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4289): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4289): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4289): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 4289): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/ActivityManager( 1015): Process com.android.email (pid 4272)(adj 9) has died(32,640)
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
D/Finsky  ( 4256): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 4337): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4337): [PushClientApplication] Push log off : This is Ship build version
,E/Zygote  ( 4382): MountEmulatedStorage()
,E/Zygote  ( 4382): v2,
I/libpersona( 4382): KNOX_SDCARD checking this for 1000
I/libpersona( 4382): KNOX_SDCARD not a persona
,I/SELinux ( 4382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4382 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/DBG_POLICYDM( 4289): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 4289): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,E/SPPClientService( 4337): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/SPPClientService( 4337): PushLog.txt file is not deleted.
,D/SPPClientService( 4337): PushLog.txt file is not deleted.
,D/SPPClientService( 4337): ============PushLog. stop!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4397): MountEmulatedStorage(),
E/Zygote  ( 4397): v2
I/libpersona( 4397): KNOX_SDCARD checking this for 10141
I/ActivityManager( 1015): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4397 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/libpersona( 4397): KNOX_SDCARD not a persona
,I/SELinux ( 4397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4382): TimaSignature is unavailable
,D/ActivityThread( 4382): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 28.549ms
,D/TimaKeyStoreProvider( 4397): TimaSignature is unavailable
D/ActivityThread( 4397): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 3586:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 668us total 20.048ms
,V/AlarmManager( 1015): waitForAlarm result :8
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 18.789ms
,E/Zygote  ( 4416): MountEmulatedStorage(),
E/Zygote  ( 4416): v2
I/libpersona( 4416): KNOX_SDCARD checking this for 10036
I/libpersona( 4416): KNOX_SDCARD not a persona
,I/SELinux ( 4416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4416 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4416): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 4397): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4397): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4397): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/ResourcesManager( 4397): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 3604:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4289): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4289): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3885): took 0.850677ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb960b4d0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb9601008 counterpartCT=4 counterpartW=80 counterparth=80
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4416): TimaSignature is unavailable
,D/ActivityThread( 4416): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3885): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575,
,E/Zygote  ( 4432): MountEmulatedStorage(),
E/Zygote  ( 4432): v2
I/libpersona( 4432): KNOX_SDCARD checking this for 1000
I/libpersona( 4432): KNOX_SDCARD not a persona
,I/SELinux ( 4432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4432): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4432 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3645:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
D/BluetoothAdapter( 3331): disable()
,D/TimaKeyStoreProvider( 4432): TimaSignature is unavailable
D/ActivityThread( 4432): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10055/pid_3556/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3540/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10056/pid_3586/cgroup.procs: No such file or directory
D/SettingsProvider( 1015): name = bluetooth_on
W/libprocessgroup( 1015): failed to open /acct/uid_10098/pid_3604/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothAdapterState( 2632): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/BluetoothAdapterProperties( 2632): Setting state to 13
I/BluetoothAdapterState( 2632): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2632): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2632): updateAdapterState state is 13
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3885): took 0.629062ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9290300 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb9609608 counterpartCT=4 counterpartW=80 counterparth=80
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2632): Autoconnection is available 
,D/BluetoothAdapterService( 2632): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2632): terminating service from this receiver
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2632): onBluetoothDisable()
D/BluetoothAdapterProperties( 2632): mDiscovering is false
,D/SecContentProvider( 1015): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2632): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothPbapService( 2632): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: false pid=3331, uid=10334
,D/SettingsProvider( 1015): name = wifi_on
,D/BluetoothSocket( 2632): close() in, this: android.bluetooth.BluetoothSocket@32120ef7, channel: 19, state: LISTENING
D/BluetoothSocket( 2632): close() this: android.bluetooth.BluetoothSocket@32120ef7, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@146a0b91, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c49d164mSocket: android.net.LocalSocket@2092cfcd impl:android.net.LocalSocketImpl@1f612082 fd:FileDescriptor[74]
D/BluetoothSocket( 2632): Closing mSocket: android.net.LocalSocket@2092cfcd impl:android.net.LocalSocketImpl@1f612082 fd:FileDescriptor[74]
,I/ActivityManager( 1015): Killing 3668:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/jxcore-log( 3331): ****TEST TOOK:  5137  ms ****
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3331): 
,E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1406): reset timer : RESET_TIMER 0
W/libprocessgroup( 1015): failed to open /acct/uid_10058/pid_3645/cgroup.procs: No such file or directory
I/wpa_supplicant( 1406): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1406): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1406): Scan requested (ret=0) - scan timeout 30 seconds
D/BluetoothAdapterProperties( 2632): Scan Mode:20
D/BluetoothAdapterState( 2632): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2632): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 2632): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/bt-btif ( 2632): cmd socket is not created
,E/bt-btm  ( 2632): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 2632): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/btif_config_util( 2632): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 2632): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x001b not found for deregistration
,I/AMMetaDataParserService( 3885): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =13
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/BluetoothTile( 1172):  onBluetoothStateChange:
,D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1172): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1172):  getBluetoothState : 13
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,D/BluetoothTile( 1172):  handleUpdatestate:false name:null
,I/SamsungIME( 1795): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothSocket( 2632): close() in, this: android.bluetooth.BluetoothSocket@36849fd0, channel: 5, state: LISTENING
,D/BluetoothSocket( 2632): close() this: android.bluetooth.BluetoothSocket@36849fd0, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d34af6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a099bc9mSocket: android.net.LocalSocket@3a04c2ce impl:android.net.LocalSocketImpl@20b5e5ef fd:FileDescriptor[76]
,D/BluetoothSocket( 2632): Closing mSocket: android.net.LocalSocket@3a04c2ce impl:android.net.LocalSocketImpl@20b5e5ef fd:FileDescriptor[76]
,D/SecurityLogAgent( 4432): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4432): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4432): StateMachine : Current State = 1
D/SecurityLogAgent( 4432): BootReceiver : completed task. Failed to return wakelock . 
,D/STATUSBAR-QSTileView( 1172): onStateChanged: Bluetooth
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4256): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3668/cgroup.procs: No such file or directory
,I/GAV2    ( 3623): Thread[GAThread,5,main]: No campaign data found.
D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,E/Zygote  ( 4476): MountEmulatedStorage()
I/libpersona( 4476): KNOX_SDCARD checking this for 10148
E/Zygote  ( 4476): v2
I/libpersona( 4476): KNOX_SDCARD not a persona
,I/SELinux ( 4476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4476 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 4476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Killing 3301:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
E/SELinux ( 4476): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1676): Read error: ssl=0xb94b72f8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1676): SSL shutdown failed: ssl=0xb94b72f8: I/O error during system call, Broken pipe,
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/GAV2    ( 3355): Thread[GAThread,5,main]: No campaign data found.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1015): Tagging socket 341 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
E/ConnectivityService( 1015): updateNetworkInfo()
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,I/qtaguid ( 1015): Untagging socket 341
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
,D/TimaKeyStoreProvider( 4476): TimaSignature is unavailable
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityThread( 4476): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiP2pService( 1015): InactiveState{ what=131204 }
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/WifiP2pService( 1015): P2pEnabledState{ what=131204 }
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiP2pService( 1015): sending p2p connection changed broadcast: FAILED
,D/WifiScanningService( 1015): SCAN_AVAILABLE : 1
D/WifiScanningService( 1015): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 1015): SCAN_AVAILABLE : 1
D/RttService( 1015): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
D/WifiDisplayController( 1015): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1015): onP2pDisconnected
,D/IpRemoteDisplayController( 1015): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1015): WfdBridgeServer is already null
D/WifiP2pService( 1015): sending p2p connection changed broadcast: DISCONNECTED
,E/WifiStateMachine( 1015): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1015): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1015): disconnect
D/WifiDisplayController( 1015): updateConnection
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiP2pService( 1015): P2pDisablingState
,D/AllShareCastTile( 1172): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/Settings( 4256): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiP2pService( 1015): P2pDisablingState{ what=147458 }
,D/WifiP2pService( 1015): p2p socket connection lost
W/Settings( 4256): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiP2pService( 1015): P2pDisabledState
,D/WifiDisplayController( 1015): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1015): onP2pDisconnected
D/IpRemoteDisplayController( 1015): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1015): WfdBridgeServer is already null
,D/WifiP2pService( 1015): P2pDisabledState{ what=143375 }
,I/SA      ( 4416): [SSP] onCreated
D/WifiP2pService( 1015): DefaultState{ what=143375 }
,D/AllShareCastTile( 1172): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10008/pid_3301/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/BadgeProvider( 4312): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,I/bt_userial_mct( 2632): exiting userial_read_thread
D/bt_userial_mct( 2632): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2632): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2632): hw_epilog_process
D/bt_userial_mct( 2632): userial_close
I/bt_vendor( 2632): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,W/bt-l2cap( 2632): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2632): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2632): ag scb idx 1 not allocated
W/bt-btif ( 2632): ag scb idx 2 not allocated
E/bt-btif ( 2632): BTA AG is already disabled, ignoring ...
,I/Process ( 4352): Sending signal. PID: 4352 SIG: 9
,D/BadgeProvider( 4312): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4312): sendNotify, [notify] : null
D/BadgeProvider( 4312): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4312): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4312): update, [UpdateCount] : 1
D/Launcher.Model( 1478): reloadBadges entered.
,I/SA      ( 4416): [TPM] There is no property file
,V/AlarmManager( 1015): waitForAlarm result :4
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
I/SA      ( 4416): [SCU] isHaveSA() - false
D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityManager.CallbackHandler( 1817): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1455): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1455): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,I/SA      ( 4416): [TPM] getModelProperty : null,
I/SA      ( 4416): [TPM] getCSCProperty : null
,E/        ( 3885): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80,
I/GFX raster( 3885): took 0.622240ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3885): Bitmap=0xb9290300 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8edb138 counterpartCT=4 counterpartW=80 counterparth=80
,I/SA      ( 4416): [DM] FLOATING AMOLED FEATURE: true,
I/SA      ( 4416): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4416): [DM] TFT FEATURE: false
,I/wpa_supplicant( 1406): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): updateIfacesLocked()
I/SA      ( 4416): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
V/NetworkStats( 1015): performPollLocked(flags=0x1)
I/SA      ( 4416): [DM] init START
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,V/NetworkStats( 1015): performPollLocked() took 6ms
,I/ActivityManager( 1015): Process com.android.exchange (pid 4352)(adj 11) has died(27,632)
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,I/AMMetaDataParserService( 3885): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): EthernetConnected: false
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE,
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
E/SQLiteLog( 4476): (284) automatic index on shooting_modes(title_id)
,I/SA      ( 4416): [DM] This device is not a Vodafone
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
W/ContextImpl( 3885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/wpa_supplicant( 1406): Blacklist: Clear (all) 
,I/bt_vendor( 2632): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 2632): bluetooth satus is on
I/bt_vendor( 2632): bt-vendor : resetting BT status
,I/bt_vendor( 2632): Starting hciattach daemon
I/bt_vendor( 2632): try to set false
I/bt_vendor( 2632): Starting hciattach daemon
,I/bt_vendor( 2632): try to set false
,I/bt_vendor( 2632): cleanup
,I/GKI_LINUX( 2632): gki_task task_id=0 [BTU] terminating,
,I/wpa_supplicant( 1406): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 32887(1752KB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 22MB/33MB, paused 3.032ms total 233.446ms
,I/GKI_LINUX( 2632): GKI_exit_task 0 done
I/GKI_LINUX( 2632): GKI_shutdown(): task [BTU] terminated
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
E/ConnectivityService( 1015): updateNetworkInfo()
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,W/ResourceType( 4416): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4416): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4416): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4416): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4416): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4416): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,I/wpa_supplicant( 1406): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1406): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1406): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1406): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1406): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
D/Tethering( 1015): InitialState.processMessage what=4
W/ResourceType( 4416): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4416): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4416): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4416): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,E/Tethering( 1015): No numeric data
,W/ResourceType( 4416): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,D/AndroidRuntime( 4471): 
D/AndroidRuntime( 4471): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothAdapterState( 2632): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
W/ResourceType( 4416): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4416): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4416): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,D/BtConfig.SecureMode( 2632): isSecureModeOn:false
D/BluetoothAdapterService( 2632): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/ResourceType( 4416): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4416): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4416): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4416): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75),
W/ResourceType( 4416): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
W/ResourceType( 4416): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4416): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4416): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75),
W/ResourceType( 4416): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4416): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75),
W/ResourceType( 4416): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4416): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/AndroidRuntime( 4471): CheckJNI is OFF
,D/AndroidRuntime( 4471): readGMSProperty: start
D/AndroidRuntime( 4471): readGMSProperty: already setted!!
D/AndroidRuntime( 4471): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4471): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4471): readGMSProperty: end
D/AndroidRuntime( 4471): addProductProperty: start
,W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.gatt.GattService
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1172): Wifi onReceive(0)
,D/HotspotTile( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1172): onStateChanged: Wi-Fi
,D/HotspotTile( 1172): onReceive : 0, 0
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
I/CalendarProvider2( 4204): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/SA      ( 4416): [SCU] isHaveSA() - false
I/SA      ( 4416): support phone number id : false
I/SA      ( 4416): [DM] Supports Ref Jpn : true
I/SA      ( 4416): [DM] init END
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{289cf5ae u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.DebugUtils( 2632): handleDebugAction() action=null
W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 2632): Received stop request...Stopping profile...
D/BtGatt.GattService( 2632): stop()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/BtGatt.AdvertiseManager( 2632): advertise clients cleared
W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.hfp.HeadsetService
I/SA      ( 4416): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4416): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4512): MountEmulatedStorage()
I/libpersona( 4512): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4512): v2
I/libpersona( 4512): KNOX_SDCARD not a persona
,I/SELinux ( 4512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1015): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4512 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4512): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.a2dp.A2dpService
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131099648
I/wpa_supplicant( 1406): Blacklist: Clear (all) 
W/ResourcesManager( 3885): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): getResourceName:com.android.mms:xml/assistant_messaging
W/ResourcesManager( 3885): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,W/ResourcesManager( 3885): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1172): updateTetherState():false, false
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2af22f
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4416): [OR] onReceive END
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked() took 9ms
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/HeadsetService( 2632): Received stop request...Stopping profile...
W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.hid.HidService
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2af22f
D/AudioService( 1015): onServiceDisconnected: Bluetooth profile: 1
,D/TimaKeyStoreProvider( 4512): TimaSignature is unavailable
,D/ActivityThread( 4512): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/AMMetaDataParserService( 3885): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.hdp.HealthService
,I/wpa_supplicant( 1406): wlan0: CTRL-EVENT-TERMINATING 
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/SA      ( 4416): [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
I/SA      ( 4416): [ODM] queryOpenData(key= GEO_IP )
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.pan.PanService,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
I/SA      ( 4416): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4416): [LBE] REF_JPN : true
I/SA      ( 4416): [BDC] create
W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.map.BluetoothMapService
I/AMMetaDataParserService( 3885): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2632): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2632): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2632): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2632): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2632): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2632): Stopping profile services that were post enabled
E/BluetoothAdapterService(2814511)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/A2dpService( 2632): Received stop request...Stopping profile...
D/A2dpStateMachine( 2632): Exit Disconnected: -1,
,D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2af22f
,I/ActivityManager( 1015): Killing 3689:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,D/BluetoothA2dp( 1015): Proxy object disconnected
D/AudioService( 1015): onServiceDisconnected: Bluetooth profile: 2
,E/BluetoothAdapterService(2814511)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.hid.HidService
,W/BluetoothHeadsetServiceJni( 2632): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2632): Cleaning up Bluetooth Handsfree callback object
,D/HidService( 2632): Received stop request...Stopping profile...
D/HidService( 2632): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2632): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2632): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2632): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2af22f
,D/HealthService( 2632): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2af22f
,D/PanService( 2632): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2af22f
,D/BluetoothPan( 1015): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 2632): Received stop request...Stopping profile...
,D/Volley  ( 4256): [643] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4256): [636] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1015): Killing 3742:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/Ads     ( 4256): Skipping gmscore version check
,I/ActivityManager( 1015): Killing 3714:com.wssnps/1000 (adj 15): empty #32
,D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2af22f
,I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,D/SapService( 2632): Received stop request...Stopping profile...
D/SapService( 2632): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2af22f
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [21]
E/BluetoothAdapterService(2814511)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2632): Proxy object disconnected
D/BluetoothAdapterService( 2632): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 2632): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2632): GKI_exit_task 2 done
I/GKI_LINUX( 2632): GKI_shutdown(): task [A2DP-MEDIA] terminated
E/BluetoothAdapterService(2814511)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(2814511)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2632): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2632): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(2814511)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/Settings( 3866): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/BluetoothPanServiceJni( 2632): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2632): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(2814511)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2632): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(2814511)( 2632): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 2632): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2632): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1172): Wifi onReceive(1)
D/STATUSBAR-QSTileView( 1172): onStateChanged: Wi-Fi
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/HotspotTile( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1172): onReceive : 1, 0
,D/BluetoothAdapterState( 2632): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2632): Setting state to 10
I/BluetoothAdapterState( 2632): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2632): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2632): updateAdapterState state is 10
D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothAdapterService( 2632): Autoconnection is available 
D/BluetoothAdapterService( 2632): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2632): Entering OffState
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 1676): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SA      ( 4416): [DBMV2] getEmailID
,I/ApplicationPolicy( 1015): updateDataUsageMap
,I/SA      ( 4416): [DBMV2] getDataV02ForItems
I/SA      ( 4416): [SSP] query invoked
,I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/SA      ( 4416): [SCU] get signed id from samsung account2.0 DB.
,I/DBG_DM  ( 3241): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,D/BluetoothA2dp( 2632): onBluetoothStateChange: up=false
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 3794:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10013/pid_3689/cgroup.procs: No such file or directory
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/BluetoothA2dp( 1015): onBluetoothStateChange: up=false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3714/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothAdapter( 3331): onBluetoothStateChange: up=false
D/BluetoothAdapter( 3331): Bluetooth is turned off, stop adv and scan
,I/SA      ( 4416): [SCU] get signed id from samsung account1.0 DB.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3885): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
D/BluetoothAdapter( 1440): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1440): Bluetooth is turned off, stop adv and scan
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BluetoothAdapter( 2632): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2632): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 3952): onBluetoothStateChange: up=false
D/BluetoothAdapter( 3952): Bluetooth is turned off, stop adv and scan
I/SA      ( 4416): [BDC] destroy
,D/BluetoothAdapter( 1676): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1676): Bluetooth is turned off, stop adv and scan
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 1455): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1455): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1427): onBluetoothStateChange: up=false,
D/BluetoothAdapter( 1427): Bluetooth is turned off, stop adv and scan
D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/BluetoothAdapter( 1172): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1172): Bluetooth is turned off, stop adv and scan
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 1015): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1015): Bluetooth is turned off, stop adv and scan
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/iu.UploadsManager( 1817): End new media; added: 0, uploading: 0, time: 665 ms
D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/Finsky  ( 4256): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/BluetoothAdapter( 1172): 363085998: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1172):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1172): 363085998: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1172):  getBluetoothState : 10
,D/BluetoothTile( 1172): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
E/AffinityControl( 4471): AffinityControl: registerfunction enter
D/BluetoothAdapter( 1172): 363085998: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1172): 363085998: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1172): 363085998: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
I/SamsungIME( 1795): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/Finsky  ( 4256): [1] Libraries$2.run: Finished loading 1 libraries.
D/PhoneStatusBar( 1172): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GKI_LINUX( 2632): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2632): GKI_exit_task 1 done
I/GKI_LINUX( 2632): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2632): cleanupNative: return from cleanup
,D/Finsky  ( 4256): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,D/AndroidRuntime( 4471): Calling main entry com.android.commands.pm.Pm,
I/art     ( 2632): System.exit called, status: 0,
I/AndroidRuntime( 2632): VM exiting with result code 0, cleanup skipped.
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3885): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/BluetoothAdapter( 1676): 878716922: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1676): 878716922: getState() :  mService = null. Returning STATE_OFF
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131099648
,I/AMMetaDataParserService( 3885): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{906185185}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1015): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1015): !@killApplicatoin: 10334, uninstall pkg
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10334 user=-1: uninstall pkg
I/ActivityManager( 1015): Killing 3331:com.example.hello/u0a334 (adj 0): stop com.example.hello cause uninstall pkg
,I/AMMetaDataParserService( 3885): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/WindowState( 1015): WIN DEATH: Window{26cb212e u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
,D/InputDispatcher( 1015): Focus left window: 3331
,I/AMMetaDataParserService( 3885): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7),
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,E/SMD     (  289): DCD OFF
,I/AMMetaDataParserService( 3885): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/PackageSettings( 1015): Skipping PackageSetting{2057ebe4 com.test.thalitest/10326} due to missing metadata
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3885): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131099648
,W/ActivityManager( 1015): Force removing ActivityRecord{1d93b50a u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1015): Set to : 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1015): Focused application set to: xxxx
,I/AMMetaDataParserService( 3885): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,D/Finsky  ( 4256): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1015): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =10
I/InputMethodManagerService( 1015): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,W/ActivityManager( 1015): Spurious death for ProcessRecord{3808bdc7 3331:com.example.hello/u0a334}, curProc for 3331: null
,I/AMMetaDataParserService( 3885): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Process com.android.bluetooth (pid 2632)(adj 0) has died(70,634)
,I/AMMetaDataParserService( 3885): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/Launcher( 1478): onRestart, Launcher: 108954187
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10334 user=0: pkg removed
,D/Tethering( 1015): interfaceRemoved wlan0
E/Tethering( 1015): attempting to remove unknown iface (wlan0), ignoring
,I/AMMetaDataParserService( 3885): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,I/AMMetaDataParserService( 3885): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/art     ( 4040): Explicit concurrent mark sweep GC freed 17112(952KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 3MB/5MB, paused 1.059ms total 39.331ms
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131099648
,I/AMMetaDataParserService( 3885): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3885): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ResourcesManager( 1455): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 1676): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1795): mOCRHelper is null
,D/Tethering( 1015): interfaceRemoved p2p0
E/Tethering( 1015): attempting to remove unknown iface (p2p0), ignoring
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Launcher( 1478): onStart, Launcher: 108954187
,D/Launcher.HomeView( 1478): onStart
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3742/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10065/pid_3794/cgroup.procs: No such file or directory
,D/Launcher( 1478): onResume, Launcher: 108954187
,I/AMMetaDataParserService( 3885): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SettingsProvider( 1015): name = kids_home_mode
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10006
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
D/RCPManagerService( 1015): PackageReceiver onReceive()
,D/Launcher.HomeView( 1478): onResume
,I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/AMMetaDataParserService( 3885): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/ActivityManager( 1015): Killing 3415:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MenuAppsGridFragment( 1478): onResume
,D/ActivityManager( 1015): handle home activity for 0
,I/WallpaperManagerService( 1015): switchPersonaWallpaper is called for personaId-0
,D/RegisteredServicesCache( 1440): empty dynamic service
,D/KnoxTimeoutHandler( 1015): post home show event for user 0
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,I/AMMetaDataParserService( 3885): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131099648
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 3885): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,D/InputDispatcher( 1015): Focus entered window: 1478
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1478): log_dcs ThreadedRenderer::initialize entered! 
,I/AMMetaDataParserService( 3885): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/AMMetaDataParserService( 3885): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3885): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3885): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131099648
,I/AMMetaDataParserService( 3885): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,I/AMMetaDataParserService( 3885): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 32651(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/34MB, paused 2.815ms total 314.482ms
,W/ResourcesManager( 3355): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3885): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ResourcesManager( 3355): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3355): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3355): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3885): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3885): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10334
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=2_task.xml
,D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10334
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1015): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3885): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3885): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
W/ResourcesManager( 3885): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
W/ResourcesManager( 3885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
W/ResourcesManager( 3885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
W/ResourcesManager( 3885): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
W/ResourcesManager( 3885): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
W/ResourcesManager( 3885): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
W/ResourcesManager( 3885): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 3331 uid 10334
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131165197
I/AMMetaDataParserService( 3885): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
D/SamsungIME( 1795): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
W/TextServicesManagerService( 1015): no available spell checker services found,
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1015): [SO] activate (ident=0xb954f0f8, enabled=0)
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SensorManager( 1015): unregisterListener ::   
I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SensorService( 1015): [SO] changed settle time [0]
D/SensorService( 1015): [SO] setDelay [200000000]
D/SensorService( 1015): [SO] activate (ident=0xb954f0f8, enabled=1)
D/SensorService( 1015): [SO] AR_init
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1015):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1015): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/DBG_DM  ( 3241): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/PanelView( 1172): There is/are notification(s) 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3885): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/PackageManager( 1015): delete codoeFile: 
,I/AASA_removePackage( 1015): UID=10334 Target=com.example.hello,
D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10334, packageName = com.example.hello
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/OpenGLRenderer( 1478): SFEffectCache::get: create texture(0xa1c29724): name, size, mSize = 34, 85680, 221248
,D/PackageManager( 1015): result of delete: 1{906185185},
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3885): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/UpdateIcingCorporaServi( 3355): UpdateCorporaTask done [took 8223 ms] updated apps [took 8223 ms] 
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/AndroidRuntime( 4471): Shutting down VM
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1015): Displayed Component not be shown by security: +687ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SIP     ( 1455): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/File    ( 1455): fail readDirectory() errno=2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/WearableService( 1676): callingUid 10011, callindPid: 1676
,I/AMMetaDataParserService( 3885): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/UsbSettingsManager( 1015): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1015): onPackageRemoved : com.example.hello
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/libprocessgroup( 1015): failed to open /acct/uid_10014/pid_3415/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131165197
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3885): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
,D/LocationInitializer( 1817): Restart initialization of location
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1676): [228] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3885): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/AuthorizationBluetoothService( 1676): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3885): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 4471): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
I/AMMetaDataParserService( 3885): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131165197
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3885): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/GCoreFlp( 1676): No location to return for getLastLocation()
,W/FusedLocationProvider( 1676): location=null
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3885): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3885): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3885): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3885): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2072): Starting #5
,I/Hs20UtilService( 2072): Message received 5007
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
W/ContextImpl( 3885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote,
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/AMMetaDataParserService( 3885): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3885): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3885): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3885): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3885): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3885): getResourcePackageName:assistant
I/AMMetaDataParserService( 3885): Resource data:2131099648
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 3885): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3885): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3885): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3885): getResourceTypeNamexml
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/SensorService( 1015): [SO] currT = 44212047000, prevT = 43751082000, diff = 460965000, [-0.402 -0.019 9.902]
D/SensorService( 1015): [SO] -0.402 -0.019 9.902
D/SensorService( 1015): [SO] [100 -> 255]
,E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 2072): Starting #6
,I/Hs20UtilService( 2072): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699),
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Un,known Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
I/AMMetaDataParserService( 3885): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
E/SQLiteLog( 3885): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 3885): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3885): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteDatabase.openD,atabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3885): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3885): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3885): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3885): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3885): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3885): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3885): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3885): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
W/System.err( 3885): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3885): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3885): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3885): 	at android.database.sql,ite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3885): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3885): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3885): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3885): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3885): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3885): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3885): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3885): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3885): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3885): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3885): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3885): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3885): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3885): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 1015): Killing 3817:com.android.managedprovisioning/u0a20 (adj 15): empty #31
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
I/Hs20UtilService( 2072): Starting #7
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	,at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 2072): Message received 5007
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2925): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2925): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2925): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2925): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2925): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
```
