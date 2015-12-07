#### Test 50242285e707819_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
W/ActivityThread( 2837): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
--------- beginning of main
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
D/TP/SmsProvider( 1443): query,matched:51, calling pid = 2235
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
D/ActivityManager( 1016): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
D/ActivityManager( 1016): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 2872): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Killing 1597:com.google.android.apps.maps/u0a107 (adj 15): empty #31
V/MediaScanner( 1225):  prescan time: 495ms (DB items: 141)
V/MediaScanner( 1225):     scan time: 85ms (Caching mode: true), (makeEntry time: 59ms ~69%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 580ms
V/MediaScanner( 1225): checked files: 133  directories : 6  (I: 0, U: 0)
I/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/TP/SmsProvider( 1443): match 51:Elapsed time : 15.628 ms
D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
D/MediaScanner( 1225): checkDefaultSounds
D/MediaScanner( 1225): system alarm_alert  : Vwiurug_etwofi5wgg
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2892): MountEmulatedStorage()
E/Zygote  ( 2892): v2
W/ContextImpl( 2872): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
I/libpersona( 2892): KNOX_SDCARD checking this for 10157
I/libpersona( 2892): KNOX_SDCARD not a persona
I/SELinux ( 2892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2892): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2892 uid=10157 gids={50157, 9997} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
D/MediaScanner( 1225): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1225): system notification_sound  : K_Oprkltf5wgg
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/NearbySettings( 1281): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1281): MountReceiver.onReceive - Internal Path
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/MediaScanner( 1225): OK. notification_sound is already exist in setting DB.
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/MediaScanner( 1225): system ringtone  : Wmfi_lpf_pwirywu5wgg
E/Zygote  ( 2910): MountEmulatedStorage()
E/Zygote  ( 2910): v2
I/SELinux ( 2910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2910): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/TimaKeyStoreProvider( 2892): TimaSignature is unavailable
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/ActivityThread( 2892): Added TimaKeyStore provider
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
I/libpersona( 2910): KNOX_SDCARD checking this for 1000
I/libpersona( 2910): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2910 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/F_PHONE ( 2872): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
W/ContextImpl( 2872): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/MediaScanner( 1225): OK. ringtone is already exist in setting DB.
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2837): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
D/TimaKeyStoreProvider( 2910): TimaSignature is unavailable
D/ActivityThread( 2910): Added TimaKeyStore provider
D/ActivityManager( 1016): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
I/LcdtestApp( 2837): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
D/SettingsProvider( 1016): name = personal_mode_enabled
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) ACTION_MEDIA_SCANNER_FINISHED = /system/media
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) ACTION_MEDIA_SCANNER_FINISHED = Ignored
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/MediaScannerService( 1225): !@done scanning volume internal
W/libprocessgroup( 1016): failed to open /acct/uid_10138/pid_1754/cgroup.procs: No such file or directory
W/SEAMService( 1016):  hashset_to_int_array returning null
W/ResourcesManager( 2892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/SEAMService( 1016):  hashset_to_int_array returning null
E/SQLiteLog( 2700): (284) automatic index on seams_container_info(seams_container_id)
E/SQLiteLog( 2700): (284) automatic index on seams_container_info(sp_id)
E/Zygote  ( 2929): MountEmulatedStorage()
E/Zygote  ( 2929): v2
I/libpersona( 2929): KNOX_SDCARD checking this for 1000
I/libpersona( 2929): KNOX_SDCARD not a persona
I/SELinux ( 2929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/SEAMService( 1016):  hashset_to_int_array returning null
E/SELinux ( 2929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2929 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
D/MediaScannerService( 1225): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
W/libprocessgroup( 1016): failed to open /acct/uid_10107/pid_1597/cgroup.procs: No such file or directory
D/Mms/MessagingNotification( 2235): isBlockingModeEnabled() = false, Zen mode = 0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2910): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2929): TimaSignature is unavailable
D/ActivityThread( 2929): Added TimaKeyStore provider
D/BluetoothBDAdrressReceiver( 2910): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 2910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=2944 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2069:com.vlingo.midas/u0a31 (adj 15): empty #31
W/ResourcesManager( 1443): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/Zygote  ( 2944): MountEmulatedStorage()
I/libpersona( 2944): KNOX_SDCARD checking this for 10159
E/Zygote  ( 2944): v2
I/libpersona( 2944): KNOX_SDCARD not a persona
I/SELinux ( 2944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
I/SELinux ( 2944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
D/F_PHONE ( 2872): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 2872): default registerAction()
I/F_PHONE ( 2872): [[com.sec.bcservice]] sendPendingMessage()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2944): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
E/Zygote  ( 2957): MountEmulatedStorage()
I/libpersona( 2957): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2957): v2
I/libpersona( 2957): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2957 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2957): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 2092:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
W/ResourcesManager( 1443): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2944): TimaSignature is unavailable
D/BadgeProvider( 1553): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/BluetoothBDTestService( 1443): onCreate()
D/ActivityThread( 2944): Added TimaKeyStore provider
E/BluetoothBDTestService( 1443): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1443): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1443): already exist!( /efs/bluetooth/bt_addr ), file length: 17
D/TimaKeyStoreProvider( 2957): TimaSignature is unavailable
D/ActivityThread( 2957): Added TimaKeyStore provider
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
I/SmartcardBootCompleteReceiver( 1281): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1281): Received intent with action - android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 2757): Verification of void com.android.email.activity.MessageListItemOuterContainer.<init>(android.content.Context, android.util.AttributeSet, int) took 115.697ms
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
W/libprocessgroup( 1016): failed to open /acct/uid_10031/pid_2069/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10050/pid_2092/cgroup.procs: No such file or directory
I/Intent to TravelDirActivity( 2944): inside TravelBroadcastReceiver
D/Launcher.Model( 1468): reloadBadges entered.
D/BadgeProvider( 1553): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1553): sendNotify, [notify] : null
D/BadgeProvider( 1553): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1553): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1553): update, [UpdateCount] : 1
I/ActivityManager( 1016): Killing 2148:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
D/Mms/MessagingNotification( 2235): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2235): remove alarm
I/art     ( 1016): Explicit concurrent mark sweep GC freed 37895(2MB) AllocSpace objects, 5(194KB) LOS objects, 33% free, 25MB/38MB, paused 2.186ms total 146.423ms
D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
I/SmartcardBootCompleteReceiver( 1281): Broadcast sent with current lockscreen type
D/Mms/MessagingNotification( 2235): updateAllHistoryAsRead()
W/ResourcesManager( 2957): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/MediaScanner( 1225): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
W/libprocessgroup( 1016): failed to open /acct/uid_10113/pid_2148/cgroup.procs: No such file or directory
D/TP/SmsProvider( 1443): query,matched:0, calling pid = 2235
D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
D/BadgeProvider( 1553): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/TP/SmsProvider( 1443): match 0:Elapsed time : 26.917 ms
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2988): MountEmulatedStorage()
E/Zygote  ( 2988): v2
I/libpersona( 2988): KNOX_SDCARD checking this for 1000
I/libpersona( 2988): KNOX_SDCARD not a persona
I/SELinux ( 2988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2988 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 1484:com.android.printspooler/u0a136 (adj 15): empty #31
E/SELinux ( 2988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
V/MediaScanner( 1225): processDirectory :  /storage/emulated/0
D/Mms/SmsReceiverService( 2235): [end]    handleBootCompleted() consume time = 762.11
D/TimaKeyStoreProvider( 2988): TimaSignature is unavailable
D/ActivityThread( 2988): Added TimaKeyStore provider
D/Launcher.Model( 1468): reloadBadges entered.
D/BadgeProvider( 1553): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1553): sendNotify, [notify] : null
D/BadgeProvider( 1553): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1553): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1553): update, [UpdateCount] : 1
I/KnoxUsageLogPro( 2957): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(75ebcf7
I/KnoxUsageLogPro( 2957): premStatus:2
I/KnoxUsageLogPro( 2957): isEulaShown : false
I/KnoxUsageLogPro( 2957): KnoxUsageReceiver onReceive : not Processible, just return
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/[SBeam] ( 1281): SBeamEnabler.initPreferenceForSbeam : 0
D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1225): processDirectory :  /storage/extSdCard
W/MediaScanner( 1225): Error opening directory, reason : Permission denied.
W/MediaScanner( 1225): 7klwibgf7fxlKdCbid7
I/DIAGMON_AGENT( 2929): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
V/MediaScanner( 1225):  prescan time: 224ms (DB items: 27)
V/MediaScanner( 1225):     scan time: 51ms (Caching mode: true), (makeEntry time: 29ms ~56%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 278ms
V/MediaScanner( 1225): checked files: 10  directories : 17  (I: 0, U: 0)
I/KnoxUsageLogPro( 2957): savePreference: key = previous_sys_time value = 1449498951403
E/Zygote  ( 3007): MountEmulatedStorage()
I/libpersona( 3007): KNOX_SDCARD checking this for 10085
E/Zygote  ( 3007): v2
I/libpersona( 3007): KNOX_SDCARD not a persona
I/SELinux ( 3007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
I/ActivityManager( 1016): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3007 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 1626:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/iu.UploadsManager( 1983): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
I/SecureStorage(  369): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 1225): !@done scanning volume external
D/FactoryTestApp( 2570): [DummyFtClient$mBroadcastReceiver](2570) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2570): [DummyFtClient$sendBootCompletedAndFinish](2570) ...
D/FactoryTestApp( 2570): [Support$Values.getString](2570) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2570): [ModuleCommon$isConnectionModeNone](2570) mConnectionMode = gsm
I/art     (  315): Explicit concurrent mark sweep GC freed 8793(375KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 732us total 23.431ms
D/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$ResponseWriter](2570) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$connectToSecPhoneService](2570)  
W/ContextImpl( 2570): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
I/ActivityManager( 1016): Killing 2253:com.sec.android.omc/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3007): TimaSignature is unavailable
D/ActivityThread( 3007): Added TimaKeyStore provider
D/ActivityManager( 1016): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/KnoxUsageLogPro( 2957): savePreference: key = previous_elapsed_time value = 33087
I/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$onServiceConnected](2570) connected done
I/ActivityManager( 1016): Killing 2283:com.sec.tcpdumpservice/1000 (adj 15): empty #31
D/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$write](2570) Send Response Message to SecPhone
D/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$write](2570) Response ��
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.075ms
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 16.869ms
I/SecureStorage( 2740): [INFO]: SPID(0x00000001)Processing data has been completed
I/SecureStorage( 2740): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
D/AT_Distributor(  319): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
W/ResourcesManager( 3007): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
D/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$handleMessage](2570) Send BOOTING COMPLETED done
W/ResourcesManager( 3007): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3007): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3007): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3007): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
I/SettingSearch/SearchIntentReceiver( 1281): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1281): search setting db init!!
E/Zygote  ( 3027): MountEmulatedStorage()
I/libpersona( 3027): KNOX_SDCARD checking this for 10160
E/Zygote  ( 3027): v2
I/libpersona( 3027): KNOX_SDCARD not a persona
I/SELinux ( 3027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
E/SELinux ( 3027): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3027 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/Process ( 2716): Sending signal. PID: 2716 SIG: 9
I/SettingSearch/SearchIntentReceiver( 1281): BOOT_COMPLETED call InitSerachDBThread thread start!
D/TimaKeyStoreProvider( 3027): TimaSignature is unavailable
D/ActivityThread( 3027): Added TimaKeyStore provider
W/libprocessgroup( 1016): failed to open /acct/uid_10136/pid_1484/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3027): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2253/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_1626/cgroup.procs: No such file or directory
E/Zygote  ( 3043): MountEmulatedStorage()
E/Zygote  ( 3043): v2
I/libpersona( 3043): KNOX_SDCARD checking this for 1000
I/libpersona( 3043): KNOX_SDCARD not a persona
I/SELinux ( 3043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3043 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2283/cgroup.procs: No such file or directory
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/AT_Distributor(  319): SetAtdStatus(), 1_1_0
D/AT_Distributor(  319): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/TimaKeyStoreProvider( 3043): TimaSignature is unavailable
D/ActivityThread( 3043): Added TimaKeyStore provider
E/Zygote  ( 3059): MountEmulatedStorage()
E/Zygote  ( 3059): v2
I/libpersona( 3059): KNOX_SDCARD checking this for 10150
I/libpersona( 3059): KNOX_SDCARD not a persona
I/SELinux ( 3059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3059 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/SELinux ( 3059): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Process com.android.exchange (pid 2716)(adj 15) has died(371,963)
I/iu.UploadsManager( 1983): End new media; added: 0, uploading: 0, time: 192 ms
W/ResourcesManager( 3043): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 3059): TimaSignature is unavailable
D/ActivityThread( 3059): Added TimaKeyStore provider
D/[0]UMC:UMCContentProvider( 3027): @onCreate
I/DIAGMON_AGENT( 2929): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
D/[0]UMC:Core( 3027): onCreate(): 
D/[0]UMC:Core( 3027): @isManagedProfileUser
D/[0]UMC:Core( 3027): userId: 0
D/[0]UMC:Core( 3027): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 3027): userInfo.isManagedProfile() : false
I/DIAGMON_AGENT( 2929): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 2929): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 2929): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2929): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2929): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/[0]UMC:DeviceInfo( 3027): USA==US==
I/ServiceManager(  327): Waiting for service AtCmdFwd...
E/USB_UICC(  301): Timeout! No signal received. Retry num = 27
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3074): MountEmulatedStorage()
I/libpersona( 3074): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3074): v2
I/libpersona( 3074): KNOX_SDCARD not a persona
I/SELinux ( 3074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1016): name = next_alarm_formatted
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10085
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
I/FOTA    ( 3043): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/TimaKeyStoreProvider( 3074): TimaSignature is unavailable
D/ActivityThread( 3074): Added TimaKeyStore provider
I/DBG_DM  ( 3043): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
E/BluetoothHeadset( 2740): BTStateChangeCB is registed
D/BluetoothHeadset( 2740): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1016): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 2740): BluetoothHeadset service is binded
,D/BluetoothA2dp( 2740): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1016): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapter( 2740): 101469778: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2740): 101469778: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2740): 101469778: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2740): 101469778: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2740): 101469778: getState() :  mService = null. Returning STATE_OFF
I/DBG_DM  ( 3043): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
I/DBG_DM  ( 3043): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3094): MountEmulatedStorage()
E/Zygote  ( 3094): v2
I/libpersona( 3094): KNOX_SDCARD checking this for 10009
I/libpersona( 3094): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3094 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3094): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/art     ( 3007): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 161.112ms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/TimaKeyStoreProvider( 3094): TimaSignature is unavailable
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityThread( 3094): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
D/USER_AGENT( 3027): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
D/[0]UMC:AdminManager( 3027): init - start
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 3074): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
D/[0]UMC:AdminManager( 3027): loadAdmins
D/[0]UMC:AdminManager( 3027): init - end
D/GSLBManager( 3027): migrateStoredUrlFromOldPref
D/GSLBManager( 3027): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 3027): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 3027): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 3027): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3027): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3027): isContainer : 0
D/EnterpriseDeviceManagerService( 1016): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 3027): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 3027): isContainer : 0
D/[0]UMC:UMCAdmin( 3027): deactivateUMCAdmin - UMC App Admin deactivated
D/ActivityManager( 1016): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 3027): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
D/[0]UMC:CoreReceiver( 3027): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 3027):  check PreETag 
D/[0]UMC:CoreReceiver( 3027): bulk enrolled package: null
V/[0]UMC:ProfileStorage( 3027): Enter loadList
D/[0]UMC:CoreReceiver( 3027): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 3027): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 3027): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 3027): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3027): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3027): isContainer : 0
D/EnterpriseDeviceManagerService( 1016): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 3027): No active admin owned by uid 10160
I/DBG_DM  ( 3043): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
D/[0]UMC:UMCAdmin( 3027): isContainer : 0
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
D/[0]UMC:UMCAdmin( 3027): deactivateUMCAdmin - UMC App Admin deactivated
W/ContextImpl( 3043): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
D/ActivityManager( 1016): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/ActivityManager( 1016): Waited long enough for: ServiceRecord{1fd37ef0 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
D/OverheatReceiver( 1178): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1178): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1178): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1178): isSafeMode = false
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 3043): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/DBG_DM  ( 3043): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
D/BootupListener( 1443): intent.getAction() = android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
D/SettingsProvider( 1016): name = internet_call_settings_visibility
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1001
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/PhoneUtilsCommon( 1443): isSupportVoLTE is false.
I/DBG_DM  ( 3043): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
D/[0]UMC:ByodSetupStarter( 3027): Container ID : 0
I/DBG_DM  ( 3043): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 3043): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3043): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/Telecom ( 1420): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
V/[0]UMC:Utils( 3027): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 3027): shutdown
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 3027): @GuardService - stopService Result = true
D/ActivityManager( 1016): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_DM  ( 3043): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
I/art     ( 3027): System.exit called, status: 0
I/AndroidRuntime( 3027): VM exiting with result code 0, cleanup skipped.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
I/DBG_DM  ( 3043): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
D/ActivityManager( 1016): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
I/DBG_DM  ( 3043): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 3043): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(155/onStartCommand)] 
W/ContextImpl( 3043): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
D/ActivityManager( 1016): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
E/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3127): MountEmulatedStorage()
E/Zygote  ( 3127): v2
I/libpersona( 3127): KNOX_SDCARD checking this for 10057
I/libpersona( 3127): KNOX_SDCARD not a persona
I/SELinux ( 3127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3127 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 3127): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3043): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Tethering( 1016): No numeric data
D/TimaKeyStoreProvider( 3127): TimaSignature is unavailable
I/DBG_DM  ( 3043): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
D/ActivityThread( 3127): Added TimaKeyStore provider
E/Tethering( 1016): No numeric data
E/Tethering( 1016): No numeric data
E/Zygote  ( 3142): MountEmulatedStorage()
E/Zygote  ( 3142): v2
I/libpersona( 3142): KNOX_SDCARD checking this for 1000
I/libpersona( 3142): KNOX_SDCARD not a persona
E/Tethering( 1016): No numeric data
I/SELinux ( 3142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/Tethering( 1016): No numeric data
I/ActivityManager( 1016): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2327:com.wsomacp/u0a25 (adj 15): empty #31
E/Tethering( 1016): No numeric data
I/ActivityManager( 1016): Killing 2205:com.sec.android.app.mt/1000 (adj 15): empty #32
I/ActivityManager( 1016): Killing 2298:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #33
I/SELinux ( 3142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3027)(adj 0) has died(337,977)
I/Telecom ( 1420): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
D/TimaKeyStoreProvider( 3142): TimaSignature is unavailable
D/ActivityThread( 3142): Added TimaKeyStore provider
D/daemonapp( 1312): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1312): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1312): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1312): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1312): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1312): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/SettingsProvider( 1016): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10162
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/[SBeam] ( 1281): SBeamEnabler.isSBeamSupported : [-1]
D/[SBeam] ( 1281): SBeamEnabler.isSBeamSupported : EXIST
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_2327/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2205/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10131/pid_2298/cgroup.procs: No such file or directory
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3159): MountEmulatedStorage()
E/Zygote  ( 3159): v2
I/libpersona( 3159): KNOX_SDCARD checking this for 1000
I/libpersona( 3159): KNOX_SDCARD not a persona
I/SELinux ( 3159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3159 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2365:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
I/SELinux ( 3159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3159): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3159): TimaSignature is unavailable
D/ActivityThread( 3159): Added TimaKeyStore provider
V/audio_hw_primary(  285): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  285): audio_extn_get_parameters: returns 
V/msm8974_platform(  285): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  285): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  285): key: 'call_forwarding' value: ''
V/InCall  ( 1919): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1919): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1919): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
E/Tethering( 1016): No numeric data
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
D/ScoverManager( 1919): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1919): InCallUtils - isCoverClosed false
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/Tethering( 1016): No numeric data
I/Telecom ( 1420): ProximitySensorManager: Proximity wake lock already released
E/Tethering( 1016): No numeric data
W/ResourcesManager( 3159): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/daemonapp( 1312): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/daemonapp( 1312): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1312): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1312): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1919): InCallUtils - isCoverClosed false
I/InCall  ( 1919): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1919): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1919): InCallPresenter -  - dismissCoverDialog()...
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/InCall  ( 1919): CallSContextMotion - stopPutDownListening
D/InCall  ( 1919): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
I/DBG_DM  ( 3043): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
E/daemonapp( 1312): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1919): InCallUtils - isCoverClosed false
D/daemonapp( 1312): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1449498952557
D/daemonapp( 1312): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1449520500000
D/daemonapp( 1312): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1312): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/PhoneStatusBarView( 1178): setCallBackground:0
D/daemonapp( 1312): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449520500000
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Tethering( 1016): No numeric data
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 28
D/daemonapp( 1312): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1449520500000
I/ActivityManager( 1016): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3176 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2380:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
E/Zygote  ( 3176): MountEmulatedStorage()
E/Zygote  ( 3176): v2
I/libpersona( 3176): KNOX_SDCARD checking this for 10086
I/libpersona( 3176): KNOX_SDCARD not a persona
I/SELinux ( 3176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3176): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_FMMDM( 3142): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
D/TimaKeyStoreProvider( 3176): TimaSignature is unavailable
D/ActivityThread( 3176): Added TimaKeyStore provider
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3196): MountEmulatedStorage()
I/libpersona( 3196): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3196): v2
I/libpersona( 3196): KNOX_SDCARD not a persona
I/DBG_FMMDM( 3142): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
I/SELinux ( 3196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_FMMDM( 3142): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
I/DBG_FMMDM( 3142): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
I/ActivityManager( 1016): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3196 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/comdaemonstockapp( 1312): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1312): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
E/SELinux ( 3196): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
D/LocationManagerService( 1016): getProviders()=[passive]
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3043): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/VideoCallManager( 1919): Instantiating VideoCallManager
W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_2365/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10088/pid_2380/cgroup.procs: No such file or directory
E/        ( 1919): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
D/TimaKeyStoreProvider( 3196): TimaSignature is unavailable
D/ActivityThread( 3196): Added TimaKeyStore provider
I/GFX construct_block_size_descriptor_2d second part( 1919): took 2.313803ms for 0*0 texture 0
E/Zygote  ( 3212): MountEmulatedStorage()
E/Zygote  ( 3212): v2
I/libpersona( 3212): KNOX_SDCARD checking this for 10166
I/libpersona( 3212): KNOX_SDCARD not a persona
I/SELinux ( 3212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/GFX generate_partition_tables( 1919): took 5.240886ms for 0*0 texture 0
E/SMD     (  290): DCD OFF
I/SELinux ( 3212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3212): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/GFX raster( 1919): took 11.531928ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1919): Bitmap=0xb9370d80 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb9388f90 counterpartCT=4 counterpartW=176 counterparth=144
I/ActivityManager( 1016): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3212 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/        ( 1919): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/Adreno-EGL( 1919): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1919): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1919): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1919): Local Branch: 
I/Adreno-EGL( 1919): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1919): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1919):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/art     (  315): Explicit concurrent mark sweep GC freed 8727(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 33.734ms
D/AndroidRuntime( 3157): 
D/AndroidRuntime( 3157): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3157): CheckJNI is OFF
D/AndroidRuntime( 3157): readGMSProperty: start
D/AndroidRuntime( 3157): readGMSProperty: already setted!!
D/AndroidRuntime( 3157): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3157): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3157): readGMSProperty: end
D/AndroidRuntime( 3157): addProductProperty: start
E/USB_UICC(  301): Timeout! No signal received. Retry num = 28
I/ServiceManager(  327): Waiting for service AtCmdFwd...
D/TimaKeyStoreProvider( 3212): TimaSignature is unavailable
D/ActivityThread( 3212): Added TimaKeyStore provider
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 20.338ms
I/GFX GPU raster( 1919): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1919): took 0.516250ms for 320*61440 texture 37809
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 18.162ms
I/draw setup( 1919): took 10.371563ms for 320*240 texture 37809
E/GFX GPU raster( 1919): drawn
I/GFX GPU raster ASTC( 1919): took 41.980518ms for 320*240 texture 12
I/GFX raster( 1919): took 42.060258ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1919): Bitmap=0xb9388f90 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb938b2d0 counterpartCT=4 counterpartW=320 counterparth=240
E/        ( 1919): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
I/GFX GPU raster( 1919): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1919): took 0.357031ms for 480*122880 texture 37813
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/draw setup( 1919): took 0.848125ms for 480*640 texture 37813
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/GFX GPU raster( 1919): drawn
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/GFX GPU raster ASTC( 1919): took 7.447969ms for 480*640 texture 12
I/GFX raster( 1919): took 7.535470ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1919): Bitmap=0xb938b2d0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb95b9760 counterpartCT=4 counterpartW=480 counterparth=640
I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
I/DBG_DM  ( 3043): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
E/Zygote  ( 3241): MountEmulatedStorage()
E/Zygote  ( 3241): v2
I/libpersona( 3241): KNOX_SDCARD checking this for 1000
I/libpersona( 3241): KNOX_SDCARD not a persona
I/SELinux ( 3241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3241): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3241 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/        ( 1919): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
I/GFX GPU raster( 1919): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1919): took 0.374583ms for 440*116864 texture 37809
I/draw setup( 1919): took 0.855729ms for 440*330 texture 37809
E/GFX GPU raster( 1919): drawn
I/GFX GPU raster ASTC( 1919): took 4.434584ms for 440*330 texture 12
I/GFX raster( 1919): took 4.513177ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1919): Bitmap=0xb95b9760 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb95cdb50 counterpartCT=4 counterpartW=440 counterparth=330
D/TimaKeyStoreProvider( 3241): TimaSignature is unavailable
D/ActivityThread( 3241): Added TimaKeyStore provider
V/VibratorService( 1016): hasVibrator - useVibetonz: true
E/        ( 1919): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1919): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1919): took 0.434531ms for 480*163840 texture 37811
I/draw setup( 1919): took 0.995416ms for 480*640 texture 37811
E/GFX GPU raster( 1919): drawn
I/GFX GPU raster ASTC( 1919): took 5.808280ms for 480*640 texture 12
I/GFX raster( 1919): took 5.900208ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1919): Bitmap=0xb95bd960 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb95cd688 counterpartCT=4 counterpartW=480 counterparth=640
D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/AffinityControl( 3157): AffinityControl: registerfunction enter
W/NotificationAccessSettings( 1281): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
V/VibratorService( 1016): hasVibrator - useVibetonz: true
V/VibratorService( 1016): hasVibrator - useVibetonz: true
V/AlarmManager( 1016): waitForAlarm result :8
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 3157): Calling main entry com.android.commands.am.Am
W/ResourcesManager( 1281): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/SearchServiceFactory( 3127): checking for language pack updates
I/PCWCLIENTTRACE_LOG( 3241): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3241): DEFAULT_LOGLEVEL : 3
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
E/        ( 1919): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/SurfaceFlinger(  257): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
I/GFX construct_block_size_descriptor_2d second part( 1919): took 2.028385ms for 0*0 texture 0
D/FocusedStackFrame( 1016): Set to : 0
I/PCWCLIENTTRACE_DMDBOpenHelper( 3241): new DMDBOpenHelper instance
D/Launcher.HomeView( 1468): onPause
I/GFX generate_partition_tables( 1919): took 7.382186ms for 0*0 texture 0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
D/Launcher( 1468): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/GFX raster( 1919): took 11.660154ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1919): Bitmap=0xb95b7020 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb95b7140 counterpartCT=4 counterpartW=176 counterparth=144
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1468
D/AndroidRuntime( 3157): Shutting down VM
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/ActivityManager( 1016): Killing 2394:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SurfaceFlinger(  257): id=10 createSurf (720x1280),1 flag=404, iello
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/UpdateRequestReceiver( 3176): ignoring update request
W/TRThreadPoolExecutor( 3127): Task "NotifyOnDoneFutureTask[fetch_opt_in_statuses]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3127): Task "NotifyOnDoneFutureTask[refresh_search_domain_and_cookies]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3127): Task "NotifyOnDoneFutureTask[update_language_packs]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
E/        ( 1919): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1919): took 2.594271ms for 0*0 texture 0
E/Zygote  ( 3268): MountEmulatedStorage()
E/Zygote  ( 3268): v2
I/libpersona( 3268): KNOX_SDCARD checking this for 10174
I/libpersona( 3268): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3268 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 3268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/GFX generate_partition_tables( 1919): took 6.574583ms for 0*0 texture 0
I/SELinux ( 3268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3268): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/GFX raster( 1919): took 11.451094ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1919): Bitmap=0xb95b7360 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb95b7300 counterpartCT=4 counterpartW=176 counterparth=144
D/ScoverManager( 1919): registerListener
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1016): registerListenerCallback : binder = android.os.BinderProxy@1c6b1d83, pid : 1919, uid : 1001, type : 1
D/TimaKeyStoreProvider( 3268): TimaSignature is unavailable
D/ActivityThread( 3268): Added TimaKeyStore provider
D/PCWCLIENTTRACE_DMContentProvider( 3241): [URIMatcher] - result : 2
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 1468): updateVisibility : ActivityRecord{163b77e4 token=android.os.BinderProxy@2cdc00f5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/UpdateRequestReceiver( 3176): ignoring update request
I/WebViewFactory( 3127): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/Launcher.HomeView( 1468): onStop
V/ActivityThread( 1468): updateVisibility : ActivityRecord{163b77e4 token=android.os.BinderProxy@2cdc00f5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3290): MountEmulatedStorage()
E/Zygote  ( 3290): v2
I/libpersona( 3290): KNOX_SDCARD checking this for 10003
I/libpersona( 3290): KNOX_SDCARD not a persona
I/SELinux ( 3290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3290 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/SELinux ( 3290): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_2394/cgroup.procs: No such file or directory
I/DBG_FMMDM( 3142): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
I/DBG_FMMDM( 3142): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
I/DBG_FMMDM( 3142): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1016): Killing 2421:com.sec.android.app.camera/u0a139 (adj 15): empty #31
I/LibraryLoader( 3127): Time to load native libraries: 3 ms (timestamps 4897-4900)
I/LibraryLoader( 3127): Expected native library version number "",actual native library version number ""
D/TimaKeyStoreProvider( 3290): TimaSignature is unavailable
D/ActivityThread( 3290): Added TimaKeyStore provider
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1016): [SO] activate (ident=0xb95c04b0, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SensorManager( 1016): unregisterListener ::   
I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
W/art     ( 3157): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb95c04b0, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/ScoverManager( 1281): serviceVersion : 16908288
D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,W/art     ( 3127): Attempt to remove local handle scope entry from IRT, ignoring
,W/TRThreadPoolExecutor( 3127): Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 19184(1008KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.578ms total 191.049ms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_2421/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,D/InCall  ( 1919): InCallPresenter -  - Finished InCallPresenter.setUp
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,D/Launcher( 1468): onTrimMemory. Level: 20
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3312): MountEmulatedStorage()
E/Zygote  ( 3312): v2
I/libpersona( 3312): KNOX_SDCARD checking this for 1000
I/libpersona( 3312): KNOX_SDCARD not a persona
I/SELinux ( 3312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/UpdateRequestReceiver( 3176): ignoring update request
E/SELinux ( 3312): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3312 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/Search.RefreshSearchDom( 3127): Search parameters fetch failed: com.google.android.apps.gsa.shared.api.io.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
W/Search.RefreshSearchDom( 3127): Search parameters fetch failed
,I/ActivityManager( 1016): Killing 2520:com.android.calendar/u0a135 (adj 15): empty #31
,W/TRThreadPoolExecutor( 3127): Task "LockboxApiWrapper[setActiveGoogleNowAccount]" is a ac. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,D/SensorService( 1016): [SO] currT = 35070128735, prevT = 34710093058, diff = 360035677, [0.172 0.096 10.132]
D/SensorService( 1016): [SO] 0.172 0.096 10.132
D/SensorService( 1016): [SO] [100 -> 255]
,E/UpdateRequestReceiver( 3176): ignoring update request
,W/TRThreadPoolExecutor( 3127): Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
E/UpdateRequestReceiver( 3176): ignoring update request
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3312): TimaSignature is unavailable
,D/ActivityThread( 3312): Added TimaKeyStore provider
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/UpdateRequestReceiver( 3176): ignoring update request
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/WebViewFactory( 3268): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/UserAnalysis.PlaceProvider( 3290): PlaceProvider onCreate(),
,W/ResourcesManager( 3212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 3337): MountEmulatedStorage()
I/libpersona( 3337): KNOX_SDCARD checking this for 10092
E/Zygote  ( 3337): v2
,I/libpersona( 3337): KNOX_SDCARD not a persona
I/SELinux ( 3337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3337 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3337): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 2595:com.android.keychain/1000 (adj 15): empty #31
,I/LibraryLoader( 3268): Time to load native libraries: 2 ms (timestamps 5171-5173)
,I/LibraryLoader( 3268): Expected native library version number "",actual native library version number ""
,D/TimaKeyStoreProvider( 3337): TimaSignature is unavailable
D/ActivityThread( 3337): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDS( 3312): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,V/WebViewChromiumFactoryProvider( 3268): Binding Chromium to main looper Looper (main, tid 1) {3fade3af}
,I/LibraryLoader( 3268): Expected native library version number "",actual native library version number ""
I/chromium( 3268): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/SensorService( 1016): [SO] 0.172 0.096 10.132
,I/DBG_FMMDS( 3312): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/UserAnalysis.SecureDbManager( 3290): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3290): SecurePlaceDbHelper() 
D/UserAnalysis( 3290): Create SecureDbHelper
,V/JNIHelp ( 3212): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/BrowserStartupController( 3268): Initializing chromium process, singleProcess=true
,W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3268): ApplicationContext is null in ApplicationStatus
,I/LockPatternUtils( 1281): isSmartCardAuthenticationAvailable: false
,W/chromium( 3268): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,D/Settings_Utils( 1281): isSupportVNFestival SM-A500FU XEO
,D/PCWCLIENTTRACE_DMContentProvider( 3241): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3312): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/SurfaceFlinger(  257): id=7 Removed Mauncher (5/8)
,I/DBG_FMMDS( 3312): [50.18.150420][Line:43][xdbDBInit] 
,I/SurfaceFlinger(  257): id=7 Removed Mauncher (-2/8)
,W/chromium( 3268): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 3268): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 3268): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,D/IntelligenceServiceApplication( 3290): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3290): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,I/Adreno-EGL( 3268): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3268): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3268): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3268): Local Branch: 
I/Adreno-EGL( 3268): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3268): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3268):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_2520/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2595/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ActivityThread( 3212): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3212): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1920f002: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,E/Zygote  ( 3359): MountEmulatedStorage()
,E/Zygote  ( 3359): v2
I/libpersona( 3359): KNOX_SDCARD checking this for 10060
I/libpersona( 3359): KNOX_SDCARD not a persona
,I/SELinux ( 3359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3359 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ProviderInstaller( 3212): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 3359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3359): TimaSignature is unavailable
D/ActivityThread( 3359): Added TimaKeyStore provider
,I/System.out( 1635): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
D/BluetoothAdapter( 3268): 942804904: getState() :  mService = null. Returning STATE_OFF
I/System.out( 1635): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1635): (HTTPLog)-Static: isShipBuild true
I/System.out( 1635): (HTTPLog)-Thread-130-456257068: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1635): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): uids 10012
D/EnterpriseController(  280): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10012
,W/Search.LoginHelper( 3127): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 3127): java.io.IOException: NetworkError
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.j.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.f.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.b.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.k.b(LoginHelper.java:841)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.p.aMt(LoginHelper.java:727)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.p.call(LoginHelper.java:724)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 3127): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 3127): 	at com.google.android.apps.gsa.shared.util.c.a.k.run(GsaThreadFactory.java:100)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  301): Timeout! No signal received. Retry num = 29
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/System.out( 1635): (HTTPLog)-Static: isSBSettingEnabled false
,W/Search.LoginHelper( 3127): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 3127): java.io.IOException: NetworkError
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.j.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.f.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.b.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.k.b(LoginHelper.java:841)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.p.aMt(LoginHelper.java:727)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.p.call(LoginHelper.java:724)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 3127): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 3127): 	at com.google.android.apps.gsa.shared.util.c.a.k.run(GsaThreadFactory.java:100)
,W/TRThreadPoolExecutor( 3127): Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1635): (HTTPLog)-Static: isSBSettingEnabled false
,I/sCloudBackupApp( 3359): sCloudBackupApp Version Info : 4.04.8.KK_APP
,W/Search.LoginHelper( 3127): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 3127): java.io.IOException: NetworkError
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.j.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.f.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.b.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.k.b(LoginHelper.java:841)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.p.aMt(LoginHelper.java:727)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.p.call(LoginHelper.java:724)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 3127): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 3127): 	at com.google.android.apps.gsa.shared.util.c.a.k.run(GsaThreadFactory.java:100)
,D/IntelligenceServiceApplication( 3290): no applications having user consent for prediction
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3391): MountEmulatedStorage()
,E/Zygote  ( 3391): v2
I/libpersona( 3391): KNOX_SDCARD checking this for 10062
I/libpersona( 3391): KNOX_SDCARD not a persona
,I/SELinux ( 3391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3391 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2641:com.samsung.android.sm/1000 (adj 15): empty #31,
,I/SELinux ( 3391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SELinux ( 3391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3391): TimaSignature is unavailable
,D/ActivityThread( 3391): Added TimaKeyStore provider
,I/System.out( 1635): (HTTPLog)-Static: isSBSettingEnabled false
,W/Search.LoginHelper( 3127): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 3127): java.io.IOException: NetworkError
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.j.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.f.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.b.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.k.b(LoginHelper.java:841)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.p.aMt(LoginHelper.java:727)
W/Search.LoginHelper( 3127): 	at com.google.android.search.core.google.b.p.call(LoginHelper.java:724)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 3127): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 3127): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 3127): 	at com.google.android.apps.gsa.shared.util.c.a.k.run(GsaThreadFactory.java:100)
,I/ActivityManager( 1016): Killing 2679:flipboard.boxer.app/u0a99 (adj 15): empty #31
,I/DBG_DM  ( 3043): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2641/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10099/pid_2679/cgroup.procs: No such file or directory
,I/ExternalOEMControlProvider( 3391): onCreate
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 3290): [PlaceDetection::stopService] Service stopped.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,W/chromium( 3268): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3414): MountEmulatedStorage(),
,E/Zygote  ( 3414): v2
I/libpersona( 3414): KNOX_SDCARD checking this for 1000
I/SELinux ( 3414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3414): KNOX_SDCARD not a persona
,I/SELinux ( 3414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3414 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2107:flipboard.app/u0a98 (adj 15): empty #31
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/SettingsProvider( 1016): name = PREVIOUS_SYS_TIME
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10062
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/DBG_FMMDS( 3312): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/PowerUI ( 1178): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1178): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/TimaKeyStoreProvider( 3414): TimaSignature is unavailable
,D/ActivityThread( 3414): Added TimaKeyStore provider
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1016): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10062
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/ResourcesManager( 3414): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/ServiceMode( 3414): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3414): setReferenceIsDumpState : 0
,D/ActivityManager( 1016): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,V/PlaceDetection v1.0.19 ( 3290): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/ActivityManager( 1016): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3431 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/UserAnalysis.MyPlaceDbPreference( 3290): Constructor Preference
,E/Zygote  ( 3431): MountEmulatedStorage()
,W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
I/DBG_FMMDS( 3312): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/libpersona( 3431): KNOX_SDCARD checking this for 10092
I/DBG_FMMDS( 3312): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/libpersona( 3431): KNOX_SDCARD not a persona
E/Zygote  ( 3431): v2
,I/SELinux ( 3431): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3431): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3431): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
I/DBG_FMMDS( 3312): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3312): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
I/DBG_FMMDS( 3312): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/DBG_FMMDS( 3312): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/AwContents( 3268): onDetachedFromWindow called when already detached. Ignoring
,E/Zygote  ( 3444): MountEmulatedStorage()
E/Zygote  ( 3444): v2
I/libpersona( 3444): KNOX_SDCARD checking this for 1000
I/libpersona( 3444): KNOX_SDCARD not a persona
I/SELinux ( 3444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2217:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
D/PhoneWindow( 3268): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3268): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 3268): CordovaWebView is running on device made by: samsung
D/TimaKeyStoreProvider( 3431): TimaSignature is unavailable
D/ActivityThread( 3431): Added TimaKeyStore provider
W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 3444): TimaSignature is unavailable
,D/ActivityThread( 3444): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 2533:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/FOTA_Client( 3094): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3094): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,W/libprocessgroup( 1016): failed to open /acct/uid_10098/pid_2107/cgroup.procs: No such file or directory
,I/FOTA_Client( 3094): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 3094): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 3472): MountEmulatedStorage()
,E/Zygote  ( 3472): v2
I/libpersona( 3472): KNOX_SDCARD checking this for 10014
I/libpersona( 3472): KNOX_SDCARD not a persona
I/SELinux ( 3472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3472): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3472 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2757:com.android.email/u0a145 (adj 15): empty #31
,I/art     (  315): Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 20.566ms
,D/TimaKeyStoreProvider( 3472): TimaSignature is unavailable
,D/ActivityThread( 3472): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 19.474ms
,D/OpenGLRenderer( 3268): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.187ms
,I/ActivityManager( 1016): Killing 2235:com.android.mms/u0a46 (adj 15): empty #31
,W/ResourcesManager( 3212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,D/PhoneWindow( 3268): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3268): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/ResourcesManager( 3212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/InputDispatcher( 1016): Focus entered window: 3268
,D/SRIB_DCS( 3268): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer( 3268): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3268): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3268): Enabling debug mode 0
,I/LockPatternUtils( 1281): isSmartCardAuthenticationAvailable: false
,D/CountryDetector( 1016): No listener is left
,V/OneTimeInitializerReceiver( 3472): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,V/OneTimeService( 3472): OneTimeService.onHandleIntent
,I/FactoryTestApp( 2570): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3024)  
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/Timeline( 3268): Timeline: Activity_idle id: android.os.BinderProxy@b7cea4a time:36185
,I/SamsungIME( 1882): getCurrentCandidateView
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s469ms
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{19c4e6e8 u0 com.example.hello/.MainActivity t2} time:36211
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2217/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2533/cgroup.procs: No such file or directory
D/NPS_WSSNPS( 3444): [] android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
W/libprocessgroup( 1016): failed to open /acct/uid_10145/pid_2757/cgroup.procs: No such file or directory
,W/ContextImpl( 3444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_2235/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3503): MountEmulatedStorage()
E/Zygote  ( 3503): v2
I/libpersona( 3503): KNOX_SDCARD checking this for 1000
I/libpersona( 3503): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3503 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,D/NPS_WSSNPS( 3444): [] Service onCreate!!
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3511): MountEmulatedStorage(),
,E/Zygote  ( 3511): v2
I/libpersona( 3511): KNOX_SDCARD checking this for 1000
I/libpersona( 3511): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3511 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/NPS_WSSNPS( 3444): [50.150621] NpsServiceTask Start
,D/NPS_WSSNPS( 3444): [50.150621] smlDBHelper
,I/art     ( 1635): Explicit concurrent mark sweep GC freed 20024(1422KB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 10MB/17MB, paused 1.039ms total 55.284ms
I/art     ( 1635): WaitForGcToComplete blocked for 55.635ms for cause Explicit
,I/SELinux ( 3503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SELinux ( 3511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3511): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3503): TimaSignature is unavailable
,D/ActivityThread( 3503): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3511): TimaSignature is unavailable
,D/ActivityThread( 3511): Added TimaKeyStore provider
,I/art     ( 1635): Explicit concurrent mark sweep GC freed 2748(122KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.020ms total 58.924ms
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3337): Setting receiver enabled: false
,I/NPS_WSSNPS( 3444): [50.150621] AsyncBulkFlagCheck
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/USB_UICC(  301): Timeout! No signal received. Retry num = 30
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,I/NPS_WSSNPS( 3444): [50.150621] IsRemain_AsyncBulkCheck
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,I/NPS_WSSNPS( 3444): [50.150621] IsRemain_Asyncing nothing
,W/ContextImpl( 3444): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3503): onCreate
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,W/ResourcesManager( 3511): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,D/NPS_WSSNPS( 3444): [50.150621] Service onDestroy,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 3549): MountEmulatedStorage()
E/Zygote  ( 3549): v2
I/libpersona( 3549): KNOX_SDCARD checking this for 10019
I/libpersona( 3549): KNOX_SDCARD not a persona
,I/SELinux ( 3549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3549 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Hs20UtilService( 3503): Starting #1
,I/Hs20UtilService( 3503): Message received 5003
,W/BindingManager( 3268): Cannot call determinedVisibility() - never saw a connection for the pid: 3268
,E/USB_UICC(  301): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  301): usb_uicc_init_qmi failed ! 
I/USB_UICC(  301): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  301): usb_uicc_cleanup, Issuing QMI deinit ... 
,E/ActivityThread( 3337): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,I/NPS_WSSNPS( 3444): [50.150621] smlBRConfigurationDelete
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/NPS_WSSNPS( 3444): [50.150621] smlBRMessageDelete
,I/NPS_WSSNPS( 3444): [50.150621] smlBREmailDelete
,I/NPS_WSSNPS( 3444): [50.150621] smlBRNetworkDelete
,I/NPS_WSSNPS( 3444): [50.150621] smlBRCallLogDelete
,I/NPS_WSSNPS( 3444): [50.150621] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3444): [50.150621] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3444): [50.150621] smlBRSMemoDelete,
I/NPS_WSSNPS( 3444): [50.150621] verifier installed? false
,I/NPS_WSSNPS( 3444): [50.150621] cpuBooster release : false
,I/SettingSearch/SearchIntentReceiver( 1281): InitSerachDBThread thread end!,
,I/RlzPingService( 3196): Setting next ping for 1450103754919,
,D/NPS_WSSNPS( 3444): [50.150621] dsServerSocket close
,I/ActivityManager( 1016): Killing 2793:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3549): TimaSignature is unavailable
,D/ActivityThread( 3549): Added TimaKeyStore provider
,I/chromium( 3268): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/DBG_DM  ( 3043): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,I/dbxyzptlk.db240408.D.h( 3337): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/dbxyzptlk.db240408.D.h( 3337): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/dbxyzptlk.db240408.D.h( 3337): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,I/ActivityManager( 1016): Killing 2811:com.sec.dsm.system/1000 (adj 15): empty #31
,W/System.err( 3212): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/KLMS-2.5.183: ( 3549): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 15:35:55 GMT+01:00 2015
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3549): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3583): MountEmulatedStorage(),
E/Zygote  ( 3583): v2
I/libpersona( 3583): KNOX_SDCARD checking this for 10022
I/libpersona( 3583): KNOX_SDCARD not a persona,
I/SELinux ( 3583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/dex2oat ( 3577): ----------------------------------------------------
I/dex2oat ( 3577): <SS>: S T A R T I N G . . .,
I/dex2oat ( 3577): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3577): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1655472694.jar --oat-fd=34 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1655472694.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/SELinux ( 3583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3583): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3583 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3549): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3549): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/dbxyzptlk.db240408.D.h( 3337): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/KLMS-2.5.183: ( 3549): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/TimaKeyStoreProvider( 3583): TimaSignature is unavailable
,D/ActivityThread( 3583): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3549): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/breakpad( 3337): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,I/KLMS-2.5.183: ( 3549): KLMSIntentService(): BOOT_COMPLETED
,W/libprocessgroup( 1016): failed to open /acct/uid_10048/pid_2793/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2811/cgroup.procs: No such file or directory
,D/SamsungIME( 1882): Dismiss ExpandCandiate
,D/JsMessageQueue( 3268): Set native->JS mode to OnlineEventsBridgeMode
,I/System.out( 3212): YouTube MDX: MDX video stage moved to NEW
,I/System.out( 3212): YouTube MDX: MDX video player state moved to UNSTARTED
,I/System.out( 3212): YouTube MDX: MDX ad player state moved to UNSTARTED
,E/AndroidProtocolHandler( 3268): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/dex2oat ( 3577): dex2oat took 88.924ms (threads: 4)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3615): MountEmulatedStorage()
E/Zygote  ( 3615): v2
I/libpersona( 3615): KNOX_SDCARD checking this for 1000
I/libpersona( 3615): KNOX_SDCARD not a persona
,I/SELinux ( 3615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3615 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 2774:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,E/SELinux ( 3615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3549): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 3615): TimaSignature is unavailable
,D/ActivityThread( 3615): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3631): MountEmulatedStorage(),
E/Zygote  ( 3631): v2
I/libpersona( 3631): KNOX_SDCARD checking this for 1000
I/libpersona( 3631): KNOX_SDCARD not a persona
,I/SELinux ( 3631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3631 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2264:com.sec.modem.settings/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3631): TimaSignature is unavailable
,D/ActivityThread( 3631): Added TimaKeyStore provider
,I/com.dropbox.sync.android.a( 3337): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/com.dropbox.sync.android.ad( 3337): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,E/MTPRx   ( 3631): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/jxcore_app_log( 3268): JniHelper::setJavaVM(0xb8fa7450), pthread_self() = -1185901144
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 21914(1178KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 26MB/39MB, paused 2.436ms total 162.388ms
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1016): mCursor = null
,I/ActivityManager( 1016): Killing 2837:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,V/MTPRx   ( 3631): sealedState: false
V/MTPRx   ( 3631): sealedUsbMassStorageState: false
,D/JX-Cordova( 3268): jxcore cordova android initializing
,D/SettingsProvider( 1016): name = mtp_usb_connection_status
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = media_player_mode
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/libprocessgroup( 1016): failed to kill 1 processes for processgroup 2774
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = access_control_enabled
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 3268): Initializing JXcore engine
W/jxcore-log( 3268): JXcore engine is ready
,E/Zygote  ( 3650): MountEmulatedStorage(),
E/Zygote  ( 3650): v2
I/libpersona( 3650): KNOX_SDCARD checking this for 10069,
I/libpersona( 3650): KNOX_SDCARD not a persona
,W/jxcore-log( 3268): Starting JXcore engine,
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3650 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2700:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/SELinux ( 3650): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3650): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3650): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3650): TimaSignature is unavailable
,D/ActivityThread( 3650): Added TimaKeyStore provider
,D/SettingsProvider( 1016): name = mtp_running_status
,E/audit   ( 1872): type=1400 msg=audit(1449498955.510:203): avc:  denied  { ioctl } for  pid=3268 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1872):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1872): type=1300 msg=audit(1449498955.510:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=be93cd58 items=0 ppid=315 ppcomm=main pid=3268 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1872): type=1320 msg=audit(1449498955.510:203): 
,D/FileShare-Server( 3650): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2264/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2837/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2700/cgroup.procs: No such file or directory
,D/SettingsProvider( 1016): name = media_mount_count
,D/SettingsProvider( 1016): name = mtp_sync_alive
,D/SettingsProvider( 1016): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1016): name = mtp_open_session
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3670 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2848:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/libpersona( 3670): KNOX_SDCARD checking this for 10094
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/libpersona( 3670): KNOX_SDCARD not a persona
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
E/Zygote  ( 3670): MountEmulatedStorage()
E/Zygote  ( 3670): v2
I/SELinux ( 3670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/SELinux ( 3670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/PCWCLIENTTRACE_PushUtil( 3241): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3241): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3241): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3241): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3241): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3241): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/jxcore-log( 3268): Platform android
W/jxcore-log( 3268): 
,W/jxcore-log( 3268): Process ARCH arm
W/jxcore-log( 3268): 
,D/TimaKeyStoreProvider( 3670): TimaSignature is unavailable
,D/ActivityThread( 3670): Added TimaKeyStore provider
,I/SamsungIME( 1882): getDebugLevel  : 0x4f4c
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/System.out( 3337): Thread-479(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3337): Thread-479(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3337): Thread-479(ApacheHTTPLog):isShipBuild true
I/System.out( 3337): Thread-479(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3337): Thread-479(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): uids 10092
D/EnterpriseController(  280): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10092
,I/jxcore-log( 3268): JXcore Cordova bridge is ready!
I/jxcore-log( 3268): 
,W/jxcore-log( 3268): JXcore engine is started
,E/SMD     (  290): DCD OFF
,W/PCWCLIENTTRACE_PCWHandler( 3241): [ensureRegistration] - netwrok is not available. action ignored
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/elm:15183( 3670): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3670): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3670): MDMBridge.setEnterpriseBridge()
,E/Zygote  ( 3691): MountEmulatedStorage()
E/Zygote  ( 3691): v2
I/libpersona( 3691): KNOX_SDCARD checking this for 10031
I/libpersona( 3691): KNOX_SDCARD not a persona
,I/SELinux ( 3691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3691): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ActivityManager( 1016): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3691 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm,
,D/elm:15183( 3670): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 3670): ElmAgentService : onCreate()
,D/elm:15183( 3670): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,V/EmergencyMode( 1405): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,I/System.out( 3337): pool-10-thread-1 calls detatch()
,D/elm:15183( 3670): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15183( 3670): BootCompletedState : startBootCompleted() call
,D/TimaKeyStoreProvider( 3691): TimaSignature is unavailable
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/ActivityThread( 3691): Added TimaKeyStore provider
,W/ContextImpl( 3212): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,V/EmergencyMode( 1405): [EmergencyBase] setBootTime
V/EmergencyMode( 1405): [EmergencyFactory] No Recovery State, kill my self.
,W/libprocessgroup( 1016): failed to open /acct/uid_1101/pid_2848/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 2892:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/elm:15183( 3670): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3670): Get License : 0
D/elm:15183( 3670): ElmAgentService : onDestroy().
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,E/jxcore-log( 3268): >> samsung-SM-A500FU
E/jxcore-log( 3268): 
,I/SamsungIME( 1882): getDebugLevel  : 0x4f4c
,I/jxcore-log( 3268): Total memory 1983791104
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): Free memory 228290560
I/jxcore-log( 3268): 
I/jxcore-log( 3268): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3268): 
I/jxcore-log( 3268): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3268): 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1016): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 3268): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): Size 720 1280
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): Screen Brightness 5
I/jxcore-log( 3268): 
E/jxcore-log( 3268): Dummy Error Log.
E/jxcore-log( 3268): 
,E/Zygote  ( 3711): MountEmulatedStorage(),
,E/Zygote  ( 3711): v2
I/libpersona( 3711): KNOX_SDCARD checking this for 1000
I/libpersona( 3711): KNOX_SDCARD not a persona
,I/SELinux ( 3711): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ResourcesManager( 3691): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/SELinux ( 3711): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3711): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3711 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SamsungIME( 1882): KeybaordView init() : load resources
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3728 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2910:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,E/Zygote  ( 3728): MountEmulatedStorage()
I/libpersona( 3728): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3728): v2
I/libpersona( 3728): KNOX_SDCARD not a persona
,I/SELinux ( 3728): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 3711): TimaSignature is unavailable
D/ActivityThread( 3711): Added TimaKeyStore provider
,I/DBG_DM  ( 3043): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/SELinux ( 3728): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3728): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1882): getCurrentKeyboard
,I/SamsungIME( 1882): getTextKeyboard
,I/art     (  315): Explicit concurrent mark sweep GC freed 8770(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 725us total 39.300ms
,D/TimaKeyStoreProvider( 3728): TimaSignature is unavailable
D/ActivityThread( 3728): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 20.312ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 20.079ms
,D/SamsungIME( 1882): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/CameraApp( 3711): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3711): Feature.Feature(context)
I/testFeature( 3711): Feature.readInternalDefaultXml()
I/testFeature( 3711): ResetFeatureValue
,I/CameraFirmware_broadcast( 3711): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3711): CameraApp.getAppFeature()...
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3745 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,E/Zygote  ( 3745): MountEmulatedStorage(),
E/Zygote  ( 3745): v2
I/ActivityManager( 1016): Killing 2929:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/libpersona( 3745): KNOX_SDCARD checking this for 10100
I/libpersona( 3745): KNOX_SDCARD not a persona
,W/libprocessgroup( 1016): failed to open /acct/uid_10157/pid_2892/cgroup.procs: No such file or directory,
,I/SELinux ( 3745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3745): TimaSignature is unavailable
,D/ActivityThread( 3745): Added TimaKeyStore provider
,D/PackageIntentReceiver( 3745): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3745): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3761): MountEmulatedStorage(),
E/Zygote  ( 3761): v2
I/libpersona( 3761): KNOX_SDCARD checking this for 10101
I/libpersona( 3761): KNOX_SDCARD not a persona,
I/SELinux ( 3761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3761): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3761 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2944:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2910/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3761): TimaSignature is unavailable
,D/ActivityThread( 3761): Added TimaKeyStore provider
,W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2929/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_2944/cgroup.procs: No such file or directory
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/VlingoApplication( 3691): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,D/BluetoothAdapter( 3691): 975509151: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3691): 975509151: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3691): 975509151: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3691): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,I/AudioService( 1016): getStreamVolume 3 index 0
,I/jxcore-log( 3268): getBuffer is called!!!!
I/jxcore-log( 3268): 
,D/FactoryTestApp( 2570): [DummyFtClient$onDestroy](2570) Destroy DummyFtClient service
,D/FactoryTestApp( 2570): [Support$Values.getString](2570) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2570): [ModuleCommon$isConnectionModeNone](2570) mConnectionMode = gsm
I/FactoryTestApp( 2570): [ModuleCommon$isRunningFtClient](2570) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2570): [DummyFtClient$onDestroy](2570) kill process
I/Process ( 2570): Sending signal. PID: 2570 SIG: 9
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3212): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3212): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3212): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/VlingoApplication( 3691): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3691): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/ActivityManager( 1016): Process com.sec.factory (pid 2570)(adj 0) has died(194,1055)
,D/DialogFlow( 3691): initQueue()
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3810 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
E/Zygote  ( 3810): MountEmulatedStorage()
E/Zygote  ( 3810): v2
I/ActivityManager( 1016): Killing 2957:com.sec.knox.bridge/1000 (adj 15): empty #31
I/libpersona( 3810): KNOX_SDCARD checking this for 10032
I/libpersona( 3810): KNOX_SDCARD not a persona
I/SELinux ( 3810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaKeyStoreProvider( 3810): TimaSignature is unavailable
,D/ActivityThread( 3810): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3833): MountEmulatedStorage()
I/libpersona( 3833): KNOX_SDCARD checking this for 10033
E/Zygote  ( 3833): v2
I/libpersona( 3833): KNOX_SDCARD not a persona
I/SELinux ( 3833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3833 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 3833): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 2988:com.sec.usbsettings/1000 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3728): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 3728): Resource data:2131165186
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/TimaKeyStoreProvider( 3833): TimaSignature is unavailable
,D/ActivityThread( 3833): Added TimaKeyStore provider
,W/ResourcesManager( 3728): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3728): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,W/ContextImpl( 1909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/SecUISvc( 1909): Service started flags 0 startId 1
,D/SecUISvc( 1909): Thread created.
,I/AMMetaDataParserService( 3728): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509,
,I/Gmail   ( 3761): getAccountsCursor
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1016): Killing 1553:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/AMMetaDataParserService( 3728): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/DBG_DM  ( 3043): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,I/AMMetaDataParserService( 3728): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2957/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2988/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_1553/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/GAV2    ( 3761): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131034113
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ResourcesManager( 3728): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 3728): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3728): took 2.131980ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3728): took 6.040208ms for 0*0 texture 0
,I/GFX raster( 3728): took 9.416667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb937c918 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb937c8e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/Gmail   ( 3761): Observing account changes for notifications,
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 3761): Error finding the version of the Email provider.....
E/Gmail   ( 3761): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3761): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3761): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3761): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3761): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3761): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 3761): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 3761): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3870): MountEmulatedStorage()
E/Zygote  ( 3870): v2
,I/libpersona( 3870): KNOX_SDCARD checking this for 10104
I/libpersona( 3870): KNOX_SDCARD not a persona
,I/SELinux ( 3870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.865781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb937c918 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb937c8e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3870 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 3870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3870): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3728): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GoogleHttpClient( 1635): GMS http client unavailable, use old client
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ResourcesManager( 3833): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 3833): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3833): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3761): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@11d83bc6 that was originally bound here
E/ActivityThread( 3761): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@11d83bc6 that was originally bound here
E/ActivityThread( 3761): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3761): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3761): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3761): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3761): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3761): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3761): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3761): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3761): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3761): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3761): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3761): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3761): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3761): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@1688a858
,D/TimaKeyStoreProvider( 3870): TimaSignature is unavailable
,D/ActivityThread( 3870): Added TimaKeyStore provider
,W/ResourcesManager( 3833): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3833): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3833): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/FileApkUtils( 1983): Spent 73ms computing apk sha1.
,D/FileApkUtils( 1983): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1983): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/DexOptUtils( 1983): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk appears to be unoptimized.
,D/DexOptUtils( 1983): Lollipop platform, using <isa> directory.
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1016): Killing 3059:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,W/ResourcesManager( 3833): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/DexOptUtils( 1983): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1983): Primary ABI of odexing process is armeabi-v7a
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3728): took 2.703125ms for 0*0 texture 0
,W/ResourcesManager( 3833): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,W/ResourcesManager( 3833): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 3870): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GFX generate_partition_tables( 3728): took 8.816354ms for 0*0 texture 0
,I/GFX raster( 3728): took 12.480259ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb937c8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93813d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1882): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SQLiteLog( 3761): (283) recovered 26 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/AMMetaDataParserService( 3728): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/dex2oat ( 3896): ----------------------------------------------------
I/dex2oat ( 3896): <SS>: S T A R T I N G . . .
I/dex2oat ( 3896): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3896): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_3059/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.595886ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9385f78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93860d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/File    ( 3761): fail readDirectory() errno=2
,D/GCM     ( 1983): COMPAT: Multi user not supported
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1635): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3728): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1983): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/GFX raster( 3728): took 0.820157ms for 96*96 texture 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9382980 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9382ad8 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1792): DispatchingService.onCreate()
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/Gmail   ( 3761): getAccountsCursor
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3761): notifyAccountChanged
,I/CheckinService( 1983): Checkin interval check for package: unspecified last checkin: 1449470940712 min interval config: 0 actual interval: 28017080
,I/AMMetaDataParserService( 3728): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.621250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9381850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9384c38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.789896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb8fadd30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9347d88 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 3074:com.policydm/1000 (adj 15): empty #31
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 28106(1652KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.743ms total 172.451ms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/CheckinService( 1983): Disabling old GoogleServicesFramework version
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3761): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3761): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/DBG_DM  ( 3043): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.525833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9364888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90b9ac8 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 1983): onCreate
,I/AMMetaDataParserService( 3728): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131034113
,I/Gmail   ( 3761): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3761): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3728): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GFX raster( 3728): took 0.909688ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb90b9ac8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9347d88 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1983): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/AuthZen ( 1983): Handling intent: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/AuthZenEventHandler( 1983): Handling event: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3728): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/CheckinService( 1983): Checking schedule, now: 1449498958155 next: 1450010203660
I/CheckinService( 1983): active receiver: disabled
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GFX raster( 3728): took 0.872345ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb90b9ac8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9347d88 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1983): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/AMMetaDataParserService( 3728): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/BaseAppContext( 1983): Using Auth Proxy for data requests.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.611927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9347d88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93264a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SystemUpdateService( 1983): cancelUpdate (empty URL)
,I/SystemUpdateService( 1983): active receiver: disabled
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3074/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3728): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1792): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.607656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9377348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90f40d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.826146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9382980 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9346d60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.780417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9381850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90f40d8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ChimeraCfgMgr( 1983): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Process ( 3833): Sending signal. PID: 3833 SIG: 9
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1983): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 1983): [KidAccountFixer] No network connection
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.854271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb8fadd30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93645a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1983): onDestroy
,I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1983): Fetching signing key...
,W/GCoreFlp( 1792): No location to return for getLastLocation()
W/FusedLocationProvider( 1983): location=null
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 3833)(adj 0) has died(151,1083)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3961): MountEmulatedStorage()
,I/libpersona( 3961): KNOX_SDCARD checking this for 10034
E/Zygote  ( 3961): v2
I/libpersona( 3961): KNOX_SDCARD not a persona
I/SELinux ( 3961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3961 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3961): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel   ( 3870): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3870): MmsConfig.loadMmsSettings
,I/Babel   ( 3870): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3870): MmsConfig.loadFromDatabase
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/Auth    ( 1635): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/GFX raster( 3728): took 0.898699ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9364888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb937d120 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/TimaKeyStoreProvider( 3961): TimaSignature is unavailable
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3961): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3728): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AuthZen ( 1983): Signing key fetched successfully!
,W/BaseAppContext( 1983): Using Auth Proxy for data requests.
,D/a       ( 1983): Opening database auth.proximity.permit_store...
,I/art     ( 1983): Explicit concurrent mark sweep GC freed 24980(1936KB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 10MB/17MB, paused 2.579ms total 153.940ms
,I/AMMetaDataParserService( 3728): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3728): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3728): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131034112
I/AMMetaDataParserService( 3728): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
I/GFX raster( 3728): took 0.597135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9377348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93645a8 counterpartCT=4 counterpartW=96 counterparth=96
,V/GmsCoreStatsServiceLauncher( 1983): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
E/Babel   ( 3870): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3870): MmsConfig.loadFromResources
,E/Babel   ( 3870): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3870): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/AuthZenTransactionCache( 1983): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1983): Clearing transaction cache
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1792): No location to return for getLastLocation()
,W/FusedLocationProvider( 1983): location=null
,E/SMD     (  290): DCD OFF
,I/AMMetaDataParserService( 3728): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/Settings( 3870): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.595677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9377348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9346d60 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3728): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,E/Zygote  ( 3981): MountEmulatedStorage(),
E/Zygote  ( 3981): v2
I/libpersona( 3981): KNOX_SDCARD checking this for 1000
I/libpersona( 3981): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3981 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3007:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
I/SELinux ( 3981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3981): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3981): TimaSignature is unavailable
,D/ActivityThread( 3981): Added TimaKeyStore provider
,D/PersistentNotificationBroadcastReceiver( 1635): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/Babel_StickerModule( 3870): App launched.
,I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3999 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 3999): MountEmulatedStorage(),
E/Zygote  ( 3999): v2
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/libpersona( 3999): KNOX_SDCARD checking this for 10028
I/GFX raster( 3728): took 0.684063ms for 96*96 texture 0
I/libpersona( 3999): KNOX_SDCARD not a persona
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb90f40d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb937d120 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 3999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3999): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3728): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
W/libprocessgroup( 1016): failed to open /acct/uid_10085/pid_3007/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3999): TimaSignature is unavailable
D/ActivityThread( 3999): Added TimaKeyStore provider
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.721354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9381850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93645a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/DBG_DM  ( 3043): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131034113
,I/AMMetaDataParserService( 3728): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.842240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb90b9ac8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9346d60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533,
,V/Babel   ( 3870): babel boot account: SMS
,W/Babel   ( 3870): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,I/art     ( 1635): Explicit concurrent mark sweep GC freed 5813(357KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/18MB, paused 2.526ms total 628.962ms
,W/Babel   ( 3870): java.lang.Exception
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3870): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3870): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3870): 	at ckh.a(SourceFile:67)
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3870): 	at bhn.a(SourceFile:301)
W/Babel   ( 3870): 	at bhn.a(SourceFile:137)
W/Babel   ( 3870): 	at bhn.a(SourceFile:126)
W/Babel   ( 3870): 	at bhn.a(SourceFile:159)
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3870): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3870): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3870): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3870): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3870): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3870): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 3870): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3870): java.lang.Exception
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3870): 	at aes.a(SourceFile:145)
W/Babel   ( 3870): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3870): 	at ckh.a(SourceFile:67)
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3870): 	at bhn.a(SourceFile:301)
W/Babel   ( 3870): 	at bhn.a(SourceFile:137)
W/Babel   ( 3870): 	at bhn.a(SourceFile:126)
W/Babel   ( 3870): 	at bhn.a(SourceFile:159)
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3870): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3870): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3870): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3870): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3870): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3870): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.809635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb90b9ac8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9370dd0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3810): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1178 (0x0)
,I/AMMetaDataParserService( 3728): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/DBG_POLICYDM( 3981): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3981): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 3981): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3981): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3981): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3981): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/Gmail   ( 3761): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.625886ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9347d88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb937d120 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/DBG_POLICYDM( 3981): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
I/DBG_POLICYDM( 3981): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 3981): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/AMMetaDataParserService( 3728): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
I/DBG_POLICYDM( 3981): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 3981): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 3870): babel boot account: thalitester@gmail.com
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.712344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9377348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93645a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3981): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Babel   ( 3870): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3870): java.lang.Exception
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3870): 	at aes.a(SourceFile:145)
W/Babel   ( 3870): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3870): 	at ckh.a(SourceFile:67)
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3870): 	at bhn.a(SourceFile:301)
W/Babel   ( 3870): 	at bhn.a(SourceFile:137)
W/Babel   ( 3870): 	at bhn.a(SourceFile:126)
W/Babel   ( 3870): 	at bhn.a(SourceFile:159)
W/Babel   ( 3870): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3870): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3870): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3870): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3870): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3870): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3870): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/SSRM:n  ( 1016): SIOP:: AP = 360,
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4022 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/Zygote  ( 4022): MountEmulatedStorage()
E/Zygote  ( 4022): v2
I/ActivityManager( 1016): Killing 3142:com.fmm.dm/1000 (adj 15): empty #31
,I/libpersona( 4022): KNOX_SDCARD checking this for 10035
I/libpersona( 4022): KNOX_SDCARD not a persona
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.931354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9382980 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93204b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4022): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3728): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/TimaKeyStoreProvider( 4022): TimaSignature is unavailable
,D/ActivityThread( 4022): Added TimaKeyStore provider
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.738698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9381850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9346d60 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ResourcesManager( 3810): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,W/ResourcesManager( 3810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4039): MountEmulatedStorage(),
I/libpersona( 4039): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4039): v2
I/libpersona( 4039): KNOX_SDCARD not a persona
,I/SELinux ( 4039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4039 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4039): TimaSignature is unavailable
D/ActivityThread( 4039): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3981): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3981): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3981): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3142/cgroup.procs: No such file or directory
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/DBG_POLICYDM( 3981): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/GFX raster( 3728): took 0.782864ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb8fadd30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9370dd0 counterpartCT=4 counterpartW=96 counterparth=96
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  285): getCameraInfo: X
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  285): getCameraInfo: X
,I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/VideoCapabilities( 3870): Unrecognized profile 2130706433 for video/avc
,E/SPPClientService( 4022): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4022): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 4022): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,W/AudioCapabilities( 3870): Unsupported mime audio/evrc
,W/AudioCapabilities( 3870): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3870): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3870): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3870): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3870): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3870): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3870): Unsupported mime audio/evrc
,D/SPPClientService( 4022): PushLog.txt file is not deleted.
D/SPPClientService( 4022): PushLog.txt file is not deleted.
D/SPPClientService( 4022): ============PushLog. stop!
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.646302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9364888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb937d120 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 3999): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/AMMetaDataParserService( 3728): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/Zygote  ( 4058): MountEmulatedStorage()
E/Zygote  ( 4058): v2
I/libpersona( 4058): KNOX_SDCARD checking this for 1000
I/libpersona( 4058): KNOX_SDCARD not a persona
,I/SELinux ( 4058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4058 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3159:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,I/art     (  315): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 22.800ms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 18.932ms
,D/TimaKeyStoreProvider( 4058): TimaSignature is unavailable
,D/ActivityThread( 4058): Added TimaKeyStore provider
W/VideoCapabilities( 3870): Unsupported mime video/wvc1
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.037ms total 19.784ms
,W/VideoCapabilities( 3870): Unsupported mime video/x-ms-wmv
,E/Zygote  ( 4077): MountEmulatedStorage()
,E/Zygote  ( 4077): v2
I/libpersona( 4077): KNOX_SDCARD checking this for 10041
I/libpersona( 4077): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4077 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3127:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/SELinux ( 4077): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4077): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4077): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 3870): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728,): Resource data:2131165203
,W/VideoCapabilities( 3870): Unsupported mime video/wvc1
,W/VideoCapabilities( 3870): Unsupported mime video/x-ms-wmv
,D/TimaKeyStoreProvider( 4077): TimaSignature is unavailable
,W/VideoCapabilities( 3870): Unsupported mime video/x-ms-wmv7
,D/ActivityThread( 4077): Added TimaKeyStore provider
,W/ResourcesManager( 3728): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3870): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3870): Unsupported mime video/mp43
,W/VideoCapabilities( 3870): Unsupported mime video/sorenson
,W/VideoCapabilities( 3870): Unsupported mime video/mp4v-esdp
,I/AMMetaDataParserService( 3728): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3728): took 3.023594ms for 0*0 texture 0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3159/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_3127/cgroup.procs: No such file or directory
,I/VideoCapabilities( 3870): Unsupported profile 4 for video/mp4v-es
,D/KnoxSetupWizardDbHelper( 4058): dbMigrationFlag : false
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/GFX generate_partition_tables( 3728): took 11.617032ms for 0*0 texture 0
,I/GFX raster( 3728): took 15.954376ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb93639a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9534d48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/ShortcutReceiver( 4058):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1792): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/KnoxShortcutUtil( 4058): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4058):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 4058):  shortcut migration not required 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4099): MountEmulatedStorage()
E/Zygote  ( 4099): v2
I/libpersona( 4099): KNOX_SDCARD checking this for 1000
I/libpersona( 4099): KNOX_SDCARD not a persona
,I/SELinux ( 4099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4099 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3290:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31,
,I/SELinux ( 4099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 3.542499ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9353020 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93530c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4099): TimaSignature is unavailable
,D/ActivityThread( 4099): Added TimaKeyStore provider
,I/GCoreUlr( 1792): Unbound from all location providers
,I/AMMetaDataParserService( 3728): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/KnoxSetupWizardClient( 4099): isShipMode : 1
I/KnoxSetupWizardClient( 4099): onReceive : android.intent.action.BOOT_COMPLETED
,E/SQLiteLog( 3870): (284) automatic index on conversation_participants_view(conversation_id)
,V/AlarmManager( 1016): waitForAlarm result :8
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3043): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/ActivityManager( 1016): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4123 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3176:com.google.android.configupdater/u0a86 (adj 15): empty #31,
,E/Zygote  ( 4123): MountEmulatedStorage()
I/libpersona( 4123): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4123): v2
I/libpersona( 4123): KNOX_SDCARD not a persona
,I/SELinux ( 4123): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,I/SELinux ( 4123): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4123): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,W/art     ( 3691): Suspending all threads took: 20.162ms
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,E/SQLiteLog( 3870): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.784688ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9353020 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb90b9ac8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4123): TimaSignature is unavailable
,E/SQLiteLog( 3870): (284) automatic index on conversation_participants_view(conversation_id)
,D/ActivityThread( 4123): Added TimaKeyStore provider
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/AMMetaDataParserService( 3728): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/accuweather( 1713): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1713): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1713): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1713): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1713): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1713): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1713): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1713): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1713): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_3290/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10086/pid_3176/cgroup.procs: No such file or directory
I/SA      ( 4077): [SSP] onCreated
,E/accuweather( 1713): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 36
,W/System.err( 4099): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 4099): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4099): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4099): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4099): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4099): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4099): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/dex2oat ( 3896): dex2oat took 2.630s (threads: 4)
,D/Finsky  ( 3999): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.779896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9353020 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fadd30 counterpartCT=4 counterpartW=96 counterparth=96
,I/System.out( 3691): INFO:Resource not found:/Common.properties Using default values
,I/AMMetaDataParserService( 3728): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/SQLiteLog( 3870): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.622864ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb935a990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9347d88 counterpartCT=4 counterpartW=96 counterparth=96
,D/DexOptUtils( 1983): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex
D/DexOptUtils( 1983): Set odex to world readable.
,D/DexOptUtils( 1983): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.odex
,D/FileApkUtils( 1983): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/AMMetaDataParserService( 3728): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/SA      ( 4077): [TPM] There is no property file
,I/SA      ( 4077): [SCU] isHaveSA() - false
,D/GmsModuleFndr( 1983): Beginning GMS chimera module scan
,E/SQLiteLog( 3870): (284) automatic index on conversation_participants_view(conversation_id)
,D/GmsModuleFndr( 1983): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1983): Beginning module configuration check
,I/SA      ( 4077): [TPM] getModelProperty : null
I/SA      ( 4077): [TPM] getCSCProperty : null
,I/SA      ( 4077): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4077): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4077): [DM] TFT FEATURE: false
,D/ChimeraCfgMgr( 1983): Module APKs unchanged, check complete
,I/GCoreUlr( 1792): DispatchingService.onDestroy()
,I/GCoreUlr( 1792): Stopping handler for UlrDispSvcFast
,I/SA      ( 4077): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4077): [DM] init START
,I/SA      ( 4077): [DM] This device is not a Vodafone
,W/Settings( 3999): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/GCoreUlr( 1792): Unbound from all location providers
,W/Settings( 3999): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourceType( 4077): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,I/ActivityManager( 1016): Killing 3312:com.fmm.ds/1000 (adj 15): empty #31
W/ResourceType( 4077): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4077): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4077): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4077): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4077): [SCU] isHaveSA() - false
,I/SA      ( 4077): support phone number id : false
,I/SA      ( 4077): [DM] Supports Ref Jpn : true
,I/SA      ( 4077): [DM] init END
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.620729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb935a990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90b9ac8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4077): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4077): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1016): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4077): [OR] onReceive END
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,I/AMMetaDataParserService( 3728): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,E/Zygote  ( 4152): MountEmulatedStorage(),
E/Zygote  ( 4152): v2,
I/libpersona( 4152): KNOX_SDCARD checking this for 10042
I/libpersona( 4152): KNOX_SDCARD not a persona
,I/SELinux ( 4152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4152 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4152): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SA      ( 4077): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4077): [ODM] queryOpenData(key= GEO_IP )
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131099648
,I/SA      ( 4077): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4077): [LBE] REF_JPN : true
,I/SA      ( 4077): [BDC] create
,D/TimaKeyStoreProvider( 4152): TimaSignature is unavailable
,D/ActivityThread( 4152): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3312/cgroup.procs: No such file or directory
,W/ResourcesManager( 4152): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 3337:com.dropbox.android/u0a92 (adj 15): empty #31
D/Volley  ( 3999): [601] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 3999): [608] DiskBasedCache.clear: Cache cleared.
,W/ResourcesManager( 3728): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 1.047448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb937c618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb936cbf0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/SA      ( 4077): [DBMV2] getEmailID
,I/SA      ( 4077): [DBMV2] getDataV02ForItems
,I/SA      ( 4077): [SSP] query invoked
,I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SA      ( 4077): [SCU] get signed id from samsung account2.0 DB.
,D/Finsky  ( 3999): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3999): [1] Libraries$2.run: Finished loading 1 libraries.
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3728): took 2.934376ms for 0*0 texture 0
I/SA      ( 4077): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4077): [BDC] destroy
,I/ActivityManager( 1016): Killing 3359:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/GFX generate_partition_tables( 3728): took 8.695521ms for 0*0 texture 0
,I/GFX raster( 3728): took 12.778438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9369c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb936a2f8 counterpartCT=4 counterpartW=96 counterparth=96
,D/Ads     ( 3999): Skipping gmscore version check
,I/AMMetaDataParserService( 3728): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.636355ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987c5b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb987c6f0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 4152): CalendarProvider2.onCreate() called
,D/Finsky  ( 3999): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3728): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.645106ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987dc18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb987dcc0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3359/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3728): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/Finsky  ( 3999): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.662709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987f140 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb987f1e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.743854ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9882098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb936a0f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3337/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131099648
,I/AMMetaDataParserService( 3728): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3728): took 0.699375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb937c618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9535098 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms,
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.682448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9369c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9383108 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.717343ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987c5b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9383108 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.730886ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987dc18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9376d30 counterpartCT=4 counterpartW=96 counterparth=96
,I/SecDataIO(  256): Write to block
,W/ContextImpl( 2553): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/AMMetaDataParserService( 3728): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_DM  ( 3043): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3043): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3043): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.759167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987f140 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9535098 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/StrictMode( 4123): StrictMode policy violation; ~duration=533 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4123): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4123): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4123): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4123): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4123): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4123): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4123): StrictMode policy violation; ~duration=526 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4123): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4123): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4123): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4123): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4123): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4123): StrictMode policy violation; ~duration=378 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4123): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4123): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4123): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4123): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4123): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4123): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4123): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4123): StrictMode policy violation; ~duration=377 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4123): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4123): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4123): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4123): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4123): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrume,ntation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4123): StrictMode policy violation; ~duration=376 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4123): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4123): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4123): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4123): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4123): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4123): StrictMode policy violation; ~duration=374 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4123): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4123): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4123): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4123): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4123): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4123): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4123): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4123): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4123): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4123): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4123): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4123): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4123): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4123): StrictMode policy violation; ~duration=372 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4123): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4123): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4123): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4123): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4123): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4123): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4123): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4123): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4123): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4123): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4123): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4123): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4123): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4123): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4123): StrictMode policy violation; ~duration=266 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4123): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4123): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4123): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4123): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4123): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4123): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4123): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/StrictMode( 4123): StrictMode policy violation; ~duration=264 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4123): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4123): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4123): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4123): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4123): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4123): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4123): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4123): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4123): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4123): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4123): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3728): took 0.833958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9882098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9383108 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3728): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131099648
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3728): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3728): took 0.706458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb937c618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9383108 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
E/Zygote  ( 4179): MountEmulatedStorage()
E/Zygote  ( 4179): v2
I/libpersona( 4179): KNOX_SDCARD checking this for 1000
I/libpersona( 4179): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4179 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3391:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
I/SELinux ( 4179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4179): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3728): took 0.634844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9369c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9535098 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1016): Killing 3414:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4179): TimaSignature is unavailable
,D/ActivityThread( 4179): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3728): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 31280(1893KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 26MB/39MB, paused 2.352ms total 159.657ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 3691): Suspending all threads took: 17.448ms
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/GFX raster( 3728): took 0.687500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987c5b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9376d30 counterpartCT=4 counterpartW=96 counterparth=96
,D/BluetoothAdapter( 3268): disable()
,I/AMMetaDataParserService( 3728): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/BluetoothManagerService( 1016): Bluetooth is already disabled. DO NOT disable again.
,I/Process ( 2553): Sending signal. PID: 2553 SIG: 9
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1016): mCursor = null
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.641302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987dc18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9383108 counterpartCT=4 counterpartW=96 counterparth=96
,D/WifiService( 1016): setWifiEnabled: false pid=3268, uid=10174
,D/SettingsProvider( 1016): name = wifi_on
,I/AMMetaDataParserService( 3728): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/jxcore-log( 3268): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3268): 
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3728): took 0.627084ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb987f140 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9535098 counterpartCT=4 counterpartW=96 counterparth=96
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3414/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3391/cgroup.procs: No such file or directory
,D/StatusChecker( 4179): onReceive : android.intent.action.BOOT_COMPLETED
,W/com.google.a.a.b.d.a( 4123): Application name is not set. Call Builder#setApplicationName.
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/StatusChecker( 4179): onReceive : net.mt.init : DONE
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.725938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9882098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9376d30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/Zygote  ( 4199): MountEmulatedStorage()
E/Zygote  ( 4199): v2
I/libpersona( 4199): KNOX_SDCARD checking this for 10116
,I/libpersona( 4199): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4199 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/SELinux ( 4199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131099648
I/SELinux ( 4199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 2553)(adj 0) has died(108,1113)
I/AMMetaDataParserService( 3728): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3728): took 0.781615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb937c618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9376d30 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 4199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.712604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9369c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9535098 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4199): TimaSignature is unavailable
,D/ActivityThread( 4199): Added TimaKeyStore provider
,I/DBG_DM  ( 3043): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec,
,I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/DBG_DM  ( 3043): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 3043): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/PageBuddyNotiSvc( 4199): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4199): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/AlarmManager( 1016): waitForAlarm result :4
I/PageBuddyNotiSvc( 4199): onCreate mCpBitFlag=0
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3728): took 0.649843ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb93205a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8fff238 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4217): MountEmulatedStorage()
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4217 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 4217): v2,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
I/libpersona( 4217): KNOX_SDCARD checking this for 10125
I/libpersona( 4217): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3728): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,I/SELinux ( 4217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 4217): TimaSignature is unavailable
,D/ActivityThread( 4217): Added TimaKeyStore provider
,I/GFX raster( 3728): took 0.670624ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb931ef68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fff238 counterpartCT=4 counterpartW=96 counterparth=96
,I/iu.UploadsManager( 1983): End new media; added: 0, uploading: 0, time: 46 ms
,W/ResourcesManager( 4217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
W/ResourcesManager( 4217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4217): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.624427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9351358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9320560 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3728): took 0.743594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb935a3d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9363958 counterpartCT=4 counterpartW=96 counterparth=96
,D/AndroidRuntime( 4207): 
D/AndroidRuntime( 4207): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/AMMetaDataParserService( 3728): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/AndroidRuntime( 4207): CheckJNI is OFF
,D/AndroidRuntime( 4207): readGMSProperty: start
D/AndroidRuntime( 4207): readGMSProperty: already setted!!
D/AndroidRuntime( 4207): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4207): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4207): readGMSProperty: end
D/AndroidRuntime( 4207): addProductProperty: start
,D/QuickConnect( 4217): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4217): Util.setSCRunningSetting - [value]0
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131099648
I/AMMetaDataParserService( 3728): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.730989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb8f9bef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f9ba98 counterpartCT=4 counterpartW=96 counterparth=96
D/SettingsProvider( 1016): name = scon_is_running
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10125
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 4217): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4217): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3728): took 0.640208ms for 96*96 texture 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9369c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9320560 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3728): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.650000ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb93205a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9345340 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4240): MountEmulatedStorage(),
E/Zygote  ( 4240): v2
I/libpersona( 4240): KNOX_SDCARD checking this for 10131
I/libpersona( 4240): KNOX_SDCARD not a persona
I/SELinux ( 4240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4240 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 4240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Killing 3431:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,E/SELinux ( 4240): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3728): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/TimaKeyStoreProvider( 4240): TimaSignature is unavailable
D/ActivityThread( 4240): Added TimaKeyStore provider
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 4240): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/GFX raster( 3728): took 0.645521ms for 96*96 texture 0
W/ResourcesManager( 4240): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb931ef68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb935a990 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 4240): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4240): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.655885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9351358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9320560 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3431/cgroup.procs: No such file or directory
,E/AffinityControl( 4207): AffinityControl: registerfunction enter,
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/SBrowserFeatureFlag( 4240): initialized in static block : loadCscFeatureValue() succeed! 
,I/GFX raster( 3728): took 0.720833ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb935a3d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9345340 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ConversationList,
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131099648
I/AMMetaDataParserService( 3728): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ManifestProvider( 4240): onCreate()
,I/GFX raster( 3728): took 0.842708ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb8f9bef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fff238 counterpartCT=4 counterpartW=96 counterparth=96
,D/AndroidRuntime( 4207): Calling main entry com.android.commands.pm.Pm,
,I/AMMetaDataParserService( 3728): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/NetworkSettingsReceiver( 4240): onReceive: android.intent.action.BOOT_COMPLETED
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{635315184}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1016): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 3268:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,E/SBrowserFeatureFlag( 4240): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@361f9266
,W/PackageSettings( 1016): Skipping PackageSetting{3f5d0f1e com.test.thalitest/10175} due to missing metadata
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3728): took 0.630053ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9369c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb935a990 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.659010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb93205a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9534598 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3728): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,I/WindowState( 1016): WIN DEATH: Window{146ab64a u0 com.example.hello/com.example.hello.MainActivity},
I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,D/InputDispatcher( 1016): Focus left window: 3268,
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SBrowserFeatureFlag( 4240): initialize : initSupportedPkg() succeed! 
W/ActivityManager( 1016): Force removing ActivityRecord{19c4e6e8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1016): Set to : 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1016): Focused application set to: xxxx
,I/VerificationLog( 4240): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.642969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb931ef68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb935c6b0 counterpartCT=4 counterpartW=96 counterparth=96
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,I/AMMetaDataParserService( 3728): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.637551ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9351358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9320560 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): Spurious death for ProcessRecord{a289d69 3268:com.example.hello/u0a174}, curProc for 3268: null
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10174 user=0: pkg removed,
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/Launcher( 1468): onRestart, Launcher: 908038758
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.728541ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb935a3d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb937ef80 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3728): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity,
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/libpersona( 4261): KNOX_SDCARD checking this for 10135
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/libpersona( 4261): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings,
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4261 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity,
I/ActivityManager( 1016): Killing 3094:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/art     ( 3810): Explicit concurrent mark sweep GC freed 16243(933KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 6MB/9MB, paused, 730us total 31.496ms
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
E/Zygote  ( 4261): MountEmulatedStorage()
E/Zygote  ( 4261): v2
I/SELinux ( 4261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Launcher( 1468): onStart, Launcher: 908038758
D/Launcher.HomeView( 1468): onStart
D/Launcher( 1468): onResume, Launcher: 908038758
D/SettingsProvider( 1016): name = kids_home_mode
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10007
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/Launcher.HomeView( 1468): onResume
E/SELinux ( 4261): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Launcher( 1468): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/TimaKeyStoreProvider( 4261): TimaSignature is unavailable
,D/ActivityThread( 4261): Added TimaKeyStore provider
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1792): Ignoring removeGeofence because network location is disabled.,
,E/SamsungIME( 1882): mOCRHelper is null
,W/ResourcesManager( 1443): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MenuAppsGridFragment( 1468): onResume
,D/ActivityManager( 1016): handle home activity for 0
I/WallpaperManagerService( 1016): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1016): post home show event for user 0
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/RegisteredComponentCache( 1433): Collect Tech packages for Knox
,D/PersonaManager( 1433): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131165197
,W/ResourcesManager( 4261): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4261): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4261): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 3728): getResourceName:com.sec.android.gallery3d:xml/assistant
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1016): Focus entered window: 1468
,I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,D/SRIB_DCS( 1468): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/AMMetaDataParserService( 3728): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/Launcher( 1468): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/AMMetaDataParserService( 3728): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,E/SMD     (  290): DCD OFF
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
,I/AMMetaDataParserService( 3728): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10174
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 22713(1721KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 26MB/39MB, paused 5.785ms total 207.036ms
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/AlarmManagerEXT( 1016): com.example.hello(10174) is removed.
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1016): uID is 10174
D/TaskPersister( 1016): removeObsoleteFile: deleting file=2_task.xml
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,D/PersonaManager( 1433): isKioskContainerExistOnDevice
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
D/RegisteredServicesCache( 1433): empty dynamic service
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1016): [SO] activate (ident=0xb95c04b0, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1016): [SO] changed settle time [0]
D/SensorService( 1016): [SO] setDelay [200000000]
D/SensorService( 1016): [SO] activate (ident=0xb98a2370, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1016):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1016): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131165197
,I/AMMetaDataParserService( 3728): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,W/InputMethodManagerService( 1016): Got RemoteException sending setActive(false) notification to pid 3268 uid 10174
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SamsungIME( 1882): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
,I/AMMetaDataParserService( 3728): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/PackageManager( 1016): delete codoeFile: 
,D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
I/AASA_removePackage( 1016): UID=10174 Target=com.example.hello
,D/PackageManager( 1016): result of delete: 1{635315184}
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 4207): Shutting down VM
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/OpenGLRenderer( 1468): SFEffectCache::get: create texture(0x9faff724): name, size, mSize = 39, 145188, 320456
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3728): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
I/AMMetaDataParserService( 3728): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
I/ActivityManager( 1016): Displayed Component not be shown by security: +353ms
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CalendarProvider2( 4152): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,E/Zygote  ( 4289): MountEmulatedStorage()
,E/Zygote  ( 4289): v2
I/libpersona( 4289): KNOX_SDCARD checking this for 10139
I/libpersona( 4289): KNOX_SDCARD not a persona
,I/SELinux ( 4289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4289 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/SELinux ( 4289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{e42f9c4 u0 com.google.android.gms/.gcm.GcmService}
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131165197
,I/AMMetaDataParserService( 3728): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,I/AMMetaDataParserService( 3728): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4289): TimaSignature is unavailable
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityThread( 4289): Added TimaKeyStore provider
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3728): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ResourcesManager( 4289): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4289): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4289): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4289): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4289): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/UsbSettingsManager( 1016): clearDefaults: com.example.hello
I/CrashAnrDetector( 1016): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_3094/cgroup.procs: No such file or directory
,I/GAV2    ( 3761): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 3728): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/ActivityManager( 1016): Killing 3472:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,W/art     ( 4207): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,I/ActivityManager( 1016): Killing 3444:com.wssnps/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3728): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3728): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131099648
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3728): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): getResourceName:com.sec.android.app.camera:xml/assistant
W/ResourcesManager( 3728): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
W/ResourcesManager( 3728): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3728): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,E/Zygote  ( 4309): MountEmulatedStorage()
E/Zygote  ( 4309): v2
I/libpersona( 4309): KNOX_SDCARD checking this for 10145
I/libpersona( 4309): KNOX_SDCARD not a persona
,I/SELinux ( 4309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4309 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4309): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Killing 3196:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/AMMetaDataParserService( 3728): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/art     (  315): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 21.280ms
,D/TimaKeyStoreProvider( 4309): TimaSignature is unavailable
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 16.969ms
,D/ActivityThread( 4309): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
,W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.009ms
,W/ResourcesManager( 4309): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4309): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4309): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4309): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4309): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3472/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3444/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3196/cgroup.procs: No such file or directory
,D/SensorService( 1016): [SO] currT = 43890115867, prevT = 43470092638, diff = 420023229, [0.172 0.096 10.132]
D/SensorService( 1016): [SO] 0.172 0.096 10.132
D/SensorService( 1016): [SO] [100 -> 255]
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3728): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3728): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3728): getResourcePackageName:assistant
I/AMMetaDataParserService( 3728): Resource data:2131165220
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ResourcesManager( 3728): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3728): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3728): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3728): getResourceTypeNamexml
,E/        ( 3728): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3728): took 0.708542ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3728): Bitmap=0xb9a7f758 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9a7f488 counterpartCT=4 counterpartW=96 counterparth=96

```
