#### Test 503880196b4ec73_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
W/art     ( 2671): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 137.214ms
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
D/Mms/MessagingNotification( 2335): isBlockingModeEnabled() = false, Zen mode = 0
--------- beginning of system
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
D/BadgeProvider( 1567): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/FactoryTestApp( 2563): [IPCWriterToSecPhoneService$onServiceConnected](2563) connected done
D/FactoryTestApp( 2563): [IPCWriterToSecPhoneService$write](2563) Send Response Message to SecPhone
D/FactoryTestApp( 2563): [IPCWriterToSecPhoneService$write](2563) Response ��
D/AT_Distributor(  311): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
I/NearbySettings( 1305): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1305): MountReceiver.onReceive - Internal Path
D/FactoryTestApp( 2563): [IPCWriterToSecPhoneService$handleMessage](2563) Send BOOTING COMPLETED done
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/GSLBManager( 2703): migrateStoredUrlFromOldPref : Finished Migrating
D/[0]UMC:UMCAdmin( 2703): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2703): Admin not found in package com.samsung.knoxpb.mdm
D/SettingsProvider( 1013): name = personal_mode_enabled
E/[0]UMC:Utils( 2703): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2703): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2703): isContainer : 0
D/EnterpriseDeviceManagerService( 1013): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2703): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2703): isContainer : 0
D/[0]UMC:UMCAdmin( 2703): deactivateUMCAdmin - UMC App Admin deactivated
D/Launcher.Model( 1489): reloadBadges entered.
I/iu.UploadsManager( 1905): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2703): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
D/[0]UMC:CoreReceiver( 2703): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2703):  check PreETag 
D/BadgeProvider( 1567): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1567): sendNotify, [notify] : null
D/BadgeProvider( 1567): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1567): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1567): update, [UpdateCount] : 1
E/SQLiteLog( 2769): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
W/ResourcesManager( 1460): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1460): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/Mms/MessagingNotification( 2335): setBadgeCount(), count=0
E/USB_UICC(  297): Timeout! No signal received. Retry num = 25
D/DSM     ( 2769): [Lines:107] Normal booted
D/DSM     ( 2769): [Lines:114] Boot completed
D/Mms/MessagingNotification( 2335): remove alarm
D/[0]UMC:CoreReceiver( 2703): bulk enrolled package: null
V/[0]UMC:ProfileStorage( 2703): Enter loadList
D/[0]UMC:CoreReceiver( 2703): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2703): deactivateUMCAdminIfNotRequired : -1
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/[0]UMC:Utils( 2703): Admin not found in package com.samsung.knoxpb.mdm
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/[0]UMC:Utils( 2703): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2703): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2703): isContainer : 0
D/AT_Distributor(  311): SetAtdStatus(), 1_1_0
D/AT_Distributor(  311): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
E/SMD     (  288): DCD OFF
D/EnterpriseDeviceManagerService( 1013): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2703): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2703): isContainer : 0
D/[0]UMC:UMCAdmin( 2703): deactivateUMCAdmin - UMC App Admin deactivated
E/Zygote  ( 2806): MountEmulatedStorage()
E/Zygote  ( 2806): v2
I/libpersona( 2806): KNOX_SDCARD checking this for 1000
I/libpersona( 2806): KNOX_SDCARD not a persona
I/SELinux ( 2806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Mms/MessagingNotification( 2335): updateAllHistoryAsRead()
I/SELinux ( 2806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2806): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SmartcardBootCompleteReceiver( 1305): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1305): Received intent with action - android.intent.action.BOOT_COMPLETED
D/[0]UMC:ByodSetupStarter( 2703): Container ID : 0
V/[0]UMC:Utils( 2703): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2703): shutdown
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/TP/SmsProvider( 1460): query,matched:0, calling pid = 2335
D/[0]UMC:GuardService( 2703): @GuardService - stopService Result = true
W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
I/SmartcardBootCompleteReceiver( 1305): Broadcast sent with current lockscreen type
I/art     ( 2703): System.exit called, status: 0
I/AndroidRuntime( 2703): VM exiting with result code 0, cleanup skipped.
D/TP/SmsProvider( 1460): match 0:Elapsed time : 12.199 ms
D/TimaKeyStoreProvider( 2806): TimaSignature is unavailable
D/ActivityThread( 2806): Added TimaKeyStore provider
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2806): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/Zygote  ( 2823): MountEmulatedStorage()
E/Zygote  ( 2823): v2
I/libpersona( 2823): KNOX_SDCARD checking this for 1000
I/libpersona( 2823): KNOX_SDCARD not a persona
I/SELinux ( 2823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/art     ( 1013): Explicit concurrent mark sweep GC freed 23857(1224KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 25MB/38MB, paused 6.296ms total 157.425ms
I/art     (  307): Explicit concurrent mark sweep GC freed 8769(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 23.157ms
D/TimaKeyStoreProvider( 2823): TimaSignature is unavailable
D/ActivityThread( 2823): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 18.237ms
D/Mms/SmsReceiverService( 2335): [end]    handleBootCompleted() consume time = 375.542187
I/ActivityManager( 1013): Killing 1187:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/art     (  307): Explicit concurrent mark sweep GC freed 4(112B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 17.757ms
I/ActivityManager( 1013): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2703)(adj 0) has died(210,1002)
W/ResourcesManager( 2823): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/daemonapp( 1282): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1282): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/[SBeam] ( 1305): SBeamEnabler.initPreferenceForSbeam : 0
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/SettingSearch/SearchIntentReceiver( 1305): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1305): search setting db init!!
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1282): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1282): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1282): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1282): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/SettingsProvider( 1013): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10162
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
I/SettingSearch/SearchIntentReceiver( 1305): BOOT_COMPLETED call InitSerachDBThread thread start!
I/iu.UploadsManager( 1905): End new media; added: 0, uploading: 0, time: 255 ms
W/ActivityThread( 2806): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
I/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1282): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
D/daemonapp( 1282): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1282): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1282): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/CursorWrapperInner( 2335): Cursor finalized without prior close()
E/daemonapp( 1282): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1282): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1448306434141
D/daemonapp( 1282): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1448328000000
D/daemonapp( 1282): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1282): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
E/Zygote  ( 2841): MountEmulatedStorage()
E/Zygote  ( 2841): v2
I/libpersona( 2841): KNOX_SDCARD checking this for 1000
I/SELinux ( 2841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 2841): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2841 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/SELinux ( 2841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_1187/cgroup.procs: No such file or directory
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2806): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
D/TimaKeyStoreProvider( 2841): TimaSignature is unavailable
D/ActivityThread( 2841): Added TimaKeyStore provider
E/Zygote  ( 2855): MountEmulatedStorage()
E/Zygote  ( 2855): v2
I/libpersona( 2855): KNOX_SDCARD checking this for 10150
I/libpersona( 2855): KNOX_SDCARD not a persona
I/SELinux ( 2855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2855 uid=10150 gids={50150, 9997} abi=armeabi-v7a
I/SELinux ( 2855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2855): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/LcdtestApp( 2806): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2855): TimaSignature is unavailable
D/ActivityThread( 2855): Added TimaKeyStore provider
E/Zygote  ( 2872): MountEmulatedStorage()
E/Zygote  ( 2872): v2
I/libpersona( 2872): KNOX_SDCARD checking this for 10086
I/libpersona( 2872): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2872 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 1406:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/SELinux ( 2872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2872): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/Zygote  ( 2884): MountEmulatedStorage()
I/libpersona( 2884): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2884): v2
I/libpersona( 2884): KNOX_SDCARD not a persona
I/SELinux ( 2884): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2884): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2884): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2884 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2872): TimaSignature is unavailable
D/ActivityThread( 2872): Added TimaKeyStore provider
I/ActivityManager( 1013): Killing 1387:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
D/daemonapp( 1282): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448328000000
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
D/daemonapp( 1282): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1448328000000
D/TimaKeyStoreProvider( 2884): TimaSignature is unavailable
D/ActivityThread( 2884): Added TimaKeyStore provider
W/ResourcesManager( 2841): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_1406/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10096/pid_1387/cgroup.procs: No such file or directory
D/comdaemonstockapp( 1282): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1282): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
W/ContextImpl( 1851): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/SecUISvc( 1851): Service started flags 0 startId 1
D/SecUISvc( 1851): Thread created.
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2906): MountEmulatedStorage()
E/Zygote  ( 2906): v2
I/libpersona( 2906): KNOX_SDCARD checking this for 10028
I/libpersona( 2906): KNOX_SDCARD not a persona
I/SELinux ( 2906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2906 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 2906): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DIAGMON_AGENT( 2884): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
E/UpdateRequestReceiver( 2872): ignoring update request
D/TimaKeyStoreProvider( 2906): TimaSignature is unavailable
D/ActivityThread( 2906): Added TimaKeyStore provider
E/UpdateRequestReceiver( 2872): ignoring update request
I/SecureStorage(  365): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
I/FOTA    ( 2841): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
E/UpdateRequestReceiver( 2872): ignoring update request
I/DBG_DM  ( 2841): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
I/SecureStorage( 2727): [INFO]: SPID(0x00000001)Processing data has been completed
I/SecureStorage( 2727): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
E/UpdateRequestReceiver( 2872): ignoring update request
E/UpdateRequestReceiver( 2872): ignoring update request
E/UpdateRequestReceiver( 2872): ignoring update request
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2934): MountEmulatedStorage()
E/Zygote  ( 2934): v2
I/libpersona( 2934): KNOX_SDCARD checking this for 10094
I/libpersona( 2934): KNOX_SDCARD not a persona
I/SELinux ( 2934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=2934 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 2934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Killing 1686:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
E/SELinux ( 2934): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2934): TimaSignature is unavailable
D/ActivityThread( 2934): Added TimaKeyStore provider
D/elm:15183( 2934): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 2934): ELMEngine.ELMEngine( context ).
D/elm:15183( 2934): MDMBridge.setEnterpriseBridge()
I/DBG_DM  ( 2841): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 2841): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 2934): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 2934): ElmAgentService : onCreate()
V/EmergencyMode( 1421): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
D/elm:15183( 2934): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 2934): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 2934): BootCompletedState : startBootCompleted() call
D/elm:15183( 2934): MDMBridge.getAllLicenseInfoFromSDK()
W/libprocessgroup( 1013): failed to open /acct/uid_10138/pid_1686/cgroup.procs: No such file or directory
I/elm:15183( 2934): Get License : 0
D/elm:15183( 2934): ElmAgentService : onDestroy().
I/ActivityManager( 1013): Killing 1550:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/DIAGMON_AGENT( 2884): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DBG_DM  ( 2841): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
I/DIAGMON_AGENT( 2884): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
W/ContextImpl( 2841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
I/DIAGMON_AGENT( 2884): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 2884): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2884): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2884): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
V/EmergencyMode( 1421): [EmergencyBase] setBootTime
V/EmergencyMode( 1421): [EmergencyFactory] No Recovery State, kill my self.
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 2841): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
E/Zygote  ( 2954): MountEmulatedStorage()
I/libpersona( 2954): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2954): v2
I/libpersona( 2954): KNOX_SDCARD not a persona
I/DBG_DM  ( 2841): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
I/SELinux ( 2954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 2841): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/SELinux ( 2954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
E/SELinux ( 2954): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 2841): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 2841): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 2841): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
D/TimaKeyStoreProvider( 2954): TimaSignature is unavailable
D/ActivityThread( 2954): Added TimaKeyStore provider
I/DBG_DM  ( 2841): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/ActivityManager( 1013): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=2954 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/libprocessgroup( 1013): failed to open /acct/uid_10057/pid_1550/cgroup.procs: No such file or directory
D/OverheatReceiver( 1172): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1172): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1172): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1172): isSafeMode = false
I/DBG_DM  ( 2841): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 2841): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(155/onStartCommand)] 
D/BootupListener( 1460): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1013): name = internet_call_settings_visibility
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1001
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/PhoneUtilsCommon( 1460): isSupportVoLTE is false.
I/DBG_DM  ( 2841): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
E/Zygote  ( 2970): MountEmulatedStorage()
E/Zygote  ( 2970): v2
I/libpersona( 2970): KNOX_SDCARD checking this for 1000
I/libpersona( 2970): KNOX_SDCARD not a persona
I/SELinux ( 2970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=2970 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Telecom ( 1431): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ContextImpl( 2841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/Telecom ( 1431): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2983): MountEmulatedStorage()
I/libpersona( 2983): KNOX_SDCARD checking this for 10012
E/Zygote  ( 2983): v2
I/libpersona( 2983): KNOX_SDCARD not a persona
I/SELinux ( 2983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=2983 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/SELinux ( 2983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2983): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/Telecom ( 1431): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
I/Telecom ( 1431): InCallController: Unbinding from InCallService unbind
I/CameraApp( 2954): CameraApp.onCreate()... mFeature : null
D/TimaKeyStoreProvider( 2970): TimaSignature is unavailable
D/ActivityThread( 2970): Added TimaKeyStore provider
I/testFeature( 2954): Feature.Feature(context)
I/testFeature( 2954): Feature.readInternalDefaultXml()
I/testFeature( 2954): ResetFeatureValue
I/CameraFirmware_broadcast( 2954): CameraFirmwareBroadCastReceiver...
I/CameraApp( 2954): CameraApp.getAppFeature()...
D/TimaKeyStoreProvider( 2983): TimaSignature is unavailable
D/AndroidRuntime( 2951): 
D/AndroidRuntime( 2951): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/ActivityThread( 2983): Added TimaKeyStore provider
D/AndroidRuntime( 2951): CheckJNI is OFF
D/AndroidRuntime( 2951): readGMSProperty: start
D/AndroidRuntime( 2951): readGMSProperty: already setted!!
D/AndroidRuntime( 2951): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2951): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2951): readGMSProperty: end
D/AndroidRuntime( 2951): addProductProperty: start
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/USB_UICC(  297): Timeout! No signal received. Retry num = 26
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 2841): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
E/Zygote  ( 3001): MountEmulatedStorage()
E/Zygote  ( 3001): v2
I/libpersona( 3001): KNOX_SDCARD checking this for 10100
I/libpersona( 3001): KNOX_SDCARD not a persona
I/SELinux ( 3001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3001 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 3001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 2060:com.vlingo.midas/u0a31 (adj 15): empty #31
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2983): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2983): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/Zygote  ( 3016): MountEmulatedStorage()
I/libpersona( 3016): KNOX_SDCARD checking this for 10003
E/Zygote  ( 3016): v2
I/libpersona( 3016): KNOX_SDCARD not a persona
I/SELinux ( 3016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3016 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3001): TimaSignature is unavailable
D/ActivityThread( 3001): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 693us total 25.164ms
I/MultiDex( 2983): VM with version 2.1.0 has multidex support
I/MultiDex( 2983): install
I/MultiDex( 2983): VM has multidex support, MultiDex support library is disabled.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 944us total 18.748ms
I/DBG_DM  ( 2841): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
V/JNIHelp ( 2983): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/TimaKeyStoreProvider( 3016): TimaSignature is unavailable
D/ActivityThread( 3016): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 19.596ms
I/ActivityManager( 1013): Killing 2107:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
W/ActivityThread( 2983): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 2983): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c10c198: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2983): Installed default security provider GmsCore_OpenSSL
E/AffinityControl( 2951): AffinityControl: registerfunction enter
D/PackageIntentReceiver( 3001): ACTION_BOOT_COMPLETED
D/AndroidRuntime( 2951): Calling main entry com.android.commands.am.Am
D/PackageIntentReceiver( 3001): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager( 1013): Killing 2122:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
D/UserAnalysis.PlaceProvider( 3016): PlaceProvider onCreate()
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/PersonaManagerService( 1013): inState():  stateMachine is null !!
I/PersonaManagerService( 1013): PersonaId don't exist
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
I/GoogleHttpClient( 1667): GMS http client unavailable, use old client
E/Zygote  ( 3047): MountEmulatedStorage()
E/Zygote  ( 3047): v2
I/libpersona( 3047): KNOX_SDCARD checking this for 1000
I/libpersona( 3047): KNOX_SDCARD not a persona
I/SELinux ( 3047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3047 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
E/SELinux ( 3047): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/audio_hw_primary(  283): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  283): audio_extn_get_parameters: returns 
V/msm8974_platform(  283): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  283): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  283): key: 'call_forwarding' value: ''
V/InCall  ( 1863): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1863): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1863): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
D/CustomFrequencyManagerService( 1013): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1013): mDVFSHelper.acquire()
D/ScoverManager( 1863): serviceVersion : 16908288
D/FocusedStackFrame( 1013): Set to : 0
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
D/PhoneWindow( 1013): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1013): *FMB* installDecor flags : 25362712
D/InCall  ( 1863): InCallUtils - isCoverClosed false
I/Telecom ( 1431): ProximitySensorManager: Proximity wake lock already released
D/Launcher.HomeView( 1489): onPause
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1013): Focused application set to: xxxx
D/InputDispatcher( 1013): Focus left window: 1489
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
W/libprocessgroup( 1013): failed to open /acct/uid_10031/pid_2060/cgroup.procs: No such file or directory
D/UserAnalysis.SecureDbManager( 3016): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 3016): SecurePlaceDbHelper() 
D/UserAnalysis( 3016): Create SecureDbHelper
D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
D/InCall  ( 1863): InCallUtils - isCoverClosed false
I/InCall  ( 1863): InCallPresenter -  - InCallState = NO_CALLS
D/AndroidRuntime( 2951): Shutting down VM
I/InCall  ( 1863): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1863): InCallPresenter -  - dismissCoverDialog()...
D/TimaKeyStoreProvider( 3047): TimaSignature is unavailable
D/ActivityThread( 3047): Added TimaKeyStore provider
D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
E/BluetoothHeadset( 2727): BTStateChangeCB is registed
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/BluetoothHeadset( 2727): doBind(): CallingUid(myUserHandle) = 0
E/Zygote  ( 3065): MountEmulatedStorage()
E/Zygote  ( 3065): v2
I/libpersona( 3065): KNOX_SDCARD checking this for 10174
I/libpersona( 3065): KNOX_SDCARD not a persona
I/SELinux ( 3065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3065): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3065 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 2727): BluetoothHeadset service is binded
D/BluetoothA2dp( 2727): doBind(): CallingUid(myUserHandle) = 0
I/ActivityManager( 1013): Killing 1506:com.android.printspooler/u0a136 (adj 15): empty #31
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
V/ActivityThread( 1489): updateVisibility : ActivityRecord{18c749ac token=android.os.BinderProxy@2806e0e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
W/libprocessgroup( 1013): failed to open /acct/uid_10050/pid_2107/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10113/pid_2122/cgroup.procs: No such file or directory
I/InCall  ( 1863): CallSContextMotion - stopPutDownListening
D/InCall  ( 1863): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
D/PhoneStatusBarView( 1172): setCallBackground:0
D/TimaKeyStoreProvider( 3065): TimaSignature is unavailable
D/ActivityThread( 3065): Added TimaKeyStore provider
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1863): InCallUtils - isCoverClosed false
V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1013): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Launcher.HomeView( 1489): onStop
D/Launcher( 1489): onTrimMemory. Level: 20
V/ActivityThread( 1489): updateVisibility : ActivityRecord{18c749ac token=android.os.BinderProxy@2806e0e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1013): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1013): [SO] activate (ident=0xb81e5da8, enabled=0)
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/BluetoothAdapter( 2727): 119761263: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2727): 119761263: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2727): 119761263: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2727): 119761263: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2727): 119761263: getState() :  mService = null. Returning STATE_OFF
D/SensorManager( 1013): unregisterListener ::   
I/Sensors ( 1013): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1013): [SO] changed settle time [1]
D/SensorService( 1013): [SO] setDelay [66000000]
D/SensorService( 1013): [SO] activate (ident=0xb81e5da8, enabled=1)
D/SensorService( 1013): [SO] AR_init
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1013): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/IntelligenceServiceApplication( 3016): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 3016): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3081): MountEmulatedStorage()
E/Zygote  ( 3081): v2
I/libpersona( 3081): KNOX_SDCARD checking this for 10060
I/libpersona( 3081): KNOX_SDCARD not a persona
I/SELinux ( 3081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3081 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2265:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
I/SELinux ( 3081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3092): MountEmulatedStorage()
I/libpersona( 3092): KNOX_SDCARD checking this for 10009
E/Zygote  ( 3092): v2
I/libpersona( 3092): KNOX_SDCARD not a persona
I/SELinux ( 3092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/SensorService( 1013): [SO] Reset Rotation Old [100], Init [1]
I/ActivityManager( 1013): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3092 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_POLICYDM( 2970): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/SELinux ( 3092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3092): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/art     ( 2951): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/VideoCallManager( 1863): Instantiating VideoCallManager
D/TimaKeyStoreProvider( 3081): TimaSignature is unavailable
D/ActivityThread( 3081): Added TimaKeyStore provider
E/        ( 1863): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1863): took 2.717604ms for 0*0 texture 0
I/DBG_POLICYDM( 2970): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/GFX generate_partition_tables( 1863): took 5.675002ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 3092): TimaSignature is unavailable
,D/ActivityThread( 3092): Added TimaKeyStore provider
,I/WebViewFactory( 3065): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/GFX raster( 1863): took 13.174220ms for 176*144 texture 0
I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1863): Bitmap=0xb7cac6c8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7cabf98 counterpartCT=4 counterpartW=176 counterparth=144
,I/DBG_POLICYDM( 2970): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,E/        ( 1863): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1863): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1863): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1863): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1863): Local Branch: 
I/Adreno-EGL( 1863): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1863): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1863):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SensorService( 1013): [SO] 0.172 0.115 10.228
,D/SensorService( 1013): [SO] [100 -> 255]
,I/LibraryLoader( 3065): Time to load native libraries: 2 ms (timestamps 2844-2846)
I/LibraryLoader( 3065): Expected native library version number "",actual native library version number ""
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 2970): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/GFX GPU raster( 1863): eglCreateImageKHR: EGL_SUCCESS
,I/DBG_POLICYDM( 2970): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 2970): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 2970): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 2970): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/glCompressedTexImage2D( 1863): took 0.643489ms for 320*61440 texture 37809
,W/libprocessgroup( 1013): failed to open /acct/uid_10136/pid_1506/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10044/pid_2265/cgroup.procs: No such file or directory
,V/WebViewChromiumFactoryProvider( 3065): Binding Chromium to main looper Looper (main, tid 1) {2cfd2831}
,I/LibraryLoader( 3065): Expected native library version number "",actual native library version number ""
,I/chromium( 3065): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/draw setup( 1863): took 12.677240ms for 320*240 texture 37809
E/GFX GPU raster( 1863): drawn
,I/GFX GPU raster ASTC( 1863): took 49.456721ms for 320*240 texture 12
I/GFX raster( 1863): took 49.546251ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1863): Bitmap=0xb7cac648 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7cac1b0 counterpartCT=4 counterpartW=320 counterparth=240
,E/        ( 1863): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1863): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1863): took 0.293437ms for 480*122880 texture 37813
I/draw setup( 1863): took 0.735365ms for 480*640 texture 37813
E/GFX GPU raster( 1863): drawn
D/SensorService( 1013): [SO] 0.172 0.096 10.228
I/GFX GPU raster ASTC( 1863): took 6.987239ms for 480*640 texture 12
I/GFX raster( 1863): took 7.055364ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1863): Bitmap=0xb7cac1b0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7ed9860 counterpartCT=4 counterpartW=480 counterparth=640
I/BrowserStartupController( 3065): Initializing chromium process, singleProcess=true
W/art     ( 3065): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3065): ApplicationContext is null in ApplicationStatus
D/IntelligenceServiceApplication( 3016): no applications having user consent for prediction
D/Finsky  ( 2906): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/chromium( 3065): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3065): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3065): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3065): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3065): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3065): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3065): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3065): Local Branch: 
I/Adreno-EGL( 3065): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3065): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3065):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DBG_DM  ( 2841): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/Tethering( 1013): No numeric data
E/        ( 1863): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1863): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1863): took 0.461250ms for 440*116864 texture 37809
I/draw setup( 1863): took 1.071459ms for 440*330 texture 37809
E/GFX GPU raster( 1863): drawn
,I/GFX GPU raster ASTC( 1863): took 4.494374ms for 440*330 texture 12
I/GFX raster( 1863): took 4.585260ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1863): Bitmap=0xb7eddab8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7edde78 counterpartCT=4 counterpartW=440 counterparth=330
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2841): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,V/PlaceDetection v1.0.19 ( 3016): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2841): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 2841): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,E/Zygote  ( 3136): MountEmulatedStorage()
E/Zygote  ( 3136): v2
I/libpersona( 3136): KNOX_SDCARD checking this for 1000
I/libpersona( 3136): KNOX_SDCARD not a persona
,I/SELinux ( 3136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3136 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 2297:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3136): TimaSignature is unavailable
,D/ActivityThread( 3136): Added TimaKeyStore provider
,D/BluetoothAdapter( 3065): 975166259: getState() :  mService = null. Returning STATE_OFF
,E/        ( 1863): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1863): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1863): took 0.451875ms for 480*163840 texture 37811
,I/draw setup( 1863): took 1.051719ms for 480*640 texture 37811
E/GFX GPU raster( 1863): drawn
,I/GFX GPU raster ASTC( 1863): took 9.041771ms for 480*640 texture 12
I/GFX raster( 1863): took 9.144948ms for 480*640 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1863): Bitmap=0xb7f1d488 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7ed9618 counterpartCT=4 counterpartW=480 counterparth=640
,D/[SBeam] ( 1305): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1305): SBeamEnabler.isSBeamSupported : EXIST
,D/KnoxSetupWizardDbHelper( 3136): dbMigrationFlag : false
,V/PlaceDetection v1.0.19 ( 3016): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3016): Constructor Preference
,E/        ( 1863): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1863): took 2.171875ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1863): took 7.409323ms for 0*0 texture 0
,I/GFX raster( 1863): took 11.694999ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1863): Bitmap=0xb7edda38 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7ed7078 counterpartCT=4 counterpartW=176 counterparth=144
,I/sCloudBackupApp( 3081): sCloudBackupApp Version Info : 4.04.8.KK_APP
,D/ShortcutReceiver( 3136):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,W/libprocessgroup( 1013): failed to open /acct/uid_10142/pid_2297/cgroup.procs: No such file or directory
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
,E/Zygote  ( 3169): MountEmulatedStorage()
E/Zygote  ( 3169): v2
I/libpersona( 3169): KNOX_SDCARD checking this for 10062
I/libpersona( 3169): KNOX_SDCARD not a persona
I/SELinux ( 3169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3169 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Killing 2313:com.sec.android.app.camera/u0a139 (adj 15): empty #31
E/SELinux ( 3169): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/KnoxShortcutUtil( 3136): getIsShortcutMigrationFor_2_3_0_Done true
D/ShortcutReceiver( 3136):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3136):  shortcut migration not required 
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3183): MountEmulatedStorage()
E/Zygote  ( 3183): v2
,I/libpersona( 3183): KNOX_SDCARD checking this for 1000
I/libpersona( 3183): KNOX_SDCARD not a persona
E/        ( 1863): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/SELinux ( 3183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3183): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 1702:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/TimaKeyStoreProvider( 3169): TimaSignature is unavailable
,D/ActivityThread( 3169): Added TimaKeyStore provider
,I/GFX construct_block_size_descriptor_2d second part( 1863): took 2.689427ms for 0*0 texture 0
I/DBG_POLICYDM( 2970): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
W/art     ( 3065): Attempt to remove local handle scope entry from IRT, ignoring
I/GFX generate_partition_tables( 1863): took 6.542291ms for 0*0 texture 0
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/GFX raster( 1863): took 11.805466ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1863): Bitmap=0xb7ed70e0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7ed7268 counterpartCT=4 counterpartW=176 counterparth=144
,I/DBG_POLICYDM( 2970): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2970): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/Tethering( 1013): No numeric data
,D/ScoverManager( 1863): registerListener
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
,I/DBG_POLICYDM( 2970): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1013): registerListenerCallback : binder = android.os.BinderProxy@9b963d3, pid : 1863, uid : 1001, type : 1
,D/TimaKeyStoreProvider( 3183): TimaSignature is unavailable
,D/ActivityThread( 3183): Added TimaKeyStore provider
,I/DBG_POLICYDM( 2970): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 2970): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 27
,E/DBG_POLICYDM( 2970): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,W/libprocessgroup( 1013): failed to open /acct/uid_10139/pid_2313/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10015/pid_1702/cgroup.procs: No such file or directory
,D/InCall  ( 1863): InCallPresenter -  - Finished InCallPresenter.setUp
,W/AwContents( 3065): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 3065): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 3065): *FMB* installDecor flags : 8456448
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SystemWebViewEngine( 3065): CordovaWebView is running on device made by: samsung
,W/art     ( 3065): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3065): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager( 1013): Killing 2379:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,E/KnoxSetupWizardClient( 3183): isShipMode : 1
I/KnoxSetupWizardClient( 3183): onReceive : android.intent.action.BOOT_COMPLETED
,D/StatusChecker( 2368): onReceive : android.intent.action.BOOT_COMPLETED
I/StatusChecker( 2368): onReceive : net.mt.init : DONE
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3215): MountEmulatedStorage()
E/Zygote  ( 3215): v2
I/libpersona( 3215): KNOX_SDCARD checking this for 10116
I/libpersona( 3215): KNOX_SDCARD not a persona
,I/SELinux ( 3215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3215): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Finsky  ( 2906): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1013): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3215 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2421:com.sec.android.omc/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3215): TimaSignature is unavailable
,D/ActivityThread( 3215): Added TimaKeyStore provider
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ExternalOEMControlProvider( 3169): onCreate
,E/Zygote  ( 3232): MountEmulatedStorage(),
,E/Zygote  ( 3232): v2,
I/libpersona( 3232): KNOX_SDCARD checking this for 1000
I/libpersona( 3232): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3232 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Killing 2463:com.wsomacp/u0a25 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 2454:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #32
I/ActivityManager( 1013): Killing 2437:com.sec.modem.settings/1000 (adj 15): empty #33
,I/SELinux ( 3232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3232): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/VibratorService( 1013): hasVibrator - useVibetonz: true
,W/NotificationAccessSettings( 1305): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3232): TimaSignature is unavailable
,D/ActivityThread( 3232): Added TimaKeyStore provider
,D/OpenGLRenderer( 3065): Render dirty regions requested: true
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,I/ActivityManager( 1013): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3249 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2480:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,E/Zygote  ( 3249): MountEmulatedStorage()
I/libpersona( 3249): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3249): v2
I/libpersona( 3249): KNOX_SDCARD not a persona
,I/SELinux ( 3249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,W/chromium( 3065): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/ResourcesManager( 1305): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SettingsProvider( 1013): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10062
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/PhoneWindow( 3065): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3065): *FMB* isFloatingMenuEnabled return false
,D/TimaKeyStoreProvider( 3249): TimaSignature is unavailable
,D/ActivityThread( 3249): Added TimaKeyStore provider
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 19366(1030KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 4.603ms total 163.089ms
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,I/PageBuddyNotiSvc( 3215): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 3249): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ContextImpl( 3215): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 3215): onCreate mCpBitFlag=0
,D/InputDispatcher( 1013): Focus entered window: 3065
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3065): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3065): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3065): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3065): Enabling debug mode 0
,W/System.err( 3183): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3183): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3183): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3183): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3183): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3183): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3183): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2480/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2379/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2421/cgroup.procs: No such file or directory
,E/Zygote  ( 3268): MountEmulatedStorage()
E/Zygote  ( 3268): v2
I/libpersona( 3268): KNOX_SDCARD checking this for 10125
I/libpersona( 3268): KNOX_SDCARD not a persona
,I/SELinux ( 3268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1013): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3268 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1013): failed to open /acct/uid_10025/pid_2463/cgroup.procs: No such file or directory
,I/SELinux ( 3268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SELinux ( 3268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2437/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10131/pid_2454/cgroup.procs: No such file or directory
,I/art     (  307): Explicit concurrent mark sweep GC freed 8756(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 20.303ms
,D/TimaKeyStoreProvider( 3268): TimaSignature is unavailable
,D/ActivityThread( 3268): Added TimaKeyStore provider
,I/ServiceMode( 3249): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3249): setReferenceIsDumpState : 0
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 17.194ms
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3268): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3268): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3268): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.735ms
,E/Zygote  ( 3285): MountEmulatedStorage()
,E/Zygote  ( 3285): v2
,I/libpersona( 3285): KNOX_SDCARD checking this for 1000
I/libpersona( 3285): KNOX_SDCARD not a persona
,I/SELinux ( 3285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3285): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3285 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_FMMDM( 3232): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/TimaKeyStoreProvider( 3285): TimaSignature is unavailable
D/ActivityThread( 3285): Added TimaKeyStore provider
,I/DBG_FMMDM( 3232): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
I/DBG_FMMDM( 3232): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3232): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3300): MountEmulatedStorage()
E/Zygote  ( 3300): v2
I/libpersona( 3300): KNOX_SDCARD checking this for 1000
I/libpersona( 3300): KNOX_SDCARD not a persona
I/SELinux ( 3300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3300 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3300): TimaSignature is unavailable
,D/ActivityThread( 3300): Added TimaKeyStore provider
,D/QuickConnect( 3268): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3268): Util.setSCRunningSetting - [value]0
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/SettingsProvider( 1013): name = scon_is_running
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10125
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1013): Displayed Component not be shown by security: +1s198ms
,D/CustomFrequencyManagerService( 1013): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1013): mDVFSHelper.release()
I/Timeline( 1013): Timeline: Activity_windows_visible id: ActivityRecord{104dbd76 u0 com.example.hello/.MainActivity t228} time:33798
,D/CustomFrequencyManagerService( 1013): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/PanelView( 1172): There is/are notification(s) 
,D/NPS_WSSNPS( 3285): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3285): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,I/SamsungIME( 1752): getCurrentCandidateView
,D/NPS_WSSNPS( 3285): [] Service onCreate!!
,I/PCWCLIENTTRACE_LOG( 3300): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3300): DEFAULT_LOGLEVEL : 3
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3300): new DMDBOpenHelper instance
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/Timeline( 3065): Timeline: Activity_idle id: android.os.BinderProxy@1eeb74dd time:33823
,W/Settings( 2906): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2906): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Zygote  ( 3318): MountEmulatedStorage()
E/Zygote  ( 3318): v2
I/libpersona( 3318): KNOX_SDCARD checking this for 1000
I/libpersona( 3318): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3318 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NPS_WSSNPS( 3285): [] NpsServiceTask Start
,D/TimaKeyStoreProvider( 3318): TimaSignature is unavailable
,D/ActivityThread( 3318): Added TimaKeyStore provider
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1013): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10062
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/ScoverManager( 1305): serviceVersion : 16908288
,D/Volley  ( 2906): [366] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1013): Killing 2544:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/Volley  ( 2906): [373] DiskBasedCache.clear: Cache cleared.
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 3285): [50.150321] smlDBHelper
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,D/PCWCLIENTTRACE_DMContentProvider( 3300): [URIMatcher] - result : 2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,I/NPS_WSSNPS( 3285): [50.150321] AsyncBulkFlagCheck
,I/DBG_FMMDM( 3232): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,D/SettingsProvider( 1013): name = access_control_enabled
I/DBG_FMMDM( 3232): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3232): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3285): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3285): [50.150321] IsRemain_Asyncing nothing
,W/ContextImpl( 3285): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,E/Zygote  ( 3343): MountEmulatedStorage()
,E/Zygote  ( 3343): v2
I/libpersona( 3343): KNOX_SDCARD checking this for 1000
I/libpersona( 3343): KNOX_SDCARD not a persona
,I/SELinux ( 3343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1013): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3343 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2529:com.android.calendar/u0a135 (adj 15): empty #31
,I/SELinux ( 3343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3354): MountEmulatedStorage()
,E/Zygote  ( 3354): v2
I/libpersona( 3354): KNOX_SDCARD checking this for 10069
I/libpersona( 3354): KNOX_SDCARD not a persona
,I/SELinux ( 3354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1013): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3354 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3354): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 3343): TimaSignature is unavailable
I/ActivityManager( 1013): Killing 2588:com.android.keychain/1000 (adj 15): empty #31
,D/ActivityThread( 3343): Added TimaKeyStore provider
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3285): [50.150321] Service onDestroy
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,D/SamsungIME( 1752): Dismiss ExpandCandiate
,I/DBG_DM  ( 2841): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/NPS_WSSNPS( 3285): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3285): [50.150321] smlBRMessageDelete
V/GLSUser ( 1667): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,I/NPS_WSSNPS( 3285): [50.150321] smlBREmailDelete
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
I/ActivityManager( 1013): Killing 2648:flipboard.boxer.app/u0a99 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,I/NPS_WSSNPS( 3285): [50.150321] smlBRNetworkDelete
,D/TimaKeyStoreProvider( 3354): TimaSignature is unavailable
I/QuickConnect( 3268): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityThread( 3354): Added TimaKeyStore provider
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/QuickConnect( 3268): PeriphStartReceiver.onReceive - no need to start
,I/NPS_WSSNPS( 3285): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3285): [50.150321] smlBRMiniDiaryDelete
I/SamsungIME( 1752): getDebugLevel  : 0x4f4c
,D/CustomFrequencyManagerService( 1013): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  tag : ACTIVITY_RESUME_BOOSTER@11
,I/NPS_WSSNPS( 3285): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3285): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3285): [50.150321] cpuBooster release : false
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/Finsky  ( 2906): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2906): [1] 2.run: Finished loading 1 libraries.
,I/NotificationStore( 1667): System rebooted after Notification storage file was last written,
I/NotificationStore( 1667): Deleting the file
I/libpersona( 3375): KNOX_SDCARD checking this for 10131
E/Zygote  ( 3375): MountEmulatedStorage()
I/libpersona( 3375): KNOX_SDCARD not a persona
E/Zygote  ( 3375): v2
,I/SELinux ( 3375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3375 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2177:flipboard.app/u0a98 (adj 15): empty #31
,E/SELinux ( 3375): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2544/cgroup.procs: No such file or directory
,I/FactoryTestApp( 2563): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2793)  
,D/NPS_WSSNPS( 3285): [50.150321] dsServerSocket close
,I/ActivityManager( 1013): Killing 2681:com.sec.usbsettings/1000 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 2335:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3375): TimaSignature is unavailable
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityThread( 3375): Added TimaKeyStore provider
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/BindingManager( 3065): Cannot call determinedVisibility() - never saw a connection for the pid: 3065
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_FMMDS( 3343): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FileShare-Server( 3354): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/DBG_FMMDS( 3343): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,V/GmsCoreStatsServiceLauncher( 1905): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3375): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3375): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3375): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3375): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/chromium( 3065): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/PCWCLIENTTRACE_DMContentProvider( 3300): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3343): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
D/Finsky  ( 2906): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 28
,D/CountryDetector( 1013): No listener is left
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/PersistentNotificationBroadcastReceiver( 1667): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/SBrowserFeatureFlag( 3375): initialized in static block : loadCscFeatureValue() succeed! 
,I/DBG_FMMDS( 3343): [50.18.150420][Line:43][xdbDBInit] 
,D/ManifestProvider( 3375): onCreate()
,I/SamsungIME( 1752): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1752): KeybaordView init() : load resources
,D/Finsky  ( 2906): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/NetworkSettingsReceiver( 3375): onReceive: android.intent.action.BOOT_COMPLETED
,D/JsMessageQueue( 3065): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup( 1013): failed to open /acct/uid_10135/pid_2529/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2588/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10099/pid_2648/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2681/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10098/pid_2177/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10046/pid_2335/cgroup.procs: No such file or directory
,I/LockPatternUtils( 1305): isSmartCardAuthenticationAvailable: false
,E/AndroidProtocolHandler( 3065): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Settings_Utils( 1305): isSupportVNFestival SM-A500FU XEO
,E/SBrowserFeatureFlag( 3375): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3a1fdb33
,D/SBrowserFeatureFlag( 3375): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 3375): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3407): MountEmulatedStorage()
E/Zygote  ( 3407): v2
I/libpersona( 3407): KNOX_SDCARD checking this for 10135
I/libpersona( 3407): KNOX_SDCARD not a persona
,I/SELinux ( 3407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3407 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2742:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,I/SELinux ( 3407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3407): TimaSignature is unavailable
,D/ActivityThread( 3407): Added TimaKeyStore provider
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1752): getCurrentKeyboard
I/SamsungIME( 1752): getTextKeyboard
,D/SamsungIME( 1752): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ResourcesManager( 3407): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3407): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3407): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1013): failed to open /acct/uid_10048/pid_2742/cgroup.procs: No such file or directory
,I/DBG_FMMDS( 3343): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,V/Finsky  ( 2906): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/DBG_FMMDS( 3343): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3343): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3343): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3343): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3343): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3343): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ActivityManager( 1013): Killing 1567:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/jxcore_app_log( 3065): JniHelper::setJavaVM(0xb7907450), pthread_self() = -1209626472
,D/JX-Cordova( 3065): jxcore cordova android initializing
,I/FOTA_Client( 3092): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1013): failed to open /acct/uid_10072/pid_1567/cgroup.procs: No such file or directory
,W/jxcore-log( 3065): Initializing JXcore engine
W/jxcore-log( 3065): JXcore engine is ready
,W/jxcore-log( 3065): Starting JXcore engine
,W/FOTA_Client( 3092): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,E/Zygote  ( 3435): MountEmulatedStorage(),
,E/Zygote  ( 3435): v2
I/libpersona( 3435): KNOX_SDCARD checking this for 10014
,I/libpersona( 3435): KNOX_SDCARD not a persona
,I/SELinux ( 3435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3435): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3435 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2671:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3447): MountEmulatedStorage()
,E/Zygote  ( 3447): v2
I/libpersona( 3447): KNOX_SDCARD checking this for 10042
I/libpersona( 3447): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 3435): TimaSignature is unavailable
,I/SELinux ( 3447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3447 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3447): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3435): Added TimaKeyStore provider
E/audit   ( 1823): type=1400 msg=audit(1448306437.456:203): avc:  denied  { ioctl } for  pid=3065 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1823):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1823): type=1300 msg=audit(1448306437.456:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bea2ad58 items=0 ppid=307 ppcomm=main pid=3065 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1823): type=1320 msg=audit(1448306437.456:203): 
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 3463): MountEmulatedStorage()
,E/Zygote  ( 3463): v2
I/libpersona( 3463): KNOX_SDCARD checking this for 10139
I/libpersona( 3463): KNOX_SDCARD not a persona
,I/SELinux ( 3463): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1013): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3463 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 3463): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3463): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3447): TimaSignature is unavailable
,D/ActivityThread( 3447): Added TimaKeyStore provider
,I/ActivityManager( 1013): Killing 2769:com.sec.dsm.system/1000 (adj 15): empty #31
,D/FileApkUtils( 1905): Spent 58ms computing apk sha1.
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
D/FileApkUtils( 1905): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1905): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 1905): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1905): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 1905): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1905): Primary ABI of odexing process is armeabi-v7a
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1013): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3484): MountEmulatedStorage()
,E/Zygote  ( 3484): v2
I/libpersona( 3484): KNOX_SDCARD checking this for 1000
I/libpersona( 3484): KNOX_SDCARD not a persona
,I/SELinux ( 3484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1905): Background partial concurrent mark sweep GC freed 6355(713KB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 10MB/16MB, paused 21.928ms total 123.543ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 8774(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 709us total 22.152ms
,D/TimaKeyStoreProvider( 3463): TimaSignature is unavailable
,D/ActivityThread( 3463): Added TimaKeyStore provider
,I/dex2oat ( 3482): ----------------------------------------------------
I/dex2oat ( 3482): <SS>: S T A R T I N G . . .
I/dex2oat ( 3482): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3482): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 735us total 19.282ms
W/InstanceID/Rpc( 1905): Found 10012
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 18.286ms
,D/TimaKeyStoreProvider( 3484): TimaSignature is unavailable
,D/ActivityThread( 3484): Added TimaKeyStore provider
,W/jxcore-log( 3065): Platform android
W/jxcore-log( 3065): 
,W/jxcore-log( 3065): Process ARCH arm
W/jxcore-log( 3065): 
W/ResourcesManager( 3463): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3463): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3463): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3463): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3463): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 2841): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,I/ActivityManager( 1013): Killing 2806:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,I/jxcore-log( 3065): JXcore Cordova bridge is ready!
I/jxcore-log( 3065): 
,W/jxcore-log( 3065): JXcore engine is started
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3447): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/jxcore-log( 3065): >> samsung-SM-A500FU
E/jxcore-log( 3065): 
,I/jxcore-log( 3065): Total memory 1983787008
I/jxcore-log( 3065): 
,I/jxcore-log( 3065): Free memory 113393664
I/jxcore-log( 3065): 
,I/jxcore-log( 3065): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3065): 
I/jxcore-log( 3065): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3065): 
,E/Zygote  ( 3507): MountEmulatedStorage(),
,I/jxcore-log( 3065): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3065): 
,E/Zygote  ( 3507): v2,
I/libpersona( 3507): KNOX_SDCARD checking this for 10145
I/libpersona( 3507): KNOX_SDCARD not a persona
,I/jxcore-log( 3065): Size 720 1280
I/jxcore-log( 3065): 
,I/SELinux ( 3507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3507 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/jxcore-log( 3065): Screen Brightness 5
I/jxcore-log( 3065): 
E/jxcore-log( 3065): Dummy Error Log.
E/jxcore-log( 3065): 
,V/OneTimeInitializerReceiver( 3435): OneTimeInitializerReceiver.onReceive
I/SELinux ( 3507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,W/ContextImpl( 3484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/TimaKeyStoreProvider( 3507): TimaSignature is unavailable
,D/ActivityThread( 3507): Added TimaKeyStore provider
,I/CalendarProvider2( 3447): CalendarProvider2.onCreate() called
,V/OneTimeService( 3435): OneTimeService.onHandleIntent
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/libprocessgroup( 1013): failed to open /acct/uid_10085/pid_2671/cgroup.procs: No such file or directory
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 29
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2769/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2806/cgroup.procs: No such file or directory
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
I/libpersona( 3526): KNOX_SDCARD checking this for 10015,
E/Zygote  ( 3526): MountEmulatedStorage()
I/libpersona( 3526): KNOX_SDCARD not a persona
E/Zygote  ( 3526): v2,
I/SELinux ( 3526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3526): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3507): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 1013): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3526 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
W/ResourcesManager( 3507): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3541): MountEmulatedStorage()
E/Zygote  ( 3541): v2
I/libpersona( 3541): KNOX_SDCARD checking this for 1000
I/libpersona( 3541): KNOX_SDCARD not a persona
,I/SELinux ( 3541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1013): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3541 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3541): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 3526): TimaSignature is unavailable
,D/ActivityThread( 3526): Added TimaKeyStore provider
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1905): COMPAT: Multi user not supported
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3541): TimaSignature is unavailable
,D/ActivityThread( 3541): Added TimaKeyStore provider
,I/ActivityManager( 1013): Killing 2823:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,I/CheckinService( 1905): Disabling old GoogleServicesFramework version
,D/GCM     ( 1667): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1905): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1905): onCreate
,W/ResourcesManager( 3541): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/SystemUpdateService( 1905): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1667): onCreate
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4192, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/ConfigFetchService( 1905): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,I/LockPatternUtils( 1305): isSmartCardAuthenticationAvailable: false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1172): Cable  true --> true mBootCompleted : true
,D/PowerUI ( 1172): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/AuthZen ( 1905): Handling intent: android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/AuthZenEventHandler( 1905): Handling event: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 3065): getBuffer is called!!!!
I/jxcore-log( 3065): 
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2823/cgroup.procs: No such file or directory
,D/TimaService( 1013): TIMA: in getTimaVersion
,D/TimaService( 1013): TIMA3: KeyStore3_init
,D/TimaService( 1013): TIMA: in getTimaVersion
,E/TLC_TZ_KEYSTORE: ( 1013): Inside TZ_KEYSTORE_initialize()
,I/TLC_TZ_KEYSTORE: ( 1013): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1013): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1013): root = /firmware/image, root_strlen = 15
,I/TLC_TZ_KEYSTORE: ( 1013): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1013): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1013): process = tima_key, process_strlen = 8
,I/TZ: qc_tlc_communication( 1013): aligned max_sendmsg_size = 1088 = 0x440
,I/TZ: qc_tlc_communication( 1013): aligned max_recvmsg_size = 1088 = 0x440
,I/TZ: qc_tlc_communication( 1013): max_message_size = 2176 = 0x880
,D/QSEECOMAPI: ( 1013): QSEECom_get_handle sb_length = 0x880
,D/QSEECOMAPI: ( 1013): App is not loaded in QSEE
,I/GCoreUlr( 1694): DispatchingService.onCreate()
,D/QSEECOMAPI: ( 1013): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1013): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1013): ctx = 0xb7de6f10, comm = 0xb7f866d8, sendmsg = 0xa05df000, recvmsg = 0xa05df440
I/TZ_init: ( 1013): TZ_init: sending initialization request...
,E/TZ_init: ( 1013): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1013): trustlet initialization failed
I/TZ_init: ( 1013): TZ_init_START...
,I/TZ_init: ( 1013): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1013): TZ_init: successful initialization
D/QSEECOMAPI: ( 1013): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1013): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1013): Count : 1, Ret : 0
,I/SystemUpdateService( 1905): cancelUpdate (empty URL)
,I/SystemUpdateService( 1905): active receiver: disabled
,D/ChimeraCfgMgr( 1905): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,I/CheckinService( 1905): Checking schedule, now: 1448306438660 next: 1448792533386
I/CheckinService( 1905): active receiver: disabled
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/DBG_DM  ( 2841): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3596 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3596): MountEmulatedStorage()
E/Zygote  ( 3596): v2
I/libpersona( 3596): KNOX_SDCARD checking this for 1000
I/libpersona( 3596): KNOX_SDCARD not a persona
,I/SELinux ( 3596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3596): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1905): Using Auth Proxy for data requests.
,I/GLSUser ( 1905): [ChannelManager] Attempting to channel bind connection HttpClient.
,D/FactoryTestApp( 2563): [DummyFtClient$onDestroy](2563) Destroy DummyFtClient service
,D/TimaKeyStoreProvider( 3596): TimaSignature is unavailable
,D/ActivityThread( 3596): Added TimaKeyStore provider
,D/FactoryTestApp( 2563): [Support$Values.getString](2563) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2563): [ModuleCommon$isConnectionModeNone](2563) mConnectionMode = gsm
I/FactoryTestApp( 2563): [ModuleCommon$isRunningFtClient](2563) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2563): [DummyFtClient$onDestroy](2563) kill process
I/Process ( 2563): Sending signal. PID: 2563 SIG: 9
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 26568(1500KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 2.331ms total 198.083ms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 30
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ConfigFetchService( 1905): service connected
,W/ContextImpl( 3541): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,I/GLSUser ( 1905): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/ChimeraCfgMgr( 1905): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/USB_UICC(  297): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  297): usb_uicc_init_qmi failed ! 
I/USB_UICC(  297): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  297): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3627): MountEmulatedStorage(),
E/Zygote  ( 3627): v2
,I/libpersona( 3627): KNOX_SDCARD checking this for 1000
I/libpersona( 3627): KNOX_SDCARD not a persona
I/SELinux ( 3627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3627 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3484): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3484): Resource data:2131165186
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3484): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3484): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,I/ActivityManager( 1013): Process com.sec.factory (pid 2563)(adj 0) has died(62,1095)
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3627): TimaSignature is unavailable
,I/dex2oat ( 3482): dex2oat took 1.546s (threads: 4)
,D/ActivityThread( 3627): Added TimaKeyStore provider
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DexOptUtils( 1905): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
D/DexOptUtils( 1905): Set odex to world readable.
,D/DexOptUtils( 1905): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,D/FileApkUtils( 1905): Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,I/Hs20UtilService( 3596): onCreate
,I/AMMetaDataParserService( 3484): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,I/AuthZen ( 1905): Fetching signing key...
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/Kids    ( 1905): [KidAccountFixer] No network connection
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/Hs20UtilService( 3596): Starting #1
,I/Hs20UtilService( 3596): Message received 5003
,W/ResourcesManager( 3627): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/Zygote  ( 3655): MountEmulatedStorage()
,E/Zygote  ( 3655): v2
I/libpersona( 3655): KNOX_SDCARD checking this for 10019
I/libpersona( 3655): KNOX_SDCARD not a persona
,I/SELinux ( 3655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3655 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 3627): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,E/Zygote  ( 3664): MountEmulatedStorage()
I/libpersona( 3664): KNOX_SDCARD checking this for 10104
E/Zygote  ( 3664): v2
I/libpersona( 3664): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3664 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 3664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 23714(1371KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 10MB/16MB, paused 1.002ms total 50.665ms
I/SELinux ( 3664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3664): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/SQLiteConnectionPool( 1667): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/TimaKeyStoreProvider( 3655): TimaSignature is unavailable
,D/ActivityThread( 3655): Added TimaKeyStore provider
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3484): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/F_PHONE ( 3627): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3627): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/AuthZen ( 1905): Signing key fetched successfully!
,D/TimaKeyStoreProvider( 3664): TimaSignature is unavailable
,D/ActivityThread( 3664): Added TimaKeyStore provider
,W/BaseAppContext( 1905): Using Auth Proxy for data requests.
,D/GmsModuleFndr( 1905): Beginning GMS chimera module scan
,I/AMMetaDataParserService( 3484): Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
W/ContextImpl( 3484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
D/GmsModuleFndr( 1905): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1905): Beginning module configuration check
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
I/AuthZen ( 1905): Starting Enrollment...
D/ChimeraCfgMgr( 1905): Module APKs unchanged, check complete
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3695): MountEmulatedStorage()
E/Zygote  ( 3695): v2
I/libpersona( 3695): KNOX_SDCARD checking this for 1000
I/libpersona( 3695): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3695 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 3664): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/SystemUpdateService( 1905): onDestroy
,D/AuthZen ( 1905): getting auth token. Attempt 0
,D/ConfigFetchService( 1905): ConfigApi connection successful.
,D/TimaKeyStoreProvider( 3695): TimaSignature is unavailable
,D/ActivityThread( 3695): Added TimaKeyStore provider
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,W/SEAMService( 1013):  hashset_to_int_array returning null
,D/F_PHONE ( 3627): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3627): default registerAction()
I/F_PHONE ( 3627): [[com.sec.bcservice]] sendPendingMessage()
,I/KLMS-2.5.183: ( 3655): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Nov 23 20:20:39 GMT+01:00 2015
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131034113
,I/GLSActivity( 1667): [ac] getting account id
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3484): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3484): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,I/GCoreUlr( 1694): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.183: ( 3655): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/SEAMService( 1013):  hashset_to_int_array returning null
,E/SQLiteLog( 3541): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3541): (284) automatic index on seams_container_info(sp_id)
,W/ResourcesManager( 3695): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/SEAMService( 1013):  hashset_to_int_array returning null
,I/KLMS-2.5.183: ( 3655): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3655): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 3715): MountEmulatedStorage(),
I/libpersona( 3715): KNOX_SDCARD checking this for 10022
E/Zygote  ( 3715): v2
I/libpersona( 3715): KNOX_SDCARD not a persona
,I/GLSUser ( 1667): [ChannelManager] Attempting to channel bind connection HttpClient.
I/SELinux ( 3715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/GLSUser ( 1667): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
E/SELinux ( 3715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3655): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3655): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/ActivityManager( 1013): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3715 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3655): KLMSIntentService(): BOOT_COMPLETED
,D/BluetoothBDAdrressReceiver( 3695): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3695): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,I/GLSUser ( 1667): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3715): TimaSignature is unavailable
,D/ActivityThread( 3715): Added TimaKeyStore provider
,W/ResourcesManager( 1460): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 3731): MountEmulatedStorage()
E/Zygote  ( 3731): v2
I/libpersona( 3731): KNOX_SDCARD checking this for 1000
I/libpersona( 3731): KNOX_SDCARD not a persona
,D/BluetoothBDTestService( 1460): onCreate()
,I/SELinux ( 3731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3731 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 3731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3731): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GFX construct_block_size_descriptor_2d second part( 3484): took 2.328073ms for 0*0 texture 0
,E/BluetoothBDTestService( 1460): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1460): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1460): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 12155(730KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 1.218ms total 214.084ms
,I/GFX generate_partition_tables( 3484): took 6.285884ms for 0*0 texture 0
,W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,I/GFX raster( 3484): took 9.948332ms for 96*96 texture 0
W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdac38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7cdaff0 counterpartCT=4 counterpartW=96 counterparth=96
I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/KLMS-2.5.183: ( 3655): KLMSIntentService(): onDestroy()
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1013): Killing 2855:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3731): TimaSignature is unavailable
,D/ActivityThread( 3731): Added TimaKeyStore provider
,I/SettingSearch/SearchIntentReceiver( 1305): InitSerachDBThread thread end!
,I/AMMetaDataParserService( 3484): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3731): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/RlzPingService( 3526): Setting next ping for 1448911239669
,I/ActivityManager( 1013): Killing 2884:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,E/AuthZen ( 1905): Error getting auth token
E/AuthZen ( 1905): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 1905): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1905): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1905): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AuthZen ( 1905): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1905): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1905): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1905): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1905): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.819948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdac38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ce3088 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3484): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/Zygote  ( 3752): MountEmulatedStorage()
E/Zygote  ( 3752): v2
I/libpersona( 3752): KNOX_SDCARD checking this for 1000
I/libpersona( 3752): KNOX_SDCARD not a persona
,I/SELinux ( 3752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1013): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3752 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2872:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/SELinux ( 3752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  307): Explicit concurrent mark sweep GC freed 8789(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 23.787ms
,I/DBG_DM  ( 2841): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,I/ActivityManager( 1013): Killing 2934:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.467ms
,D/a       ( 1905): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 1905): Initialized cache in: /data/data/com.google.android.gms/files
,D/TimaKeyStoreProvider( 3752): TimaSignature is unavailable
,D/ActivityThread( 3752): Added TimaKeyStore provider
,D/AuthZenTransactionCache( 1905): Clearing transaction cache
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 20.091ms
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3484): took 2.407867ms for 0*0 texture 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,I/KnoxUsageLogPro( 3731): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 3731): premStatus:2
,I/GFX generate_partition_tables( 3484): took 7.608541ms for 0*0 texture 0
,I/GFX raster( 3484): took 10.907189ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdfd18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cdfe70 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KnoxUsageLogPro( 3731): savePreference: key = previous_sys_time value = 1448306439796
,I/KnoxUsageLogPro( 3731): isEulaShown : false
I/KnoxUsageLogPro( 3731): KnoxUsageReceiver onReceive : not Processible, just return
,I/AMMetaDataParserService( 3484): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/Zygote  ( 3770): MountEmulatedStorage()
I/libpersona( 3770): KNOX_SDCARD checking this for 10072
E/Zygote  ( 3770): v2
I/libpersona( 3770): KNOX_SDCARD not a persona
I/SELinux ( 3770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3770 uid=10072 gids={50072, 9997} abi=armeabi-v7a
E/SELinux ( 3770): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 2954:com.sec.factory.camera/1000 (adj 15): empty #31
,E/MTPRx   ( 3752): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedState
D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1013): mCursor = null
,V/MTPRx   ( 3752): sealedState: false
V/MTPRx   ( 3752): sealedUsbMassStorageState: false
,D/SettingsProvider( 1013): name = mtp_usb_connection_status
,D/SettingsProvider( 1013): name = media_player_mode
,D/TimaKeyStoreProvider( 3770): TimaSignature is unavailable
,D/ActivityThread( 3770): Added TimaKeyStore provider
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_10150/pid_2855/cgroup.procs: No such file or directory
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2884/cgroup.procs: No such file or directory
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/libprocessgroup( 1013): failed to open /acct/uid_10086/pid_2872/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10094/pid_2934/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2954/cgroup.procs: No such file or directory
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/SettingsProvider( 1013): name = mtp_running_status
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/BadgeProvider( 3770): onCreate
D/BadgeProvider( 3770): DatabaseHelper
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 3770): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SettingsProvider( 1013): name = media_mount_count
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = mtp_sync_alive
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/Launcher.Model( 1489): reloadBadges entered.
,D/BadgeProvider( 3770): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3770): sendNotify, [notify] : null
D/BadgeProvider( 3770): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3770): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3770): update, [UpdateCount] : 1
,D/SettingsProvider( 1013): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1013): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/Zygote  ( 3795): MountEmulatedStorage()
,I/libpersona( 3795): KNOX_SDCARD checking this for 10146
E/Zygote  ( 3795): v2
I/libpersona( 3795): KNOX_SDCARD not a persona
I/SELinux ( 3795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3795 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SELinux ( 3795): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 2970:com.policydm/1000 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 3001:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/SettingsProvider( 1013): name = mtp_open_session
,D/TimaKeyStoreProvider( 3795): TimaSignature is unavailable
,D/ActivityThread( 3795): Added TimaKeyStore provider
,I/KnoxUsageLogPro( 3731): savePreference: key = previous_elapsed_time value = 37198
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/PCWCLIENTTRACE_PushUtil( 3300): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3300): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3300): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3300): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3300): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3300): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/ResourcesManager( 3795): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2970/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10100/pid_3001/cgroup.procs: No such file or directory
,W/PCWCLIENTTRACE_PCWHandler( 3300): [ensureRegistration] - netwrok is not available. action ignored
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3813): MountEmulatedStorage()
E/Zygote  ( 3813): v2
I/libpersona( 3813): KNOX_SDCARD checking this for 10031
I/libpersona( 3813): KNOX_SDCARD not a persona
,I/SELinux ( 3813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3813 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,E/SELinux ( 3813): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 3016:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1013): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 3507): Sending signal. PID: 3507 SIG: 9
,I/GFX raster( 3484): took 0.695103ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ce3c88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce3de0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3813): TimaSignature is unavailable
,D/ActivityThread( 3813): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3484): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/CalendarProvider2( 3447): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ResourcesManager( 3813): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.833281ms for 96*96 texture 0
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ce18b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce1a10 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1013): Killing 3047:com.samsung.helphub/1000 (adj 15): empty #31
,W/libprocessgroup( 1013): failed to open /acct/uid_10003/pid_3016/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3484): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3832): MountEmulatedStorage()
E/Zygote  ( 3832): v2
I/libpersona( 3832): KNOX_SDCARD checking this for 1000
I/libpersona( 3832): KNOX_SDCARD not a persona
,I/SELinux ( 3832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1013): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=3832 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/lowmemorykiller(  254): Error writing /proc/3507/oom_score_adj; errno=22
I/ActivityManager( 1013): Killing 3081:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/SELinux ( 3832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/GCoreUlr( 1694): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/SELinux ( 3832): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.767032ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ce3978 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cdff00 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1013): Process com.android.email (pid 3507)(adj 11) has died(57,1117)
,D/TimaKeyStoreProvider( 3832): TimaSignature is unavailable
,D/ActivityThread( 3832): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3047/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10060/pid_3081/cgroup.procs: No such file or directory
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3484): took 0.683750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdb080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cdff00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534,
,E/Zygote  ( 3851): MountEmulatedStorage(),
E/Zygote  ( 3851): v2
I/libpersona( 3851): KNOX_SDCARD checking this for 10145,
I/ActivityManager( 1013): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=3851 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/libpersona( 3851): KNOX_SDCARD not a persona
,I/SELinux ( 3851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3851): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3851): TimaSignature is unavailable,
,D/ActivityThread( 3851): Added TimaKeyStore provider
,I/ActivityManager( 1013): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=3869 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1013): Killing 3136:com.sec.knox.foldercontainer/1000 (adj 15): empty #31,
,I/Babel_SMS( 3664): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 3664): MmsConfig.loadMmsSettings
I/Babel_SMS( 3664): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 3664): MmsConfig.loadFromDatabase
,E/Zygote  ( 3869): MountEmulatedStorage()
I/libpersona( 3869): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3869): v2
I/libpersona( 3869): KNOX_SDCARD not a persona
,I/SELinux ( 3869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3869): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/VlingoApplication( 3813): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,W/ResourcesManager( 3851): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/TimaKeyStoreProvider( 3869): TimaSignature is unavailable
,I/GFX raster( 3484): took 0.531146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdff00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e8d620 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityThread( 3869): Added TimaKeyStore provider
,W/ResourcesManager( 3851): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3851): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 26530(1581KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 2.546ms total 183.091ms
,W/ResourcesManager( 3851): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecurityLogAgent:SEDenialService( 1013): Got CLOSE_WRITE Event sk.log
,W/ResourcesManager( 3851): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3484): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/SecurityLogAgent:SEDenialService( 1013): Got CLOSE_WRITE Event sk.log
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131034113
,I/AMMetaDataParserService( 3484): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3484): took 1.605052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdac38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e8ecd0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3136/cgroup.procs: No such file or directory
,E/Babel_SMS( 3664): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3664): MmsConfig.loadFromResources
,D/BluetoothAdapter( 3813): 228510728: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3813): 228510728: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3813): 228510728: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3813): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,I/GCoreUlr( 1694): Unbound from all location providers
,D/PackageManager( 1013): [MSG] MCS_UNBIND
,E/Babel_SMS( 3664): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 3664): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/ActivityManager( 1013): Killing 3169:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/AMMetaDataParserService( 3484): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/QCamera2Factory(  283): getCameraInfo: X
,I/GFX raster( 3484): took 0.849427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdac38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ca3f60 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3484): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/SecurityLogAgent( 3869): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 3869): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 3869): StateMachine : Current State = 1
D/SecurityLogAgent( 3869): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3889): MountEmulatedStorage()
E/Zygote  ( 3889): v2
I/libpersona( 3889): KNOX_SDCARD checking this for 10152
I/libpersona( 3889): KNOX_SDCARD not a persona
,I/SELinux ( 3889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3889): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=3889 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 3183:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,E/SQLiteLog( 1667): (10) POSIX Error : 11 SQLite Error : 3850
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/Settings( 3664): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GFX raster( 3484): took 0.682083ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7a15218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cc2c18 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3889): TimaSignature is unavailable
D/ActivityThread( 3889): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3484): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/Babel_Crash( 3664): startup - clean
,D/VlingoApplication( 3813): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3813): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/DialogFlow( 3813): initQueue()
,I/Babel   ( 3664): deleted: false for 0
,I/GCoreUlr( 1694): DispatchingService.onDestroy()
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GCoreUlr( 1694): Unbound from all location providers
,I/GFX raster( 3484): took 0.731562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc2b98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79667a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,W/libprocessgroup( 1013): failed to open /acct/uid_10062/pid_3169/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3183/cgroup.procs: No such file or directory
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 3889): (284) automatic index on shooting_modes(title_id)
,I/AMMetaDataParserService( 3484): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.995833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7964828 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ca3f60 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1013): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3911 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2034:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,E/Zygote  ( 3911): MountEmulatedStorage()
E/Zygote  ( 3911): v2
I/libpersona( 3911): KNOX_SDCARD checking this for 10032
I/libpersona( 3911): KNOX_SDCARD not a persona
,I/SELinux ( 3911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/SELinux ( 3911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3911): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3484): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3922): MountEmulatedStorage(),
E/Zygote  ( 3922): v2
,I/libpersona( 3922): KNOX_SDCARD checking this for 1000
I/libpersona( 3922): KNOX_SDCARD not a persona
,I/SELinux ( 3922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3922): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=3922 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.921511ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb79667a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cc2c18 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3911): TimaSignature is unavailable
,D/ActivityThread( 3911): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/DBG_DM  ( 2841): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,D/TimaKeyStoreProvider( 3922): TimaSignature is unavailable
,D/ActivityThread( 3922): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_10012/pid_2034/cgroup.procs: No such file or directory
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.922031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdb080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ca3f60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/ActivityManager( 1013): Killing 2368:com.sec.android.app.mt/1000 (adj 15): empty #31
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.656823ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc2c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ca3f60 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3484): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/Zygote  ( 3944): MountEmulatedStorage()
E/Zygote  ( 3944): v2
I/libpersona( 3944): KNOX_SDCARD checking this for 1101
I/libpersona( 3944): KNOX_SDCARD not a persona
I/SELinux ( 3944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1013): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3944 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 3232:com.fmm.dm/1000 (adj 15): empty #31
,E/SELinux ( 3944): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3484): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3484): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3484): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131034112
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3484): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3484): took 0.719115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc2b98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ca3f60 counterpartCT=4 counterpartW=96 counterparth=96
,D/BadgeProvider( 3770): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 3944): TimaSignature is unavailable
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/ActivityThread( 3944): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3484): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/Launcher.Model( 1489): reloadBadges entered.
,D/BadgeProvider( 3770): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3770): sendNotify, [notify] : null
D/BadgeProvider( 3770): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3770): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3770): update, [UpdateCount] : 1
,W/ActivityManager( 1013): getTasks: caller 10146 does not hold GET_TASKS; limiting output
W/ResourcesManager( 3944): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
I/Process ( 3795): Sending signal. PID: 3795 SIG: 9
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3484): took 0.739583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc2b98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ca3f60 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2368/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3232/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,I/AMMetaDataParserService( 3484): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,W/VideoCapabilities( 3664): Unrecognized profile 2130706433 for video/avc
,V/SmartcardService( 3944): main Received broadcast
V/SmartcardService( 3944): Starting smartcard service after boot completed
,D/ActivityManager( 1013): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,W/AudioCapabilities( 3664): Unsupported mime audio/evrc
,I/ActivityManager( 1013): Killing 3249:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,W/AudioCapabilities( 3664): Unsupported mime audio/qcelp
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/AudioCapabilities( 3664): Unsupported mime audio/mpeg-L1
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
,I/GFX raster( 3484): took 0.719115ms for 96*96 texture 0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ca3f60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ca5eb0 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3484): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/AudioCapabilities( 3664): Unsupported mime audio/mpeg-L2,
,W/AudioCapabilities( 3664): Unsupported mime audio/x-ms-wma,
,W/AudioCapabilities( 3664): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3664): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3664): Unsupported mime audio/evrc
,E/Zygote  ( 3965): MountEmulatedStorage()
,E/Zygote  ( 3965): v2
I/libpersona( 3965): KNOX_SDCARD checking this for 1000
I/libpersona( 3965): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=3965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SELinux ( 3965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/GFX raster( 3484): took 0.632917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb79667a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ca5eb0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 3965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,E/SELinux ( 3965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/art     (  307): Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 26.724ms
,W/VideoCapabilities( 3664): Unsupported mime video/wvc1
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataPar,serService( 3484): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131034113
W/VideoCapabilities( 3664): Unsupported mime video/x-ms-wmv
D/TimaKeyStoreProvider( 3965): TimaSignature is unavailable
I/AMMetaDataParserService( 3484): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
D/ActivityThread( 3965): Added TimaKeyStore provider
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3484): took 0.870157ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdac38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ca5eb0 counterpartCT=4 counterpartW=96 counterparth=96
W/VideoCapabilities( 3664): Unrecognized profile/level 32768/2 for video/mp4v-es
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 16.781ms
W/VideoCapabilities( 3664): Unsupported mime video/wvc1
W/VideoCapabilities( 3664): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 3664): Unsupported mime video/x-ms-wmv7
I/AMMetaDataParserService( 3484): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/VideoCapabilities( 3664): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 3664): Unsupported mime video/mp43
W/VideoCapabilities( 3664): Unsupported mime video/sorenson
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.522ms
W/VideoCapabilities( 3664): Unsupported mime video/mp4v-esdp
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3484): took 0.821718ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdac38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ccf200 counterpartCT=4 counterpartW=96 counterparth=96
,V/AlarmManager( 1013): waitForAlarm result :4
E/Zygote  ( 3980): MountEmulatedStorage()
E/Zygote  ( 3980): v2
I/libpersona( 3980): KNOX_SDCARD checking this for 10033
I/AMMetaDataParserService( 3484): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
I/libpersona( 3980): KNOX_SDCARD not a persona
,I/SELinux ( 3980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3980): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3980 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3268:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,I/ActivityManager( 1013): Process com.android.exchange (pid 3795)(adj 15) has died(44,1122)
,D/TimaKeyStoreProvider( 3980): TimaSignature is unavailable
,D/ActivityThread( 3980): Added TimaKeyStore provider
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.730989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7a15218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce3f30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ContextImpl( 3965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,I/VideoCapabilities( 3664): Unsupported profile 4 for video/mp4v-es
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3996): MountEmulatedStorage(),
I/libpersona( 3996): KNOX_SDCARD checking this for 10157
E/Zygote  ( 3996): v2
I/libpersona( 3996): KNOX_SDCARD not a persona,
I/SELinux ( 3996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3996 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3249/cgroup.procs: No such file or directory
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.641719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc2b98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce3f30 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1013): failed to open /acct/uid_10125/pid_3268/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3484): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/TimaKeyStoreProvider( 3996): TimaSignature is unavailable
,D/ActivityThread( 3996): Added TimaKeyStore provider
,W/ResourcesManager( 3996): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3664): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3664): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3664): Unrecognized profile 2130706433 for video/avc
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.827708ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7964828 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce3f30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/VideoCapabilities( 3664): Unrecognized profile 2130706433 for video/avc
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3980): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3980): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3980): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 4013): MountEmulatedStorage()
,E/Zygote  ( 4013): v2
I/libpersona( 4013): KNOX_SDCARD checking this for 10159
I/libpersona( 4013): KNOX_SDCARD not a persona
,I/SELinux ( 4013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 4013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/GFX raster( 3484): took 0.629635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb79667a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce3f30 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 4013): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4013 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3980): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3980): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/vclib   ( 3664): onServiceConnected
,W/Babel   ( 3664): Attempted to change video mute state without an active call.
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/GFX raster( 3484): took 0.693750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdb080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce3f30 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3980): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3980): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3980): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4013): TimaSignature is unavailable
,D/ActivityThread( 4013): Added TimaKeyStore provider
E/Zygote  ( 4029): MountEmulatedStorage()
E/Zygote  ( 4029): v2
I/libpersona( 4029): KNOX_SDCARD checking this for 10035
I/libpersona( 4029): KNOX_SDCARD not a persona
I/SELinux ( 4029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/SELinux ( 4029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4029 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4029): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 3285:com.wssnps/1000 (adj 15): empty #31
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.533281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc2c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce13f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4029): TimaSignature is unavailable
,D/ActivityThread( 4029): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/Intent to TravelDirActivity( 4013): inside TravelBroadcastReceiver
,I/ActivityManager( 1013): Killing 3318:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484,): Resource data:2131165203
W/ResourcesManager( 3484): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3484): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3484): took 2.842605ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3484): took 10.490888ms for 0*0 texture 0
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3285/cgroup.procs: No such file or directory
,I/GFX raster( 3484): took 14.470159ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ca2150 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7ca2028 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3318/cgroup.procs: No such file or directory
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 1.086616ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7e8fd28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e8fd60 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 4029): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4029): [PushClientApplication] Push log off : This is Ship build version
,W/ProcessCpuTracker( 1013): Skipping unknown process pid 3318
,I/AMMetaDataParserService( 3484): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/SPPClientService( 4029): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
,E/SPPClientService( 4029): [SystemStateMoniter] Current Time : 38904
,D/SPPClientService( 4029): PushLog.txt file is not deleted.
D/SPPClientService( 4029): PushLog.txt file is not deleted.
D/SPPClientService( 4029): ============PushLog. stop!
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.836041ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7e8fd28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ca2028 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4057): MountEmulatedStorage(),
E/Zygote  ( 4057): v2
I/libpersona( 4057): KNOX_SDCARD checking this for 10166
I/libpersona( 4057): KNOX_SDCARD not a persona
,I/SELinux ( 4057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3484): took 0.988542ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7e8fd28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7cbee30 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1013): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4057 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 3343:com.fmm.ds/1000 (adj 15): empty #31
,I/SELinux ( 4057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4057): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4057): TimaSignature is unavailable
,D/ActivityThread( 4057): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3484): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.714948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cbee30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cbf0e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/System.out( 3813): INFO:Resource not found:/Common.properties Using default values
,I/AMMetaDataParserService( 3484): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3343/cgroup.procs: No such file or directory
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 1.259739ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cbee30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce1778 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/Process ( 3980): Sending signal. PID: 3980 SIG: 9
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
W/ContextImpl( 3484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131099648
,W/ResourcesManager( 3484): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3484): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.712865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cda990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cda288 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/ActivityManager( 1013): Process com.sec.android.app.sns3 (pid 3980)(adj 0) has died(35,1135)
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4073): MountEmulatedStorage()
,E/Zygote  ( 4073): v2
I/libpersona( 4073): KNOX_SDCARD checking this for 10034
I/libpersona( 4073): KNOX_SDCARD not a persona
,I/SELinux ( 4073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/DBG_DM  ( 2841): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec,
,I/SELinux ( 4073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4073): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1013): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4073 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX construct_block_size_descriptor_2d second part( 3484): took 2.451822ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3484): took 8.612344ms for 0*0 texture 0
I/GFX raster( 3484): took 11.990208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7cc4bd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4073): TimaSignature is unavailable
,D/ActivityThread( 4073): Added TimaKeyStore provider
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.651250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb81ea0b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb81ea1f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourcesManager( 4057): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4057): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SQLiteLog( 1667): (10) POSIX Error : 11 SQLite Error : 3850
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.672709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb81ed6c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81ed800 counterpartCT=4 counterpartW=96 counterparth=96
,V/JNIHelp ( 4057): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/AMMetaDataParserService( 3484): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4093): MountEmulatedStorage(),
,I/libpersona( 4093): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4093): v2
,I/libpersona( 4093): KNOX_SDCARD not a persona
I/SELinux ( 4093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1013): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 3354:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4093): TimaSignature is unavailable
,D/ActivityThread( 4093): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_10069/pid_3354/cgroup.procs: No such file or directory
,W/ActivityThread( 4057): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4057): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36d61162: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4057): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 3911): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3911): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3911): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 4093): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4093): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4093): [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourcesManager( 3911): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/GFX raster( 3484): took 0.631041ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ccdef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cce028 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.802656ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cce210 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cce348 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131099648
,I/AMMetaDataParserService( 3484): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.689584ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cda990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb803af90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.629739ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7cc5c80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.623646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb81ea0b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7cc6cf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.644062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb81ed6c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7cc7d50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.642031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ccdef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cc8da0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.761717ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cce210 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cc8da0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131099648
,I/AMMetaDataParserService( 3484): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.823802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cda990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cca048 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.789479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7ccc168 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 1.445312ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb81ea0b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7cc7d50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
E/YouTube MDX( 4057): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/dex2oat ( 4118): ----------------------------------------------------
,I/dex2oat ( 4118): <SS>: S T A R T I N G . . .
I/dex2oat ( 4118): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4118): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1186633406.jar --oat-fd=25 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1186633406.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.694895ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb81ed6c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7cc7d50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.675990ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ccdef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cce098 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/dex2oat ( 4118): dex2oat took 41.946ms (threads: 4)
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.984375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cce210 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cc3640 counterpartCT=4 counterpartW=96 counterparth=96
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/AMMetaDataParserService( 3484): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ContextImpl( 4057): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131099648
I/AMMetaDataParserService( 3484): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3484): took 0.915728ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cda990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c836b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 4093): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 4093): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4093): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 1.295625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7c836b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_POLICYDM( 4093): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/DBG_POLICYDM( 4093): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/GFX raster( 3484): took 0.662083ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb81ea0b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7c836b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4093): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4093): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4093): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 4093): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4093): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/AMMetaDataParserService( 3484): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_POLICYDM( 4093): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4093): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4093): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.643385ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb81ed6c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c836b8 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4093): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4093): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4093): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,I/AMMetaDataParserService( 3484): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4142): MountEmulatedStorage(),
I/libpersona( 4142): KNOX_SDCARD checking this for 10041
E/Zygote  ( 4142): v2
I/libpersona( 4142): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4142 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1013): Killing 3375:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,I/SELinux ( 4142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4142): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/SSRM:n  ( 1013): SIOP:: AP = 410
,I/GFX raster( 3484): took 0.650209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ccdef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c836b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4142): TimaSignature is unavailable
,D/ActivityThread( 4142): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4093): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4093): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 4093): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 4093): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 2841): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,W/libprocessgroup( 1013): failed to open /acct/uid_10131/pid_3375/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4057): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/BluetoothAdapter( 3065): disable()
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,E/BluetoothManagerService( 1013): Bluetooth is already disabled. DO NOT disable again.
,W/ContextImpl( 4057): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4057): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider( 1013): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1013): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1013): mCursor = null
,W/InstanceID/Rpc( 4057): Found 10012
,I/SA      ( 4142): [SSP] onCreated
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.736042ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ce13f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ce3f30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4057): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/WifiService( 1013): setWifiEnabled: false pid=3065, uid=10174
,D/SettingsProvider( 1013): name = wifi_on
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131099648
,I/AMMetaDataParserService( 3484): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,I/jxcore-log( 3065): ****TEST TOOK:  5133  ms ****
I/jxcore-log( 3065): 
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/jxcore-log( 3065): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3065): 
,I/GFX raster( 3484): took 0.696979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc23c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb795ae18 counterpartCT=4 counterpartW=96 counterparth=96
E/SMD     (  288): DCD OFF
I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.631042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdf780 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7ca4db0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4142): [TPM] There is no property file
,I/SA      ( 4142): [SCU] isHaveSA() - false
,I/AMMetaDataParserService( 3484): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SA      ( 4142): [TPM] getModelProperty : null
I/SA      ( 4142): [TPM] getCSCProperty : null
,I/SA      ( 4142): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4142): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4142): [DM] TFT FEATURE: false
,I/SA      ( 4142): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4142): [DM] init START
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3484): took 0.611823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ce4a28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7964828 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SA      ( 4142): [DM] This device is not a Vodafone,
,W/ResourceType( 4142): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4142): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4142): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4142): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ResourceType( 4142): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4142): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4142): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourceType( 4142): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4142): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
I/GFX raster( 3484): took 0.838698ms for 96*96 texture 0
W/ResourceType( 4142): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb79032d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81edc00 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourceType( 4142): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4142): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4142): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/AMMetaDataParserService( 3484): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SA      ( 4142): [SCU] isHaveSA() - false
I/SA      ( 4142): support phone number id : false
I/SA      ( 4142): [DM] Supports Ref Jpn : true
,I/SA      ( 4142): [DM] init END
,I/SA      ( 4142): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 4142): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
I/GFX raster( 3484): took 0.749636ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ccdef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cd57b8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4142): [OR] onReceive END
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4142): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4142): [ODM] queryOpenData(key= GEO_IP )
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.728698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ce13f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ca4db0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4142): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4142): [LBE] REF_JPN : true
I/SA      ( 4142): [BDC] create
I/AMMetaDataParserService( 3484): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131099648
,I/AMMetaDataParserService( 3484): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3484): took 0.695521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cc23c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cda990 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SA      ( 4142): [DBMV2] getEmailID
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/SA      ( 4142): [DBMV2] getDataV02ForItems
I/SA      ( 4142): [SSP] query invoked
,I/SA      ( 4142): [SCU] get signed id from samsung account2.0 DB.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/GFX raster( 3484): took 0.624011ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7cdf780 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7cc1ce8 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 4142): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4142): [BDC] destroy
,I/ActivityManager( 1013): Killing 2983:com.google.android.gms:car/u0a12 (adj 15): empty #31
,I/AMMetaDataParserService( 3484): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4197): MountEmulatedStorage()
E/Zygote  ( 4197): v2
I/libpersona( 4197): KNOX_SDCARD checking this for 10101
I/libpersona( 4197): KNOX_SDCARD not a persona
,I/SELinux ( 4197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.651459ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ce4a28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7cc2b98 counterpartCT=4 counterpartW=96 counterparth=96,
,I/SELinux ( 4197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4197): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4197 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AMMetaDataParserService( 3484): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/TimaKeyStoreProvider( 4197): TimaSignature is unavailable
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityThread( 4197): Added TimaKeyStore provider
I/GFX raster( 3484): took 0.654115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb79032d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7964828 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3484): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/ActivityManager( 1013): Killing 2906:com.android.vending/u0a28 (adj 15): empty #31
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.727969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ccdef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb790fbd0 counterpartCT=4 counterpartW=96 counterparth=96
,D/AndroidRuntime( 4183): 
D/AndroidRuntime( 4183): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4183): CheckJNI is OFF
D/AndroidRuntime( 4183): readGMSProperty: start
D/AndroidRuntime( 4183): readGMSProperty: already setted!!
D/AndroidRuntime( 4183): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4183): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4183): readGMSProperty: end
D/AndroidRuntime( 4183): addProductProperty: start
W/ActivityManager( 1013): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3484): took 0.724219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb7ce13f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cbee30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3484): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1013): failed to open /acct/uid_10012/pid_2983/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10028/pid_2906/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
W/ContextImpl( 3484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity,
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I,/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131165197
W/ResourcesManager( 3484): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3484): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
I/AMMetaDataParserService( 3484): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
E/AffinityControl( 4183): AffinityControl: registerfunction enter
,D/AndroidRuntime( 4183): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1013): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1013): START PACKAGE DELETE: observer{380007000}
D/PackageManager( 1013): pkg{<packageName>}
D/PackageManager( 1013): user{0}
D/PackageManager( 1013): caller{2000}
D/PackageManager( 1013): flags{3}
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1013): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1013): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1013): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1013): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1013): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1013): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1013): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1013): Killing 3065:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1013): Force removing ActivityRecord{104dbd76 u0 com.example.hello/.MainActivity t228}: app died, no saved state
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/FocusedStackFrame( 1013): Set to : 0
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1013): Focused application set to: xxxx
I/AMMetaDataParserService( 3484): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
D/InputDispatcher( 1013): Focus left window: 3065
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/CustomFrequencyManagerService( 1013): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1013): mDVFSHelper.acquire()
,I/AMMetaDataParserService( 3484): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131165197
,W/PackageSettings( 1013): Skipping PackageSetting{39807ad com.test.thalitest/10175} due to missing metadata,
,I/AMMetaDataParserService( 3484): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1013): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1013): Force stopping com.example.hello appid=10174 user=0: pkg removed
,I/AMMetaDataParserService( 3484): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1013): CustomStartingWindow se packge removed so remove capture also
,I/AMMetaDataParserService( 3484): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/Launcher( 1489): onRestart, Launcher: 975166259
,D/Launcher( 1489): onStart, Launcher: 975166259
D/Launcher.HomeView( 1489): onStart
,D/Launcher( 1489): onResume, Launcher: 975166259
,D/SettingsProvider( 1013): name = kids_home_mode
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
,I/AMMetaDataParserService( 3484): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10007
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/Launcher.HomeView( 1489): onResume
,D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,V/AlarmManager( 1013): waitForAlarm result :4
,W/ResourcesManager( 1460): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,E/SamsungIME( 1752): mOCRHelper is null
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131165197
,I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
,I/AMMetaDataParserService( 3484): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,D/RegisteredComponentCache( 1445): Collect Tech packages for Knox
,D/PersonaManager( 1445): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3484): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3484): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3484): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3484): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartM,msSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 39701(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 26MB/40MB, paused 3.331ms total 171.544ms
I/art     ( 1013): WaitForGcToComplete blocked for 136.080ms for cause Explicit
,D/PackageManager( 1013): delete codoeFile: 
,D/AASAuninstall( 1013): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
I/AASA_removePackage( 1013): UID=10174 Target=com.example.hello
,D/PackageManager( 1013): result of delete: 1{380007000}
,D/AndroidRuntime( 4183): Shutting down VM
,D/PersonaManager( 1445): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1445): empty dynamic service
,D/RCPManagerService( 1013): PackageReceiver onReceive()
,I/HarmonyEASService( 1013): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1013): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/OTPFW   ( 1013): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1013): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1013): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1013): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1013): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1013): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1013): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1013): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1013): uID is 10174
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello,
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1013): removeObsoleteFile: deleting file=228_task.xml
,V/EnterpriseBillingPolicy( 1013): uID is 10174
D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
D/SSRM:aZ ( 1013): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter,
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null,
D/SensorService( 1013): [SO] activate (ident=0xb81e5da8, enabled=0)
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1013): unregisterListener ::   
I/DBG_DM  ( 2841): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/Sensors ( 1013): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1013): [SO] changed settle time [0]
D/SensorService( 1013): [SO] setDelay [200000000]
D/SensorService( 1013): [SO] activate (ident=0xb81e5da8, enabled=1)
D/SensorService( 1013): [SO] AR_init
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1013): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 8714(604KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 2.345ms total 150.138ms
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1013): mCursor = null
W/GeofencerStateMachine( 1694): Ignoring removeGeofence because network location is disabled.
,D/EnterpriseDeviceManagerService( 1013): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1013): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1013): no available spell checker services found
,D/MenuAppsGridFragment( 1489): onResume
,D/ActivityManager( 1013): handle home activity for 0
I/WallpaperManagerService( 1013): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1013): post home show event for user 0
D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
D/WallpaperManagerService( 1013):  force update = false; persona id = 0; current user =0; current persona = 0
I/AMMetaDataParserService( 3484): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3484): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131099648
D/KnoxTimeoutHandler( 1013): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ResourcesManager( 3484): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3484): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3484): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/InputDispatcher( 1013): Focus entered window: 1489
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1489): log_dcs ThreadedRenderer::initialize entered! 
,I/AMMetaDataParserService( 3484): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1013): Got RemoteException sending setActive(false) notification to pid 3065 uid 10174
,D/PanelView( 1172): There is/are notification(s) 
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/CustomFrequencyManagerService( 1013): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1013): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1013): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1013  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/SamsungIME( 1752): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/art     ( 4183): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/Gmail   ( 4197): getAccountsCursor
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0,
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.UploadsManager( 1905): End new media; added: 0, uploading: 0, time: 389 ms
,D/SensorService( 1013): [SO] Reset Rotation Old [100], Init [1]
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,W/ResourceType( 1013): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,I/AMMetaDataParserService( 3484): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3484): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3484): getResourcePackageName:assistant
I/AMMetaDataParserService( 3484): Resource data:2131165220
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 3484): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 3484): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3484): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3484): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3484): getResourceTypeNamexml
,I/ActivityManager( 1013): Displayed Component not be shown by security: +548ms
,W/ResourcesManager( 1013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/GAV2    ( 4197): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GFX raster( 3484): took 0.933646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb83ddc18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83dd948 counterpartCT=4 counterpartW=96 counterparth=96
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3484): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/SQLiteLog( 3484): (10) unixWrite() File Descriptor : 47 gets errno : 9
E/SQLiteLog( 3484): (10) unixWrite() File Descriptor : 47 gets errno : 9
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteDatabase( 3484): Error inserting actname=com.android.settings.GridSettings amicon=[B@3f192642 appname=com.android.settings id=1448306444035 amtitle=Search amstate=1 amintent=com.android.settings.Search amlabel=2131363521
E/SQLiteDatabase( 3484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
E/SQLiteDatabase( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3484): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3484): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3484): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3484): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/        ( 3484): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3484): took 0.845781ms for 96*96 texture 0
,E/SQLiteLog( 4197): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4197): (3850) statement aborts at 33: [DELETE FROM Mailbox WHERE accountKey NOT IN (SELECT _id FROM Account)] disk I/O error
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3484): Bitmap=0xb83f0060 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83f0198 counterpartCT=4 counterpartW=96 counterparth=96
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1013): clearDefaults: com.example.hello
I/AMMetaDataParserService( 3484): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
I/CrashAnrDetector( 1013): onPackageRemoved : com.example.hello
,E/SQLiteLog( 3484): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,W/GAV2    ( 4197): Thread[AsyncTask #2,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/SQLiteDatabase( 3484): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3484): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3484): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3484): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3484): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3484): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3484): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3484): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3484): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3484): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3484): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3484): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3484): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3484): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3484): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3484): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3484): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3484): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3484): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3484): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3484): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3484): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3484): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4197),: FATAL EXCEPTION: AsyncTask #2
E/AndroidRuntime( 4197): Process: com.google.android.gm, PID: 4197
E/AndroidRuntime( 4197): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4197): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 4197): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4197): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4197): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4197): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4197): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4197): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4197): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4197): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4197): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
E/AndroidRuntime( 4197): 	at com.android.email.provider.EmailProvider.a(SourceFile:519)
E/AndroidRuntime( 4197): 	at com.android.email.provider.EmailProvider.c(SourceFile:596)
E/AndroidRuntime( 4197): 	at com.android.email.provider.EmailProvider.e(SourceFile:1235)
E/AndroidRuntime( 4197): 	at com.android.email.provider.EmailProvider.a(SourceFile:425)
E/AndroidRuntime( 4197): 	at com.android.email.provider.EmailProvider.query(SourceFile:1443)
E/AndroidRuntime( 4197): 	at android.content.ContentProvider.query(ContentProvider.java:993)
E/AndroidRuntime( 4197): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/AndroidRuntime( 4197): 	at android.content.ContentResolver.query(ContentResolver.java:489)
E/AndroidRuntime( 4197): 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:64)
E/AndroidRuntime( 4197): 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:42)
E/AndroidRuntime( 4197): 	at android.content.AsyncTaskLoader.onLoadInBackground(AsyncTaskLoader.java:312)
E/AndroidRuntime( 4197): 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:69)
E/AndroidRuntime( 4197): 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:57)
E/AndroidRuntime( 4197): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 4197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4197): 	... 3 more
W/System.err( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3484): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3484): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3484): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3484): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3484): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ActivityManager( 1013): Killing 3092:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/PhoneWindow( 1013): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 1013): *FMB* installDecor flags : 8519682
E/DropBoxManagerService( 1013): Can't write: system_app_crash
E/DropBoxManagerService( 1013): java.io.FileNotFoundException: /data/system/dropbox/drop161.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1013): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1013): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1013): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1013): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1013): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1013): 	... 5 more
,I/Gmail   ( 4197): Observing account changes for notifications
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/InputDispatcher( 1013): Focus left window: 1489
D/InputDispatcher( 1013): Focus entered window: 1013
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled return false
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/SurfaceFlinger(  257): id=13 createSurf (97x97),1 flag=4, hm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/SRIB_DCS( 1013): log_dcs ThreadedRenderer::initialize entered! 

```
