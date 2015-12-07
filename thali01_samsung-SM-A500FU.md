#### Test 502422852e23b2c_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/TimaKeyStoreProvider( 2841): TimaSignature is unavailable
D/ActivityThread( 2841): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 2854): TimaSignature is unavailable
D/ActivityThread( 2854): Added TimaKeyStore provider
D/TP/SmsProvider( 1439): query,matched:26, calling pid = 2238
D/TP/SmsProvider( 1439): match 26:Elapsed time : 10.693 ms
D/QSEECOMAPI: ( 1013): Loaded image: APP id = 8
I/TZ: qc_tlc_communication( 1013): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1013): ctx = 0xb78051e8, comm = 0xb77ebdf8, sendmsg = 0x9d705000, recvmsg = 0x9d705440
I/TZ_init: ( 1013): TZ_init: sending initialization request...
E/TZ_init: ( 1013): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1013): trustlet initialization failed
I/TZ_init: ( 1013): TZ_init_START...
D/Mms/SmsReceiver( 2238): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2238): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2238): isDefault true
D/BadgeProvider( 2841): onCreate
D/BadgeProvider( 2841): DatabaseHelper
--------- beginning of system
W/ResourcesManager( 2854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BadgeProvider( 2841): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1013): failed to open /acct/uid_10072/pid_1548/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10057/pid_1521/cgroup.procs: No such file or directory
E/Zygote  ( 2879): MountEmulatedStorage()
E/Zygote  ( 2879): v2
I/libpersona( 2879): KNOX_SDCARD checking this for 10159
I/libpersona( 2879): KNOX_SDCARD not a persona
I/SELinux ( 2879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2879): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=2879 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/TZ_init: ( 1013): TZ_init_with_data: sending initialization request...
I/ActivityManager( 1013): Killing 1748:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
I/TZ_init: ( 1013): TZ_init: successful initialization
D/QSEECOMAPI: ( 1013): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1013): QSEECom_shutdown_app, app_id = 8
E/TLC_TZ_KEYSTORE: ( 1013): Count : 1, Ret : 0
I/ActivityManager( 1013): Killing 1631:com.google.android.apps.maps/u0a107 (adj 15): empty #31
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
D/TimaKeyStoreProvider( 2879): TimaSignature is unavailable
D/ActivityThread( 2879): Added TimaKeyStore provider
D/SettingsProvider( 1013): name = block_emergency_message
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10048
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
W/ActivityManager( 1013): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
D/Launcher.Model( 1462): reloadBadges entered.
D/BadgeProvider( 2841): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2841): sendNotify, [notify] : null
D/BadgeProvider( 2841): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2841): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2841): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2238): setBadgeCount(), count=0
E/SQLiteLog( 2823): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
D/Mms/MessagingNotification( 2238): remove alarm
D/ActivityManager( 1013): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
W/libprocessgroup( 1013): failed to open /acct/uid_10107/pid_1631/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10138/pid_1748/cgroup.procs: No such file or directory
D/Mms/MessagingNotification( 2238): updateAllHistoryAsRead()
I/Intent to TravelDirActivity( 2879): inside TravelBroadcastReceiver
I/WifiCredService( 1290): onCreate
I/art     ( 1439): Explicit concurrent mark sweep GC freed 39030(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/13MB, paused 981us total 152.033ms
D/TP/MmsProvider( 1439): Query uri=content://mms, match=0, calling pid = 2238
D/TP/SmsProvider( 1439): query,matched:0, calling pid = 2238
D/WifiTimerReceiver( 1290): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1290): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1290): Action boot completed received
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
D/TP/SmsProvider( 1439): match 0:Elapsed time : 3.640 ms
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1013): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2902 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 2902): MountEmulatedStorage()
E/Zygote  ( 2902): v2
I/libpersona( 2902): KNOX_SDCARD checking this for 1000
I/libpersona( 2902): KNOX_SDCARD not a persona
I/SELinux ( 2902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Killing 2073:com.vlingo.midas/u0a31 (adj 15): empty #31
I/SELinux ( 2902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/MediaScanner( 1227): processDirectory :  /system/media
D/DSM     ( 2823): [Lines:107] Normal booted
D/DSM     ( 2823): [Lines:114] Boot completed
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2902): TimaSignature is unavailable
D/ActivityThread( 2902): Added TimaKeyStore provider
E/Zygote  ( 2918): MountEmulatedStorage()
E/Zygote  ( 2918): v2
I/ActivityManager( 1013): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2918 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 2918): KNOX_SDCARD checking this for 1000
I/libpersona( 2918): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Killing 2093:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
V/MediaScanner( 1227):  prescan time: 538ms (DB items: 141)
V/MediaScanner( 1227):     scan time: 80ms (Caching mode: true), (makeEntry time: 23ms ~28%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 618ms
V/MediaScanner( 1227): checked files: 133  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1227): checkDefaultSounds
W/ContextImpl( 2697): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
I/SELinux ( 2918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2918): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
D/NearbySettings( 1290): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1290): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1290): MountReceiver.onReceive - Create mPrefHandler
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2918): TimaSignature is unavailable
D/ActivityThread( 2918): Added TimaKeyStore provider
D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
D/NearbySettings( 1290): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1013): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
V/NearbySettings( 1290): MountReceiver.mPrefHandler - 7002
D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
E/Zygote  ( 2936): MountEmulatedStorage()
E/Zygote  ( 2936): v2
I/libpersona( 2936): KNOX_SDCARD checking this for 1000
I/libpersona( 2936): KNOX_SDCARD not a persona
I/SELinux ( 2936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
I/SELinux ( 2936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2936): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=2936 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Mms/MessagingNotification( 2238): [end]    nonBlockingUpdateMessageIndicator() consume time = 440.905261
I/NearbySettings( 1290): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1290): MountReceiver.onReceive - Internal Path
D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/SettingsProvider( 1013): name = personal_mode_enabled
D/TimaKeyStoreProvider( 2936): TimaSignature is unavailable
D/ActivityThread( 2936): Added TimaKeyStore provider
W/libprocessgroup( 1013): failed to open /acct/uid_10031/pid_2073/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10050/pid_2093/cgroup.procs: No such file or directory
W/ResourcesManager( 2918): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/SEAMService( 1013):  hashset_to_int_array returning null
W/SEAMService( 1013):  hashset_to_int_array returning null
E/SQLiteLog( 2697): (284) automatic index on seams_container_info(seams_container_id)
E/SQLiteLog( 2697): (284) automatic index on seams_container_info(sp_id)
W/SEAMService( 1013):  hashset_to_int_array returning null
W/ActivityThread( 2918): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
I/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2918): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/LcdtestApp( 2918): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
I/art     ( 1013): Explicit concurrent mark sweep GC freed 28309(1611KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 25MB/38MB, paused 2.140ms total 141.885ms
D/SecurityLogAgent:SEDenialService( 1013): Got CLOSE_WRITE Event sk.log
D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService( 1013): Got CLOSE_WRITE Event sk.log
I/ActivityManager( 1013): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2955 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 1479:com.android.printspooler/u0a136 (adj 15): empty #31
E/Zygote  ( 2955): MountEmulatedStorage()
I/ActivityManager( 1013): Killing 2151:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
E/Zygote  ( 2955): v2
I/libpersona( 2955): KNOX_SDCARD checking this for 10160
I/libpersona( 2955): KNOX_SDCARD not a persona
I/SELinux ( 2955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2955): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 1439): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 2936): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/BadgeProvider( 2841): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
D/MediaScannerService( 1227): !@done scanning volume internal
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1439): query,matched:200, calling pid = 2238
D/TimaKeyStoreProvider( 2955): TimaSignature is unavailable
D/ActivityThread( 2955): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1439): match 200:Elapsed time : 13.537 ms
W/ContextImpl( 2936): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
E/Zygote  ( 2971): MountEmulatedStorage()
I/libpersona( 2971): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2971): v2
I/libpersona( 2971): KNOX_SDCARD not a persona
I/SELinux ( 2971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2971): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
I/ActivityManager( 1013): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 1598:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/ActivityManager( 1013): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
D/TimaKeyStoreProvider( 2971): TimaSignature is unavailable
D/ActivityThread( 2971): Added TimaKeyStore provider
I/SmartcardBootCompleteReceiver( 1290): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1290): Received intent with action - android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
D/Launcher.Model( 1462): reloadBadges entered.
D/BadgeProvider( 2841): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 2841): sendNotify, [notify] : null
D/BadgeProvider( 2841): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 2841): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2841): update, [UpdateCount] : 1
W/ResourcesManager( 2955): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/F_PHONE ( 2936): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
W/ContextImpl( 2936): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
E/Zygote  ( 2989): MountEmulatedStorage()
E/Zygote  ( 2989): v2
I/libpersona( 2989): KNOX_SDCARD checking this for 1000
I/libpersona( 2989): KNOX_SDCARD not a persona
I/SELinux ( 2989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2989 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2989): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
I/art     (  317): Explicit concurrent mark sweep GC freed 8774(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 672us total 23.941ms
D/TimaKeyStoreProvider( 2989): TimaSignature is unavailable
D/ActivityThread( 2989): Added TimaKeyStore provider
E/USB_UICC(  309): Timeout! No signal received. Retry num = 26
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 34.900ms
W/libprocessgroup( 1013): failed to open /acct/uid_10136/pid_1479/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10113/pid_2151/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10015/pid_1598/cgroup.procs: No such file or directory
W/ResourcesManager( 2989): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 19.576ms
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/TP/SmsProvider( 1439): query,matched:0, calling pid = 2238
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/TP/SmsProvider( 1439): match 0:Elapsed time : 6.491 ms
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
W/ActivityManager( 1013): getTasks: caller 10146 does not hold GET_TASKS; limiting output
I/Process ( 2713): Sending signal. PID: 2713 SIG: 9
D/BluetoothBDAdrressReceiver( 2989): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 2989): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
D/F_PHONE ( 2936): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 2936): default registerAction()
I/F_PHONE ( 2936): [[com.sec.bcservice]] sendPendingMessage()
D/ActivityManager( 1013): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1439): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
D/BluetoothBDTestService( 1439): onCreate()
E/BluetoothBDTestService( 1439): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1439): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1439): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/SecureStorage( 2736): [INFO]: SPID(0x00000001)Processing data has been completed
I/SecureStorage( 2736): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
E/Zygote  ( 3009): MountEmulatedStorage()
E/Zygote  ( 3009): v2
I/libpersona( 3009): KNOX_SDCARD checking this for 1000
I/libpersona( 3009): KNOX_SDCARD not a persona
I/SELinux ( 3009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3009 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3009): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SmartcardBootCompleteReceiver( 1290): Broadcast sent with current lockscreen type
D/TP/SmsProvider( 1439): query,matched:51, calling pid = 2238
D/TP/SmsProvider( 1439): match 51:Elapsed time : 3.070 ms
D/TimaKeyStoreProvider( 3009): TimaSignature is unavailable
D/ActivityThread( 3009): Added TimaKeyStore provider
I/ActivityManager( 1013): Process com.android.exchange (pid 2713)(adj 15) has died(376,966)
D/Mms/MessagingNotification( 2238): isBlockingModeEnabled() = false, Zen mode = 0
W/ResourcesManager( 3009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BadgeProvider( 2841): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/DIAGMON_AGENT( 2971): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
D/[0]UMC:UMCContentProvider( 2955): @onCreate
D/[0]UMC:Core( 2955): onCreate(): 
D/[0]UMC:Core( 2955): @isManagedProfileUser
D/[0]UMC:Core( 2955): userId: 0
D/[0]UMC:Core( 2955): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2955): userInfo.isManagedProfile() : false
D/[0]UMC:DeviceInfo( 2955): USA==US==
D/[SBeam] ( 1290): SBeamEnabler.initPreferenceForSbeam : 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
I/SettingSearch/SearchIntentReceiver( 1290): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1290): search setting db init!!
D/Launcher.Model( 1462): reloadBadges entered.
D/BadgeProvider( 2841): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2841): sendNotify, [notify] : null
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
D/BadgeProvider( 2841): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2841): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2841): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2238): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2238): remove alarm
I/SettingSearch/SearchIntentReceiver( 1290): BOOT_COMPLETED call InitSerachDBThread thread start!
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
I/KnoxUsageLogPro( 3009): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1439): query,matched:0, calling pid = 2238
D/TP/SmsProvider( 1439): match 0:Elapsed time : 3.168 ms
I/KnoxUsageLogPro( 3009): savePreference: key = previous_sys_time value = 1449497269087
E/Zygote  ( 3030): MountEmulatedStorage()
,E/Zygote  ( 3030): v2
I/libpersona( 3030): KNOX_SDCARD checking this for 1000
I/libpersona( 3030): KNOX_SDCARD not a persona
I/SELinux ( 3030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3030 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/KnoxUsageLogPro( 3009): premStatus:2
D/TimaKeyStoreProvider( 3030): TimaSignature is unavailable
D/ActivityThread( 3030): Added TimaKeyStore provider
I/KnoxUsageLogPro( 3009): isEulaShown : false
I/KnoxUsageLogPro( 3009): KnoxUsageReceiver onReceive : not Processible, just return
I/KnoxUsageLogPro( 3009): savePreference: key = previous_elapsed_time value = 33091
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
E/Zygote  ( 3044): MountEmulatedStorage()
E/Zygote  ( 3044): v2
I/libpersona( 3044): KNOX_SDCARD checking this for 10150
I/libpersona( 3044): KNOX_SDCARD not a persona
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
I/SELinux ( 3044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
I/SELinux ( 3044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3044): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3044 uid=10150 gids={50150, 9997} abi=armeabi-v7a
D/Mms/MessagingNotification( 2238): updateAllHistoryAsRead()
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1227): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/TimaKeyStoreProvider( 3044): TimaSignature is unavailable
D/ActivityThread( 3044): Added TimaKeyStore provider
E/Zygote  ( 3060): MountEmulatedStorage()
I/libpersona( 3060): KNOX_SDCARD checking this for 10085
E/Zygote  ( 3060): v2
I/libpersona( 3060): KNOX_SDCARD not a persona
I/SELinux ( 3060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3060): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3060 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/USER_AGENT( 2955): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
W/ResourcesManager( 3030): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/Mms/SmsReceiverService( 2238): [end]    handleBootCompleted() consume time = 815.70552
D/TimaKeyStoreProvider( 3060): TimaSignature is unavailable
I/ActivityManager( 1013): Killing 2256:com.sec.android.omc/1000 (adj 15): empty #31
D/ActivityThread( 3060): Added TimaKeyStore provider
V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
D/[0]UMC:AdminManager( 2955): init - start
E/BluetoothHeadset( 2736): BTStateChangeCB is registed
D/BluetoothHeadset( 2736): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1013): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
W/ResourcesManager( 3060): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3060): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3060): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3060): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3060): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3060): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 2736): BluetoothHeadset service is binded
D/BluetoothA2dp( 2736): doBind(): CallingUid(myUserHandle) = 0
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
D/ActivityManager( 1013): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
D/BluetoothAdapter( 2736): 419524765: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2736): 419524765: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2736): 419524765: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2736): 419524765: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2736): 419524765: getState() :  mService = null. Returning STATE_OFF
D/[0]UMC:AdminManager( 2955): loadAdmins
V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
V/MediaScanner( 1227):  prescan time: 81ms (DB items: 27)
V/MediaScanner( 1227):     scan time: 48ms (Caching mode: true), (makeEntry time: 40ms ~83%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 13ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 142ms
V/MediaScanner( 1227): checked files: 10  directories : 17  (I: 0, U: 0)
D/MediaScannerService( 1227): !@done scanning volume external
D/[0]UMC:AdminManager( 2955): init - end
D/GSLBManager( 2955): migrateStoredUrlFromOldPref
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2570): [DummyFtClient$sendBootCompletedAndFinish](2570) ...
D/FactoryTestApp( 2570): [Support$Values.getString](2570) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2570): [ModuleCommon$isConnectionModeNone](2570) mConnectionMode = gsm
D/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$ResponseWriter](2570) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$connectToSecPhoneService](2570)  
W/ContextImpl( 2570): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/ActivityManager( 1013): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$onServiceConnected](2570) connected done
D/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$write](2570) Send Response Message to SecPhone
D/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$write](2570) Response ��
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2256/cgroup.procs: No such file or directory
D/AT_Distributor(  324): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$handleMessage](2570) Send BOOTING COMPLETED done
I/iu.UploadsManager( 1915): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
D/GSLBManager( 2955): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 2955): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2955): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2955): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2955): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2955): isContainer : 0
D/EnterpriseDeviceManagerService( 1013): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2955): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2955): isContainer : 0
D/[0]UMC:UMCAdmin( 2955): deactivateUMCAdmin - UMC App Admin deactivated
D/ActivityManager( 1013): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2955): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
D/[0]UMC:CoreReceiver( 2955): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2955):  check PreETag 
D/[0]UMC:CoreReceiver( 2955): bulk enrolled package: null
V/[0]UMC:ProfileStorage( 2955): Enter loadList
D/[0]UMC:CoreReceiver( 2955): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2955): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2955): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2955): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2955): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2955): isContainer : 0
D/EnterpriseDeviceManagerService( 1013): isManagedProfileUser(): userId = 0
I/FOTA    ( 3030): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
E/[0]UMC:UMCAdmin( 2955): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2955): isContainer : 0
D/[0]UMC:UMCAdmin( 2955): deactivateUMCAdmin - UMC App Admin deactivated
D/AT_Distributor(  324): SetAtdStatus(), 1_1_0
D/AT_Distributor(  324): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/[0]UMC:ByodSetupStarter( 2955): Container ID : 0
V/[0]UMC:Utils( 2955): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2955): shutdown
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2955): @GuardService - stopService Result = true
I/art     ( 2955): System.exit called, status: 0
I/AndroidRuntime( 2955): VM exiting with result code 0, cleanup skipped.
I/iu.UploadsManager( 1915): End new media; added: 0, uploading: 0, time: 79 ms
I/DIAGMON_AGENT( 2971): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT( 2971): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DBG_DM  ( 3030): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
I/DIAGMON_AGENT( 2971): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 2971): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DBG_DM  ( 3030): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
I/DIAGMON_AGENT( 2971): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2971): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/DBG_DM  ( 3030): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
D/SettingsProvider( 1013): name = next_alarm_formatted
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10085
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
I/ActivityManager( 1013): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2955)(adj 0) has died(352,979)
D/daemonapp( 1351): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1351): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1351): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1351): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1351): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1351): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1351): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1351): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1351): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1351): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1351): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1351): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/SettingsProvider( 1013): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10162
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
D/daemonapp( 1351): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1351): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/daemonapp( 1351): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1351): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1351): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1351): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/Zygote  ( 3087): MountEmulatedStorage()
E/Zygote  ( 3087): v2
I/libpersona( 3087): KNOX_SDCARD checking this for 1000
I/libpersona( 3087): KNOX_SDCARD not a persona
I/SELinux ( 3087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/daemonapp( 1351): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1351): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/SELinux ( 3087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3087): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1351): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1449497269572
D/daemonapp( 1351): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1449518820000
D/daemonapp( 1351): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1351): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/daemonapp( 1351): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449518820000
I/DBG_DM  ( 3030): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
W/ContextImpl( 3030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
D/daemonapp( 1351): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 17
D/daemonapp( 1351): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1449518820000
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
D/TimaKeyStoreProvider( 3087): TimaSignature is unavailable
D/ActivityThread( 3087): Added TimaKeyStore provider
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
D/OverheatReceiver( 1173): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1173): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1173): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1173): isSafeMode = false
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 3030): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
W/art     ( 3060): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 132.686ms
D/BootupListener( 1439): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1013): name = internet_call_settings_visibility
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/DBG_DM  ( 3030): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1001
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/PhoneUtilsCommon( 1439): isSupportVoLTE is false.
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 3030): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 3030): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 3030): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3030): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/Telecom ( 1415): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
D/ActivityManager( 1013): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
D/ActivityManager( 1013): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_DM  ( 3030): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3030): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 3030): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(155/onStartCommand)] 
E/Zygote  ( 3103): MountEmulatedStorage()
E/Zygote  ( 3103): v2
I/libpersona( 3103): KNOX_SDCARD checking this for 10057
I/libpersona( 3103): KNOX_SDCARD not a persona
I/SELinux ( 3103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3103 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 3103): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/DBG_DM  ( 3030): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
W/ContextImpl( 3030): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1013): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_DM  ( 3030): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
D/TimaKeyStoreProvider( 3103): TimaSignature is unavailable
D/comdaemonstockapp( 1351): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/ActivityThread( 3103): Added TimaKeyStore provider
D/comdaemonstockapp( 1351): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3120): MountEmulatedStorage()
E/Zygote  ( 3120): v2
I/libpersona( 3120): KNOX_SDCARD checking this for 10166
I/libpersona( 3120): KNOX_SDCARD not a persona
I/SELinux ( 3120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3120 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 3120): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/Telecom ( 1415): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
I/DBG_DM  ( 3030): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
I/ServiceManager(  328): Waiting for service AtCmdFwd...
E/USB_UICC(  309): Timeout! No signal received. Retry num = 27
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3120): TimaSignature is unavailable
D/ActivityThread( 3120): Added TimaKeyStore provider
E/Zygote  ( 3138): MountEmulatedStorage()
E/Zygote  ( 3138): v2
I/libpersona( 3138): KNOX_SDCARD checking this for 10009
I/libpersona( 3138): KNOX_SDCARD not a persona
I/SELinux ( 3138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3138): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3138 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2286:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
D/TimaKeyStoreProvider( 3138): TimaSignature is unavailable
D/ActivityThread( 3138): Added TimaKeyStore provider
I/DBG_POLICYDM( 3087): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 3087): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 3087): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3087): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 3087): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 3087): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3087): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3087): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 3087): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 3087): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
D/AndroidRuntime( 3118): 
D/AndroidRuntime( 3118): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3118): CheckJNI is OFF
D/AndroidRuntime( 3118): readGMSProperty: start
D/AndroidRuntime( 3118): readGMSProperty: already setted!!
D/AndroidRuntime( 3118): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3118): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3118): readGMSProperty: end
D/AndroidRuntime( 3118): addProductProperty: start
W/libprocessgroup( 1013): failed to open /acct/uid_10131/pid_2286/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 3087): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
I/DBG_DM  ( 3030): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
V/audio_hw_primary(  289): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  289): audio_extn_get_parameters: returns 
V/msm8974_platform(  289): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  289): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  289): key: 'call_forwarding' value: ''
V/InCall  ( 1973): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1973): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1973): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
I/DBG_POLICYDM( 3087): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
D/ScoverManager( 1973): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1973): InCallUtils - isCoverClosed false
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
I/Telecom ( 1415): ProximitySensorManager: Proximity wake lock already released
D/InCall  ( 1973): InCallUtils - isCoverClosed false
I/InCall  ( 1973): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1973): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1973): InCallPresenter -  - dismissCoverDialog()...
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3170): MountEmulatedStorage()
I/libpersona( 3170): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3170): v2
I/libpersona( 3170): KNOX_SDCARD not a persona
I/SELinux ( 3170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3170 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3170): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/InCall  ( 1973): CallSContextMotion - stopPutDownListening
D/InCall  ( 1973): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
D/PhoneStatusBarView( 1173): setCallBackground:0
D/LocationManagerService( 1013): getProviders()=[passive]
D/TimaKeyStoreProvider( 3170): TimaSignature is unavailable
D/ActivityThread( 3170): Added TimaKeyStore provider
E/AffinityControl( 3118): AffinityControl: registerfunction enter
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1973): InCallUtils - isCoverClosed false
D/AndroidRuntime( 3118): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1013): inState():  stateMachine is null !!
I/PersonaManagerService( 1013): PersonaId don't exist
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
I/DBG_DM  ( 3030): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1013): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1013): mDVFSHelper.acquire()
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
I/DBG_DM  ( 3030): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
I/SurfaceFlinger(  256): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  256): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1013): Set to : 0
D/PhoneWindow( 1013): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1013): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1462): onPause
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1013): Focused application set to: xxxx
D/InputDispatcher( 1013): Focus left window: 1462
D/Launcher( 1462): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, iello
D/AndroidRuntime( 3118): Shutting down VM
D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/VideoCallManager( 1973): Instantiating VideoCallManager
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
E/        ( 1973): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1973): took 2.798645ms for 0*0 texture 0
I/GFX generate_partition_tables( 1973): took 5.122240ms for 0*0 texture 0
I/GFX raster( 1973): took 11.803749ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1973): Bitmap=0xb746f8e0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7487af0 counterpartCT=4 counterpartW=176 counterparth=144
W/ResourcesManager( 3120): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3120): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/        ( 1973): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/Adreno-EGL( 1973): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1973): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1973): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1973): Local Branch: 
I/Adreno-EGL( 1973): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1973): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1973):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/GFX GPU raster( 1973): eglCreateImageKHR: EGL_SUCCESS
I/DBG_POLICYDM( 3087): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/glCompressedTexImage2D( 1973): took 0.427865ms for 320*61440 texture 37809
I/DBG_POLICYDM( 3087): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/DBG_POLICYDM( 3087): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
I/draw setup( 1973): took 11.067500ms for 320*240 texture 37809
E/GFX GPU raster( 1973): drawn
E/DBG_POLICYDM( 3087): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
I/GFX GPU raster ASTC( 1973): took 42.984167ms for 320*240 texture 12
I/GFX raster( 1973): took 43.068802ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1973): Bitmap=0xb7487af0 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7489e30 counterpartCT=4 counterpartW=320 counterparth=240
V/JNIHelp ( 3120): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
E/        ( 1973): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1973): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1973): took 0.361094ms for 480*122880 texture 37813
I/draw setup( 1973): took 0.919635ms for 480*640 texture 37813
E/GFX GPU raster( 1973): drawn
I/GFX GPU raster ASTC( 1973): took 7.670519ms for 480*640 texture 12
I/GFX raster( 1973): took 7.822707ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1973): Bitmap=0xb7489e30 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb76b82c0 counterpartCT=4 counterpartW=480 counterparth=640
I/art     ( 1013): Explicit concurrent mark sweep GC freed 15763(866KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.527ms total 182.660ms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/Tethering( 1013): No numeric data
D/SecurityLogAgent:SEDenialService( 1013): Got CLOSE_WRITE Event sk.log
E/Tethering( 1013): No numeric data
E/Tethering( 1013): No numeric data
E/Tethering( 1013): No numeric data
E/Tethering( 1013): No numeric data
E/Tethering( 1013): No numeric data
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3207): MountEmulatedStorage()
I/ActivityManager( 1013): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3207 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 3207): v2
I/libpersona( 3207): KNOX_SDCARD checking this for 10174
I/SELinux ( 3207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3207): KNOX_SDCARD not a persona
W/System  ( 3120): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fd2f410: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 3120): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 3120): Installed default security provider GmsCore_OpenSSL
I/SELinux ( 3207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3207): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
E/        ( 1973): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/GFX GPU raster( 1973): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1973): took 0.441093ms for 440*116864 texture 37809
I/draw setup( 1973): took 1.051823ms for 440*330 texture 37809
E/GFX GPU raster( 1973): drawn
I/ActivityManager( 1013): Killing 2298:com.sec.tcpdumpservice/1000 (adj 15): empty #31
I/GFX GPU raster ASTC( 1973): took 5.335208ms for 440*330 texture 12
I/GFX raster( 1973): took 5.400104ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1973): Bitmap=0xb76b82c0 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb76cc6b0 counterpartCT=4 counterpartW=440 counterparth=330
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
V/ActivityThread( 1462): updateVisibility : ActivityRecord{352fffd3 token=android.os.BinderProxy@148e81d8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/art     ( 3118): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/Zygote  ( 3221): MountEmulatedStorage()
E/Zygote  ( 3221): v2
I/libpersona( 3221): KNOX_SDCARD checking this for 1000
I/libpersona( 3221): KNOX_SDCARD not a persona
I/SELinux ( 3221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/TimaKeyStoreProvider( 3207): TimaSignature is unavailable
I/SELinux ( 3221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3221 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityThread( 3207): Added TimaKeyStore provider
I/ActivityManager( 1013): Killing 2208:com.sec.android.app.mt/1000 (adj 15): empty #31
E/SELinux ( 3221): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1013): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1462): onStop
,E/        ( 1973): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1973): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1973): took 0.455313ms for 480*163840 texture 37811
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/draw setup( 1973): took 1.038906ms for 480*640 texture 37811
E/GFX GPU raster( 1973): drawn,
I/art     (  317): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 677us total 20.750ms
,I/GFX GPU raster ASTC( 1973): took 6.780365ms for 480*640 texture 12
I/GFX raster( 1973): took 6.897553ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1973): Bitmap=0xb76bc4c0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb76cc1e8 counterpartCT=4 counterpartW=480 counterparth=640
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 3221): TimaSignature is unavailable
,D/ActivityThread( 3221): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 17.471ms
,D/Launcher( 1462): onTrimMemory. Level: 20
V/ActivityThread( 1462): updateVisibility : ActivityRecord{352fffd3 token=android.os.BinderProxy@148e81d8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 22.800ms
W/TRThreadPoolExecutor( 3103): Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3103): Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
E/        ( 1973): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1973): took 2.908750ms for 0*0 texture 0
W/TRThreadPoolExecutor( 3103): Task "NotifyOnDoneFutureTask[log_applications_to_clearcut_unconditionally]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3103): Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
I/GFX generate_partition_tables( 1973): took 7.665156ms for 0*0 texture 0
W/TRThreadPoolExecutor( 3103): Task "NotifyOnDoneFutureTask[log_contacts_to_clearcut_unconditionally]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
I/GFX raster( 1973): took 12.700364ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1973): Bitmap=0xb76b5b80 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb76b5ca0 counterpartCT=4 counterpartW=176 counterparth=144
I/SearchServiceFactory( 3103): refreshing search history.
,W/ResourcesManager( 3221): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3244): MountEmulatedStorage()
,E/Zygote  ( 3244): v2
I/libpersona( 3244): KNOX_SDCARD checking this for 1000
I/libpersona( 3244): KNOX_SDCARD not a persona
,I/SELinux ( 3244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2298/cgroup.procs: No such file or directory
I/ActivityManager( 1013): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3244 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3244): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 2393:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
I/ActivityManager( 1013): Killing 2366:com.sec.android.gallery3d/u0a44 (adj 15): empty #32
I/ActivityManager( 1013): Killing 2331:com.wsomacp/u0a25 (adj 15): empty #33
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 3244): TimaSignature is unavailable
,D/ActivityThread( 3244): Added TimaKeyStore provider
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/        ( 1973): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/GFX construct_block_size_descriptor_2d second part( 1973): took 2.589270ms for 0*0 texture 0
,V/AlarmManager( 1013): waitForAlarm result :8
,I/GFX generate_partition_tables( 1973): took 6.297343ms for 0*0 texture 0
,I/GFX raster( 1973): took 11.114323ms for 176*144 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1973): Bitmap=0xb76b5ec0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb76b5e60 counterpartCT=4 counterpartW=176 counterparth=144
,E/Zygote  ( 3260): MountEmulatedStorage()
I/libpersona( 3260): KNOX_SDCARD checking this for 10003
E/Zygote  ( 3260): v2
I/libpersona( 3260): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3260 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1013): [SO] activate (ident=0xb74bb5e8, enabled=0)
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,I/WebViewFactory( 3207): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/SensorManager( 1013): unregisterListener ::   
I/Sensors ( 1013): AccelerometerSensor(0) setDelay : 66000000(ns)
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1013): [SO] changed settle time [1]
D/SensorService( 1013): [SO] setDelay [66000000]
,D/SensorService( 1013): [SO] activate (ident=0xb74bb5e8, enabled=1)
D/SensorService( 1013): [SO] AR_init
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/[SBeam] ( 1290): SBeamEnabler.isSBeamSupported : [-1]
,D/SensorManager( 1013): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/[SBeam] ( 1290): SBeamEnabler.isSBeamSupported : EXIST
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2208/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10142/pid_2393/cgroup.procs: No such file or directory
,I/DBG_FMMDM( 3244): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,E/Zygote  ( 3267): MountEmulatedStorage()
,E/Zygote  ( 3267): v2
I/libpersona( 3267): KNOX_SDCARD checking this for 10086
E/Tethering( 1013): No numeric data
I/libpersona( 3267): KNOX_SDCARD not a persona
,E/Tethering( 1013): No numeric data
E/Tethering( 1013): No numeric data
,I/ActivityManager( 1013): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3267 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2381:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,I/DBG_FMMDM( 3244): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3244): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3244): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device,
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 3207): Time to load native libraries: 2 ms (timestamps 4757-4759)
I/LibraryLoader( 3207): Expected native library version number "",actual native library version number ""
,I/SELinux ( 3260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ScoverManager( 1973): registerListener
I/SELinux ( 3260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
,E/SELinux ( 3260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1013): registerListenerCallback : binder = android.os.BinderProxy@efd7133, pid : 1973, uid : 1001, type : 1
I/SELinux ( 3267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/SensorService( 1013): [SO] Reset Rotation Old [100], Init [1]
E/Tethering( 1013): No numeric data
,I/SELinux ( 3267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3267): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/SMD     (  294): DCD OFF
E/Zygote  ( 3275): MountEmulatedStorage(),
I/libpersona( 3275): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3275): v2
I/libpersona( 3275): KNOX_SDCARD not a persona
I/SELinux ( 3275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3275 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,E/SELinux ( 3275): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/USB_UICC(  309): Timeout! No signal received. Retry num = 28
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/InCall  ( 1973): InCallPresenter -  - Finished InCallPresenter.setUp
,D/TimaKeyStoreProvider( 3275): TimaSignature is unavailable
D/ActivityThread( 3275): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 3267): TimaSignature is unavailable
D/ActivityThread( 3267): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3260): TimaSignature is unavailable
,D/ActivityThread( 3260): Added TimaKeyStore provider
,D/SensorService( 1013): [SO] 0.172 0.096 10.132
D/SensorService( 1013): [SO] [100 -> 255]
,V/WebViewChromiumFactoryProvider( 3207): Binding Chromium to main looper Looper (main, tid 1) {39de8505}
,I/LibraryLoader( 3207): Expected native library version number "",actual native library version number ""
,I/chromium( 3207): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,W/libprocessgroup( 1013): failed to open /acct/uid_10025/pid_2331/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10044/pid_2366/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10088/pid_2381/cgroup.procs: No such file or directory
,I/BrowserStartupController( 3207): Initializing chromium process, singleProcess=true
,W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3207): ApplicationContext is null in ApplicationStatus
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,D/UserAnalysis.PlaceProvider( 3260): PlaceProvider onCreate()
,W/chromium( 3207): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,W/NotificationAccessSettings( 1290): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,W/chromium( 3207): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 3207): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 3207): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,I/Adreno-EGL( 3207): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3207): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3207): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3207): Local Branch: 
I/Adreno-EGL( 3207): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3207): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3207):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/PCWCLIENTTRACE_LOG( 3275): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 3275): DEFAULT_LOGLEVEL : 3
,I/WebViewFactory( 3103): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,W/ResourcesManager( 1290): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 1915): Storage manager: low false usage 1.43MB avail 8.67GB capacity 9.93GB
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3275): new DMDBOpenHelper instance
,I/SurfaceFlinger(  256): id=6 Removed Mauncher (5/8)
,I/SurfaceFlinger(  256): id=6 Removed Mauncher (-2/8)
,I/LibraryLoader( 3103): Time to load native libraries: 2 ms (timestamps 4973-4975)
,I/LibraryLoader( 3103): Expected native library version number "",actual native library version number ""
D/PCWCLIENTTRACE_DMContentProvider( 3275): [URIMatcher] - result : 2
,W/Icing   ( 1915): Received bad json for section weights override -- ignoring.
,D/BluetoothAdapter( 3207): 742306086: getState() :  mService = null. Returning STATE_OFF
,I/DBG_FMMDM( 3244): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3244): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3244): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/art     ( 3103): Attempt to remove local handle scope entry from IRT, ignoring
,W/TRThreadPoolExecutor( 3103): Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,E/Zygote  ( 3338): MountEmulatedStorage()
E/Zygote  ( 3338): v2
I/libpersona( 3338): KNOX_SDCARD checking this for 1000
I/libpersona( 3338): KNOX_SDCARD not a persona
,I/SELinux ( 3338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2519:com.android.calendar/u0a135 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 2428:com.sec.android.app.camera/u0a139 (adj 15): empty #32
,D/TimaKeyStoreProvider( 3338): TimaSignature is unavailable
,D/ActivityThread( 3338): Added TimaKeyStore provider
,D/UserAnalysis.SecureDbManager( 3260): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3260): SecurePlaceDbHelper() 
D/UserAnalysis( 3260): Create SecureDbHelper
,I/DBG_FMMDS( 3338): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3338): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/PCWCLIENTTRACE_DMContentProvider( 3275): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3338): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,E/UpdateRequestReceiver( 3267): ignoring update request
,D/ScoverManager( 1290): serviceVersion : 16908288
,I/DBG_FMMDS( 3338): [50.18.150420][Line:43][xdbDBInit] 
,W/Icing   ( 1915): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 1915): Received bad json for section weights override -- ignoring.
,W/Icing   ( 1915): Received bad json for corpus context scoring override -- ignoring.
,E/UpdateRequestReceiver( 3267): ignoring update request
,D/IntelligenceServiceApplication( 3260): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3260): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/UpdateRequestReceiver( 3267): ignoring update request
,E/Zygote  ( 3361): MountEmulatedStorage()
E/Zygote  ( 3361): v2
I/libpersona( 3361): KNOX_SDCARD checking this for 10060
I/libpersona( 3361): KNOX_SDCARD not a persona
I/SELinux ( 3361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3361 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 3361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1013): failed to open /acct/uid_10139/pid_2428/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10135/pid_2519/cgroup.procs: No such file or directory
E/UpdateRequestReceiver( 3267): ignoring update request
D/IntelligenceServiceApplication( 3260): no applications having user consent for prediction
D/TimaKeyStoreProvider( 3361): TimaSignature is unavailable
D/ActivityThread( 3361): Added TimaKeyStore provider
,E/UpdateRequestReceiver( 3267): ignoring update request
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 3260): [PlaceDetection::stopService] Service stopped.
,E/UpdateRequestReceiver( 3267): ignoring update request
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3386): MountEmulatedStorage()
E/Zygote  ( 3386): v2
I/libpersona( 3386): KNOX_SDCARD checking this for 10092
I/libpersona( 3386): KNOX_SDCARD not a persona
I/SELinux ( 3386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3386 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2594:com.android.keychain/1000 (adj 15): empty #31
,E/SELinux ( 3386): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/SensorService( 1013): [SO] 0.172 0.096 10.132
,I/DBG_DM  ( 3030): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,D/TimaKeyStoreProvider( 3386): TimaSignature is unavailable
,D/ActivityThread( 3386): Added TimaKeyStore provider
,I/LockPatternUtils( 1290): isSmartCardAuthenticationAvailable: false
,D/Settings_Utils( 1290): isSupportVNFestival SM-A500FU XEO
,V/PlaceDetection v1.0.19 ( 3260): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/chromium( 3207): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/UserAnalysis.MyPlaceDbPreference( 3260): Constructor Preference
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2594/cgroup.procs: No such file or directory
,I/DBG_FMMDS( 3338): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/DBG_FMMDS( 3338): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3338): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3338): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3338): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3338): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3338): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/ActivityManager( 1013): Killing 2640:com.samsung.android.sm/1000 (adj 15): empty #31
,I/FOTA_Client( 3138): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3138): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3138): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,I/sCloudBackupApp( 3361): sCloudBackupApp Version Info : 4.04.8.KK_APP,
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
,W/FOTA_Client( 3138): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3412): MountEmulatedStorage()
E/Zygote  ( 3412): v2
I/libpersona( 3412): KNOX_SDCARD checking this for 10062
,I/libpersona( 3412): KNOX_SDCARD not a persona
,I/SELinux ( 3412): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3412 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2680:flipboard.boxer.app/u0a99 (adj 15): empty #31
I/SELinux ( 3412): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3412): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/art     ( 3120): Suspending all threads took: 19.261ms
,E/Zygote  ( 3426): MountEmulatedStorage()
I/libpersona( 3426): KNOX_SDCARD checking this for 10092
E/Zygote  ( 3426): v2
I/libpersona( 3426): KNOX_SDCARD not a persona
,I/SELinux ( 3426): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3426): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3426): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3426 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/AwContents( 3207): onDetachedFromWindow called when already detached. Ignoring
,E/Zygote  ( 3438): MountEmulatedStorage()
E/Zygote  ( 3438): v2
I/libpersona( 3438): KNOX_SDCARD checking this for 10014
I/libpersona( 3438): KNOX_SDCARD not a persona
,I/SELinux ( 3438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/TimaKeyStoreProvider( 3412): TimaSignature is unavailable
E/SELinux ( 3438): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityThread( 3412): Added TimaKeyStore provider
I/ActivityManager( 1013): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3438 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2108:flipboard.app/u0a98 (adj 15): empty #31
,D/PhoneWindow( 3207): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3207): *FMB* installDecor flags : 8456448
,D/TimaKeyStoreProvider( 3426): TimaSignature is unavailable
,D/ActivityThread( 3426): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2640/cgroup.procs: No such file or directory
,D/SystemWebViewEngine( 3207): CordovaWebView is running on device made by: samsung
,W/ResourcesManager( 3120): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3120): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/TimaKeyStoreProvider( 3438): TimaSignature is unavailable
,D/ActivityThread( 3438): Added TimaKeyStore provider
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1173): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1173): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
W/System.err( 3120): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/libprocessgroup( 1013): failed to open /acct/uid_10099/pid_2680/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10098/pid_2108/cgroup.procs: No such file or directory
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/System.out( 3120): YouTube MDX: MDX video stage moved to NEW
,I/System.out( 3120): YouTube MDX: MDX video player state moved to UNSTARTED
,I/System.out( 3120): YouTube MDX: MDX ad player state moved to UNSTARTED
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/USB_UICC(  309): Timeout! No signal received. Retry num = 29
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,V/OneTimeInitializerReceiver( 3438): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,D/OpenGLRenderer( 3207): Render dirty regions requested: true
,I/dex2oat ( 3457): ----------------------------------------------------
I/dex2oat ( 3457): <SS>: S T A R T I N G . . .
I/dex2oat ( 3457): <SS>: Zip is absent. Canceled.
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/dex2oat ( 3457): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1815309205.jar --oat-fd=33 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads1815309205.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/LockPatternUtils( 1290): isSmartCardAuthenticationAvailable: false
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,V/OneTimeService( 3438): OneTimeService.onHandleIntent
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/PhoneWindow( 3207): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 3207): *FMB* isFloatingMenuEnabled return false
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit
,I/ActivityManager( 1013): Killing 2220:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/InputDispatcher( 1013): Focus entered window: 3207
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3207): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3207): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3207): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3207): Enabling debug mode 0
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3495): MountEmulatedStorage(),
I/libpersona( 3495): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3495): v2
I/libpersona( 3495): KNOX_SDCARD not a persona
I/SELinux ( 3495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3495 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3495): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     (  317): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 951us total 26.189ms
,D/TimaKeyStoreProvider( 3495): TimaSignature is unavailable
,D/ActivityThread( 3495): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 17.291ms
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3386): Setting receiver enabled: false
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2220/cgroup.procs: No such file or directory
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 709us total 19.926ms
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
I/Hs20UtilService( 3495): onCreate
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/Timeline( 3207): Timeline: Activity_idle id: android.os.BinderProxy@1ad93398 time:36033
,I/SamsungIME( 1826): getCurrentCandidateView,
,E/Zygote  ( 3517): MountEmulatedStorage()
I/libpersona( 3517): KNOX_SDCARD checking this for 10019
E/Zygote  ( 3517): v2
I/libpersona( 3517): KNOX_SDCARD not a persona
,I/Hs20UtilService( 3495): Starting #1
,I/Hs20UtilService( 3495): Message received 5003
,I/ActivityManager( 1013): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3517 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/art     ( 1607): Explicit concurrent mark sweep GC freed 12864(985KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 10MB/17MB, paused 1.055ms total 103.345ms
,E/SELinux ( 3517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Displayed Component not be shown by security: +1s675ms
,D/CustomFrequencyManagerService( 1013): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1013): Timeline: Activity_windows_visible id: ActivityRecord{1ac4ba66 u0 com.example.hello/.MainActivity t2} time:36075
W/ActivityManager( 1013): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1013): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 3517): TimaSignature is unavailable
,D/ActivityThread( 3517): Added TimaKeyStore provider
,I/ExternalOEMControlProvider( 3412): onCreate
,I/dex2oat ( 3457): dex2oat took 332.970ms (threads: 4)
,E/ActivityThread( 3386): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3540 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/KLMS-2.5.183: ( 3517): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 15:07:52 GMT+01:00 2015
,E/Zygote  ( 3540): MountEmulatedStorage()
,E/Zygote  ( 3540): v2
,I/libpersona( 3540): KNOX_SDCARD checking this for 1000
,I/libpersona( 3540): KNOX_SDCARD not a persona
,I/SELinux ( 3540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,I/SELinux ( 3540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
E/SELinux ( 3540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dbxyzptlk.db240408.D.h( 3386): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/dbxyzptlk.db240408.D.h( 3386): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/dbxyzptlk.db240408.D.h( 3386): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3517): KLMSAbstractReciever(): onReceive().END.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,D/SettingsProvider( 1013): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10062
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/BindingManager( 3207): Cannot call determinedVisibility() - never saw a connection for the pid: 3207
,I/chromium( 3207): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SurfaceFlinger(  256): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  256): id=10 Removed iello (-2/8)
,E/Zygote  ( 3554): MountEmulatedStorage()
I/libpersona( 3554): KNOX_SDCARD checking this for 10022
E/Zygote  ( 3554): v2
I/libpersona( 3554): KNOX_SDCARD not a persona
I/SELinux ( 3554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3554 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,I/SELinux ( 3554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3554): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/dbxyzptlk.db240408.D.h( 3386): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,D/TimaKeyStoreProvider( 3540): TimaSignature is unavailable
,D/ActivityThread( 3540): Added TimaKeyStore provider
I/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3077)  
,I/DBG_DM  ( 3030): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/SettingsProvider( 1013): name = PREVIOUS_ELAPSED_TIME
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10062
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/ActivityManager( 1013): Killing 2534:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3554): TimaSignature is unavailable
,D/ActivityThread( 3554): Added TimaKeyStore provider
,D/CustomFrequencyManagerService( 1013): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  tag : ACTIVITY_RESUME_BOOSTER@11
,D/breakpad( 3386): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1290): InitSerachDBThread thread end!
,W/ResourcesManager( 3540): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3517): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3517): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SamsungIME( 1826): Dismiss ExpandCandiate
,I/KLMS-2.5.183: ( 3517): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3517): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3517): KLMSIntentService(): BOOT_COMPLETED
,I/ServiceMode( 3540): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3540): setReferenceIsDumpState : 0
,D/JsMessageQueue( 3207): Set native->JS mode to OnlineEventsBridgeMode
,I/com.dropbox.sync.android.a( 3386): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/RlzPingService( 3170): Setting next ping for 1450102072467
,I/KLMS-2.5.183: ( 3517): KLMSIntentService(): onDestroy()
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 21493(1128KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.299ms total 179.615ms
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2534/cgroup.procs: No such file or directory
E/Zygote  ( 3581): MountEmulatedStorage()
E/Zygote  ( 3581): v2
I/libpersona( 3581): KNOX_SDCARD checking this for 1000
I/libpersona( 3581): KNOX_SDCARD not a persona
I/SELinux ( 3581): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/AndroidProtocolHandler( 3207): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/SELinux ( 3581): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3581): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3581 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2238:com.android.mms/u0a46 (adj 15): empty #31,
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3592): MountEmulatedStorage()
E/Zygote  ( 3592): v2
I/libpersona( 3592): KNOX_SDCARD checking this for 1000
I/libpersona( 3592): KNOX_SDCARD not a persona
,I/SELinux ( 3592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1013): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1013): Killing 2771:com.android.email/u0a145 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3581): TimaSignature is unavailable
,D/ActivityThread( 3581): Added TimaKeyStore provider
,E/SELinux ( 3592): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3592): TimaSignature is unavailable
,D/ActivityThread( 3592): Added TimaKeyStore provider
,D/CountryDetector( 1013): No listener is left
,I/ActivityManager( 1013): Killing 2759:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/jxcore_app_log( 3207): JniHelper::setJavaVM(0xb70a6450), pthread_self() = -1218497024
,D/JX-Cordova( 3207): jxcore cordova android initializing
,E/MTPRx   ( 3592): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,I/SamsungIME( 1826): getDebugLevel  : 0x4f4c
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1013): mCursor = null
,V/MTPRx   ( 3592): sealedState: false
V/MTPRx   ( 3592): sealedUsbMassStorageState: false
,D/SettingsProvider( 1013): name = mtp_usb_connection_status
,I/com.dropbox.sync.android.ad( 3386): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3120): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/SettingsProvider( 1013): name = media_player_mode
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = mtp_running_status
,D/NPS_WSSNPS( 3581): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3581): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1013): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,D/SettingsProvider( 1013): name = media_mount_count
W/jxcore-log( 3207): Initializing JXcore engine
W/jxcore-log( 3207): JXcore engine is ready
,W/jxcore-log( 3207): Starting JXcore engine
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,D/NPS_WSSNPS( 3581): [] Service onCreate!!
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1013): name = mtp_sync_alive
,I/SamsungIME( 1826): getDebugLevel  : 0x4f4c
,E/USB_UICC(  309): Timeout! No signal received. Retry num = 30
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/Zygote  ( 3618): MountEmulatedStorage()
E/Zygote  ( 3618): v2
,I/libpersona( 3618): KNOX_SDCARD checking this for 1000
I/libpersona( 3618): KNOX_SDCARD not a persona
,I/SELinux ( 3618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1013): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3618 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/SELinux ( 3618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3618): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1826): KeybaordView init() : load resources
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = sdcard_launch
,D/SettingsProvider( 1013): name = boot_time_connected
,D/SettingsProvider( 1013): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/NPS_WSSNPS( 3581): [50.150621] NpsServiceTask Start
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/NPS_WSSNPS( 3581): [50.150621] smlDBHelper
,E/audit   ( 1904): type=1400 msg=audit(1449497272.840:203): avc:  denied  { ioctl } for  pid=3207 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1904):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1904): type=1300 msg=audit(1449497272.840:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bec21d58 items=0 ppid=317 ppcomm=main pid=3207 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1904): type=1320 msg=audit(1449497272.840:203): 
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3618): TimaSignature is unavailable
,D/ActivityThread( 3618): Added TimaKeyStore provider
,E/USB_UICC(  309): Timeout! No signal received. Reach maximum retries!,
E/USB_UICC(  309): usb_uicc_init_qmi failed ! 
I/USB_UICC(  309): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  309): usb_uicc_cleanup, Issuing QMI deinit ... 
,I/NPS_WSSNPS( 3581): [50.150621] AsyncBulkFlagCheck,
,W/ResourcesManager( 3618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,E/libprocessgroup( 1013): failed to kill 1 processes for processgroup 2771,
I/PCWCLIENTTRACE_PushUtil( 3275): SPPPushClient is installed : true,
I/PCWCLIENTTRACE_PushUtil( 3275): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3275): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3275): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3275): ACTION_BOOTUP - Version: 4.82,
D/PCWCLIENTTRACE_SYSTEMReceiver( 3275): ACTION_BOOTUP - Push type: [SPP, GCM]
,I/SamsungIME( 1826): getCurrentKeyboard,
I/SamsungIME( 1826): getTextKeyboard
,W/libprocessgroup( 1013): failed to open /acct/uid_10046/pid_2238/cgroup.procs: No such file or directory,
W/libprocessgroup( 1013): failed to open /acct/uid_10152/pid_2759/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/NPS_WSSNPS( 3581): [50.150621] IsRemain_AsyncBulkCheck,
,W/PCWCLIENTTRACE_PCWHandler( 3275): [ensureRegistration] - netwrok is not available. action ignored,
,I/NPS_WSSNPS( 3581): [50.150621] IsRemain_Asyncing nothing,
W/ContextImpl( 3581): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast,
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3645): MountEmulatedStorage(),
E/Zygote  ( 3645): v2
I/libpersona( 3645): KNOX_SDCARD checking this for 10031
I/libpersona( 3645): KNOX_SDCARD not a persona
,I/SELinux ( 3645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3645): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3645 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2271:com.sec.modem.settings/1000 (adj 15): empty #31
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 3581): [50.150621] Service onDestroy
,I/NPS_WSSNPS( 3581): [50.150621] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3581): [50.150621] smlBRMessageDelete
,I/NPS_WSSNPS( 3581): [50.150621] smlBREmailDelete
,I/NPS_WSSNPS( 3581): [50.150621] smlBRNetworkDelete
,I/NPS_WSSNPS( 3581): [50.150621] smlBRCallLogDelete
I/NPS_WSSNPS( 3581): [50.150621] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3581): [50.150621] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3581): [50.150621] smlBRSMemoDelete
I/NPS_WSSNPS( 3581): [50.150621] verifier installed? false
I/NPS_WSSNPS( 3581): [50.150621] cpuBooster release : false
,W/jxcore-log( 3207): Platform android
W/jxcore-log( 3207): 
,W/jxcore-log( 3207): Process ARCH arm
W/jxcore-log( 3207): 
D/TimaKeyStoreProvider( 3645): TimaSignature is unavailable
,D/ActivityThread( 3645): Added TimaKeyStore provider
,W/ResourcesManager( 3645): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/jxcore-log( 3207): JXcore Cordova bridge is ready!
I/jxcore-log( 3207): 
,W/jxcore-log( 3207): JXcore engine is started
,D/NPS_WSSNPS( 3581): [50.150621] dsServerSocket close
,I/ActivityManager( 1013): Killing 2790:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/SamsungIME( 1826): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ActivityManager( 1013): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3662 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2811:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,E/Zygote  ( 3662): MountEmulatedStorage(),
,E/Zygote  ( 3662): v2,
I/libpersona( 3662): KNOX_SDCARD checking this for 10094,
I/libpersona( 3662): KNOX_SDCARD not a persona
,I/SELinux ( 3662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3662): TimaSignature is unavailable
D/ActivityThread( 3662): Added TimaKeyStore provider
,E/jxcore-log( 3207): >> samsung-SM-A500FU
E/jxcore-log( 3207): 
,I/jxcore-log( 3207): Total memory 1983791104
I/jxcore-log( 3207): 
,I/jxcore-log( 3207): Free memory 214396928
I/jxcore-log( 3207): 
I/jxcore-log( 3207): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3207): 
I/jxcore-log( 3207): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3207): 
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2271/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1101/pid_2811/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10048/pid_2790/cgroup.procs: No such file or directory
,I/jxcore-log( 3207): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3207): 
,I/jxcore-log( 3207): Size 720 1280
I/jxcore-log( 3207): 
,I/jxcore-log( 3207): Screen Brightness 5
I/jxcore-log( 3207): 
,E/jxcore-log( 3207): Dummy Error Log.
E/jxcore-log( 3207): 
,D/elm:15183( 3662): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3662): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3662): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1013): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,I/System.out( 3386): Thread-489(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/System.out( 3386): Thread-489(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3386): Thread-489(ApacheHTTPLog):isShipBuild true
I/System.out( 3386): Thread-489(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3386): Thread-489(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  276): uids 10092
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10092
,D/elm:15183( 3662): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,V/EmergencyMode( 1399): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/elm:15183( 3662): ElmAgentService : onCreate()
,D/elm:15183( 3662): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 3662): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15183( 3662): BootCompletedState : startBootCompleted() call
,I/DBG_DM  ( 3030): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
I/System.out( 3386): pool-10-thread-1 calls detatch()
,D/elm:15183( 3662): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3662): Get License : 0
D/elm:15183( 3662): ElmAgentService : onDestroy().
,I/ActivityManager( 1013): Killing 2854:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,V/EmergencyMode( 1399): [EmergencyBase] setBootTime
,V/EmergencyMode( 1399): [EmergencyFactory] No Recovery State, kill my self.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/VlingoApplication( 3645): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,E/Zygote  ( 3694): MountEmulatedStorage()
,E/Zygote  ( 3694): v2
I/libpersona( 3694): KNOX_SDCARD checking this for 1000
I/libpersona( 3694): KNOX_SDCARD not a persona
,I/SELinux ( 3694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3694 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1013): Killing 2879:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,E/SELinux ( 3694): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3706): MountEmulatedStorage(),
E/Zygote  ( 3706): v2
I/libpersona( 3706): KNOX_SDCARD checking this for 1000
,I/libpersona( 3706): KNOX_SDCARD not a persona
,I/SELinux ( 3706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3706 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3706): TimaSignature is unavailable
,D/ActivityThread( 3706): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3694): TimaSignature is unavailable
,D/ActivityThread( 3694): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/BluetoothAdapter( 3645): 929282421: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3645): 929282421: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3645): 929282421: getState() :  mService = null. Returning STATE_OFF
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/VlingoAndroidCore( 3645): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,I/AudioService( 1013): getStreamVolume 3 index 0
,W/libprocessgroup( 1013): failed to open /acct/uid_10157/pid_2854/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10159/pid_2879/cgroup.procs: No such file or directory
,I/CameraApp( 3706): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3706): Feature.Feature(context)
I/testFeature( 3706): Feature.readInternalDefaultXml()
I/testFeature( 3706): ResetFeatureValue
,D/SettingsProvider( 1013): name = access_control_enabled
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/CameraFirmware_broadcast( 3706): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3706): CameraApp.getAppFeature()...
,I/ActivityManager( 1013): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3729 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2823:com.sec.dsm.system/1000 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3729): MountEmulatedStorage()
E/Zygote  ( 3729): v2
I/libpersona( 3729): KNOX_SDCARD checking this for 10069
I/libpersona( 3729): KNOX_SDCARD not a persona
I/SELinux ( 3729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  317): Explicit concurrent mark sweep GC freed 8757(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 658us total 39.081ms
,D/TimaKeyStoreProvider( 3729): TimaSignature is unavailable,
D/ActivityThread( 3729): Added TimaKeyStore provider,
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 19.393ms
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3120): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/,
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3120): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/,
W/ContextImpl( 3120): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    (  255): Returning OperationFailed - no handler for errno 0,
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 701us total 24.943ms,
,I/ActivityManager( 1013): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3750 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 3750): MountEmulatedStorage()
E/Zygote  ( 3750): v2
I/ActivityManager( 1013): Killing 2902:com.sec.usbsettings/1000 (adj 15): empty #31
I/libpersona( 3750): KNOX_SDCARD checking this for 10100
I/libpersona( 3750): KNOX_SDCARD not a persona
,I/SELinux ( 3750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/TimaKeyStoreProvider( 3750): TimaSignature is unavailable
,D/ActivityThread( 3750): Added TimaKeyStore provider
,I/jxcore-log( 3207): getBuffer is called!!!!
I/jxcore-log( 3207): 
,D/VlingoApplication( 3645): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3645): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/DialogFlow( 3645): initQueue()
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2823/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2902/cgroup.procs: No such file or directory
,D/FileShare-Server( 3729): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3783 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2697:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,E/Zygote  ( 3783): MountEmulatedStorage()
E/Zygote  ( 3783): v2
I/libpersona( 3783): KNOX_SDCARD checking this for 10032,
I/libpersona( 3783): KNOX_SDCARD not a persona
,D/PackageIntentReceiver( 3750): ACTION_BOOT_COMPLETED,
I/SELinux ( 3783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/SELinux ( 3783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageIntentReceiver( 3750): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3800 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2918:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,E/Zygote  ( 3800): MountEmulatedStorage()
I/libpersona( 3800): KNOX_SDCARD checking this for 10101
E/Zygote  ( 3800): v2
I/libpersona( 3800): KNOX_SDCARD not a persona
,I/SELinux ( 3800): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3800): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/TimaKeyStoreProvider( 3783): TimaSignature is unavailable
,D/ActivityThread( 3783): Added TimaKeyStore provider
,E/SELinux ( 3800): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3800): TimaSignature is unavailable
,D/ActivityThread( 3800): Added TimaKeyStore provider
,I/Icing   ( 1915): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager( 1013): Killing 2971:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1013): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3818): MountEmulatedStorage(),
E/Zygote  ( 3818): v2
I/libpersona( 3818): KNOX_SDCARD checking this for 1000
I/libpersona( 3818): KNOX_SDCARD not a persona
I/SELinux ( 3818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3818 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2697/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3818): TimaSignature is unavailable
,D/ActivityThread( 3818): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2918/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2971/cgroup.procs: No such file or directory
,W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/art     ( 3645): Suspending all threads took: 5.889ms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3841): MountEmulatedStorage()
,E/Zygote  ( 3841): v2
I/libpersona( 3841): KNOX_SDCARD checking this for 10033
I/libpersona( 3841): KNOX_SDCARD not a persona
,I/SELinux ( 3841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3841): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3841 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2989:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3841): TimaSignature is unavailable
,D/ActivityThread( 3841): Added TimaKeyStore provider
,D/FactoryTestApp( 2570): [DummyFtClient$onDestroy](2570) Destroy DummyFtClient service
,D/SamsungIME( 1826): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/FactoryTestApp( 2570): [Support$Values.getString](2570) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2570): [ModuleCommon$isConnectionModeNone](2570) mConnectionMode = gsm
I/FactoryTestApp( 2570): [ModuleCommon$isRunningFtClient](2570) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2570): [DummyFtClient$onDestroy](2570) kill process
I/Process ( 2570): Sending signal. PID: 2570 SIG: 9
,I/DBG_DM  ( 3030): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/ActivityManager( 1013): Process com.sec.factory (pid 2570)(adj 0) has died(166,1069)
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ContextImpl( 1953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{2f32809b u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,D/ActivityManager( 1013): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2989/cgroup.procs: No such file or directory
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1953): Thread created.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/SecUISvc( 1953): Service started flags 0 startId 1
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/PackageManager( 1013): [MSG] MCS_UNBIND
,I/ActivityManager( 1013): Killing 3009:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/FileApkUtils( 1915): Spent 35ms computing apk sha1.
,D/FileApkUtils( 1915): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1915): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/Gmail   ( 3800): getAccountsCursor
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1013): failed to kill pid 3009: No such process
,D/DexOptUtils( 1915): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1915): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 1915): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1915): Primary ABI of odexing process is armeabi-v7a
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3009/cgroup.procs: No such file or directory
,W/GAV2    ( 3800): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1013): Killing 2841:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/dex2oat ( 3869): ----------------------------------------------------,
I/dex2oat ( 3869): <SS>: S T A R T I N G . . .
I/dex2oat ( 3869): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3869): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk --oat-fd=86 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup( 1013): failed to open /acct/uid_10072/pid_2841/cgroup.procs: No such file or directory
,E/Gmail   ( 3800): Error finding the version of the Email provider.....
E/Gmail   ( 3800): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3800): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3800): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3800): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3800): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3800): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,W/ResourcesManager( 3841): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3841): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3841): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 3800): getAccountsCursor
,W/ResourcesManager( 3841): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3841): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ResourcesManager( 3841): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3841): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3841): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/GoogleHttpClient( 1607): GMS http client unavailable, use old client,
,E/Zygote  ( 3882): MountEmulatedStorage(),
,I/ActivityManager( 1013): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3882 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 3882): v2
I/libpersona( 3882): KNOX_SDCARD checking this for 10104,
I/libpersona( 3882): KNOX_SDCARD not a persona
,I/SELinux ( 3882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3882): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3882): TimaSignature is unavailable
,D/ActivityThread( 3882): Added TimaKeyStore provider
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3818): Resource data:2131165186
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ResourcesManager( 3818): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3818): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3818): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,W/ResourcesManager( 3882): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3800): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@3316f47 that was originally bound here
E/ActivityThread( 3800): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@3316f47 that was originally bound here
E/ActivityThread( 3800): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3800): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3800): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3800): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3800): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3800): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3800): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3800): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3800): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3800): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3800): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3800): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3800): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1013): Unbind failed: could not find connection for android.os.BinderProxy@1a3c562c
,I/Icing   ( 1915): Internal init done: storage state 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/Icing   ( 1915): Post-init done
,I/Icing   ( 1915): Query from com.google.android.googlequicksearchbox start 0 num 1000
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 27035(1549KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 26MB/39MB, paused 2.273ms total 143.088ms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3800): Observing account changes for notifications
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,E/SQLiteLog( 3800): (283) recovered 24 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/DBG_DM  ( 3030): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,E/Icing   ( 1915): No scoring data for corpus [20]
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3818): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1915): Query from com.google.android.googlequicksearchbox start 0 num 1000
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ApplicationLogger( 3103): logBytes() : Old Hash = -551177352 : New Hash = 2135716984
,D/GCM     ( 1915): COMPAT: Multi user not supported
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/System.out( 3645): INFO:Resource not found:/Common.properties Using default values
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,D/GCM     ( 1607): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ResourcesManager( 3783): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ResourcesManager( 3783): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CheckinService( 1915): Checkin interval check for package: unspecified last checkin: 1449470940712 min interval config: 0 actual interval: 26334779
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131034113
,I/GCoreUlr( 1915): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1769): DispatchingService.onCreate()
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3818): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3818): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX construct_block_size_descriptor_2d second part( 3818): took 2.239844ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3818): took 5.992448ms for 0*0 texture 0
,I/GFX raster( 3818): took 9.545313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747a3c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb747a750 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3818): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/CheckinService( 1915): Disabling old GoogleServicesFramework version
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.876667ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747a3c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74827c0 counterpartCT=4 counterpartW=96 counterparth=96
,E/File    ( 3800): fail readDirectory() errno=2
,I/AMMetaDataParserService( 3818): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/Gmail   ( 3800): notifyAccountChanged
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3818): took 2.793177ms for 0*0 texture 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3800): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/GFX generate_partition_tables( 3818): took 8.238020ms for 0*0 texture 0
,I/GFX raster( 3818): took 12.290936ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747f008 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb747f150 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 1915): onCreate
,I/AMMetaDataParserService( 3818): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/SystemUpdateService( 1915): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ActivityManager( 1013): Killing 3044:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/AuthZen ( 1915): Handling intent: android.intent.action.BOOT_COMPLETED
,I/Gmail   ( 3800): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ApplicationLogger( 3103): logEvent(): Logged 1875 bytes in 5435 ms
,D/AuthZenEventHandler( 1915): Handling event: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.933541ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb74839c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7483b28 counterpartCT=4 counterpartW=96 counterparth=96
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3800): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3800): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 1915): Checking schedule, now: 1449497275863 next: 1450010203660
I/CheckinService( 1915): active receiver: disabled
,I/ActivityManager( 1013): Killing 3087:com.policydm/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3818): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/BaseAppContext( 1915): Using Auth Proxy for data requests.
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3818): took 0.944479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747e460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb747e5c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3818): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.684064ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb74830b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74831f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SystemUpdateService( 1915): cancelUpdate (empty URL)
I/SystemUpdateService( 1915): active receiver: disabled
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.679844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747d748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb747d8b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/Babel   ( 3882): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3882): MmsConfig.loadMmsSettings
I/Babel   ( 3882): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3882): MmsConfig.loadFromDatabase
,W/libprocessgroup( 1013): failed to open /acct/uid_10150/pid_3044/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3087/cgroup.procs: No such file or directory
,E/Babel   ( 3882): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3882): MmsConfig.loadFromResources
,E/Babel   ( 3882): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3882): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1769): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/Process ( 3841): Sending signal. PID: 3841 SIG: 9
,I/AuthZen ( 1915): Fetching signing key...
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.534635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747b720 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb747b888 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 3882): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131034113
,I/AMMetaDataParserService( 3818): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.854114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747a3c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7480ca8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ChimeraCfgMgr( 1915): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1915): Signing key fetched successfully!
,W/BaseAppContext( 1915): Using Auth Proxy for data requests.
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.968333ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747a3c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7480ca8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1013): Process com.sec.android.app.sns3 (pid 3841)(adj 0) has died(128,1097)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3818): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3970): MountEmulatedStorage()
E/Zygote  ( 3970): v2
I/libpersona( 3970): KNOX_SDCARD checking this for 10034
I/libpersona( 3970): KNOX_SDCARD not a persona
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.798177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747f008 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb747d208 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 3970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3970 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3818): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/DBG_DM  ( 3030): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,D/TimaKeyStoreProvider( 3970): TimaSignature is unavailable
,D/ActivityThread( 3970): Added TimaKeyStore provider
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.862916ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb74839c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7480ca8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/art     ( 1607): Explicit concurrent mark sweep GC freed 7884(470KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 10MB/17MB, paused 1.152ms total 243.796ms
,I/Babel_StickerModule( 3882): App launched.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/a       ( 1915): Opening database auth.proximity.permit_store...
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 3.075833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747e460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb747d208 counterpartCT=4 counterpartW=96 counterparth=96
,D/AuthZenTransactionCache( 1915): Initialized cache in: /data/data/com.google.android.gms/files
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AuthZenTransactionCache( 1915): Clearing transaction cache
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/EventLogService( 1915): Aggregate from 1449495334303 (log), 1449495334303 (data)
,I/AMMetaDataParserService( 3818): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ChimeraCfgMgr( 1915): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SystemUpdateService( 1915): onDestroy
,E/Zygote  ( 3992): MountEmulatedStorage()
E/Zygote  ( 3992): v2
I/libpersona( 3992): KNOX_SDCARD checking this for 1000
I/libpersona( 3992): KNOX_SDCARD not a persona
,I/SELinux ( 3992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3818): took 0.772500ms for 96*96 texture 0
I/ActivityManager( 1013): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3992 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7480ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb747d208 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1013): Killing 3060:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
V/Babel   ( 3882): babel boot account: SMS
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.765313ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7462340 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7462e28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/art     ( 1915): Explicit concurrent mark sweep GC freed 35088(2MB) AllocSpace objects, 34(544KB) LOS objects, 40% free, 10MB/18MB, paused 1.434ms total 66.027ms
,W/Kids    ( 1915): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 1915): [KidAccountFixer] No network connection
,W/art     ( 3882): Suspending all threads took: 67.285ms
,D/TimaKeyStoreProvider( 3992): TimaSignature is unavailable
,D/ActivityThread( 3992): Added TimaKeyStore provider
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/Auth    ( 1607): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.534844ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747d208 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7439798 counterpartCT=4 counterpartW=96 counterparth=96
,W/Babel   ( 3882): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,I/AMMetaDataParserService( 3818): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/Babel   ( 3882): java.lang.Exception
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3882): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3882): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3882): 	at ckh.a(SourceFile:67)
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3882): 	at bhn.a(SourceFile:301)
W/Babel   ( 3882): 	at bhn.a(SourceFile:137)
W/Babel   ( 3882): 	at bhn.a(SourceFile:126)
W/Babel   ( 3882): 	at bhn.a(SourceFile:159)
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3882): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3882): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3882): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3882): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3882): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3882): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 3882): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3882): java.lang.Exception
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3882): 	at aes.a(SourceFile:145)
W/Babel   ( 3882): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3882): 	at ckh.a(SourceFile:67)
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3882): 	at bhn.a(SourceFile:301)
W/Babel   ( 3882): 	at bhn.a(SourceFile:137)
W/Babel   ( 3882): 	at bhn.a(SourceFile:126)
W/Babel   ( 3882): 	at bhn.a(SourceFile:159)
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3882): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3882): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3882): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3882): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3882): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3882): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3818): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3818): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131034112
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3818): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.611719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7424318 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74435b0 counterpartCT=4 counterpartW=96 counterparth=96
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1769): No location to return for getLastLocation()
,W/FusedLocationProvider( 1915): location=null
,V/GmsCoreStatsServiceLauncher( 1915): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,E/SMD     (  294): DCD OFF
,W/libprocessgroup( 1013): failed to open /acct/uid_10085/pid_3060/cgroup.procs: No such file or directory
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.599792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7424318 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7439798 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.640156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb74435b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7442c88 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3818): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.630677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7480ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7461898 counterpartCT=4 counterpartW=96 counterparth=96
,V/Babel   ( 3882): babel boot account: thalitester@gmail.com
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/PersistentNotificationBroadcastReceiver( 1607): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4015): MountEmulatedStorage(),
E/Zygote  ( 4015): v2
I/libpersona( 4015): KNOX_SDCARD checking this for 10028
I/libpersona( 4015): KNOX_SDCARD not a persona
,I/SELinux ( 4015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/Babel   ( 3882): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3882): java.lang.Exception
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3882): 	at aes.a(SourceFile:145)
W/Babel   ( 3882): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3882): 	at ckh.a(SourceFile:67)
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
,W/Babel   ( 3882): 	at bhn.a(SourceFile:301)
W/Babel   ( 3882): 	at bhn.a(SourceFile:137)
W/Babel   ( 3882): 	at bhn.a(SourceFile:126)
W/Babel   ( 3882): 	at bhn.a(SourceFile:159)
W/Babel   ( 3882): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3882): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3882): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559),
W/Babel   ( 3882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3882): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3882): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3882): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3882): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SELinux ( 4015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4015): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity,
I/ActivityManager( 1013): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4015 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131034113
,W/GCoreFlp( 1769): No location to return for getLastLocation(),
W/FusedLocationProvider( 1915): location=null
,I/AMMetaDataParserService( 3818): getResourceName:com.android.contacts:xml/assistant_main
D/SSRM:n  ( 1013): SIOP:: AP = 360
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.822709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb745bcd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb71ae2e0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4015): TimaSignature is unavailable
,D/ActivityThread( 4015): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3818): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.999844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb745bcd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7447448 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3818): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 3992): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/DBG_POLICYDM( 3992): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4035): MountEmulatedStorage(),
E/Zygote  ( 4035): v2
I/libpersona( 4035): KNOX_SDCARD checking this for 1000
I/SELinux ( 4035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4035): KNOX_SDCARD not a persona
,I/SELinux ( 4035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_POLICYDM( 3992): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3992): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3992): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/TimaKeyStoreProvider( 4035): TimaSignature is unavailable
,D/ActivityThread( 4035): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3992): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3992): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,W/QCamera2Factory(  289): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  289): getCameraInfo: X
,W/QCamera2Factory(  289): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  289): getCameraInfo: X
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3800): getAccountsCursor
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_POLICYDM( 3992): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/GFX raster( 3818): took 0.623698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7462e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7442c88 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3882): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3882): Unsupported mime audio/evrc
,I/DBG_POLICYDM( 3992): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3992): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/AMMetaDataParserService( 3818): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/AudioCapabilities( 3882): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3882): Unsupported mime audio/mpeg-L1
,D/PowerManagerService( 1013): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1173 (0x0)
,W/AudioCapabilities( 3882): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3882): Unsupported mime audio/x-ms-wma
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,I/GFX raster( 3818): took 0.715729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7424318 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7461898 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3818): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/DBG_POLICYDM( 3992): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,W/AudioCapabilities( 3882): Unsupported mime audio/x-ima
,W/art     ( 3645): Suspending all threads took: 13.352ms
,I/DBG_POLICYDM( 3992): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,W/AudioCapabilities( 3882): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3882): Unsupported mime audio/evrc
,E/Zygote  ( 4054): MountEmulatedStorage()
E/Zygote  ( 4054): v2
I/libpersona( 4054): KNOX_SDCARD checking this for 1000
I/libpersona( 4054): KNOX_SDCARD not a persona
,I/SELinux ( 4054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/VideoCapabilities( 3882): Unsupported mime video/wvc1
,E/SELinux ( 4054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 3103:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,W/VideoCapabilities( 3882): Unsupported mime video/x-ms-wmv
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,I/GFX raster( 3818): took 1.135052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747e460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb71ae2e0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/art     (  317): Explicit concurrent mark sweep GC freed 8763(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 921us total 27.279ms
,W/VideoCapabilities( 3882): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3882): Unsupported mime video/wvc1
,I/DBG_DM  ( 3030): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/AMMetaDataParserService( 3818): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.564ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 16.864ms
,W/VideoCapabilities( 3882): Unsupported mime video/x-ms-wmv
D/TimaKeyStoreProvider( 4054): TimaSignature is unavailable
D/ActivityThread( 4054): Added TimaKeyStore provider
,I/ActivityManager( 1013): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4070 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4070): MountEmulatedStorage(),
E/Zygote  ( 4070): v2
I/libpersona( 4070): KNOX_SDCARD checking this for 10035
I/libpersona( 4070): KNOX_SDCARD not a persona
I/SELinux ( 4070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4070): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 3221:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,W/VideoCapabilities( 3882): Unsupported mime video/x-ms-wmv7
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.746406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7480ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7439798 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3882): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3882): Unsupported mime video/mp43
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/TimaKeyStoreProvider( 4070): TimaSignature is unavailable
,D/ActivityThread( 4070): Added TimaKeyStore provider
,W/VideoCapabilities( 3882): Unsupported mime video/sorenson
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.906823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7462340 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7447448 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3882): Unsupported mime video/mp4v-esdp
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_POLICYDM( 3992): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3992): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,D/KnoxSetupWizardDbHelper( 4054): dbMigrationFlag : false
,I/DBG_POLICYDM( 3992): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3992): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/ShortcutReceiver( 4054):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.528282ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747d208 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7442c88 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 4015): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/AMMetaDataParserService( 3818): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/KnoxShortcutUtil( 4054): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4054):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 4054):  shortcut migration not required 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4090): MountEmulatedStorage(),
,E/Zygote  ( 4090): v2,
,I/libpersona( 4090): KNOX_SDCARD checking this for 1000,
I/libpersona( 4090): KNOX_SDCARD not a persona
,I/VideoCapabilities( 3882): Unsupported profile 4 for video/mp4v-es
I/ActivityManager( 1013): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4090 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3244:com.fmm.dm/1000 (adj 15): empty #31
I/SELinux ( 4090): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity,
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3818): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
I/SELinux ( 4090): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SPPClientService( 4070): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4070): [PushClientApplication] Push log off : This is Ship build version
,E/SELinux ( 4090): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4090): TimaSignature is unavailable
,E/SPPClientService( 4070): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/ActivityThread( 4090): Added TimaKeyStore provider
,I/GCoreUlr( 1769): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131165203
,I/GCoreUlr( 1769): Unbound from all location providers
,W/ResourcesManager( 3818): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3818): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,D/SPPClientService( 4070): PushLog.txt file is not deleted.
D/SPPClientService( 4070): PushLog.txt file is not deleted.
D/SPPClientService( 4070): ============PushLog. stop!
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3818): took 2.767864ms for 0*0 texture 0
,E/KnoxSetupWizardClient( 4090): isShipMode : 1
I/KnoxSetupWizardClient( 4090): onReceive : android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/art     ( 3645): Suspending all threads took: 13.795ms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/GFX generate_partition_tables( 3818): took 10.307606ms for 0*0 texture 0
,I/GFX raster( 3818): took 13.912136ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb745dd28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb745f348 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576,
E/Zygote  ( 4116): MountEmulatedStorage()
E/Zygote  ( 4116): v2
I/libpersona( 4116): KNOX_SDCARD checking this for 10041,
I/libpersona( 4116): KNOX_SDCARD not a persona
,I/SELinux ( 4116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.822188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb745dee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7631720 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4116): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4116 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SecDataIO(  255): Write to block
I/ActivityManager( 1013): Killing 3260:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,I/AMMetaDataParserService( 3818): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4116): TimaSignature is unavailable
,D/ActivityThread( 4116): Added TimaKeyStore provider
,I/ActivityManager( 1013): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4132 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3338:com.fmm.ds/1000 (adj 15): empty #31
,E/Zygote  ( 4132): MountEmulatedStorage()
I/libpersona( 4132): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4132): v2
I/libpersona( 4132): KNOX_SDCARD not a persona
I/SELinux ( 4132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4132): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 2550): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 3030): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3030): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,D/TimaKeyStoreProvider( 4132): TimaSignature is unavailable
,E/DBG_DM  ( 3030): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,D/ActivityThread( 4132): Added TimaKeyStore provider
,I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/dex2oat ( 3869): dex2oat took 2.992s (threads: 4)
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.777396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb745dee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7630958 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/DexOptUtils( 1915): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex
D/DexOptUtils( 1915): Set odex to world readable.
,D/DexOptUtils( 1915): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.odex
,D/FileApkUtils( 1915): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,W/System.err( 4090): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4090): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4090): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4090): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4090): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4090): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4090): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/GmsModuleFndr( 1915): Beginning GMS chimera module scan
,D/GmsModuleFndr( 1915): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 1915): Beginning module configuration check
,D/ChimeraCfgMgr( 1915): Module APKs unchanged, check complete
,W/libprocessgroup( 1013): failed to open /acct/uid_10057/pid_3103/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3221/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3244/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10003/pid_3260/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3338/cgroup.procs: No such file or directory
,I/GCoreUlr( 1769): DispatchingService.onDestroy()
,I/GCoreUlr( 1769): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1769): Unbound from all location providers
,E/SQLiteLog( 3882): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 3882): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 3882): (284) automatic index on conversation_participants_view(conversation_id)
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 32988(2030KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 26MB/39MB, paused 2.406ms total 161.127ms
,I/Process ( 2550): Sending signal. PID: 2550 SIG: 9
,E/SQLiteLog( 3882): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 1.004219ms for 96*96 texture 0
,E/SQLiteLog( 3882): (284) automatic index on conversation_participants_view(conversation_id)
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb745dee8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb762e8a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,D/Finsky  ( 4015): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/ActivityManager( 1013): Killing 3361:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/SA      ( 4116): [SSP] onCreated
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.617969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb745f600 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb745f738 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1013): Process com.sec.android.app.sysscope (pid 2550)(adj 0) has died(105,1121)
,W/Settings( 4015): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4015): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/AMMetaDataParserService( 3818): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.612968ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb745f600 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7631720 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,W/libprocessgroup( 1013): failed to open /acct/uid_10060/pid_3361/cgroup.procs: No such file or directory
,I/SA      ( 4116): [TPM] There is no property file
,I/SA      ( 4116): [SCU] isHaveSA() - false
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/SA      ( 4116): [TPM] getModelProperty : null
I/SA      ( 4116): [TPM] getCSCProperty : null
,I/SA      ( 4116): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4116): [DM] PRODUCT AMOLED FEATURE: false
,I/SA      ( 4116): [DM] TFT FEATURE: false
,I/SA      ( 4116): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4116): [DM] init START
,W/ContextImpl( 3818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/SA      ( 4116): [DM] This device is not a Vodafone
,W/ResourceType( 4116): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
D/GCMRegistrar( 3386): resetting backoff for com.dropbox.android
,W/ResourceType( 4116): No package identifier when getting value for resource number 0x00000000
D/Volley  ( 4015): [606] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1013): Killing 3267:com.google.android.configupdater/u0a86 (adj 15): empty #31
,D/Volley  ( 4015): [613] DiskBasedCache.clear: Cache cleared.
W/ResourceType( 4116): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4116): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4116): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4116): [SCU] isHaveSA() - false
I/SA      ( 4116): support phone number id : false
I/SA      ( 4116): [DM] Supports Ref Jpn : true
,I/SA      ( 4116): [DM] init END
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,I/SA      ( 4116): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4116): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,D/Ads     ( 4015): Skipping gmscore version check
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1013): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,V/GCMRegistrar( 3386): Registering app com.dropbox.android of senders 735665981150
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3818): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,W/ResourcesManager( 3818): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.764843ms for 96*96 texture 0
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747a118 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7474b78 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4116): [OR] onReceive END
,D/Finsky  ( 4015): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4015): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4116): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4116): [ODM] queryOpenData(key= GEO_IP )
,D/BluetoothAdapter( 3207): disable()
W/libprocessgroup( 1013): failed to open /acct/uid_10086/pid_3267/cgroup.procs: No such file or directory
,E/Zygote  ( 4177): MountEmulatedStorage(),
I/libpersona( 4177): KNOX_SDCARD checking this for 10042
E/Zygote  ( 4177): v2
I/libpersona( 4177): KNOX_SDCARD not a persona
,I/SELinux ( 4177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4177): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4177 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SA      ( 4116): getMccForGalaxyJpn step2 GEO_IP MCC : 260
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/SA      ( 4116): [LBE] REF_JPN : true
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
I/SA      ( 4116): [BDC] create
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/BluetoothManagerService( 1013): Bluetooth is already disabled. DO NOT disable again.
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3818): took 2.508177ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 4177): TimaSignature is unavailable
,D/SecContentProvider( 1013): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1013): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1013): mCursor = null
D/ActivityThread( 4177): Added TimaKeyStore provider
,D/WifiService( 1013): setWifiEnabled: false pid=3207, uid=10174
,I/GFX generate_partition_tables( 3818): took 8.795468ms for 0*0 texture 0
D/SettingsProvider( 1013): name = wifi_on
,I/GFX raster( 3818): took 12.368229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7474b78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74678f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/jxcore-log( 3207): ****TEST TOOK:  5087  ms ****
I/jxcore-log( 3207): 
,I/jxcore-log( 3207): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3207): 
,D/GCM     ( 1607): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
D/Finsky  ( 4015): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/SA      ( 4116): [DBMV2] getEmailID
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.643489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb746ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb746ed90 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4177): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
I/SA      ( 4116): [DBMV2] getDataV02ForItems
I/SA      ( 4116): [SSP] query invoked
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/SA      ( 4116): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1607): GCM config loaded
,I/DBG_DM  ( 3030): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
D/Finsky  ( 4015): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/SA      ( 4116): [SCU] get signed id from samsung account1.0 DB.
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.662395ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747b1a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb746e670 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/SA      ( 4116): [BDC] destroy
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/StrictMode( 4132): StrictMode policy violation; ~duration=421 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4132): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4132): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4132): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4132): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4132): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4132): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4132): StrictMode policy violation; ~duration=405 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4132): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4132): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4132): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4132): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4132): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4132): StrictMode policy violation; ~duration=337 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4132): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4132): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4132): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4132): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4132): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4132): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4132): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4132): StrictMode policy violation; ~duration=336 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4132): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4132): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4132): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4132): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4132): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4132): StrictMode policy violation; ~duration=335 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4132): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4132): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4132): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4132): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4132): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/StrictMode( 4132): StrictMode policy violation; ~duration=333 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4132): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4132): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4132): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4132): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4132): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4132): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4132): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4132): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4132): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4132): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4132): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4132): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4132): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/StrictMode( 4132): StrictMode policy violation; ~duration=316 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4132): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4132): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4132): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4132): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4132): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4132): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4132): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4132): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4132): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4132): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4132): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4132): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4132): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4132): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/StrictMode( 4132): StrictMode policy violation; ~duration=280 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4132): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4132): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4132): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4132): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4132): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4132): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4132): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/StrictMode( 4132): StrictMode policy violation; ~duration=279 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4132): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4132): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4132): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4132): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4132): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4132): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4132): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4132): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4132): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4132): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4132): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4132): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4132): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4132): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/CalendarProvider2( 4177): CalendarProvider2.onCreate() called
E/DBG_DM  ( 3030): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
E/Zygote  ( 4201): MountEmulatedStorage()
E/Zygote  ( 4201): v2
I/libpersona( 4201): KNOX_SDCARD checking this for 1000
I/libpersona( 4201): KNOX_SDCARD not a persona
I/SELinux ( 4201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4201 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3386:com.dropbox.android/u0a92 (adj 15): empty #31
,I/SELinux ( 4201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.636563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb77de0e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77de190 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 4201): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3030): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
I/ActivityManager( 1013): Killing 3138:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
D/TimaKeyStoreProvider( 4201): TimaSignature is unavailable
,D/ActivityThread( 4201): Added TimaKeyStore provider
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.750834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb746e928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb746e670 counterpartCT=4 counterpartW=96 counterparth=96
,I/System.out( 1607): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1607): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1607): (HTTPLog)-Static: isShipBuild true
I/System.out( 1607): (HTTPLog)-Thread-186-653844921: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1607): (HTTPLog)-Static: isSBSettingEnabled false
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10012
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
,I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,D/StatusChecker( 4201): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4201): onReceive : net.mt.init : DONE
,W/libprocessgroup( 1013): failed to open /acct/uid_10009/pid_3138/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10092/pid_3386/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.995937ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747a118 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77e09c0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/Zygote  ( 4223): MountEmulatedStorage(),
E/Zygote  ( 4223): v2
I/libpersona( 4223): KNOX_SDCARD checking this for 10116
I/libpersona( 4223): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4223 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
I/ActivityManager( 1013): Killing 3412:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
I/SELinux ( 4223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4223): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/com.google.a.a.b.d.a( 4132): Application name is not set. Call Builder#setApplicationName.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4223): TimaSignature is unavailable,
D/ActivityThread( 4223): Added TimaKeyStore provider
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.641198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7474b78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb746e210 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/AndroidRuntime( 4198): 
D/AndroidRuntime( 4198): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4198): CheckJNI is OFF
D/AndroidRuntime( 4198): readGMSProperty: start
D/AndroidRuntime( 4198): readGMSProperty: already setted!!
D/AndroidRuntime( 4198): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4198): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4198): readGMSProperty: end
D/AndroidRuntime( 4198): addProductProperty: start
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3818): took 1.059896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb746ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7466758 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,I/PageBuddyNotiSvc( 4223): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4223): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4223): onCreate mCpBitFlag=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.690990ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747b1a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb745be90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.639896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb77de0e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77e09c0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4247): MountEmulatedStorage()
I/libpersona( 4247): KNOX_SDCARD checking this for 10125
E/Zygote  ( 4247): v2
I/libpersona( 4247): KNOX_SDCARD not a persona
I/SELinux ( 4247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4247): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4247 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,W/libprocessgroup( 1013): failed to open /acct/uid_10062/pid_3412/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4247): TimaSignature is unavailable
,D/ActivityThread( 4247): Added TimaKeyStore provider
,W/ResourcesManager( 4247): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4247): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4247): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.713281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb746e928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77e09c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,E/AffinityControl( 4198): AffinityControl: registerfunction enter
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.680209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747a118 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb746eca8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/AndroidRuntime( 4198): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1013): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1013): START PACKAGE DELETE: observer{264401560}
D/PackageManager( 1013): pkg{<packageName>}
D/PackageManager( 1013): user{0}
D/PackageManager( 1013): caller{2000}
D/PackageManager( 1013): flags{3}
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1013): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1013): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService( 1013): deletePackage- pkg:com.example.hello, edmuserId:0,
D/PackageManager( 1013): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1013): deletePackage- pkg:com.example.hello, edmuserId:-1
D/PackageManager( 1013): !@killApplicatoin: 10174, uninstall pkg
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled
I/ActivityManager( 1013): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
D/QuickConnect( 4247): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1013): Killing 3207:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg,
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled :  enabled true
D/QuickConnect( 4247): Util.setSCRunningSetting - [value]0
,W/ActivityManager( 1013): Force removing ActivityRecord{1ac4ba66 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1013): Set to : 0
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1013): Focused application set to: xxxx
D/InputDispatcher( 1013): Focus left window: 3207
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (-2/7)
,V/AlarmManager( 1013): waitForAlarm result :4
,D/CustomFrequencyManagerService( 1013): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1013): mDVFSHelper.acquire()
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.786406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7474b78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb746eca8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.612500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb746ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb746eca8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.684375ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747b1a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7482d38 counterpartCT=4 counterpartW=96 counterparth=96
,W/PackageSettings( 1013): Skipping PackageSetting{27c82a8c com.test.thalitest/10175} due to missing metadata
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.781094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb77de0e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb746eca8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1013): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.718230ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb746e928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7482d38 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1013): Force stopping com.example.hello appid=10174 user=0: pkg removed
,D/SettingsProvider( 1013): name = scon_is_running
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10125
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,W/ActivityManager( 1013): CustomStartingWindow se packge removed so remove capture also
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.704270ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747a118 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb746eca8 counterpartCT=4 counterpartW=96 counterparth=96
D/Launcher( 1462): onRestart, Launcher: 372218644
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/Launcher( 1462): onStart, Launcher: 372218644
D/Launcher.HomeView( 1462): onStart
,D/Launcher( 1462): onResume, Launcher: 372218644
,D/SettingsProvider( 1013): name = kids_home_mode
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10007
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/Launcher.HomeView( 1462): onResume
,I/QuickConnect( 4247): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,D/Launcher( 1462): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/QuickConnect( 4247): PeriphStartReceiver.onReceive - no need to start
,I/art     ( 3783): Explicit concurrent mark sweep GC freed 15473(900KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 6MB/9MB, paused 708us total 42.639ms
,I/art     ( 3783): WaitForGcToComplete blocked for 9.543ms for cause HomogeneousSpaceCompact
,E/SamsungIME( 1826): mOCRHelper is null
,I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/GeofencerStateMachine( 1769): Ignoring removeGeofence because network location is disabled.
,I/GFX raster( 3818): took 0.725417ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7474b78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7460208 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 1439): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MenuAppsGridFragment( 1462): onResume
,D/ActivityManager( 1013): handle home activity for 0
I/WallpaperManagerService( 1013): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1013): post home show event for user 0
D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
D/RegisteredComponentCache( 1422): Collect Tech packages for Knox
,I/SurfaceFlinger(  256): id=12 createSurf (720x1280),1 flag=4, Mauncher
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.774531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb746ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb746eca8 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1013): Focus entered window: 1462
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,I/ActivityManager( 1013): Killing 3426:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1462): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher( 1462): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.813281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747b1a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7460208 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/PersonaManager( 1422): isKioskContainerExistOnDevice
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.801770ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb77de0e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb746eca8 counterpartCT=4 counterpartW=96 counterparth=96
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1013): mCursor = null
,W/InputMethodManagerService( 1013): Got RemoteException sending setActive(false) notification to pid 3207 uid 10174
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SamsungIME( 1826): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/Zygote  ( 4272): MountEmulatedStorage()
I/libpersona( 4272): KNOX_SDCARD checking this for 10131
E/Zygote  ( 4272): v2
I/libpersona( 4272): KNOX_SDCARD not a persona
I/SELinux ( 4272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4272): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1013): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4272 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/TimaKeyStoreProvider( 4272): TimaSignature is unavailable
,D/ActivityThread( 4272): Added TimaKeyStore provider
I/GFX raster( 3818): took 0.719062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7104ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb70a2818 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 26845(1885KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 26MB/39MB, paused 3.928ms total 245.647ms
,I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
D/PersonaManager( 1013): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.965156ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747cba8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77de0b0 counterpartCT=4 counterpartW=96 counterparth=96
,D/EnterpriseDeviceManagerService( 1013): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1013): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1013): no available spell checker services found
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/PackageManager( 1013): delete codoeFile: 
,D/AASAuninstall( 1013): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
,I/AASA_removePackage( 1013): UID=10174 Target=com.example.hello
,D/PackageManager( 1013): result of delete: 1{264401560}
,D/AndroidRuntime( 4198): Shutting down VM
,D/RCPManagerService( 1013): PackageReceiver onReceive()
,I/HarmonyEASService( 1013): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1422): isKioskContainerExistOnDevice
,I/ActivityManager( 1013): Displayed Component not be shown by security: +357ms
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 1013): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1013): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1013): OtpDbHelper::getInstance New instance created
,D/RegisteredServicesCache( 1422): empty dynamic service
,D/OTPFW   ( 1013): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1013): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1013): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1013): ProvisionData::getAllEntries Table is empty
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 1013): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1013): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1013): uID is 10174
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1013): uID is 10174
D/SSRM:aZ ( 1013): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
D/TaskPersister( 1013): removeObsoleteFile: deleting file=2_task.xml
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
,V/AlarmManagerEXT( 1013): com.example.hello(10174) is removed.
D/SensorService( 1013): [SO] activate (ident=0xb74bb5e8, enabled=0)
D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.660260ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7462070 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7424318 counterpartCT=4 counterpartW=96 counterparth=96
,D/SensorManager( 1013): unregisterListener ::   
,I/Sensors ( 1013): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1013): [SO] changed settle time [0]
D/SensorService( 1013): [SO] setDelay [200000000]
D/SensorService( 1013): [SO] activate (ident=0xb74bb5e8, enabled=1)
D/SensorService( 1013): [SO] AR_init
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/CustomFrequencyManagerService( 1013): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1013): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1013): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ResourcesManager( 4272): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4272): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4272): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4272): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SensorManager( 1013): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1013):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1013): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,I/iu.UploadsManager( 1915): End new media; added: 0, uploading: 0, time: 387 ms
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.733488ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb74601d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7439798 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourceType( 1013): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SBrowserFeatureFlag( 4272): initialized in static block : loadCscFeatureValue() succeed! 
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ManifestProvider( 4272): onCreate()
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/NetworkSettingsReceiver( 4272): onReceive: android.intent.action.BOOT_COMPLETED
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.687239ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7482cb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7447448 counterpartCT=4 counterpartW=96 counterparth=96
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1013): clearDefaults: com.example.hello
I/CrashAnrDetector( 1013): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1013): failed to open /acct/uid_10092/pid_3426/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/SBrowserFeatureFlag( 4272): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@162f9b14
,D/SBrowserFeatureFlag( 4272): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4272): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,W/art     ( 4198): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3818): took 0.633282ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb77de0e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb747c6d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4292): MountEmulatedStorage(),
I/libpersona( 4292): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4292): v2,
I/libpersona( 4292): KNOX_SDCARD not a persona
I/SELinux ( 4292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SELinux ( 4292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GFX raster( 3818): took 0.787656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7104ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb743af18 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1013): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4292 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3438:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
I/AMMetaDataParserService( 3818): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3818): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3818): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3818): getResourcePackageName:assistant
I/AMMetaDataParserService( 3818): Resource data:2131099648
,I/AMMetaDataParserService( 3818): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3818): getResourceTypeNamexml
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.682187ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb747cba8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb70a2818 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4292): TimaSignature is unavailable
,D/ActivityThread( 4292): Added TimaKeyStore provider
,D/SensorService( 1013): [SO] Reset Rotation Old [100], Init [1]
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.667135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7462070 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7447448 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
W/ResourcesManager( 4292): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4292): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3818): took 0.661197ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb74601d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7461420 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/SQLiteLog( 3818): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3818): (3850) statement aborts at 19: [INSERT INTO AMData(actname,amicon,appname,id,amtitle,amstate,amintent,amlabel) VALUES (?,?,?,?,?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 3818): Error inserting actname=com.android.mms.ui.ConversationList amicon=[B@1f720324 appname=com.android.mms id=1449497279529 amtitle=Add from contacts amstate=1 amintent=com.android.mms.ui.composemessagefragment.attachcontacts amlabel=2131493291
E/SQLiteDatabase( 3818): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 3818): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
E/SQLiteDatabase( 3818): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3818): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3818): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3818): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3818): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3818): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/        ( 3818): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3818): took 0.670261ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3818): Bitmap=0xb7482cb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb745cdc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3818): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/SQLiteLog( 3818): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3818): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3818): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3818): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3818): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3818): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3818): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3818): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3818): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3818): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3818): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3818): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3818): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3818): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3818): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3818): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3818): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3818): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3818): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3818): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3818): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3818): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3818): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3818): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3818): ,	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3818): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3818): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3818): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3818): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3818): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager( 1013): Killing 3170:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/libprocessgroup( 1013): failed to open /acct/uid_10014/pid_3438/cgroup.procs: No such file or directory
,D/daemonapp( 1351): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup( 1013): failed to open /acct/uid_10015/pid_3170/cgroup.procs: No such file or directory
,D/CustomFrequencyManagerService( 1013): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  tag : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/WallpaperManager( 1462): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1462): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true

```
