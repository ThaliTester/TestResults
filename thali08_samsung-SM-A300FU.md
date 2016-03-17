#### Test 625090941eef958_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 08:35:45.459  3076  3129 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
--------- beginning of system
03-17 08:35:45.459  1018  1042 W libprocessgroup: failed to open /acct/uid_10110/pid_2333/cgroup.procs: No such file or directory
03-17 08:35:45.499   300   300 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 08:35:45.509   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-17 08:35:45.519  3076  3129 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@145dc31: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:35:45.519  3076  3129 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 08:35:45.519  3093  3093 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 08:35:45.519  1335  1335 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 08:35:45.519  1335  1335 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-17 08:35:45.519  1250  2966 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 08:35:45.519  1522  1522 D Launcher.Model: reloadBadges entered.
03-17 08:35:45.519  1610  1635 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 08:35:45.519  1610  1635 D BadgeProvider: sendNotify, [notify] : null
03-17 08:35:45.519  1610  1635 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 08:35:45.519  1610  1635 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 08:35:45.519  1610  1635 D BadgeProvider: update, [UpdateCount] : 1
03-17 08:35:45.519  3076  3129 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 08:35:45.529  2471  3009 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 08:35:45.529  1335  1335 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 08:35:45.539  1335  3137 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-17 08:35:45.539  2471  3009 D Mms/MessagingNotification: remove alarm
03-17 08:35:45.539  3093  3093 D DSM     : [Lines:107] Normal booted
03-17 08:35:45.539  3093  3093 D DSM     : [Lines:114] Boot completed
,03-17 08:35:45.539  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.539  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.539  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.539  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.549  1250  2966 V MediaScanner: processDirectory :  /storage/emulated/0
03-17 08:35:45.549  1250  2966 D MediaScanner: Skipping:
03-17 08:35:45.549  1250  2966 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-17 08:35:45.559  3139  3139 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.559  3139  3139 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:45.559  3139  3139 E Zygote  : v2
03-17 08:35:45.559  3139  3139 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:45.559  3139  3139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:45.559  1250  2966 D MediaScanner: Skipping:
03-17 08:35:45.559  1250  2966 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-17 08:35:45.559  1250  2966 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 08:35:45.559  1250  2966 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 08:35:45.559  1250  2966 W MediaScanner: 7klwibgf7fxlKdCbid7
03-17 08:35:45.569  3139  3139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:45.569  1018  1565 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 08:35:45.569  3139  3139 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:45.569  2471  3138 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 08:35:45.569  1250  2966 V MediaScanner:  prescan time: 329ms (DB items: 26)
03-17 08:35:45.569  1250  2966 V MediaScanner:     scan time: 19ms (Caching mode: true), (makeEntry time: 10ms ~52%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 08:35:45.569  1250  2966 V MediaScanner: postscan time: 6ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 08:35:45.569  1250  2966 V MediaScanner:    total time: 354ms
03-17 08:35:45.569  1250  2966 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
03-17 08:35:45.579  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.579  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.579  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.579  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.579  1495  1506 D TP/SmsProvider: query,matched:0, calling pid = 2471
03-17 08:35:45.579  1495  1506 D TP/SmsProvider: match 0:Elapsed time : 1.823 ms
03-17 08:35:45.589  3139  3139 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:45.589  3139  3139 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:45.589  3155  3155 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.589  3155  3155 E Zygote  : v2
03-17 08:35:45.589  3155  3155 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:45.589  3155  3155 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:45.589  3155  3155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:45.599  3155  3155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:45.599  1018  1537 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3155 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 08:35:45.599  1018  1537 I ActivityManager: Killing 2436:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
03-17 08:35:45.599  3155  3155 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:45.599  1250  2966 D MediaScannerService: !@done scanning volume external
03-17 08:35:45.599  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.599  1018  1030 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 08:35:45.599  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
03-17 08:35:45.599  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.599  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.599  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.599  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.619  3170  3170 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.619  3170  3170 E Zygote  : v2
03-17 08:35:45.619  3170  3170 I libpersona: KNOX_SDCARD checking this for 10088
03-17 08:35:45.619  3170  3170 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:45.619  3170  3170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:45.619  1018  1030 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3170 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 08:35:45.629  3155  3155 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:45.629  3170  3170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:45.629  3155  3155 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:45.629  3170  3170 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 08:35:45.629  1018  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.629  1018  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.629  1018  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.629  1018  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.639  3139  3139 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 08:35:45.659  3189  3189 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.659  3189  3189 E Zygote  : v2
03-17 08:35:45.659  3189  3189 I libpersona: KNOX_SDCARD checking this for 10146
03-17 08:35:45.659  3189  3189 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:45.659  1018  1447 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3189 uid=10146 gids={50146, 9997} abi=armeabi-v7a
03-17 08:35:45.659  3189  3189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:45.669  2623  2623 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2623) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:35:45.669  2623  2623 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2623) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 08:35:45.669  3189  3189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:45.669  2623  2623 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2623) ...
03-17 08:35:45.669  2623  2623 D FactoryTestApp: [Support$Values.getString](2623) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 08:35:45.669  2623  2623 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2623) mConnectionMode = gsm
03-17 08:35:45.669  3189  3189 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 08:35:45.669  2623  2623 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2623) Create IPCWriterToSecPhoneService
03-17 08:35:45.669  2623  2623 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2623)  
03-17 08:35:45.669  3170  3170 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:45.669  3170  3170 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:45.679  1018  1042 W libprocessgroup: failed to open /acct/uid_10139/pid_2436/cgroup.procs: No such file or directory
03-17 08:35:45.679  2646  2744 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 08:35:45.679  2623  2623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-17 08:35:45.679  1018  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.679  1018  1230 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.679  1018  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 08:35:45.689  3155  3155 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 08:35:45.699  2646  2744 D BluetoothMediaBrowser: no now playing list
03-17 08:35:45.699  2646  2744 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-17 08:35:45.709  2471  3009 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 706.344011
03-17 08:35:45.709  3189  3189 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:45.709  3189  3189 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:45.769  3155  3155 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 08:35:45.769  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-17 08:35:45.769  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
03-17 08:35:45.779  3155  3155 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
03-17 08:35:45.799  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 08:35:45.819  3113  3113 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
03-17 08:35:45.819  2623  2623 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2623) connected done
03-17 08:35:45.829  2623  2623 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2623) Send Response Message to SecPhone
03-17 08:35:45.829  2623  2623 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2623) Response ��
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 08:35:45.829  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 08:35:45.839  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 08:35:45.839  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 08:35:45.839  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 08:35:45.839  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 08:35:45.839  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 08:35:45.839  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 08:35:45.839  3155  3155 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 08:35:45.849  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.849  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.849  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.849  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.869   312  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 08:35:45.869  3212  3212 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.869  3212  3212 E Zygote  : v2
03-17 08:35:45.869  3212  3212 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:45.869  3212  3212 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:45.869  1018  1031 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3212 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 08:35:45.879  1018  1031 I ActivityManager: Killing 2453:com.sec.android.app.camera/u0a135 (adj 15): empty #31
03-17 08:35:45.879  3113  3113 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
03-17 08:35:45.879  3139  3139 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
03-17 08:35:45.889  3212  3212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:45.899  3212  3212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:45.899  3212  3212 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:45.899  2623  2623 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2623) Send BOOTING COMPLETED done
03-17 08:35:45.909  3113  3113 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
03-17 08:35:45.919  3212  3212 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:45.919  3212  3212 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:45.969   312  1075 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 08:35:45.969   312  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 08:35:45.969  3212  3212 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
03-17 08:35:45.989  1018  1230 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 08:35:45.989  1018  1230 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 08:35:45.989  1018  1230 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 08:35:45.989  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 08:35:45.989  1018  1018 I MotionRecognitionService: Plugged
03-17 08:35:45.989  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 08:35:45.989  1018  1042 W libprocessgroup: failed to open /acct/uid_10135/pid_2453/cgroup.procs: No such file or directory
03-17 08:35:45.999  1186  1186 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 08:35:45.999  1186  1186 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 08:35:45.999  1186  1186 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 08:35:45.999  1186  1186 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 08:35:45.999  1457  1457 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 08:35:45.999  1457  1457 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 08:35:46.009  3113  3113 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
03-17 08:35:46.009  2646  2646 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 08:35:46.009  2646  2740 D HeadsetStateMachine: Disconnected process message: 10
03-17 08:35:46.019  3139  3139 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
03-17 08:35:46.019  1186  1186 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 08:35:46.019  1186  1186 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 08:35:46.019  1186  1186 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 08:35:46.019  1186  1186 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 08:35:46.019  1186  1186 D SViewCoverView: level :100 plugged : 2
03-17 08:35:46.019  3139  3139 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
03-17 08:35:46.029  3113  3113 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
03-17 08:35:46.029  3139  3139 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
03-17 08:35:46.049   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 08:35:46.049   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 08:35:46.049  3076  3076 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-17 08:35:46.069  3113  3113 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
03-17 08:35:46.089  3139  3139 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
03-17 08:35:46.089  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
03-17 08:35:46.089  3139  3139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
03-17 08:35:46.089  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.089  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:46.089  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-17 08:35:46.099  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
03-17 08:35:46.099  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
03-17 08:35:46.099  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
03-17 08:35:46.109  3113  3113 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
03-17 08:35:46.109  1186  1186 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-17 08:35:46.109  1186  1186 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 08:35:46.109  1186  1186 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-17 08:35:46.109  1186  1186 D OverheatReceiver: isSafeMode = false
03-17 08:35:46.129  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
03-17 08:35:46.129  3139  3139 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-17 08:35:46.129  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-17 08:35:46.129  3139  3139 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-17 08:35:46.129  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-17 08:35:46.139  1495  1495 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-17 08:35:46.139  1018  1566 D SettingsProvider: name = internet_call_settings_visibility
03-17 08:35:46.139  1018  1566 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:46.139  1018  1566 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 08:35:46.139  1018  1566 D SettingsProvider: selectionArgs: false
03-17 08:35:46.139  1018  1566 D SettingsProvider: selectionArgs: 1001
03-17 08:35:46.139  1018  1566 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:46.139  1018  1566 D SettingsProvider: ret = -1
03-17 08:35:46.139  1495  1495 D PhoneUtilsCommon: isSupportVoLTE is false.
03-17 08:35:46.149  3139  3139 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-17 08:35:46.149  3113  3113 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
03-17 08:35:46.159  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-17 08:35:46.159  3139  3139 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-17 08:35:46.169  3139  3228 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
03-17 08:35:46.169  3139  3139 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-17 08:35:46.179  3139  3139 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
03-17 08:35:46.189  3139  3139 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-17 08:35:46.189  3139  3139 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-17 08:35:46.189  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
03-17 08:35:46.189  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
03-17 08:35:46.189  3139  3139 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
03-17 08:35:46.199  3212  3212 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
03-17 08:35:46.199  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.199  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:46.199  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-17 08:35:46.199  3139  3228 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
03-17 08:35:46.209  3164  3164 D AndroidRuntime: 
03-17 08:35:46.209  3164  3164 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 08:35:46.209  3139  3139 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-17 08:35:46.209  3139  3228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-17 08:35:46.219  3164  3164 D AndroidRuntime: CheckJNI is OFF
03-17 08:35:46.219  3164  3164 D AndroidRuntime: readGMSProperty: start
03-17 08:35:46.219  3164  3164 D AndroidRuntime: readGMSProperty: already setted!!
03-17 08:35:46.219  3164  3164 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 08:35:46.219  3164  3164 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 08:35:46.219  3164  3164 D AndroidRuntime: readGMSProperty: end
03-17 08:35:46.219  3164  3164 D AndroidRuntime: addProductProperty: start
03-17 08:35:46.219  3113  3113 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
03-17 08:35:46.219  1018  1537 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.219  3212  3212 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
03-17 08:35:46.219  1018  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:46.219  1018  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-17 08:35:46.219  1472  1472 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
03-17 08:35:46.219  3212  3212 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
03-17 08:35:46.219  3212  3212 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 08:35:46.219  3212  3212 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-17 08:35:46.219  3212  3212 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-17 08:35:46.229  3139  3139 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
03-17 08:35:46.229  1018  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.229  1018  1230 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:46.229  1018  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-17 08:35:46.239  1018  1566 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.239  1018  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:46.239  1018  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-17 08:35:46.249  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.249  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.249  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.249  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.269  3245  3245 E Zygote  : MountEmulatedStorage()
03-17 08:35:46.269  1018  1030 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3245 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-17 08:35:46.269  3245  3245 E Zygote  : v2
03-17 08:35:46.269  3245  3245 I libpersona: KNOX_SDCARD checking this for 10052
03-17 08:35:46.269  3245  3245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:46.269  3245  3245 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:46.269  3245  3245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:46.269  3245  3245 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 08:35:46.279  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 08:35:46.279  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 08:35:46.279  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:46.279  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:46.279  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:46.279  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:46.279  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.279  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.279  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.279  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.299  3270  3270 E Zygote  : MountEmulatedStorage()
03-17 08:35:46.299  3270  3270 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:46.299  3270  3270 E Zygote  : v2
03-17 08:35:46.299  3270  3270 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:46.299  3245  3245 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:46.299  3245  3245 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:46.299  3270  3270 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:46.309  1018  1079 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3270 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 08:35:46.309  3270  3270 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:46.309  3270  3270 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:46.309  1018  1537 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.309  1018  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:46.309  1018  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-17 08:35:46.309  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.309  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.309  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.309  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.329  3281  3281 E Zygote  : MountEmulatedStorage()
03-17 08:35:46.329  3281  3281 I libpersona: KNOX_SDCARD checking this for 10090
03-17 08:35:46.329  3281  3281 E Zygote  : v2
03-17 08:35:46.329  3281  3281 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:46.329  3281  3281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:46.329  1018  1569 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3281 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-17 08:35:46.339  1018  1569 I ActivityManager: Killing 1628:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-17 08:35:46.339  3281  3281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:46.339  3139  3228 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
03-17 08:35:46.339  3281  3281 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:46.359  3270  3270 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:46.359  3270  3270 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:46.369  3281  3281 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:46.369  3281  3281 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:46.369  1018  1043 I ActivityManager: Waited long enough for: ServiceRecord{1c776d67 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-17 08:35:46.379  1472  1472 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
03-17 08:35:46.419  1018  1042 W libprocessgroup: failed to open /acct/uid_10014/pid_1628/cgroup.procs: No such file or directory
03-17 08:35:46.429  1018  1521 E Tethering: No numeric data
03-17 08:35:46.429  1018  1030 E Tethering: No numeric data
03-17 08:35:46.429  1018  1566 E Tethering: No numeric data
03-17 08:35:46.429  3281  3281 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-17 08:35:46.429  1018  1447 E Tethering: No numeric data
03-17 08:35:46.429  3281  3281 D elm:15121: ELMEngine.ELMEngine( context ).
03-17 08:35:46.439  1018  1520 E Tethering: No numeric data
03-17 08:35:46.439  3281  3281 D elm:15121: MDMBridge.setEnterpriseBridge()
03-17 08:35:46.439  1018  1565 E Tethering: No numeric data
03-17 08:35:46.439  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.439  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:46.439  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-17 08:35:46.449  3281  3281 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-17 08:35:46.459  3281  3281 D elm:15121: ElmAgentService : onCreate()
03-17 08:35:46.459  3281  3304 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-17 08:35:46.459  3281  3281 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 08:35:46.459  3281  3281 D elm:15121: BootCompletedState : startBootCompleted() call
03-17 08:35:46.469  3281  3281 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-17 08:35:46.489  3139  3228 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
03-17 08:35:46.499   300   300 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 08:35:46.499  1457  1457 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
03-17 08:35:46.509  3076  3076 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 08:35:46.509   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-17 08:35:46.519  3281  3281 I elm:15121: Get License : 0
03-17 08:35:46.519  3281  3281 D elm:15121: ElmAgentService : onDestroy().
03-17 08:35:46.519  1018  1566 I ActivityManager: Killing 2507:com.sec.modem.settings/1000 (adj 15): empty #31
03-17 08:35:46.529  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.539  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.539  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.539  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.539  3270  3270 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
03-17 08:35:46.549  3270  3270 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 08:35:46.549  3320  3320 E Zygote  : MountEmulatedStorage()
03-17 08:35:46.549  3320  3320 E Zygote  : v2
03-17 08:35:46.549  3320  3320 I libpersona: KNOX_SDCARD checking this for 10014
03-17 08:35:46.549  3320  3320 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:46.549  3320  3320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:46.549  3320  3320 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:46.549  3320  3320 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 08:35:46.559  3270  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-17 08:35:46.559  1018  1566 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3320 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
03-17 08:35:46.559  3270  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-17 08:35:46.559  1018  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.559  1018  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.559  1018  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.559  1018  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.559  3270  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-17 08:35:46.569  3270  3314 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 08:35:46.569  3270  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-17 08:35:46.579  3270  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-17 08:35:46.579  3331  3331 E Zygote  : MountEmulatedStorage()
03-17 08:35:46.579  3331  3331 I libpersona: KNOX_SDCARD checking this for 10008
03-17 08:35:46.579  3331  3331 E Zygote  : v2
03-17 08:35:46.579  3331  3331 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:46.579  3270  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-17 08:35:46.579  3331  3331 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:46.579  3331  3331 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:46.579  3139  3228 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-17 08:35:46.589  3331  3331 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 08:35:46.589  1018  1520 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3331 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 08:35:46.589  3139  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-17 08:35:46.599   300   300 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 08:35:46.599   300   300 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 08:35:46.599   300   300 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 08:35:46.599   300   300 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-17 08:35:46.599  3320  3320 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:46.599  3320  3320 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:46.609  3270  3314 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
03-17 08:35:46.619  3331  3331 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:46.619  3331  3331 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:46.639  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2507/cgroup.procs: No such file or directory
03-17 08:35:46.639  3139  3228 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
03-17 08:35:46.639  3270  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-17 08:35:46.649  3270  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-17 08:35:46.649  3270  3270 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-17 08:35:46.649  3270  3270 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-17 08:35:46.649  3270  3270 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
03-17 08:35:46.659  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-17 08:35:46.669  1018  1230 D LocationManagerService: getProviders()=[passive]
03-17 08:35:46.669  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-17 08:35:46.679  1018  1565 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-17 08:35:46.679  1018  1566 I AudioService: getStreamVolume 3 index 0
03-17 08:35:46.709  2646  2726 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
03-17 08:35:46.719  3245  3366 I ContactAccountLoggerTas: canRun() : Opted Out
03-17 08:35:46.719  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.719  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:46.719  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-17 08:35:46.719  1335  3137 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
03-17 08:35:46.719  1335  3137 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
03-17 08:35:46.729  3113  3257 I System.out: Thread-399(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-17 08:35:46.729   287   287 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-17 08:35:46.739   287   287 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 08:35:46.739   287   287 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 08:35:46.739   287   287 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 08:35:46.739   287   287 I str_params: key: 'call_forwarding' value: ''
03-17 08:35:46.739  1968  1968 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 08:35:46.739  1968  1968 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-17 08:35:46.739  1968  1968 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
03-17 08:35:46.739  3113  3257 I System.out: Thread-399(ApacheHTTPLog):isSBSettingEnabled false
03-17 08:35:46.739  3113  3257 I System.out: Thread-399(ApacheHTTPLog):isShipBuild true
03-17 08:35:46.739  3113  3257 I System.out: Thread-399(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 08:35:46.739  3113  3257 I System.out: Thread-399(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 08:35:46.739  1968  1968 D ScoverManager: serviceVersion : 16908288
03-17 08:35:46.739  1018  1447 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 08:35:46.739  1968  1968 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 08:35:46.749  1472  1472 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-17 08:35:46.749  1018  1569 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 08:35:46.749  1968  1968 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 08:35:46.749  1968  1968 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
03-17 08:35:46.749  1968  1968 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-17 08:35:46.749  1968  1968 D InCall  : InCallPresenter -  - dismissCoverDialog()...
03-17 08:35:46.749   279   949 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 08:35:46.749   279   949 D Netd    : getNetworkForDns: using netid 502 for uid 10088
03-17 08:35:46.759  1018  1537 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.759  1018  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:46.759  1018  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-17 08:35:46.759  1968  1968 I InCall  : CallSContextMotion - stopPutDownListening
03-17 08:35:46.759  1968  1968 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
03-17 08:35:46.769  1018  1230 E Tethering: No numeric data
03-17 08:35:46.769  1018  1565 E Tethering: No numeric data
03-17 08:35:46.769  1018  1537 E Tethering: No numeric data
03-17 08:35:46.769  3245  3366 I Velvet.VelvetFactory: refreshing search history.
03-17 08:35:46.779  1018  1230 I ActivityManager: Killing 2530:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 08:35:46.809  1186  1186 D PhoneStatusBarView: setCallBackground:0
03-17 08:35:46.809  1018  1521 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 08:35:46.809  1968  1968 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 08:35:46.829  1018  1230 E Tethering: No numeric data
03-17 08:35:46.849  1018  1521 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-17 08:35:46.859  1968  1968 D VideoCallManager: Instantiating VideoCallManager
03-17 08:35:46.869  3164  3164 E AffinityControl: AffinityControl: registerfunction enter
03-17 08:35:46.869  1018  1537 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-17 08:35:46.869  1018  1031 I AudioService: getStreamVolume 3 index 0
03-17 08:35:46.869  3245  3245 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
03-17 08:35:46.879  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 08:35:46.879  1968  1968 I GFX construct_block_size_descriptor_2d second part: took 2.493125ms for 0*0 texture 0
03-17 08:35:46.879  3245  3245 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-17 08:35:46.879  3270  3314 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-17 08:35:46.879  3245  3245 I ContactLabelSupplier: get() : Execute runnable (UI thread)
03-17 08:35:46.879  1968  1968 I GFX generate_partition_tables: took 5.218854ms for 0*0 texture 0
03-17 08:35:46.889  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2530/cgroup.procs: No such file or directory
03-17 08:35:46.889  1968  1968 I GFX raster: took 11.621302ms for 176*144 texture 0
03-17 08:35:46.889   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 08:35:46.889  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb75349c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7534fd8 counterpartCT=4 counterpartW=176 counterparth=144
03-17 08:35:46.889   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 08:35:46.889  1018  1447 V VibratorService: hasVibrator - useVibetonz: true
03-17 08:35:46.899  3270  3314 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 08:35:46.899  3076  3076 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-17 08:35:46.899   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 08:35:46.899  3076  3076 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
03-17 08:35:46.899   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 08:35:46.899  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
03-17 08:35:46.909  1968  1968 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 08:35:46.909  1968  1968 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 08:35:46.909  1968  1968 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 08:35:46.909  1968  1968 I Adreno-EGL: Local Branch: 
03-17 08:35:46.909  1968  1968 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 08:35:46.909  1968  1968 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 08:35:46.909  1968  1968 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-17 08:35:46.909  3164  3164 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 08:35:46.909   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 08:35:46.909   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 08:35:46.909  3076  3076 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
03-17 08:35:46.919  1018  1447 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.919  1018  1447 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:46.919  1018  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-17 08:35:46.929  1018  1230 E PersonaManagerService: inState():  stateMachine is null !!
03-17 08:35:46.929  1018  1230 I PersonaManagerService: PersonaId don't exist
03-17 08:35:46.929  1018  1230 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 08:35:46.929  1968  1968 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 08:35:46.939  1335  3137 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
03-17 08:35:46.939  1018  1565 V VibratorService: hasVibrator - useVibetonz: true
03-17 08:35:46.939  1968  1968 I glCompressedTexImage2D: took 0.428177ms for 320*61440 texture 37809
03-17 08:35:46.949  1018  1230 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:35:46.949  1018  1569 V VibratorService: hasVibrator - useVibetonz: true
03-17 08:35:46.949  1968  1968 I draw setup: took 10.830938ms for 320*240 texture 37809
03-17 08:35:46.949  1968  1968 E GFX GPU raster: drawn
03-17 08:35:46.959  1968  1968 I GFX GPU raster ASTC: took 43.903856ms for 320*240 texture 12
03-17 08:35:46.959  1968  1968 I GFX raster: took 43.984845ms for 320*240 texture 0
03-17 08:35:46.959  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7533c90 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7535350 counterpartCT=4 counterpartW=320 counterparth=240
03-17 08:35:46.959  3270  3314 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
03-17 08:35:46.959  3270  3314 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
03-17 08:35:46.959  3270  3314 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
03-17 08:35:46.969  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-17 08:35:46.969  1968  1968 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 08:35:46.969  1018  1230 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 08:35:46.969  1018  1230 W ActivityManager: mDVFSHelper.acquire()
03-17 08:35:46.969  1968  1968 I glCompressedTexImage2D: took 0.380417ms for 480*122880 texture 37813
03-17 08:35:46.969  1968  1968 I draw setup: took 0.895989ms for 480*640 texture 37813
03-17 08:35:46.969  1968  1968 E GFX GPU raster: drawn
03-17 08:35:46.979  1018  1230 D FocusedStackFrame: Set to : 0
03-17 08:35:46.979  1968  1968 I GFX GPU raster ASTC: took 7.729844ms for 480*640 texture 12
03-17 08:35:46.979  1968  1968 I GFX raster: took 7.810990ms for 480*640 texture 0
03-17 08:35:46.979  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7535350 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb77765b8 counterpartCT=4 counterpartW=480 counterparth=640
03-17 08:35:46.979  1018  1230 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 08:35:46.979  1018  1230 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:35:46.979  1018  1230 D InputDispatcher: Focused application set to: xxxx
03-17 08:35:46.979  1018  1230 D InputDispatcher: Focus left window: 1522
03-17 08:35:46.979  3164  3164 D AndroidRuntime: Shutting down VM
03-17 08:35:46.979  1522  1522 D Launcher.HomeView: onPause
03-17 08:35:46.979  1522  1522 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 08:35:46.989  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.989  1457  1457 V EmergencyMode: [EmergencyBase] setBootTime
03-17 08:35:46.989  1457  1457 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
03-17 08:35:46.989  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.989  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.989  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.999  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 08:35:46.999  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 08:35:46.999  1335  3137 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 08:35:47.009  3396  3396 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.009  3396  3396 I libpersona: KNOX_SDCARD checking this for 10167
03-17 08:35:47.009  3396  3396 E Zygote  : v2
03-17 08:35:47.009  3396  3396 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:47.009  3396  3396 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:47.019  1018  1569 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3396 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 08:35:47.019  3396  3396 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:47.019  3396  3396 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 08:35:47.019  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:35:47.019  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 08:35:47.019  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 08:35:47.019  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 08:35:47.029  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
03-17 08:35:47.029  1968  1968 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 08:35:47.029  1968  1968 I glCompressedTexImage2D: took 0.385260ms for 440*116864 texture 37809
03-17 08:35:47.029  1968  1968 I draw setup: took 0.935677ms for 440*330 texture 37809
03-17 08:35:47.029  1968  1968 E GFX GPU raster: drawn
03-17 08:35:47.029  1968  1968 I GFX GPU raster ASTC: took 5.024792ms for 440*330 texture 12
03-17 08:35:47.029  1968  1968 I GFX raster: took 5.113646ms for 440*330 texture 0
03-17 08:35:47.029  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb77765b8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb778b0e0 counterpartCT=4 counterpartW=440 counterparth=330
03-17 08:35:47.039  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
03-17 08:35:47.049   307   307 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 40.849ms
03-17 08:35:47.059   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 08:35:47.059  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-17 08:35:47.059  1968  1968 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 08:35:47.059  1968  1968 I glCompressedTexImage2D: took 0.422031ms for 480*163840 texture 37811
03-17 08:35:47.059  1968  1968 I draw setup: took 0.903229ms for 480*640 texture 37811
03-17 08:35:47.059  1968  1968 E GFX GPU raster: drawn
03-17 08:35:47.069  1968  1968 I GFX GPU raster ASTC: took 5.656196ms for 480*640 texture 12
03-17 08:35:47.069  1968  1968 I GFX raster: took 5.761196ms for 480*640 texture 0
03-17 08:35:47.069  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb778b0e0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb77763a8 counterpartCT=4 counterpartW=480 counterparth=640
03-17 08:35:47.069  3396  3396 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:47.069  3396  3396 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:47.069  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
03-17 08:35:47.079   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 25.812ms
03-17 08:35:47.089  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
03-17 08:35:47.089  3270  3315 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 08:35:47.089  3270  3315 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 08:35:47.099  3270  3314 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
03-17 08:35:47.099  3270  3314 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
03-17 08:35:47.099   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 18.106ms
03-17 08:35:47.099  1018  1537 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 08:35:47.099  1018  1537 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 08:35:47.099  1018  1537 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 08:35:47.099  3270  3315 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-17 08:35:47.099  3270  3315 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-17 08:35:47.099  3270  3315 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-17 08:35:47.109  3270  3314 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
03-17 08:35:47.109  3270  3315 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-17 08:35:47.109  3270  3315 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-17 08:35:47.119  3270  3314 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/08:35:47
03-17 08:35:47.119  3270  3314 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
03-17 08:35:47.119  3270  3315 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-17 08:35:47.119  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 08:35:47.119  3270  3315 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-17 08:35:47.129  3270  3315 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
03-17 08:35:47.129  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 08:35:47.129  1968  1968 I GFX construct_block_size_descriptor_2d second part: took 2.124427ms for 0*0 texture 0
03-17 08:35:47.139  3270  3314 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
03-17 08:35:47.139  1968  1968 I GFX generate_partition_tables: took 7.499167ms for 0*0 texture 0
03-17 08:35:47.139  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.139  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.139  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.139  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.139  1968  1968 I GFX raster: took 11.566354ms for 176*144 texture 0
03-17 08:35:47.139  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb77763a8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb775fac8 counterpartCT=4 counterpartW=176 counterparth=144
03-17 08:35:47.139  1018  1048 D PersonaManager: isKioskContainerExistOnDevice
03-17 08:35:47.149  3245  3366 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
03-17 08:35:47.149  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 08:35:47.149  1335  3137 D ScoverManager: serviceVersion : 16908288
03-17 08:35:47.149  1968  1968 I GFX construct_block_size_descriptor_2d second part: took 2.471354ms for 0*0 texture 0
03-17 08:35:47.159  3417  3417 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.159  3417  3417 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:47.159  3417  3417 E Zygote  : v2
03-17 08:35:47.159  3417  3417 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:47.169  3417  3417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:47.169  3417  3417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:47.169  3417  3417 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:47.169  1018  1230 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3417 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 08:35:47.169  1968  1968 I GFX generate_partition_tables: took 6.438021ms for 0*0 texture 0
03-17 08:35:47.169  1968  1968 I GFX raster: took 11.038437ms for 176*144 texture 0
03-17 08:35:47.169  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb77664a8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7530fc8 counterpartCT=4 counterpartW=176 counterparth=144
03-17 08:35:47.179  1968  1968 D ScoverManager: registerListener
03-17 08:35:47.179  1018  1565 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 08:35:47.179  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:47.179  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:47.179  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-17 08:35:47.179  1018  1079 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 08:35:47.179  1018  1079 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@35a921fc, pid : 1968, uid : 1001, type : 1
03-17 08:35:47.179  3245  3367 W GAV2    : Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-17 08:35:47.189  3270  3290 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 08:35:47.189  1522  1522 V ActivityThread: updateVisibility : ActivityRecord{7fb13d8 token=android.os.BinderProxy@3b4f507 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 08:35:47.189  1522  1522 D Launcher.HomeView: onStop
03-17 08:35:47.189  1522  1522 V ActivityThread: updateVisibility : ActivityRecord{7fb13d8 token=android.os.BinderProxy@3b4f507 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 08:35:47.189  3270  3290 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 08:35:47.189  3245  3367 W GAV2    : Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
03-17 08:35:47.199  1522  1522 D Launcher: onTrimMemory. Level: 20
03-17 08:35:47.199  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 08:35:47.199  3164  3164 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 08:35:47.199  1018  1018 D SensorService: [SO] activate (ident=0xb7a40300, enabled=0)
03-17 08:35:47.199  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 08:35:47.199  3245  3372 I ContactAccountLoggerTas: canRun() : Opted Out
03-17 08:35:47.199  3270  3315 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
03-17 08:35:47.209  1018  1018 D SensorManager: unregisterListener ::   
03-17 08:35:47.209  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 08:35:47.209  1018  1018 D SensorService: [SO] changed settle time [1]
03-17 08:35:47.209  1018  1018 D SensorService: [SO] setDelay [66000000]
03-17 08:35:47.209  1018  1018 D SensorService: [SO] activate (ident=0xb7a40300, enabled=1)
03-17 08:35:47.209  1018  1018 D SensorService: [SO] AR_init
03-17 08:35:47.209  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 08:35:47.219  1968  1968 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 08:35:47.219  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 08:35:47.229  3245  3366 I LibraryLoader: Loading: webviewchromium
,03-17 08:35:47.239  3245  3366 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 7047-7054)
03-17 08:35:47.239  3245  3366 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 08:35:47.239  3270  3290 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 08:35:47.249  3270  3314 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 08:35:47.249  3417  3417 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:47.249  3417  3417 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.249  1018  1537 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 08:35:47.249  3270  3284 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 08:35:47.249  3270  3284 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 08:35:47.249  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.249  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.249  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.249  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.259  3270  3284 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true,
,03-17 08:35:47.269  3245  3366 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:47.269  3270  3315 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
03-17 08:35:47.269  3439  3439 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.269  3439  3439 E Zygote  : v2
03-17 08:35:47.269  3439  3439 I libpersona: KNOX_SDCARD checking this for 10055
03-17 08:35:47.269  3439  3439 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:47.269  3439  3439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:47.269  1018  1031 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3439 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-17 08:35:47.279  3439  3439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:47.279  3439  3439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:47.279  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 08:35:47.279  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 08:35:47.279  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:47.289  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-17 08:35:47.289  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:47.289  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:47.289  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:47.319  3439  3439 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.319  3439  3439 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.359  1018  1040 D SensorService: [SO] -0.460 0.192 9.864
03-17 08:35:47.359  1018  1040 D SensorService: [SO] [100 -> 255]
,03-17 08:35:47.369  1018  1625 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:47.369  1018  1625 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:47.369  3270  3314 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
03-17 08:35:47.369  1018  1625 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 08:35:47.379  3270  3314 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 08:35:47.399  3245  3367 I ContactLabelSupplier: get() : OptedIn = false
,03-17 08:35:47.399  1018  1566 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 08:35:47.409  3396  3396 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 08:35:47.439  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:47.439  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:47.439  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 08:35:47.449  3396  3396 I LibraryLoader: Loading: webviewchromium
,03-17 08:35:47.449  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:47.449  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:47.449  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 08:35:47.449  3396  3396 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7259-7265)
03-17 08:35:47.449  3396  3396 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 08:35:47.449  1018  1030 I art     : Explicit concurrent mark sweep GC freed 24290(1373KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/33MB, paused 9.805ms total 211.858ms
,03-17 08:35:47.469   292   292 E SMD     : DCD OFF
,03-17 08:35:47.469  1018  1565 I ActivityManager: Killing 2543:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,03-17 08:35:47.489  3439  3439 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 08:35:47.489  3396  3396 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19243630}
,03-17 08:35:47.489  3396  3396 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 08:35:47.489  3396  3396 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 08:35:47.489  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:47.489  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:47.489  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 08:35:47.499  1018  1537 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:47.499  1018  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:47.499  1018  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 08:35:47.499  3076  3468 W MessageQueue: Handler (android.os.Handler) {1fa9f603} sending message to a Handler on a dead thread
03-17 08:35:47.499  3076  3468 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {1fa9f603} sending message to a Handler on a dead thread
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at ffw.a(SourceFile:327)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at guw.a(SourceFile:120)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at guf.c(SourceFile:26)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at gui.run(SourceFile:297)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:35:47.499  3076  3468 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 08:35:47.499  3270  3315 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
03-17 08:35:47.499  1018  1566 I ActivityManager: Killing 2556:com.wsomacp/u0a23 (adj 15): empty #31
,03-17 08:35:47.509  1018  1566 I ActivityManager: Killing 2578:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 08:35:47.509  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.509  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.509  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.509   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-17 08:35:47.509  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.539  3396  3396 I BrowserStartupController: Initializing chromium process, renderers=0
,03-17 08:35:47.539  3396  3396 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:47.549  3270  3315 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 08:35:47.549  3476  3476 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.549  3476  3476 E Zygote  : v2
03-17 08:35:47.549  3476  3476 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:47.549  3476  3476 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:47.559  1018  1565 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3476 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:47.559  3476  3476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:47.559  3476  3476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:47.559  3476  3476 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:47.569  1018  1565 I ActivityManager: Killing 2498:com.sec.android.app.mt/1000 (adj 15): empty #31
03-17 08:35:47.569  3270  3315 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
03-17 08:35:47.569  3245  3273 W art     : Suspending all threads took: 13.623ms
03-17 08:35:47.579  1018  1230 I ActivityManager: Killing 1780:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-17 08:35:47.579  3396  3396 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
03-17 08:35:47.579  3396  3396 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
03-17 08:35:47.579  3396  3396 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
03-17 08:35:47.589  3439  3439 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-17 08:35:47.589  3439  3439 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 08:35:47.589  3439  3439 D UserAnalysis: Create SecureDbHelper
,03-17 08:35:47.599  3476  3476 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.599  3476  3476 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.599   258   446 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 08:35:47.599   258   453 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 08:35:47.609  3396  3396 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 08:35:47.609  3396  3396 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 08:35:47.609  3396  3396 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 08:35:47.609  3396  3396 I Adreno-EGL: Local Branch: 
03-17 08:35:47.609  3396  3396 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 08:35:47.609  3396  3396 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 08:35:47.609  3396  3396 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-17 08:35:47.609  3417  3417 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 08:35:47.609  3417  3417 I testFeature: Feature.Feature(context)
03-17 08:35:47.609  3417  3417 I testFeature: Feature.readInternalDefaultXml()
03-17 08:35:47.609  3417  3417 I testFeature: ResetFeatureValue
,03-17 08:35:47.619  3417  3417 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 08:35:47.619  3417  3417 I CameraApp: CameraApp.getAppFeature()...
,03-17 08:35:47.629  3439  3439 D IntelligenceServiceApplication: onCreate()
,03-17 08:35:47.629  3439  3439 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 08:35:47.639  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.639  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.639  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.639  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.649  3439  3439 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 08:35:47.649  1018  1042 W libprocessgroup: failed to open /acct/uid_10127/pid_2543/cgroup.procs: No such file or directory
03-17 08:35:47.649  3076  3471 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
03-17 08:35:47.649  3076  3471 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 08:35:47.649  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2578/cgroup.procs: No such file or directory
03-17 08:35:47.649  3076  3471 I System.out: Thread-435(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 08:35:47.649  3076  3471 I System.out: Thread-435(ApacheHTTPLog):isSBSettingEnabled false
03-17 08:35:47.649  3076  3471 I System.out: Thread-435(ApacheHTTPLog):isShipBuild true
03-17 08:35:47.649  3076  3471 I System.out: Thread-435(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 08:35:47.649  3076  3471 I System.out: Thread-435(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 08:35:47.649   279   949 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 08:35:47.649  1018  1042 W libprocessgroup: failed to open /acct/uid_10023/pid_2556/cgroup.procs: No such file or directory
03-17 08:35:47.649   279   949 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-17 08:35:47.659  1957  1957 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 08:35:47.669  3505  3505 E Zygote  : MountEmulatedStorage()
,03-17 08:35:47.669  3505  3505 E Zygote  : v2
03-17 08:35:47.669  3505  3505 I libpersona: KNOX_SDCARD checking this for 10095
03-17 08:35:47.669  3505  3505 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:47.669  3505  3505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:47.669  1018  1565 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3505 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
03-17 08:35:47.669  3505  3505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:47.669  1018  1565 I ActivityManager: Killing 2608:com.android.calendar/u0a131 (adj 15): empty #31
03-17 08:35:47.669  3505  3505 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:47.679  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.679  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.679  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.679  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.689  3139  3228 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 08:35:47.689  3505  3505 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.689  3505  3505 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.699  3523  3523 E Zygote  : MountEmulatedStorage()
,03-17 08:35:47.699  3523  3523 E Zygote  : v2
03-17 08:35:47.699  3523  3523 I libpersona: KNOX_SDCARD checking this for 10056
03-17 08:35:47.699  3523  3523 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:47.699  3523  3523 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 08:35:47.699  3523  3523 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:47.699  1018  1565 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3523 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 08:35:47.699  3523  3523 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:47.699  1335  3137 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
03-17 08:35:47.699  1018  1565 I ActivityManager: Killing 2661:com.android.keychain/1000 (adj 15): empty #31
,03-17 08:35:47.699   279   949 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 08:35:47.699   279   949 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-17 08:35:47.709  3439  3439 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 08:35:47.719  1018  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:47.719  1018  1230 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:47.719  1018  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 08:35:47.719  3476  3476 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 08:35:47.719  1957  1957 D SecUISvc: Service started flags 0 startId 1
,03-17 08:35:47.719  1957  3540 D SecUISvc: Thread created.
03-17 08:35:47.729  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.729  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.729  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.729  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.739  1335  3137 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
03-17 08:35:47.739  3523  3523 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.739  3523  3523 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.739  3544  3544 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.739  3544  3544 E Zygote  : v2
03-17 08:35:47.739  3544  3544 I libpersona: KNOX_SDCARD checking this for 10026
03-17 08:35:47.739  3544  3544 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:47.739  3544  3544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:47.739  3544  3544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:47.749  3544  3544 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 08:35:47.749  1018  1569 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3544 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 08:35:47.759  1335  3137 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-17 08:35:47.779  3544  3544 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.779  3544  3544 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.789  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_1780/cgroup.procs: No such file or directory
,03-17 08:35:47.789  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2498/cgroup.procs: No such file or directory
,03-17 08:35:47.789  1018  1042 W libprocessgroup: failed to open /acct/uid_10131/pid_2608/cgroup.procs: No such file or directory
03-17 08:35:47.789  1335  3137 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-17 08:35:47.799  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2661/cgroup.procs: No such file or directory
,03-17 08:35:47.799  3476  3476 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 08:35:47.799  3476  3476 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 08:35:47.799  3476  3476 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 08:35:47.799  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.809  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.809  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.809  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.809  3505  3505 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-17 08:35:47.819  3559  3559 E Zygote  : MountEmulatedStorage(),
03-17 08:35:47.819  3559  3559 E Zygote  : v2
03-17 08:35:47.819  3559  3559 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:47.819  3559  3559 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:47.819  1018  1030 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3559 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:47.819  3559  3559 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:47.819  3439  3439 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-17 08:35:47.819  3439  3439 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 08:35:47.819  3559  3559 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 08:35:47.829  3559  3559 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:47.839  3396  3500 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-17 08:35:47.849  3505  3505 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-17 08:35:47.849  3559  3559 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.849  3559  3559 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.859  3396  3396 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
03-17 08:35:47.859  3245  3366 I qtaguid : Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
,03-17 08:35:47.879  3505  3505 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-17 08:35:47.879  3505  3505 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-17 08:35:47.879  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.879  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.879  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.879  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.879  1018  2759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 08:35:47.909  3579  3579 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.909  3579  3579 E Zygote  : v2
03-17 08:35:47.909  3579  3579 I libpersona: KNOX_SDCARD checking this for 10098
03-17 08:35:47.909  3579  3579 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:47.909  3579  3579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:47.909  3579  3579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:47.909  3579  3579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:47.909  1018  1566 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3579 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,03-17 08:35:47.929  3579  3579 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.929  3579  3579 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.949  3559  3559 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 08:35:47.949  3559  3559 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 08:35:47.959  3559  3559 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 08:35:47.969  3544  3544 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 08:35:47.969  3559  3571 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 08:35:47.979  3579  3579 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 08:35:47.989  3579  3579 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 08:35:47.989  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.989  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.989  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.989  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.989  3396  3396 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:47.999  3396  3396 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 08:35:47.999  3601  3601 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.999  3601  3601 E Zygote  : v2
03-17 08:35:47.999  3601  3601 I libpersona: KNOX_SDCARD checking this for 10099
03-17 08:35:47.999  3601  3601 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:48.009  3601  3601 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:48.009  1018  1537 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3601 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 08:35:48.009  3601  3601 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:48.009  1018  1537 I ActivityManager: Killing 2407:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,03-17 08:35:48.009  3601  3601 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 08:35:48.009  3396  3396 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 08:35:48.009  3396  3396 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 08:35:48.019  3523  3523 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-17 08:35:48.019  3396  3396 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 08:35:48.029  3396  3396 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 08:35:48.029  3396  3396 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:48.039  3601  3601 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-17 08:35:48.039  3601  3601 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.049  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.049  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.049  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.049  1018  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.069  3621  3621 E Zygote  : MountEmulatedStorage()
,03-17 08:35:48.069  3621  3621 E Zygote  : v2
03-17 08:35:48.069  3621  3621 I libpersona: KNOX_SDCARD checking this for 10058
03-17 08:35:48.069  3621  3621 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:48.079  1018  1537 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3621 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 08:35:48.079  1018  1537 I ActivityManager: Killing 2703:com.android.chrome/u0a77 (adj 15): empty #31
,03-17 08:35:48.079  3621  3621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:48.079  3621  3621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:48.079  3621  3621 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:48.109  3621  3621 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.119  3621  3621 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.119  3396  3636 D OpenGLRenderer: Render dirty regions requested: true
,03-17 08:35:48.119  1018  2802 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:35:48.129  3476  3476 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 08:35:48.129  3476  3476 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 08:35:48.129  3476  3476 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 08:35:48.129  1018  1625 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 08:35:48.129  1018  1625 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 08:35:48.129  1018  1625 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 08:35:48.129  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 08:35:48.129  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 08:35:48.139  1018  1042 W libprocessgroup: failed to open /acct/uid_10039/pid_2407/cgroup.procs: No such file or directory
,03-17 08:35:48.139  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.139  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.139  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.139  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.139  3396  3396 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 08:35:48.139  3396  3396 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 08:35:48.149  3637  3637 E Zygote  : MountEmulatedStorage()
,03-17 08:35:48.149  3637  3637 E Zygote  : v2
03-17 08:35:48.149  3637  3637 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:48.149  3637  3637 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:48.149  1018  1030 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3637 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 08:35:48.149  3637  3637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 08:35:48.149  1018  1030 I ActivityManager: Killing 2841:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-17 08:35:48.149  1018  1030 I ActivityManager: Killing 2752:com.android.email/u0a141 (adj 15): empty #32
,03-17 08:35:48.159  3637  3637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:48.159  3637  3637 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:48.179   307   307 I art     : Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 23.942ms
,03-17 08:35:48.199   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 22.329ms
,03-17 08:35:48.199  3637  3637 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.199  3637  3637 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.219   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 657us total 16.966ms
,03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
,03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
,03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052,
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
,03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
,03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052,
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
,03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
,03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
,03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
,03-17 08:35:48.239  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
03-17 08:35:48.239  3245  3366 I qtaguid : Untagging socket 43
,03-17 08:35:48.279  1018  1042 W libprocessgroup: failed to open /acct/uid_10077/pid_2703/cgroup.procs: No such file or directory
,03-17 08:35:48.279  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2841/cgroup.procs: No such file or directory
,03-17 08:35:48.279  1018  1042 W libprocessgroup: failed to open /acct/uid_10141/pid_2752/cgroup.procs: No such file or directory
,03-17 08:35:48.329   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 08:35:48.339  1018  1569 D InputDispatcher: Focus entered window: 3396
,03-17 08:35:48.339  3637  3637 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 08:35:48.339  3637  3637 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 08:35:48.349  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:35:48.349  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 08:35:48.349  3396  3396 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 08:35:48.349  3396  3636 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 08:35:48.349  3396  3636 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-17 08:35:48.349  3396  3636 D OpenGLRenderer: Enabling debug mode 0
,03-17 08:35:48.379  1018  1569 V VibratorService: hasVibrator - useVibetonz: true
,03-17 08:35:48.389  1018  1537 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 08:35:48.399  1186  1186 I StatusBar: Icon Only
,03-17 08:35:48.399  1186  1186 D PanelView: There is/are notification(s) 
,03-17 08:35:48.409  1018  3666 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:35:48.409  3396  3396 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7e32bf time:38227
,03-17 08:35:48.489  1335  3137 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 08:35:48.509  3544  3544 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.,
,03-17 08:35:48.509  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s524ms
,03-17 08:35:48.509  1018  1048 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 08:35:48.509   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 08:35:48.509  1018  1048 W ActivityManager: mDVFSHelper.release()
,03-17 08:35:48.509  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c6bed21 u0 com.test.thalitest/.MainActivity t11} time:38329
,03-17 08:35:48.519  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 08:35:48.529  3245  3366 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3245, getuid(): 10052
,03-17 08:35:48.529  3559  3571 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 08:35:48.539  1335  1355 W art     : Suspending all threads took: 10.986ms
,03-17 08:35:48.539  3637  3637 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 08:35:48.549  3637  3637 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 08:35:48.559  3076  3471 I System.out: Thread-435 calls detatch()
,03-17 08:35:48.589  1843  1843 I SamsungIME: getCurrentCandidateView
,03-17 08:35:48.589  3621  3621 I ExternalOEMControlProvider: onCreate
,03-17 08:35:48.599  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.599  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.599  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.599  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.599  3544  3544 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 08:35:48.609  3544  3544 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 08:35:48.609  3245  3372 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 08:35:48.619  3678  3678 E Zygote  : MountEmulatedStorage(),
03-17 08:35:48.619  3678  3678 E Zygote  : v2
03-17 08:35:48.619  3678  3678 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:48.619  3678  3678 I libpersona: KNOX_SDCARD not a persona,
03-17 08:35:48.619  3678  3678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:48.619  3678  3678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:48.619  3678  3678 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:48.619  1018  1521 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3678 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:48.629  1018  1537 D SettingsProvider: name = PREVIOUS_SYS_TIME,
03-17 08:35:48.629  1018  1537 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:48.629  1018  1537 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 08:35:48.629  1018  1537 D SettingsProvider: selectionArgs: false
03-17 08:35:48.629  1018  1537 D SettingsProvider: selectionArgs: 10058
03-17 08:35:48.629  1018  1537 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:48.629  1018  1537 D SettingsProvider: ret = -1
,03-17 08:35:48.649  1018  1537 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 08:35:48.659  1018  1030 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 08:35:48.659  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:48.659  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 08:35:48.659  1018  1030 D SettingsProvider: selectionArgs: false
03-17 08:35:48.659  1018  1030 D SettingsProvider: selectionArgs: 10058
03-17 08:35:48.659  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:48.659  1018  1030 D SettingsProvider: ret = -1
,03-17 08:35:48.659  3678  3678 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.659  3678  3678 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:48.669  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:48.669  3637  3637 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 08:35:48.679  1018  1030 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 08:35:48.689  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:48.689  3139  3228 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 08:35:48.689  3678  3678 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 08:35:48.699  3113  3257 I System.out: pool-10-thread-1 calls detatch()
,03-17 08:35:48.719  1843  1843 D SamsungIME: Dismiss ExpandCandiate
,03-17 08:35:48.719  3637  3637 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 08:35:48.719  3637  3637 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 08:35:48.729  3396  3396 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-17 08:35:48.729  3637  3637 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 08:35:48.729  3637  3637 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 08:35:48.729  3637  3637 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 08:35:48.729  3637  3637 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 08:35:48.729   258  1119 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 08:35:48.729   258   446 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 08:35:48.779  3331  3331 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 08:35:48.789  3331  3331 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 08:35:48.789  1018  1030 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:35:48.789  3331  3331 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 08:35:48.799  3331  3331 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 08:35:48.809  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.809  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.809  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.809  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.819  3544  3658 D Volley  : [486] g.b: Cache cleared.
,03-17 08:35:48.819  3544  3598 D Volley  : [480] g.b: Cache cleared.,
03-17 08:35:48.819  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 08:35:48.819  3678  3678 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 08:35:48.819  3678  3678 I ServiceMode: setReferenceIsDumpState : 0
,03-17 08:35:48.819  3704  3704 E Zygote  : MountEmulatedStorage()
03-17 08:35:48.819  3704  3704 E Zygote  : v2
,03-17 08:35:48.819  3704  3704 I libpersona: KNOX_SDCARD checking this for 10013
03-17 08:35:48.819  3704  3704 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:48.819  3704  3704 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 08:35:48.829  1018  1625 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3704 uid=10013 gids={50013, 9997} abi=armeabi-v7a
03-17 08:35:48.829  3544  3703 D Ads     : Skipping gmscore version check
,03-17 08:35:48.829  1018  1625 I ActivityManager: Killing 2864:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-17 08:35:48.829  3704  3704 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:48.829  3396  3669 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-17 08:35:48.829  3396  3669 I chromium: 
03-17 08:35:48.829  3704  3704 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 08:35:48.839  1018  1625 I ActivityManager: Killing 2889:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 08:35:48.849  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.849  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.849  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.849  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.859  3704  3704 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.859  3704  3704 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.869  3720  3720 E Zygote  : MountEmulatedStorage()
03-17 08:35:48.869  3720  3720 E Zygote  : v2
03-17 08:35:48.869  3720  3720 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:48.869  3720  3720 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:48.869  3720  3720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:48.869  3720  3720 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:48.869  3720  3720 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:48.879  1018  1625 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3720 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:48.879  1018  1625 I ActivityManager: Killing 2937:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-17 08:35:48.879  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:48.879  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:48.879  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 08:35:48.899  1843  1843 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 08:35:48.899  3720  3720 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.899  3720  3720 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.899  2623  3210 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3210)  
,03-17 08:35:48.899  3544  3544 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-17 08:35:48.919  3544  3544 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 08:35:48.919  3544  3544 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 08:35:48.949  1018  1625 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:48.949  1018  1625 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:48.949  1018  1625 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:48.959  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:48.959  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:48.959  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 08:35:48.969  3396  3729 D jxcore_app_log: JniHelper::setJavaVM(0xb7179448), pthread_self() = -1216183728
,03-17 08:35:48.979  1018  1042 W libprocessgroup: failed to open /acct/uid_10153/pid_2937/cgroup.procs: No such file or directory
03-17 08:35:48.979  1018  1042 W libprocessgroup: failed to open /acct/uid_1101/pid_2889/cgroup.procs: No such file or directory
03-17 08:35:48.979  1018  1042 W libprocessgroup: failed to open /acct/uid_10097/pid_2864/cgroup.procs: No such file or directory
,03-17 08:35:48.979  3704  3704 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 08:35:48.979  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:48.979  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:48.979  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 08:35:48.989  3704  3742 V OneTimeService: OneTimeService.onHandleIntent
,03-17 08:35:48.989  3396  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 08:35:48.989  3396  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 08:35:48.989  3396  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 08:35:48.989  3396  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 08:35:48.989  3396  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 08:35:48.989  3396  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c42c49a added. We now have 1 listener(s)
,03-17 08:35:48.999  3396  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-17 08:35:48.999  3396  3729 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-17 08:35:48.999  3396  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-17 08:35:48.999  3396  3729 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 08:35:48.999  3396  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 08:35:48.999  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:48.999  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:48.999  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:49.009  1018  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.009  1018  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.009  1018  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:49.019  1018  1447 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.019  3720  3720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
03-17 08:35:49.019  3720  3720 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
03-17 08:35:49.019  1018  1447 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.019  1018  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 08:35:49.019  3396  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cc40c1 added. We now have 1 listener(s)
03-17 08:35:49.019  3396  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 08:35:49.019  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.019  1018  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.019  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 08:35:49.019  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.019  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:35:49.019  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 08:35:49.029  3396  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 08:35:49.029  3396  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 08:35:49.029  3396  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 08:35:49.029  3396  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 08:35:49.029  3396  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 08:35:49.029  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.029  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.029  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:49.039  3396  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 08:35:49.039  3720  3720 D NPS_WSSNPS: [] Service onCreate!!
,03-17 08:35:49.039  1335  3137 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 08:35:49.039  3396  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-17 08:35:49.049  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.049  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.049  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.049  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.049  3720  3749 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 08:35:49.059  3544  3544 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-17 08:35:49.059  3755  3755 E Zygote  : MountEmulatedStorage()
,03-17 08:35:49.059  3755  3755 E Zygote  : v2
03-17 08:35:49.059  3755  3755 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:49.059  3755  3755 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:49.059  3755  3755 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:49.059  3755  3755 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:49.059  1018  1079 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:49.069  3755  3755 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:49.069  1335  3137 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 08:35:49.069  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.069  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.069  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:49.079  1018  1537 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.079  1018  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.079  1018  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 08:35:49.099  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.099  3396  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 08:35:49.099  3396  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 08:35:49.099  3396  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 08:35:49.099  3396  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 08:35:49.099  3396  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 08:35:49.099  3396  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 08:35:49.099  3396  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 08:35:49.099  3396  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 08:35:49.099  3396  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 08:35:49.099  3396  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 08:35:49.099  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:49.099  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
03-17 08:35:49.099  1335  3137 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 08:35:49.099  1745  1745 I Hs20UtilService: Starting #5
03-17 08:35:49.099  1745  1774 I Hs20UtilService: Message received 5003
,03-17 08:35:49.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.109  2171  3738 D FileApkUtils: Optimizing (staging complete)
,03-17 08:35:49.109  2171  3738 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-17 08:35:49.109  2171  3738 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 08:35:49.119  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 08:35:49.119  3755  3755 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:49.119  3755  3755 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.119  3774  3774 E Zygote  : MountEmulatedStorage()
03-17 08:35:49.129  3774  3774 E Zygote  : v2
03-17 08:35:49.129  3774  3774 I libpersona: KNOX_SDCARD checking this for 10018
03-17 08:35:49.129  3774  3774 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:49.129  3396  3396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-17 08:35:49.129  1018  1031 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3774 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,03-17 08:35:49.129  3774  3774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:49.139  3774  3774 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:49.139  3774  3774 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:49.159  3396  3396 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 08:35:49.169  3720  3720 D NPS_WSSNPS: [50.150321] smlDBHelper
03-17 08:35:49.169  1018  1565 I ActivityManager: Killing 2952:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 08:35:49.179  3774  3774 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:49.179  3774  3774 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.199  3601  3753 I Gmail   : getAccountsCursor
,03-17 08:35:49.209  3544  3544 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 08:35:49.219  3601  3601 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 08:35:49.229  1018  1565 D SettingsProvider: name = access_control_enabled
,03-17 08:35:49.239  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.239  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.239  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.239  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.239  2171  3738 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,03-17 08:35:49.249  3794  3794 E Zygote  : MountEmulatedStorage(),
03-17 08:35:49.249  3794  3794 E Zygote  : v2
03-17 08:35:49.249  3794  3794 I libpersona: KNOX_SDCARD checking this for 10065
03-17 08:35:49.249  3794  3794 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:49.249  3794  3794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 08:35:49.249  3794  3794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 08:35:49.249  3794  3794 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:49.249  1018  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3794 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 08:35:49.259  1018  1031 I ActivityManager: Killing 2289:flipboard.app/u0a96 (adj 15): empty #31
,03-17 08:35:49.259  1018  1520 I ActivityManager: Killing 2880:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-17 08:35:49.289  3720  3720 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 08:35:49.299  3720  3811 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-17 08:35:49.299  3720  3811 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-17 08:35:49.299  3720  3811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 08:35:49.299  1018  1566 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.299  1018  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:49.299  1018  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 08:35:49.299  3794  3794 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:49.299  3794  3794 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.309  3774  3774 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 08:35:49 GMT+01:00 2016
,03-17 08:35:49.309  3720  3720 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 08:35:49.309  1018  1447 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.309  1018  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:49.309  1018  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 08:35:49.319  3720  3720 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-17 08:35:49.329  3720  3720 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-17 08:35:49.329  3720  3720 I NPS_WSSNPS: [50.150321] smlBREmailDelete
03-17 08:35:49.329  3720  3720 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-17 08:35:49.329  3720  3720 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-17 08:35:49.329  3720  3720 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-17 08:35:49.329  3720  3720 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
,03-17 08:35:49.329  3720  3720 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-17 08:35:49.329  3720  3720 I NPS_WSSNPS: [50.150321] cpuBooster release : false
03-17 08:35:49.349  3774  3774 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
03-17 08:35:49.349  1843  1843 I SamsungIME: getDebugLevel  : 0x4f4c
03-17 08:35:49.349  3720  3720 D NPS_WSSNPS: [50.150321] dsServerSocket close
03-17 08:35:49.359  1018  1079 I ActivityManager: Killing 1196:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-17 08:35:49.369  1018  1625 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.369  1018  1625 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.369  1018  1625 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:49.369  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.369  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.369  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.369  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.379  3774  3774 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 08:35:49.389  1843  1843 I SamsungIME: KeybaordView init() : load resources
,03-17 08:35:49.389  3814  3814 E Zygote  : MountEmulatedStorage()
03-17 08:35:49.389  3774  3774 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-17 08:35:49.389  1018  1079 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3814 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,03-17 08:35:49.389  3814  3814 E Zygote  : v2
03-17 08:35:49.389  3814  3814 I libpersona: KNOX_SDCARD checking this for 10020
03-17 08:35:49.389  3814  3814 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:49.389  1018  1521 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-17 08:35:49.389  3774  3774 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 08:35:49.389  3814  3814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:49.399  3814  3814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:49.399  3814  3814 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:49.409  1018  1521 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:35:49.409  1018  1447 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.409  1018  1447 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.409  1018  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 08:35:49.409  3774  3812 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 08:35:49.419  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.419  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.419  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 08:35:49.439  3814  3814 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:49.439  3814  3814 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.449  1018  1566 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:35:49.449  3601  3832 E Gmail   : Error finding the version of the Email provider.....
03-17 08:35:49.449  3601  3832 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 08:35:49.449  3601  3832 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 08:35:49.449  3601  3832 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-17 08:35:49.449  3601  3832 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 08:35:49.449  3601  3832 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:35:49.449  3601  3832 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:35:49.449  3601  3832 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 08:35:49.449  3601  3832 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 08:35:49.449  3601  3832 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 08:35:49.459  1843  1843 I SamsungIME: getCurrentKeyboard
03-17 08:35:49.459  1843  1843 I SamsungIME: getTextKeyboard
,03-17 08:35:49.469  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.469  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.469  3774  3812 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
03-17 08:35:49.469  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:49.469  3794  3794 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 08:35:49.479  3320  3320 I RlzPingService: Setting next ping for 1458804949478
,03-17 08:35:49.479  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.479  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.479  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 08:35:49.519  1018  1447 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.519  1018  1447 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.519  1018  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 08:35:49.529  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:35:49.529  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2952/cgroup.procs: No such file or directory
,03-17 08:35:49.529  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:35:49.529  1018  1042 W libprocessgroup: failed to open /acct/uid_10096/pid_2289/cgroup.procs: No such file or directory
,03-17 08:35:49.539  1018  1042 W libprocessgroup: failed to open /acct/uid_10081/pid_2880/cgroup.procs: No such file or directory
,03-17 08:35:49.539  1018  1042 W libprocessgroup: failed to open /acct/uid_10003/pid_1196/cgroup.procs: No such file or directory
,03-17 08:35:49.549  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:35:49.569  1018  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.569  1018  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.569  1018  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 08:35:49.599  3601  3823 I Gmail   : Observing account changes for notifications
,03-17 08:35:49.659  1642  3838 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 08:35:49.669  3601  3753 I Gmail   : getAccountsCursor
,03-17 08:35:49.669  1843  1843 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 08:35:49.689  3774  3774 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 08:35:49.689  3139  3228 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 08:35:49.749  3601  3835 E SQLiteLog: (283) recovered 82 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 08:35:49.759  1018  1521 I art     : Explicit concurrent mark sweep GC freed 22188(1169KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.870ms total 183.050ms
,03-17 08:35:49.769  1018  1625 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.769  1018  1625 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.769  1018  1625 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:49.779  1018  3760 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.779  1018  3760 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.779  1018  3760 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.779  1018  3760 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.789  3844  3844 E Zygote  : MountEmulatedStorage(),
03-17 08:35:49.799  3844  3844 I libpersona: KNOX_SDCARD checking this for 10102
03-17 08:35:49.799  3844  3844 E Zygote  : v2
03-17 08:35:49.799  3844  3844 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:49.799  3844  3844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:49.799  3844  3844 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:49.799  3844  3844 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 08:35:49.799  1018  3760 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3844 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 08:35:49.829  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.829  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.829  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:49.829  1018  1569 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:35:49.839  1018  1447 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.839  1018  1447 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:49.839  1018  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:49.849  3601  3835 E File    : fail readDirectory() errno=2
,03-17 08:35:49.849  3601  3842 I Gmail   : notifyAccountChanged
,03-17 08:35:49.859  1018  3760 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.859  1018  3760 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.859  1018  3760 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.859  1018  3760 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.859  3844  3844 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:49.859  3844  3844 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.869  3861  3861 E Zygote  : MountEmulatedStorage()
03-17 08:35:49.869  3861  3861 E Zygote  : v2
03-17 08:35:49.869  3861  3861 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:49.869  3861  3861 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:49.869  3861  3861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:49.879  3861  3861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:49.879  3861  3861 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:49.879  1018  3760 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3861 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:49.889  3601  3842 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 08:35:49.889  1018  1031 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 08:35:49.889  3396  3409 I art     : Background sticky concurrent mark sweep GC freed 34465(2MB) AllocSpace objects, 4(1038KB) LOS objects, 21% free, 9MB/12MB, paused 6.236ms total 38.089ms
,03-17 08:35:49.909  3601  3842 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 08:35:49.909  3601  3601 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@1ca7af43 that was originally bound here
03-17 08:35:49.909  3601  3601 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@1ca7af43 that was originally bound here
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:35:49.909  3601  3601 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 08:35:49.909  1018  1537 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@37d24ebd
,03-17 08:35:49.919  1018  1520 I ActivityManager: Killing 2471:com.android.mms/u0a41 (adj 15): empty #31
,03-17 08:35:49.929  3861  3861 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:49.929  3861  3861 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.939  3844  3844 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 08:35:49.959  3601  3842 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 08:35:49.959  3601  3842 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 08:35:49.959  1018  1565 I ActivityManager: Killing 2994:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,03-17 08:35:49.969  1934  1934 D ChimeraCfgMgr: Reading stored module config
,03-17 08:35:49.989  1018  1566 I ActivityManager: Killing 3010:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 08:35:50.009  3861  3861 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 08:35:50.009  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 08:35:50.009  1018  1447 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 08:35:50.009  1018  1447 D SecContentProvider2: mCursor = null
,03-17 08:35:50.009  1018  1018 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 08:35:50.009  1018  1625 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 08:35:50.009  1018  1625 D SecContentProvider2: mCursor = null
,03-17 08:35:50.009  3861  3861 V MTPRx   : sealedState: false
03-17 08:35:50.009  3861  3861 V MTPRx   : sealedUsbMassStorageState: false
,03-17 08:35:50.019  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.019  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.019  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.019  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.029  3880  3880 E Zygote  : MountEmulatedStorage()
03-17 08:35:50.029  3880  3880 E Zygote  : v2
03-17 08:35:50.029  3880  3880 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:50.029  3880  3880 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:50.029  3880  3880 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:50.029  3880  3880 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:50.029  3880  3880 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:50.039  1018  1018 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3880 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:50.049  1018  1566 D SettingsProvider: name = mtp_usb_connection_status
,03-17 08:35:50.059  1018  3760 D SettingsProvider: name = media_player_mode
,03-17 08:35:50.059  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.069  3880  3880 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.069  3880  3880 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.069  1018  1537 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 08:35:50.079  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.079  1018  3760 D SettingsProvider: name = mtp_running_status
,03-17 08:35:50.089  1018  1565 D SettingsProvider: name = media_mount_count
,03-17 08:35:50.089  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.089  1018  1566 D CountryDetector: No listener is left
,03-17 08:35:50.099  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.109  1018  1521 D SettingsProvider: name = mtp_sync_alive
,03-17 08:35:50.109  3396  3772 W jxcore-log: Initializing JXcore engine
03-17 08:35:50.109  3396  3772 W jxcore-log: JXcore engine is ready
,03-17 08:35:50.109  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.119  2171  2171 W InstanceID/Rpc: Found 10011
,03-17 08:35:50.159  1018  1042 W libprocessgroup: failed to open /acct/uid_10043/pid_2994/cgroup.procs: No such file or directory
,03-17 08:35:50.159  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3010/cgroup.procs: No such file or directory
,03-17 08:35:50.159  1018  1042 W libprocessgroup: failed to open /acct/uid_10041/pid_2471/cgroup.procs: No such file or directory
,03-17 08:35:50.169  1910  1910 E audit   : type=1400 msg=audit(1458200150.169:205): avc:  denied  { ioctl } for  pid=3772 comm="Thread-467" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 08:35:50.169  1910  1910 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:50.169  1910  1910 E audit   : type=1300 msg=audit(1458200150.169:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=91f6b8f8 items=0 ppid=307 ppcomm=main pid=3772 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-467" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 08:35:50.169  1910  1910 E audit   : type=1320 msg=audit(1458200150.169:205): 
,03-17 08:35:50.179  3396  3772 W jxcore-log: Starting JXcore engine
,03-17 08:35:50.229  1018  1030 D SettingsProvider: name = sdcard_launch
,03-17 08:35:50.229  1934  1934 D WearableService: callingUid 10011, callindPid: 1934
,03-17 08:35:50.229  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.259  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:35:50.259  1018  1566 D SettingsProvider: name = boot_time_connected
,03-17 08:35:50.269  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.289  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 08:35:50.289  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 08:35:50.289  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:50.289  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:50.289  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:50.289  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:50.299  3396  3772 W jxcore-log: Platform android
03-17 08:35:50.299  3396  3772 W jxcore-log: 
03-17 08:35:50.299  3396  3772 W jxcore-log: Process ARCH arm
03-17 08:35:50.299  3396  3772 W jxcore-log: 
,03-17 08:35:50.319  1018  1447 D SettingsProvider: name = mtp_open_session
,03-17 08:35:50.339  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,03-17 08:35:50.349  1018  1565 I ActivityManager: Killing 3028:com.google.android.configupdater/u0a82 (adj 15): empty #31
03-17 08:35:50.349  3880  3880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 08:35:50.359  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:50.359  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:50.359  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 08:35:50.359  1018  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.359  1018  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.359  1018  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.359  1018  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.359  3559  3559 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 08:35:50.369  3559  3559 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 08:35:50.369  3559  3559 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 08:35:50.369  3559  3559 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
,03-17 08:35:50.369  3559  3559 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 08:35:50.369  3559  3559 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 08:35:50.379  3904  3904 E Zygote  : MountEmulatedStorage()
03-17 08:35:50.379  3904  3904 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:50.379  3904  3904 E Zygote  : v2
03-17 08:35:50.379  3904  3904 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:50.379  3904  3904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:50.379  3904  3904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:50.379  3904  3904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 08:35:50.379  1018  1520 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3904 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:50.399   307   307 I art     : Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 23.566ms
,03-17 08:35:50.399  3559  3559 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 08:35:50.419  3904  3904 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:50.419   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 17.547ms
,03-17 08:35:50.419  3904  3904 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.439  3270  3314 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 08:35:50.439   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 19.931ms
,03-17 08:35:50.449  3904  3904 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 08:35:50.469  1018  1042 W libprocessgroup: failed to open /acct/uid_10082/pid_3028/cgroup.procs: No such file or directory
,03-17 08:35:50.469   292   292 E SMD     : DCD OFF
,03-17 08:35:50.489  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 08:35:50.489  1018  3760 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.489  3270  3314 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 08:35:50.489  1018  3760 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:35:50.489  1018  3760 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 08:35:50.489  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 08:35:50.489  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 08:35:50.499  3559  3559 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 08:35:50.499  3559  3559 I ReactiveServiceManager: Supported : 1
,03-17 08:35:50.499  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.499  1018  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:50.499  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:50.519  1018  1625 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-17 08:35:50.519  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-17 08:35:50.519  1018  1625 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 08:35:50.519  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 08:35:50.519  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 08:35:50.519  3270  3314 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 08:35:50.529  3904  3904 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 08:35:50.529  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 08:35:50.539  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.539  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.539  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.539  1018  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.549  1018  1625 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 08:35:50.549  3396  3772 I jxcore-log: JXcore Cordova bridge is ready!
03-17 08:35:50.549  3396  3772 I jxcore-log: 
,03-17 08:35:50.549  3396  3772 W jxcore-log: JXcore engine is started
,03-17 08:35:50.559  3925  3925 E Zygote  : MountEmulatedStorage()
,03-17 08:35:50.559  1018  1566 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 08:35:50.559  3925  3925 E Zygote  : v2
03-17 08:35:50.559  3925  3925 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:50.559  3925  3925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:50.559  3925  3925 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:50.559  1934  1934 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-17 08:35:50.559  3925  3925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:50.569  3925  3925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:50.569  1018  1625 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 08:35:50.569  1018  1625 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-17 08:35:50.569  1018  1625 E terrier : handleString: Failed to handle string(-4)
03-17 08:35:50.569  1018  1625 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 08:35:50.569  3396  3729 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-17 08:35:50.569  3559  3559 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 08:35:50.569  3559  3559 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 08:35:50.569  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.569  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:50.569  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 08:35:50.579  3844  3932 I Babel   : MmsConfig: mnc/mcc: 0/0
,03-17 08:35:50.579  3844  3932 I Babel   : MmsConfig.loadMmsSettings
03-17 08:35:50.579  3844  3932 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-17 08:35:50.579  3844  3932 I Babel   : MmsConfig.loadFromDatabase
,03-17 08:35:50.579  3396  3396 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 08:35:50.589  3559  3559 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 08:35:50.589  3559  3559 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 08:35:50.589  3559  3559 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 08:35:50.589  3559  3559 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 08:35:50.589  3925  3925 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:50.589  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.589  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.589  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.589  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.589  3925  3925 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.609  3944  3944 E Zygote  : MountEmulatedStorage()
03-17 08:35:50.609  3944  3944 E Zygote  : v2
03-17 08:35:50.609  3944  3944 I libpersona: KNOX_SDCARD checking this for 10028
03-17 08:35:50.609  3944  3944 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:50.609  3944  3944 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:50.609  3396  3772 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 08:35:50.609  3396  3772 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 08:35:50.609  1018  1565 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3944 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,03-17 08:35:50.619  3944  3944 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:50.619  3944  3944 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 08:35:50.629  3904  3904 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 08:35:50.629  3904  3904 I F_PHONE : default registerAction()
03-17 08:35:50.629  3904  3904 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 08:35:50.629  3396  3396 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
03-17 08:35:50.629  3396  3396 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
03-17 08:35:50.629  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.629  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:50.629  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:50.639  1018  3760 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:35:50.639  1018  3760 D FocusedStackFrame: Set to : 0
03-17 08:35:50.639  1018  3760 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 08:35:50.639  1018  3760 D InputDispatcher: Focused application set to: xxxx
03-17 08:35:50.639  1018  3760 D InputDispatcher: Focus left window: 3396
03-17 08:35:50.639  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:35:50.639  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 08:35:50.659   258   453 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (191 us)
,03-17 08:35:50.669  3925  3925 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 08:35:50.679  3944  3944 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.679  3944  3944 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.689  3396  3729 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 60ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 08:35:50.699  3139  3228 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 08:35:50.709  1018  1537 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 08:35:50.719  1018  1537 W ActivityManager: mDVFSHelper.acquire()
,03-17 08:35:50.729  1018  1537 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1,
03-17 08:35:50.729  1018  1537 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 08:35:50.729  1018  1537 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 08:35:50.729  3844  3932 E Babel   : canonicalizeMccMnc: invalid mccmnc ,
03-17 08:35:50.729  3844  3932 I Babel   : MmsConfig.loadFromResources
03-17 08:35:50.729  3844  3932 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-17 08:35:50.729  3844  3932 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-17 08:35:50.729  3925  3925 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-17 08:35:50.729  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 08:35:50.759  1522  1522 D Launcher: onRestart, Launcher: 500073820
,03-17 08:35:50.759  3844  3858 W art     : Suspending all threads took: 16.792ms
,03-17 08:35:50.769  1522  1522 D Launcher: onStart, Launcher: 500073820
03-17 08:35:50.769  1522  1522 D Launcher.HomeView: onStart
,03-17 08:35:50.769  1522  1522 D Launcher: onResume, Launcher: 500073820
,03-17 08:35:50.769  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.769  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:50.769  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
03-17 08:35:50.769  1018  1031 D SettingsProvider: name = kids_home_mode
03-17 08:35:50.769  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:50.769  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
03-17 08:35:50.769  1018  1031 D SettingsProvider: selectionArgs: false
03-17 08:35:50.769  1018  1031 D SettingsProvider: selectionArgs: 10006
03-17 08:35:50.769  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:50.769  1018  1031 D SettingsProvider: ret = -1
03-17 08:35:50.769  1522  1522 D Launcher.HomeView: onResume
,03-17 08:35:50.779  2623  2623 D FactoryTestApp: [DummyFtClient$onDestroy](2623) Destroy DummyFtClient service
,03-17 08:35:50.779  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 08:35:50.779  1018  1018 D SensorService: [SO] activate (ident=0xb7a40300, enabled=0)
,03-17 08:35:50.779  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 08:35:50.779  3844  3924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 08:35:50.789  1495  1495 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 08:35:50.789  1495  1495 D BluetoothBDTestService: onCreate()
,03-17 08:35:50.799  1495  1495 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 08:35:50.799  1495  1495 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 08:35:50.799  1018  1018 D SensorManager: unregisterListener ::   
,03-17 08:35:50.799  1495  1495 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-17 08:35:50.799  3844  3924 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 08:35:50.799  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 08:35:50.799  1018  1018 D SensorService: [SO] changed settle time [0]
,03-17 08:35:50.799  1018  1018 D SensorService: [SO] setDelay [200000000]
03-17 08:35:50.799  1018  1018 D SensorService: [SO] activate (ident=0xb7a40300, enabled=1)
,03-17 08:35:50.799  1018  1018 D SensorService: [SO] AR_init
,03-17 08:35:50.799  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 08:35:50.809  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-17 08:35:50.809  1522  1522 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 08:35:50.819  3844  3924 W AudioCapabilities: Unsupported mime audio/qcelp,
03-17 08:35:50.819  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.819  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.819  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.819  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 08:35:50.829  3844  3924 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 08:35:50.829  3844  3924 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 08:35:50.839  3965  3965 E Zygote  : MountEmulatedStorage(),
03-17 08:35:50.849  3965  3965 E Zygote  : v2
,03-17 08:35:50.849  3965  3965 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 08:35:50.849  3965  3965 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:50.849  3965  3965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 08:35:50.849  3965  3965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 08:35:50.859  3965  3965 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 08:35:50.859  1018  1565 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:50.859  2623  2623 D FactoryTestApp: [Support$Values.getString](2623) id=MODEL_COMMUNICATION_MODE, value=gsm,
03-17 08:35:50.859  2623  2623 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2623) mConnectionMode = gsm
03-17 08:35:50.859  2623  2623 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2623) RUNNING_FTCLIENT : false
03-17 08:35:50.859  2623  2623 D FactoryTestApp: [DummyFtClient$onDestroy](2623) kill process
03-17 08:35:50.859  2623  2623 I Process : Sending signal. PID: 2623 SIG: 9
03-17 08:35:50.859  1018  1230 W ActivityManager: userId = 0, bbcId = -10000,
03-17 08:35:50.859  1018  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:50.859  1018  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:50.879  3844  3924 W AudioCapabilities: Unsupported mime audio/x-ms-wma,
03-17 08:35:50.889  1018  1566 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.889  1018  1566 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:50.889  1018  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 08:35:50.889  1522  1522 D MenuAppsGridFragment: onResume,
03-17 08:35:50.889  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 08:35:50.889  1018  1521 D ActivityManager: handle home activity for 0
03-17 08:35:50.889  1018  1521 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 08:35:50.889  1018  1521 D KnoxTimeoutHandler: post home show event for user 0
03-17 08:35:50.889  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0,
03-17 08:35:50.889  1018  1521 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 08:35:50.889  1018  1521 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 08:35:50.889  1018  1521 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 08:35:50.889  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 08:35:50.889  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 08:35:50.909  3844  3924 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 08:35:50.909  3965  3965 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.909  3844  3924 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 08:35:50.909   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=4, Mauncher
,03-17 08:35:50.909  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 08:35:50.909  3965  3965 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:50.909  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 08:35:50.909  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:35:50.919  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:35:50.919  1018  1030 D InputDispatcher: Focus entered window: 1522
,03-17 08:35:50.919  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 08:35:50.919  1522  1522 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 08:35:50.919  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 08:35:50.929  3844  3924 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 08:35:50.929  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.929  1018  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:50.929  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:50.939  1522  1522 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 08:35:50.939  1018  3760 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 08:35:50.949  1018  3981 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:35:50.959  1186  1186 I StatusBar: Icon Only
03-17 08:35:50.959  1186  1186 D PanelView: There is/are notification(s) 
,03-17 08:35:50.959  3396  3396 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 08:35:50.969  1843  1843 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 08:35:50.969  3960  3960 D AndroidRuntime: 
03-17 08:35:50.969  3960  3960 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 08:35:50.969  3960  3960 D AndroidRuntime: CheckJNI is OFF
,03-17 08:35:50.969  3960  3960 D AndroidRuntime: readGMSProperty: start
03-17 08:35:50.969  3960  3960 D AndroidRuntime: readGMSProperty: already setted!!
03-17 08:35:50.969  3960  3960 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 08:35:50.969  3960  3960 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 08:35:50.969  3960  3960 D AndroidRuntime: readGMSProperty: end
03-17 08:35:50.969  3960  3960 D AndroidRuntime: addProductProperty: start
,03-17 08:35:50.989  1018  1079 I ActivityManager: Process com.sec.factory (pid 2623)(adj 0) has died(22,648)
,03-17 08:35:50.999  3844  3844 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
03-17 08:35:51.009  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-17 08:35:51.009  3965  3965 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 08:35:51.039  1522  1522 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b4f507 time:40852
,03-17 08:35:51.039  1018  1048 D PersonaManager: isKioskContainerExistOnDevice
,03-17 08:35:51.049  1018  1048 I ActivityManager: Displayed Component not be shown by security: +322ms,
,03-17 08:35:51.059  1018  1521 W ActivityManager: userId = 0, bbcId = -10000,
03-17 08:35:51.059  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.059  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.079  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,03-17 08:35:51.079  2171  2171 D ChimeraCfgMgr: Reading stored module config
,03-17 08:35:51.089  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.089  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.089  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.089  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:35:51.089  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 08:35:51.089  3844  3924 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 08:35:51.089  3880  3911 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 08:35:51.089  3880  3911 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 08:35:51.089  3880  3911 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 08:35:51.089  3880  3911 I AMMetaDataParserService: Resource data:2131165186
,03-17 08:35:51.099  3844  3924 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 08:35:51.099  3880  3911 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 08:35:51.099  3880  3911 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 08:35:51.099  3880  3911 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 08:35:51.099  3880  3911 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 08:35:51.119  1018  3761 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 08:35:51.119  3844  3924 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 08:35:51.119  3880  3911 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,03-17 08:35:51.119  3880  3911 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 08:35:51.129  3965  3965 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 08:35:51.129  3965  3992 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458200151140
,03-17 08:35:51.139  3965  3965 I KnoxUsageLogPro: premStatus:2
,03-17 08:35:51.139  3960  3960 E AffinityControl: AffinityControl: registerfunction enter
,03-17 08:35:51.139  3965  3965 I KnoxUsageLogPro: isEulaShown : false
03-17 08:35:51.139  3965  3965 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 08:35:51.149  1018  1079 I ActivityManager: Killing 3113:com.dropbox.android/u0a88 (adj 15): empty #31
,03-17 08:35:51.149  1018  1625 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.149  1018  1625 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.149  1018  1625 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.169  3960  3960 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 08:35:51.169  1642  1669 I art     : Explicit concurrent mark sweep GC freed 3203(136KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 747us total 106.335ms
,03-17 08:35:51.179  1642  1662 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 08:35:51.189  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.189  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.189  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.209  1018  1040 D SensorService: [SO] currT = 41021014000, prevT = 40531066000, diff = 489948000, [-0.441 0.211 9.883]
,03-17 08:35:51.209  1018  1040 D SensorService: [SO] -0.441 0.211 9.883
03-17 08:35:51.209  1018  1040 D SensorService: [SO] [100 -> 255]
,03-17 08:35:51.209  1018  1043 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 08:35:51.209  1018  1043 W ActivityManager: mDVFSHelper.release()
03-17 08:35:51.219  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 08:35:51.249  3844  3924 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 08:35:51.249  2171  2171 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-17 08:35:51.249  2171  2171 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 08:35:51.259  1018  1042 W libprocessgroup: failed to open /acct/uid_10088/pid_3113/cgroup.procs: No such file or directory
,03-17 08:35:51.259  3844  3924 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 08:35:51.259  1018  1520 D PackageManager: START PACKAGE DELETE: observer{377373735}
03-17 08:35:51.259  1018  1520 D PackageManager: pkg{<packageName>}
03-17 08:35:51.259  1018  1520 D PackageManager: user{0}
03-17 08:35:51.259  1018  1520 D PackageManager: caller{2000}
03-17 08:35:51.259  1018  1520 D PackageManager: flags{2}
03-17 08:35:51.259  1018  1520 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 08:35:51.259  1018  1520 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 08:35:51.259  1018  1520 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 08:35:51.259  1018  1520 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 08:35:51.259  3880  3911 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-17 08:35:51.259  2171  2171 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
03-17 08:35:51.259  1018  1520 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 08:35:51.259  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,03-17 08:35:51.259  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 08:35:51.259  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-17 08:35:51.269  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
,03-17 08:35:51.269  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 08:35:51.269  1934  1934 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 08:35:51.269  1018  1058 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-17 08:35:51.279  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.279  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.279  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 08:35:51.279  3601  3754 I Gmail   : getAccountsCursor
,03-17 08:35:51.279  3844  3924 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 08:35:51.279  2171  3923 D GCM     : COMPAT: Multi user not supported
,03-17 08:35:51.279  3844  3924 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 08:35:51.289  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,03-17 08:35:51.289  1018  1043 I ActivityManager: Killing 3396:com.test.thalitest/u0a167 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-17 08:35:51.289  3844  3924 W VideoCapabilities: Unsupported mime video/mp43
,03-17 08:35:51.289  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 08:35:51.289  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 08:35:51.289  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:51.299  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:51.299  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:51.299  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:51.299  3880  3911 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-17 08:35:51.309  3844  3924 W VideoCapabilities: Unsupported mime video/sorenson,
,03-17 08:35:51.309  3944  3944 I System.out: Inside onCreate() of WakeupTriggerProvide
,03-17 08:35:51.319  3944  3944 I System.out: Inside WakeupProvider
,03-17 08:35:51.329  3844  3924 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 08:35:51.329  3880  3911 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,03-17 08:35:51.339  3965  3992 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 40942
,03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 08:35:51.339  3880  39,11 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 08:35:51.339  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-17 08:35:51.349  3844  3924 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
03-17 08:35:51.349  3880  3911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 08:35:51.389  1018  1058 W PackageSettings: Skipping PackageSetting{2b3a6bb3 com.example.hello/10168} due to missing metadata
,03-17 08:35:51.399  1018  1625 I WindowState: WIN DEATH: Window{2d4a16af u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-17 08:35:51.429  1018  1447 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.429  1018  1447 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.429  1018  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.439  3601  3702 I Gmail   : getAccountsCursor
,03-17 08:35:51.439  1018  1566 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.439  1018  1566 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.439  1018  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.439  1934  1934 D GCM     : COMPAT: Multi user not supported
,03-17 08:35:51.449  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.449  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.449  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.459  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-17 08:35:51.479   258  3667 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 08:35:51.479   258   446 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 08:35:51.479  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-17 08:35:51.479  3880  3911 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 08:35:51.479  3880  3911 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 08:35:51.479  3880  3911 I AMMetaDataParserService: Resource data:2131034113
,03-17 08:35:51.489   258   453 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 08:35:51.489  3880  3911 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 08:35:51.489  3880  3911 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 08:35:51.489  3880  3911 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 08:35:51.499  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
03-17 08:35:51.499  3844  3844 V Babel   : babel boot account: SMS
,03-17 08:35:51.499  3844  3844 V Babel   : babel boot account: thalitester@gmail.com
03-17 08:35:51.499  3880  3911 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-17 08:35:51.499  3880  3911 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 08:35:51.499  1018  3760 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.499  1018  3760 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.499  1018  3760 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.509  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:51.529  3880  3911 I GFX construct_block_size_descriptor_2d second part: took 3.756821ms for 0*0 texture 0
,03-17 08:35:51.529  3880  3911 I GFX generate_partition_tables: took 6.141823ms for 0*0 texture 0
,03-17 08:35:51.529  3880  3911 I GFX raster: took 11.160624ms for 96*96 texture 0
03-17 08:35:51.529  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb755e9c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb755eb00 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:51.539  1018  1018 D RCPManagerService: PackageReceiver onReceive()
03-17 08:35:51.539  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 08:35:51.539  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 08:35:51.549  1843  1843 E SamsungIME: mOCRHelper is null
,03-17 08:35:51.549  1495  1495 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 08:35:51.549  3880  3911 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 08:35:51.549  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.549  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.549  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.549  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.559  4008  4008 E Zygote  : MountEmulatedStorage()
,03-17 08:35:51.569  4008  4008 E Zygote  : v2
03-17 08:35:51.569  4008  4008 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:51.569  4008  4008 I libpersona: KNOX_SDCARD not a persona,
,03-17 08:35:51.569  4008  4008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 08:35:51.569  4008  4008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 08:35:51.569  1018  1230 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:51.569  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 08:35:51.569  1018  1230 I ActivityManager: Killing 1610:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
03-17 08:35:51.569  4008  4008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:51.569  3944  3944 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-17 08:35:51.579  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bb53041 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:41396
,03-17 08:35:51.579  1018  1625 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.579  1018  1625 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.579  1018  1625 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.579  3880  3911 I GFX raster: took 0.910314ms for 96*96 texture 0
03-17 08:35:51.579  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb755e9c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb75288c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:51.599  1018  1097 V AlarmManager: waitForAlarm result :4
,03-17 08:35:51.599  1018  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.599  1018  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.599  1018  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 08:35:51.599  3880  3911 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 08:35:51.619  4008  4008 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:51.619  4008  4008 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:51.619  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 08:35:51.629  2171  3923 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 08:35:51.649  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:51.649  3880  3911 I GFX construct_block_size_descriptor_2d second part: took 2.906095ms for 0*0 texture 0
,03-17 08:35:51.669  3880  3911 I GFX generate_partition_tables: took 7.508751ms for 0*0 texture 0
,03-17 08:35:51.669  3880  3911 I GFX raster: took 11.474014ms for 96*96 texture 0
03-17 08:35:51.669  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7545c10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75288c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:51.669  1018  1097 V AlarmManager: waitForAlarm result :4
,03-17 08:35:51.679  3880  3911 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 08:35:51.679  1018  3760 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.679  1018  3760 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 08:35:51.679  1018  3760 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.689  1018  1625 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 08:35:51.689  1018  1625 D SecContentProvider2: mCursor = null
,03-17 08:35:51.699  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:51.699  3880  3911 I GFX raster: took 0.670208ms for 96*96 texture 0
,03-17 08:35:51.699  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7545138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75288c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:51.709  1018  1129 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-17 08:35:51.709  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 08:35:51.709  1018  1129 V NetworkStats: performPollLocked(flags=0x3)
,03-17 08:35:51.709  1483  1483 D RegisteredServicesCache: empty dynamic service
,03-17 08:35:51.709  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 08:35:51.709  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 08:35:51.709  3139  3228 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 08:35:51.709  1018  1129 V NetworkStats: performPollLocked() took 7ms
03-17 08:35:51.709  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 08:35:51.719  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.719  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:51.719  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 08:35:51.729  3880  3911 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 08:35:51.729  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 08:35:51.729  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 08:35:51.729  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 08:35:51.739  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:51.739  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 08:35:51.739  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-17 08:35:51.739  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,03-17 08:35:51.739  1018  1018 V EnterpriseBillingPolicy: uID is 10167
03-17 08:35:51.739  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
,03-17 08:35:51.749  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 08:35:51.749  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 08:35:51.749  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 08:35:51.749  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 08:35:51.749  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 08:35:51.749  3880  3911 I GFX raster: took 0.897135ms for 96*96 texture 0
03-17 08:35:51.749  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb75288c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7544698 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:51.749  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 08:35:51.749  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 08:35:51.749  2171  4026 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 08:35:51.759  3880  3911 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 08:35:51.759  3944  3944 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-17 08:35:51.779  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 08:35:51.779  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 08:35:51.779  1018  1042 W TextServicesManagerService: no available spell checker services found
,03-17 08:35:51.819  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:51.819  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:51.829  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:51.829  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:51.889  1018  1031 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1186 (0x0),
,03-17 08:35:51.899  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.899  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 08:35:51.899  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:51.909  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.909  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.909  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.909  1018  1625 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.919  1018  1058 I art     : Explicit concurrent mark sweep GC freed 46887(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/37MB, paused 4.004ms total 252.031ms
,03-17 08:35:51.919  4033  4033 E Zygote  : MountEmulatedStorage()
03-17 08:35:51.919  4033  4033 E Zygote  : v2
03-17 08:35:51.919  4033  4033 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:51.919  4033  4033 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:51.919  4033  4033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:51.929  1018  1625 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4033 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:51.929  4033  4033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicy: uID is 10167
03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 08:35:51.929  1018  2759 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-17 08:35:51.929  4033  4033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 08:35:51.929  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 08:35:51.939  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:51.939  3880  3911 I GFX raster: took 0.659166ms for 96*96 texture 0
03-17 08:35:51.939  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb75686b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7568570 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:51.949  1018  1625 I ActivityManager: Killing 3093:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 08:35:51.949  1018  1169 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
,03-17 08:35:51.949  1018  1169 D TaskPersister: removeObsoleteFile: deleting file=11_task_thumbnail.png
,03-17 08:35:51.959  3880  3911 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 08:35:51.969  4033  4033 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:51.969  4033  4033 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:51.999  1018  1058 D PackageManager: delete codoeFile: 
,03-17 08:35:51.999  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,03-17 08:35:51.999  1018  1058 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 08:35:52.009  1018  1058 D PackageManager: result of delete: 1{377373735}
,03-17 08:35:52.009  3960  3960 D AndroidRuntime: Shutting down VM
,03-17 08:35:52.029  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:52.029  3880  3911 I GFX raster: took 0.668021ms for 96*96 texture 0
03-17 08:35:52.029  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7181380 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb71d2d48 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:52.039  3880  3911 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 08:35:52.069  2171  4028 I CheckinService: Checking schedule, now: 1458200152082 next: 1458299986961
,03-17 08:35:52.069  2171  4028 I CheckinService: active receiver: disabled
,03-17 08:35:52.069  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 08:35:52.089  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 08:35:52.089  1018  1058 D PackageManager: userId{-1}
03-17 08:35:52.089  1018  1058 D PackageManager: andCode{true}
,03-17 08:35:52.089  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:52.089  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.089  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.089  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.089  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:52.099  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:52.099  4050  4050 E Zygote  : MountEmulatedStorage()
03-17 08:35:52.099  4050  4050 E Zygote  : v2
03-17 08:35:52.099  4050  4050 I libpersona: KNOX_SDCARD checking this for 10003
03-17 08:35:52.099  4050  4050 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:52.109  4050  4050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:52.109  4050  4050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:52.109  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:52.109  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4050 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-17 08:35:52.109  4050  4050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:52.119  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 08:35:52.119  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:35:52.119  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 08:35:52.129  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:52.149  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:52.149  3880  3911 I GFX raster: took 0.528698ms for 96*96 texture 0
03-17 08:35:52.149  4033  4033 E KnoxSetupWizardClient: isShipMode : 1
03-17 08:35:52.149  4050  4050 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:52.149  4033  4033 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 08:35:52.149  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb753d028 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb71d2d48 counterpartCT=4 counterpartW=96 counterparth=96
03-17 08:35:52.149  4050  4050 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:52.149  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:52.149  1018  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:52.149  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 08:35:52.159  3880  3911 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 08:35:52.169  3944  3944 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 08:35:52.169  3944  3944 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 08:35:52.169  3245  3416 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 08:35:52.169  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:52.169  1018  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:52.169  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:52.179  2171  2171 D SystemUpdateService: onCreate
,03-17 08:35:52.179  3880  3911 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 08:35:52.179  3880  3911 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 08:35:52.179  3880  3911 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 08:35:52.179  3880  3911 I AMMetaDataParserService: Resource data:2131034113
,03-17 08:35:52.179  3880  3911 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 08:35:52.179  3880  3911 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 08:35:52.179  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:52.179  3880  3911 I GFX raster: took 0.811667ms for 96*96 texture 0
03-17 08:35:52.179  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb755e9c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb71cd358 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:52.189  3880  3911 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 08:35:52.199  2171  4031 I Icing   : Storage manager: low false usage 2.11MB avail 9.95GB capacity 11.63GB
,03-17 08:35:52.209  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:52.209  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:52.209  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:52.219  3960  3960 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,03-17 08:35:52.229  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:52.229  3880  3911 I GFX raster: took 0.804323ms for 96*96 texture 0
03-17 08:35:52.229  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb755e9c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb753d310 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:52.239  3944  3944 D DialogFlow: initQueue()
03-17 08:35:52.239  4033  4033 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 08:35:52.249  3880  3911 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 08:35:52.249  4033  4033 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 08:35:52.249  4033  4033 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
03-17 08:35:52.249  4033  4033 D ShortcutReceiver:  shortcut migration not required 
,03-17 08:35:52.259  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.259  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.259  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.259  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:52.269  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:52.269  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:52.269  1018  1565 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4078 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 08:35:52.279  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:35:52.279  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 08:35:52.279  2171  2171 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 08:35:52.279  4078  4078 E Zygote  : MountEmulatedStorage()
03-17 08:35:52.279  4078  4078 E Zygote  : v2
03-17 08:35:52.279  4078  4078 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:52.279  4078  4078 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:52.279  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 08:35:52.279  3880  3911 I GFX raster: took 0.611459ms for 96*96 texture 0
03-17 08:35:52.279  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7545c10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb753d310 counterpartCT=4 counterpartW=96 counterparth=96
03-17 08:35:52.279  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-17 08:35:52.279  1018  1565 I ActivityManager: Killing 3155:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 08:35:52.289  1018  1565 I ActivityManager: Killing 3170:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31,
,03-17 08:35:52.289  4078  4078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 08:35:52.289  4033  4068 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-17 08:35:52.299  4078  4078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 08:35:52.299  4078  4078 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:52.299  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:35:52.299  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 08:35:52.299  1522  1522 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 08:35:52.299  1522  1522 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 08:35:52.299  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:35:52.299  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 08:35:52.309  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 08:35:52.309  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 08:35:52.309  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:52.309  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:52.309  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:52.309  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:52.309  3880  3911 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531,
,03-17 08:35:52.309  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:52.309  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-17 08:35:52.309  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-17 08:35:52.319  2171  4086 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
03-17 08:35:52.319  1018  1042 W libprocessgroup: failed to open /acct/uid_10068/pid_1610/cgroup.procs: No such file or directory
03-17 08:35:52.319  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3093/cgroup.procs: No such file or directory
,03-17 08:35:52.319  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.319  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.319  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:52.319  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:52.319  4033  4068 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
,03-17 08:35:52.319  4033  4068 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
,03-17 08:35:52.329  4033  4068 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
,03-17 08:35:52.329  4033  4068 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
,03-17 08:35:52.329  4033  4068 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
,03-17 08:35:52.329  4033  4068 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 08:35:52.339  4096  4096 E Zygote  : MountEmulatedStorage(),
03-17 08:35:52.339  4096  4096 E Zygote  : v2
03-17 08:35:52.339  4096  4096 I libpersona: KNOX_SDCARD checking this for 10029
03-17 08:35:52.339  4096  4096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:52.339  4096  4096 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:52.339  4096  4096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 08:35:52.339  4096  4096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:52.349  1018  1031 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4096 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-17 08:35:52.349  1018  1031 I ActivityManager: Killing 3189:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-17 08:35:52.369  4078  4078 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:52.369  4078  4078 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:52.379  4096  4096 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:52.379  4096  4096 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:52.399  2171  4086 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 08:35:52.399  1018  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:52.399  1018  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 08:35:52.399  1018  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:52.429  4078  4078 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 08:35:52.439  4078  4078 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 08:35:52.439  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:52.439  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.439  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.439  1018  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:52.459  4118  4118 E Zygote  : MountEmulatedStorage(),
03-17 08:35:52.459  4118  4118 E Zygote  : v2
03-17 08:35:52.459  1018  1230 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4118 uid=10113 gids={50113, 9997} abi=armeabi-v7a
03-17 08:35:52.459  4118  4118 I libpersona: KNOX_SDCARD checking this for 10113
03-17 08:35:52.459  4118  4118 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:52.469  4118  4118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 08:35:52.469  4118  4118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 08:35:52.469  1018  1230 I ActivityManager: Killing 3212:com.sec.android.diagmonagent/1000 (adj 15): empty #31
03-17 08:35:52.469  4118  4118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:52.489  3880  3911 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 08:35:52.489  3880  3911 I GFX raster: took 0.666666ms for 96*96 texture 0
03-17 08:35:52.489  3880  3911 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7545138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb71d2d48 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 08:35:52.499  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3155/cgroup.procs: No such file or directory
,03-17 08:35:52.499  1018  1042 W libprocessgroup: failed to open /acct/uid_10088/pid_3170/cgroup.procs: No such file or directory
,03-17 08:35:52.509  4118  4118 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:52.509  4118  4118 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:52.519  1018  1569 F PackageManager: Package Manager Crash
03-17 08:35:52.519  1018  1569 F PackageManager: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
03-17 08:35:52.519  1018  1569 F PackageManager: 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1668)
03-17 08:35:52.519  1018  1569 F PackageManager: 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:17048)
03-17 08:35:52.519  1018  1569 F PackageManager: 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:16893)
03-17 08:35:52.519  1018  1569 F PackageManager: 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1429)
03-17 08:35:52.519  1018  1569 F PackageManager: 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2985)
03-17 08:35:52.519  1018  1569 F PackageManager: 	at android.os.Binder.execTransact(Binder.java:461)
,03-17 08:35:52.519  3880  3911 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
03-17 08:35:52.519  3880  3911 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,03-17 08:35:52.519  3880  3911 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:35:52.519  3880  3911 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 08:35:52.529  3880  3911 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:52.529  3880  3911 W System.err: 	at andro,id.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:52.529  3880  3911 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
03-17 08:35:52.529  3880  3911 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-17 08:35:52.529  3880  3911 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 08:35:52.529  3880  3911 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 08:35:52.529  1018  3761 I ActivityManager: Killing 3270:com.policydm/1000 (adj 15): empty #31
03-17 08:35:52.549  2171  3983 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-17 08:35:52.549  2171  3983 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-17 08:35:52.559  1018  3761 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:52.559  1018  3761 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.559  1018  3761 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.559  1018  3761 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:52.559  4118  4118 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 08:35:52.569  1018  1042 W libprocessgroup: failed to open /acct/uid_10146/pid_3189/cgroup.procs: No such file or directory
,03-17 08:35:52.569  4118  4118 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-17 08:35:52.579  1018  1043 E DropBoxManagerService: Can't write: system_server_wtf
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop29.tmp: open failed: EROFS (Read-only file system)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	,at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15891)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:15704)
03-17 08:35:52.579  1018  1043 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15676),

```
