#### Test 62548124d9c0fd9_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-19 12:52:10.667  1341  1341 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-19 12:52:10.667  1341  1341 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-19 12:52:10.667  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 139
03-19 12:52:10.667  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458409920000
03-19 12:52:10.677  1341  3180 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-19 12:52:10.677  1818  1818 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-19 12:52:10.677  1818  1818 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
--------- beginning of system
03-19 12:52:10.677  1341  1341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-19 12:52:10.687  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.687  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.687  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.687  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.717  3183  3183 E Zygote  : MountEmulatedStorage()
03-19 12:52:10.717  3183  3183 E Zygote  : v2
03-19 12:52:10.717  3183  3183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:10.717  3183  3183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:10.717  3183  3183 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:10.717  1020  1494 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:10.717  3183  3183 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:10.717  3183  3183 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:10.717  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.717  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.717  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.717  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.727  3137  3137 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-19 12:52:10.727  1020  1572 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 12:52:10.727  1020  1572 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:52:10.727  1020  1572 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:52:10.727  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:52:10.737  3195  3195 E Zygote  : MountEmulatedStorage()
03-19 12:52:10.737  3195  3195 E Zygote  : v2
03-19 12:52:10.737  3195  3195 I libpersona: KNOX_SDCARD checking this for 10146
03-19 12:52:10.737  3195  3195 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:10.737  3195  3195 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:10.747  3183  3183 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:10.747  3183  3183 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:10.747  3195  3195 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:10.747  1020  1507 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3195 uid=10146 gids={50146, 9997} abi=armeabi-v7a
03-19 12:52:10.747  3195  3195 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-19 12:52:10.747  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.747  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.747  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.747  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.757  3137  3137 D DSM     : [Lines:107] Normal booted
03-19 12:52:10.757  3137  3137 D DSM     : [Lines:114] Boot completed
03-19 12:52:10.767  3195  3195 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:10.767  3195  3195 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:10.767  3213  3213 E Zygote  : MountEmulatedStorage()
03-19 12:52:10.767  3213  3213 E Zygote  : v2
03-19 12:52:10.767  3213  3213 I libpersona: KNOX_SDCARD checking this for 10161
03-19 12:52:10.767  3213  3213 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:10.767  3213  3213 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:10.777  3213  3213 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:10.777  1020  1497 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3213 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:10.777  3213  3213 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-19 12:52:10.787  1020  1020 I MotionRecognitionService: Plugged
03-19 12:52:10.787  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:52:10.787  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:52:10.787  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:52:10.787  1199  1199 D PowerUI : Cable  true --> true mBootCompleted : true
03-19 12:52:10.787  1199  1199 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-19 12:52:10.797  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:52:10.797  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 12:52:10.797  3183  3183 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 12:52:10.797  2658  2658 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 12:52:10.797  2658  2748 D HeadsetStateMachine: Disconnected process message: 10
03-19 12:52:10.807  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:10.807  1020  1081 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-19 12:52:10.807  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
03-19 12:52:10.807  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.807  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.807  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.807  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.817  3213  3213 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:10.817  3213  3213 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:10.827  1020  1081 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3230 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:10.827  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 12:52:10.827  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 12:52:10.827  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 12:52:10.827  1199  1199 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:52:10.827  1199  1199 D SViewCoverView: level :100 plugged : 2
03-19 12:52:10.827  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.827  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.827  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.827  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.827  3230  3230 E Zygote  : MountEmulatedStorage()
03-19 12:52:10.827  3230  3230 E Zygote  : v2
03-19 12:52:10.827  3230  3230 I libpersona: KNOX_SDCARD checking this for 10088
03-19 12:52:10.827  3230  3230 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:10.837  3230  3230 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:10.837  3230  3230 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:10.837  3230  3230 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-19 12:52:10.857  3242  3242 E Zygote  : MountEmulatedStorage()
03-19 12:52:10.857  3242  3242 E Zygote  : v2
03-19 12:52:10.857  3242  3242 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:10.857  3242  3242 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:10.857  3242  3242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:10.857  1020  1497 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3242 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:10.857  3230  3230 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:10.857  3230  3230 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:10.857  3242  3242 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:10.857  3242  3242 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:10.857  1020  1497 I ActivityManager: Killing 2341:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
03-19 12:52:10.887  3242  3242 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:10.887  3242  3242 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:10.907  3242  3242 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-19 12:52:10.947  1020  1045 W libprocessgroup: failed to open /acct/uid_10110/pid_2341/cgroup.procs: No such file or directory
03-19 12:52:11.037  3242  3242 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-19 12:52:11.047  1020  1506 I ActivityManager: Killing 1663:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-19 12:52:11.067  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-19 12:52:11.067  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
03-19 12:52:11.067  3242  3242 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
03-19 12:52:11.097  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-19 12:52:11.097  3160  3160 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
03-19 12:52:11.107  1020  1045 W libprocessgroup: failed to open /acct/uid_10014/pid_1663/cgroup.procs: No such file or directory
03-19 12:52:11.117  1199  1199 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:11.117  1199  1199 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:11.117  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-19 12:52:11.117  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-19 12:52:11.117  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-19 12:52:11.117  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-19 12:52:11.117  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-19 12:52:11.127  3213  3263 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-19 12:52:11.127  3213  3263 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-19 12:52:11.127  3242  3242 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-19 12:52:11.127  3242  3242 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-19 12:52:11.127  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.127  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.127  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.127  1020  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.147  3268  3268 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.147  3268  3268 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:11.147  3268  3268 E Zygote  : v2
03-19 12:52:11.147  3268  3268 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.147  3268  3268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:11.157  1020  1497 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:11.157  1020  1497 I ActivityManager: Killing 2413:com.sec.modem.settings/1000 (adj 15): empty #31
03-19 12:52:11.157  3268  3268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:11.157  3268  3268 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:11.167  3160  3160 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
03-19 12:52:11.177   298   298 E USB_UICC: Timeout! No signal received. Retry num = 30
03-19 12:52:11.177  3268  3268 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:11.177  3268  3268 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:11.187  3213  3263 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-19 12:52:11.227  3183  3183 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
03-19 12:52:11.227   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-19 12:52:11.237  3160  3160 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
03-19 12:52:11.237  3213  3263 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-19 12:52:11.237  3213  3263 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a402270: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-19 12:52:11.237  3213  3263 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-19 12:52:11.247  3160  3160 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
03-19 12:52:11.257  3160  3160 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
03-19 12:52:11.267  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2413/cgroup.procs: No such file or directory
03-19 12:52:11.267  3183  3183 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
03-19 12:52:11.277  3183  3183 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
03-19 12:52:11.277  3183  3183 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
03-19 12:52:11.287  3160  3160 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
03-19 12:52:11.317   298   298 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-19 12:52:11.317   298   298 E USB_UICC: usb_uicc_init_qmi failed ! 
03-19 12:52:11.317   298   298 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-19 12:52:11.317   298   298 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-19 12:52:11.317  1020  1046 I ActivityManager: Waited long enough for: ServiceRecord{25e9bcd9 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-19 12:52:11.377  3160  3160 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
03-19 12:52:11.377  3183  3183 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
03-19 12:52:11.387  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
03-19 12:52:11.387  3183  3183 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
03-19 12:52:11.387  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.387  1020  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.387  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-19 12:52:11.387  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
03-19 12:52:11.397  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
03-19 12:52:11.397  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
03-19 12:52:11.397  3268  3268 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
03-19 12:52:11.397  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
03-19 12:52:11.397  1199  1199 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-19 12:52:11.397  3183  3183 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-19 12:52:11.407  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-19 12:52:11.407  3183  3183 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-19 12:52:11.407  3160  3160 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
03-19 12:52:11.407  1199  1199 D OverheatReceiver: into the SAFE_MODE_ACTION
03-19 12:52:11.407  1199  1199 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-19 12:52:11.407  1199  1199 D OverheatReceiver: isSafeMode = false
03-19 12:52:11.407  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-19 12:52:11.407  3183  3183 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-19 12:52:11.417  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-19 12:52:11.417  3183  3183 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-19 12:52:11.417  3183  3183 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-19 12:52:11.417  1483  1483 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-19 12:52:11.417  1020  1571 D SettingsProvider: name = internet_call_settings_visibility
03-19 12:52:11.417  1020  1571 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:11.417  1020  1571 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:11.417  1020  1571 D SettingsProvider: selectionArgs: false
03-19 12:52:11.417  1020  1571 D SettingsProvider: selectionArgs: 1001
03-19 12:52:11.417  1020  1571 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:11.417  1020  1571 D SettingsProvider: ret = -1
03-19 12:52:11.417  1483  1483 D PhoneUtilsCommon: isSupportVoLTE is false.
03-19 12:52:11.417  3183  3285 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
03-19 12:52:11.427  3183  3183 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
03-19 12:52:11.427   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-19 12:52:11.427   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
03-19 12:52:11.427  3213  3213 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-19 12:52:11.427  3183  3183 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-19 12:52:11.427  3183  3183 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-19 12:52:11.437  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
03-19 12:52:11.437  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
03-19 12:52:11.437  3183  3285 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
03-19 12:52:11.437  3183  3183 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
03-19 12:52:11.437  3183  3183 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-19 12:52:11.437  3183  3285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-19 12:52:11.477  1459  1459 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
03-19 12:52:11.487  3160  3160 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
03-19 12:52:11.517  3223  3223 D AndroidRuntime: 
03-19 12:52:11.517  3223  3223 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-19 12:52:11.517  3223  3223 D AndroidRuntime: CheckJNI is OFF
03-19 12:52:11.517  3223  3223 D AndroidRuntime: readGMSProperty: start
03-19 12:52:11.517  3223  3223 D AndroidRuntime: readGMSProperty: already setted!!
03-19 12:52:11.517  3223  3223 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-19 12:52:11.517  3223  3223 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-19 12:52:11.517  3223  3223 D AndroidRuntime: readGMSProperty: end
03-19 12:52:11.517  3223  3223 D AndroidRuntime: addProductProperty: start
03-19 12:52:11.597  1020  1309 I art     : Explicit concurrent mark sweep GC freed 30400(1531KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.382ms total 150.420ms
03-19 12:52:11.597  1020  1309 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.597  1020  1309 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.597  1020  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-19 12:52:11.597  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.597  1020  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.597  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-19 12:52:11.617  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.617  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.617  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-19 12:52:11.627  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.627  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.627  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.627  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.637  3312  3312 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.637  3312  3312 E Zygote  : v2
03-19 12:52:11.637  3312  3312 I libpersona: KNOX_SDCARD checking this for 10052
03-19 12:52:11.637  3312  3312 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.637  3312  3312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:11.637  1020  1309 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3312 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-19 12:52:11.647  3268  3268 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
03-19 12:52:11.647  3312  3312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:11.647  3312  3312 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-19 12:52:11.657  3183  3183 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
03-19 12:52:11.657  3268  3268 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
03-19 12:52:11.657  3268  3268 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
03-19 12:52:11.657  3268  3268 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-19 12:52:11.657  3268  3268 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-19 12:52:11.657  3268  3268 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-19 12:52:11.667  1020  1570 E Tethering: No numeric data
03-19 12:52:11.667  1020  1507 E Tethering: No numeric data
03-19 12:52:11.667  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.667  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.667  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.667  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.667  1020  1506 E Tethering: No numeric data
03-19 12:52:11.667  1020  1572 E Tethering: No numeric data
03-19 12:52:11.677  1020  1570 E Tethering: No numeric data
03-19 12:52:11.677  3312  3312 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:11.677  3312  3312 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:11.687  3328  3328 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.687  3328  3328 E Zygote  : v2
03-19 12:52:11.687  3328  3328 I libpersona: KNOX_SDCARD checking this for 10090
03-19 12:52:11.687  3328  3328 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.687  1020  1032 E Tethering: No numeric data
03-19 12:52:11.687  3328  3328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:11.687  3328  3328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:11.687  3183  3285 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
03-19 12:52:11.687  3328  3328 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:11.687  1020  1569 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3328 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-19 12:52:11.687  1020  1569 I ActivityManager: Killing 2446:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-19 12:52:11.727  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.727  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.727  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.727  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.727  3328  3328 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:11.727  3328  3328 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:11.747  1020  1793 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3347 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:11.747  3347  3347 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.747  3347  3347 E Zygote  : v2
03-19 12:52:11.747  3347  3347 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:11.747  3347  3347 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.747  3347  3347 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:11.747  3347  3347 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:11.747  3347  3347 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:11.747  1459  1459 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
03-19 12:52:11.777  3347  3347 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:11.787  3347  3347 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:11.817  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2446/cgroup.procs: No such file or directory
03-19 12:52:11.817  3183  3285 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
03-19 12:52:11.827  1020  1572 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.827  1020  1572 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:11.827  1020  1572 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-19 12:52:11.837  1341  3180 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
03-19 12:52:11.837  1341  3180 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
03-19 12:52:11.867  1020  1572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.867  1020  1572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.867  1020  1572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.867  1020  1572 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.877  3367  3367 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.877  3367  3367 I libpersona: KNOX_SDCARD checking this for 10014
03-19 12:52:11.877  3367  3367 E Zygote  : v2
03-19 12:52:11.877  3367  3367 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.877  3367  3367 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:11.877  1020  1572 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3367 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
03-19 12:52:11.887  3367  3367 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:11.887  3367  3367 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-19 12:52:11.897  1020  1497 E Tethering: No numeric data
03-19 12:52:11.897  3183  3285 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-19 12:52:11.907  1020  1081 E Tethering: No numeric data
03-19 12:52:11.907  1020  1507 E Tethering: No numeric data
03-19 12:52:11.917  3183  3285 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-19 12:52:11.917  3367  3367 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:11.917  3183  3285 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
03-19 12:52:11.917  3367  3367 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:11.917  1020  1497 D LocationManagerService: getProviders()=[passive]
03-19 12:52:11.927  1020  1569 E Tethering: No numeric data
03-19 12:52:11.937  3328  3328 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-19 12:52:11.937  3328  3328 D elm:15121: ELMEngine.ELMEngine( context ).
03-19 12:52:11.947  3328  3328 D elm:15121: MDMBridge.setEnterpriseBridge()
03-19 12:52:11.947  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.947  1020  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.947  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-19 12:52:11.957  3328  3328 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-19 12:52:11.957  3328  3328 D elm:15121: ElmAgentService : onCreate()
03-19 12:52:11.957  3328  3386 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-19 12:52:11.957  3328  3328 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-19 12:52:11.957  3328  3328 D elm:15121: BootCompletedState : startBootCompleted() call
03-19 12:52:11.967  3328  3328 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-19 12:52:11.967  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.977  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.977  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.977  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.977  1442  1442 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
03-19 12:52:11.987  3394  3394 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.987  3394  3394 E Zygote  : v2
03-19 12:52:11.987  3394  3394 I libpersona: KNOX_SDCARD checking this for 10008
03-19 12:52:11.987  3394  3394 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.987  3394  3394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:11.987  3328  3328 I elm:15121: Get License : 0
03-19 12:52:11.987  3328  3328 D elm:15121: ElmAgentService : onDestroy().
03-19 12:52:11.987  3394  3394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:11.987  1020  1309 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3394 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:11.987  3394  3394 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-19 12:52:11.997  1020  1497 V VibratorService: hasVibrator - useVibetonz: true
03-19 12:52:11.997  1341  3180 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
03-19 12:52:12.007   305   305 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 22.031ms
03-19 12:52:12.017  3394  3394 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:12.017  3394  3394 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:12.017  1020  1570 V VibratorService: hasVibrator - useVibetonz: true
03-19 12:52:12.027  1442  1442 V EmergencyMode: [EmergencyBase] setBootTime
03-19 12:52:12.027  1442  1442 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
03-19 12:52:12.027  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:12.027  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:12.027  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-19 12:52:12.027  1020  1572 V VibratorService: hasVibrator - useVibetonz: true
03-19 12:52:12.027   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.168ms
03-19 12:52:12.037  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.037  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.037  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.037  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.037  3347  3347 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
03-19 12:52:12.037  3347  3347 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-19 12:52:12.047  3347  3347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-19 12:52:12.047  1341  3180 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-19 12:52:12.047  3347  3403 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-19 12:52:12.047   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 17.200ms
03-19 12:52:12.057  3347  3347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-19 12:52:12.057  3347  3347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-19 12:52:12.057  3347  3347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-19 12:52:12.067  3347  3347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-19 12:52:12.067  3418  3418 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.067  3418  3418 E Zygote  : v2
03-19 12:52:12.067  1020  1570 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3418 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:12.067  3418  3418 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:12.067  3418  3418 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.067  3418  3418 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:12.067  3347  3347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-19 12:52:12.067  3347  3347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-19 12:52:12.067  3418  3418 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:12.067  3347  3347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-19 12:52:12.067  3418  3418 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:12.077  3347  3347 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-19 12:52:12.077  3347  3347 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-19 12:52:12.087  3223  3223 E AffinityControl: AffinityControl: registerfunction enter
03-19 12:52:12.087  3347  3347 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
03-19 12:52:12.097  3418  3418 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:12.097  3418  3418 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:12.107  3160  3323 I System.out: Thread-399(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-19 12:52:12.117  3160  3323 I System.out: Thread-399(ApacheHTTPLog):isSBSettingEnabled false
03-19 12:52:12.117  3160  3323 I System.out: Thread-399(ApacheHTTPLog):isShipBuild true
03-19 12:52:12.117  3160  3323 I System.out: Thread-399(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-19 12:52:12.117  3160  3323 I System.out: Thread-399(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-19 12:52:12.117   276   944 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-19 12:52:12.117   276   944 D Netd    : getNetworkForDns: using netid 502 for uid 10088
03-19 12:52:12.127  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:12.127  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:12.127  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-19 12:52:12.127  3223  3223 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-19 12:52:12.137  1020  1032 I ActivityManager: Killing 2461:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
03-19 12:52:12.187  3347  3403 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
03-19 12:52:12.197  1020  1045 W libprocessgroup: failed to open /acct/uid_10127/pid_2461/cgroup.procs: No such file or directory
03-19 12:52:12.197  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-19 12:52:12.207   289   289 E SMD     : DCD OFF
03-19 12:52:12.217  3418  3418 I CameraApp: CameraApp.onCreate()... mFeature : null
03-19 12:52:12.217  3418  3418 I testFeature: Feature.Feature(context)
03-19 12:52:12.217  3418  3418 I testFeature: Feature.readInternalDefaultXml()
03-19 12:52:12.217  3418  3418 I testFeature: ResetFeatureValue
03-19 12:52:12.217  3418  3418 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-19 12:52:12.217  3418  3418 I CameraApp: CameraApp.getAppFeature()...
03-19 12:52:12.227  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.227  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.227  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.227  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.227   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-19 12:52:12.237  1020  1506 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3446 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-19 12:52:12.237  1020  1506 I ActivityManager: Killing 2478:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-19 12:52:12.237  3446  3446 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.237  3446  3446 I libpersona: KNOX_SDCARD checking this for 10095
03-19 12:52:12.237  3446  3446 E Zygote  : v2
03-19 12:52:12.237  3446  3446 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.237  3446  3446 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:12.247  3446  3446 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:12.247  3446  3446 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:12.277  3446  3446 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:12.277  3446  3446 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:12.287   281   281 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-19 12:52:12.287   281   281 D audio_hw_extn: audio_extn_get_parameters: returns 
03-19 12:52:12.287   281   281 V msm8974_platform: platform_get_parameters: exit: returns - 
03-19 12:52:12.287   281   281 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-19 12:52:12.287   281   281 I str_params: key: 'call_forwarding' value: ''
03-19 12:52:12.287  2029  2029 V InCall  : ProximitySensor -  - screenonImmediately: false
03-19 12:52:12.287  2029  2029 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-19 12:52:12.287  2029  2029 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
03-19 12:52:12.287  1020  1571 E PersonaManagerService: inState():  stateMachine is null !!
03-19 12:52:12.287  1020  1571 I PersonaManagerService: PersonaId don't exist
03-19 12:52:12.287  1020  1571 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-19 12:52:12.287  2029  2029 D ScoverManager: serviceVersion : 16908288
03-19 12:52:12.287  1020  1570 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-19 12:52:12.297  2029  2029 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-19 12:52:12.297  1459  1459 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-19 12:52:12.297  1020  1081 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-19 12:52:12.297  2029  2029 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-19 12:52:12.297  1020  1571 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 12:52:12.297  2029  2029 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
03-19 12:52:12.297  2029  2029 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-19 12:52:12.297  2029  2029 D InCall  : InCallPresenter -  - dismissCoverDialog()...
03-19 12:52:12.307  2029  2029 I InCall  : CallSContextMotion - stopPutDownListening
03-19 12:52:12.307  2029  2029 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
03-19 12:52:12.317  1341  3180 D ScoverManager: serviceVersion : 16908288
03-19 12:52:12.317  1020  1571 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-19 12:52:12.317  3312  3392 I ContactAccountLoggerTas: canRun() : Opted Out
03-19 12:52:12.317  1020  1571 W ActivityManager: mDVFSHelper.acquire()
03-19 12:52:12.327  1199  1199 D PhoneStatusBarView: setCallBackground:0
03-19 12:52:12.327  1020  1571 D FocusedStackFrame: Set to : 0
03-19 12:52:12.327  1020  1497 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-19 12:52:12.327  2029  2029 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-19 12:52:12.337  1020  1571 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-19 12:52:12.337  1020  1571 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 12:52:12.337  1020  1571 D InputDispatcher: Focused application set to: xxxx
03-19 12:52:12.337  1020  1571 D InputDispatcher: Focus left window: 1508
03-19 12:52:12.337  3223  3223 D AndroidRuntime: Shutting down VM
03-19 12:52:12.337  1020  1569 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-19 12:52:12.347  1020  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-19 12:52:12.347  1020  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-19 12:52:12.347  3446  3446 D PreloadFilterInstaller: uses FILTER_DB_VER_1
03-19 12:52:12.357  1020  1570 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:12.357  1020  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:12.357  1020  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-19 12:52:12.357  1508  1508 D Launcher.HomeView: onPause
03-19 12:52:12.357  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2478/cgroup.procs: No such file or directory
03-19 12:52:12.357  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-19 12:52:12.357  3213  3213 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
03-19 12:52:12.357  3347  3361 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-19 12:52:12.367  3347  3361 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-19 12:52:12.367  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:52:12.367  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.367  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.367  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.367  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.367  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-19 12:52:12.377  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-19 12:52:12.377  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-19 12:52:12.377  3446  3446 E SQLiteLog: (284) automatic index on titles(filter_id)
03-19 12:52:12.377   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-19 12:52:12.387  3462  3462 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.387  3462  3462 I libpersona: KNOX_SDCARD checking this for 10167
03-19 12:52:12.387  3462  3462 E Zygote  : v2
03-19 12:52:12.387  3462  3462 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.387  3462  3462 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:12.387  3462  3462 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:12.387  3462  3462 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-19 12:52:12.387  1020  1494 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3462 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-19 12:52:12.397  2029  2029 D VideoCallManager: Instantiating VideoCallManager
03-19 12:52:12.407  3347  3403 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-19 12:52:12.407  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-19 12:52:12.407  2029  2029 I GFX construct_block_size_descriptor_2d second part: took 2.584791ms for 0*0 texture 0
03-19 12:52:12.417  3347  3403 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-19 12:52:12.417  2029  2029 I GFX generate_partition_tables: took 5.256876ms for 0*0 texture 0
03-19 12:52:12.417  3462  3462 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:12.417  2029  2029 I GFX raster: took 11.680886ms for 176*144 texture 0
03-19 12:52:12.417  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867c0e8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb867ade8 counterpartCT=4 counterpartW=176 counterparth=144
03-19 12:52:12.417  3462  3462 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:12.417  3347  3361 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
03-19 12:52:12.427  1020  1569 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 12:52:12.427  1020  1569 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-19 12:52:12.427  1020  1569 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 12:52:12.427  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
03-19 12:52:12.427  2029  2029 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-19 12:52:12.427  2029  2029 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-19 12:52:12.427  2029  2029 I Adreno-EGL: Build Date: 04/06/15 Mon
03-19 12:52:12.427  2029  2029 I Adreno-EGL: Local Branch: 
03-19 12:52:12.427  2029  2029 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-19 12:52:12.427  2029  2029 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-19 12:52:12.427  2029  2029 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-19 12:52:12.437  1020  1572 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-19 12:52:12.437  1020  1033 I AudioService: getStreamVolume 3 index 0
03-19 12:52:12.437  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{3f70ebb3 token=android.os.BinderProxy@bc06120 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-19 12:52:12.437  1508  1508 D Launcher.HomeView: onStop
03-19 12:52:12.437  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{3f70ebb3 token=android.os.BinderProxy@bc06120 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-19 12:52:12.447  3312  3312 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
03-19 12:52:12.447  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 12:52:12.447  3446  3446 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-19 12:52:12.447  3446  3446 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
03-19 12:52:12.457  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.457  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.457  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.457  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.467  3347  3403 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
03-19 12:52:12.467  3347  3403 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
03-19 12:52:12.477  3481  3481 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.477  3481  3481 E Zygote  : v2
03-19 12:52:12.477  3481  3481 I libpersona: KNOX_SDCARD checking this for 10098
03-19 12:52:12.477  2029  2029 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-19 12:52:12.477  3481  3481 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.477  1020  1033 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3481 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-19 12:52:12.487  3481  3481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:12.487  3481  3481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:12.487  3481  3481 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:12.487  1020  1033 I ActivityManager: Killing 2521:com.wsomacp/u0a23 (adj 15): empty #31
03-19 12:52:12.487  2029  2029 I glCompressedTexImage2D: took 0.455156ms for 320*61440 texture 37809
03-19 12:52:12.497  3347  3403 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
03-19 12:52:12.497  1020  1051 D PersonaManager: isKioskContainerExistOnDevice
03-19 12:52:12.497  3347  3359 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-19 12:52:12.507  2029  2029 I draw setup: took 12.054478ms for 320*240 texture 37809
03-19 12:52:12.507  2029  2029 E GFX GPU raster: drawn
03-19 12:52:12.507  2029  2029 I GFX GPU raster ASTC: took 42.813436ms for 320*240 texture 12
03-19 12:52:12.507  2029  2029 I GFX raster: took 42.895570ms for 320*240 texture 0
03-19 12:52:12.507  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867c2b8 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb867c180 counterpartCT=4 counterpartW=320 counterparth=240
03-19 12:52:12.507  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-19 12:52:12.507  1020  1020 D SensorService: [SO] activate (ident=0xb8a992d8, enabled=0)
03-19 12:52:12.507  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled, 1, handle 0, en 0
03-19 12:52:12.507  3312  3312 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-19 12:52:12.517  1020  1020 D SensorManager: unregisterListener ::   
03-19 12:52:12.517  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-19 12:52:12.517  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-19 12:52:12.517  2029  2029 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-19 12:52:12.517  1020  1020 D SensorService: [SO] changed settle time [1]
03-19 12:52:12.517  1020  1020 D SensorService: [SO] setDelay [66000000]
03-19 12:52:12.517  1020  1020 D SensorService: [SO] activate (ident=0xb8afe3a8, enabled=1)
03-19 12:52:12.517  1020  1020 D SensorService: [SO] AR_init
03-19 12:52:12.517  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-19 12:52:12.527  3312  3312 I ContactLabelSupplier: get() : Execute runnable (UI thread)
03-19 12:52:12.527  1508  1508 D Launcher: onTrimMemory. Level: 20
03-19 12:52:12.527  2029  2029 I glCompressedTexImage2D: took 0.557032ms for 480*122880 texture 37813
03-19 12:52:12.527  2029  2029 I draw setup: took 1.108229ms for 480*640 texture 37813
03-19 12:52:12.527  2029  2029 E GFX GPU raster: drawn
03-19 12:52:12.527  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-19 12:52:12.527  2029  2029 I GFX GPU raster ASTC: took 7.532760ms for 480*640 texture 12
03-19 12:52:12.527  2029  2029 I GFX raster: took 7.612188ms for 480*640 texture 0
03-19 12:52:12.527  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88bd390 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb88bd640 counterpartCT=4 counterpartW=480 counterparth=640
03-19 12:52:12.537  3347  3359 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-19 12:52:12.537  3347  3359 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
03-19 12:52:12.547  3223  3223 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-19 12:52:12.557  3312  3393 I ContactLabelSupplier: get() : OptedIn = false
,03-19 12:52:12.567  3481  3481 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.567  3481  3481 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.577  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-19 12:52:12.577  2029  2029 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-19 12:52:12.577  2029  2029 I glCompressedTexImage2D: took 0.347917ms for 440*116864 texture 37809
03-19 12:52:12.577  2029  2029 I draw setup: took 0.701667ms for 440*330 texture 37809
03-19 12:52:12.577  2029  2029 E GFX GPU raster: drawn
,03-19 12:52:12.577  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-19 12:52:12.577  2029  2029 I GFX GPU raster ASTC: took 4.328645ms for 440*330 texture 12
,03-19 12:52:12.577  2029  2029 I GFX raster: took 4.411250ms for 440*330 texture 0
03-19 12:52:12.577  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88bd640 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb867c190 counterpartCT=4 counterpartW=440 counterparth=330
,03-19 12:52:12.587  1020  2777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-19 12:52:12.597  1020  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-19 12:52:12.597  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-19 12:52:12.607  2029  2029 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-19 12:52:12.607  2029  2029 I glCompressedTexImage2D: took 0.444011ms for 480*163840 texture 37811
03-19 12:52:12.607  2029  2029 I draw setup: took 0.986094ms for 480*640 texture 37811
03-19 12:52:12.607  2029  2029 E GFX GPU raster: drawn
,03-19 12:52:12.607  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.607  2029  2029 I GFX GPU raster ASTC: took 5.854583ms for 480*640 texture 12
03-19 12:52:12.607  2029  2029 I GFX raster: took 5.911562ms for 480*640 texture 0
03-19 12:52:12.607  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88a85f0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb867b288 counterpartCT=4 counterpartW=480 counterparth=640
,03-19 12:52:12.607  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.607  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.607  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.607  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-19 12:52:12.617  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-19 12:52:12.627  3347  3403 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-19 12:52:12.627  3504  3504 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.627  3504  3504 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:12.627  3504  3504 E Zygote  : v2
03-19 12:52:12.627  3504  3504 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.627  3347  3403 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
03-19 12:52:12.637  1020  1569 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3504 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:12.627  3504  3504 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:12.627  3504  3504 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:12.627  3504  3504 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:12.637  1020  1569 I ActivityManager: Killing 2398:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-19 12:52:12.637  1020  1569 I ActivityManager: Killing 2587:com.sec.android.app.camera/u0a135 (adj 15): empty #32
,03-19 12:52:12.637  1020  1569 I ActivityManager: Killing 2570:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #33
,03-19 12:52:12.637  1020  1045 W libprocessgroup: failed to open /acct/uid_10023/pid_2521/cgroup.procs: No such file or directory
,03-19 12:52:12.647  3347  3404 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-19 12:52:12.647  3347  3404 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-19 12:52:12.657  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-19 12:52:12.657  2029  2029 I GFX construct_block_size_descriptor_2d second part: took 2.498542ms for 0*0 texture 0
,03-19 12:52:12.667  1020  1043 D SensorService: [SO] -0.460 0.211 9.883
03-19 12:52:12.667  1020  1043 D SensorService: [SO] [100 -> 255]
,03-19 12:52:12.667  2029  2029 I GFX generate_partition_tables: took 7.753595ms for 0*0 texture 0
,03-19 12:52:12.667  3504  3504 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.667  3504  3504 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.667  2029  2029 I GFX raster: took 12.356928ms for 176*144 texture 0
,03-19 12:52:12.677  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88a6ef0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb88bd218 counterpartCT=4 counterpartW=176 counterparth=144
,03-19 12:52:12.677  1020  1569 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-19 12:52:12.687  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-19 12:52:12.687  2029  2029 I GFX construct_block_size_descriptor_2d second part: took 2.519740ms for 0*0 texture 0
,03-19 12:52:12.697  2029  2029 I GFX generate_partition_tables: took 6.265625ms for 0*0 texture 0
,03-19 12:52:12.697  1020  1309 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-19 12:52:12.697  3481  3481 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-19 12:52:12.697  2029  2029 I GFX raster: took 10.895104ms for 176*144 texture 0
03-19 12:52:12.697  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88bd218 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb88d2198 counterpartCT=4 counterpartW=176 counterparth=144
,03-19 12:52:12.707  2029  2029 D ScoverManager: registerListener
,03-19 12:52:12.707  3347  3403 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-19 12:52:12.707  1020  1571 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 12:52:12.707  1020  1570 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 12:52:12.707  1020  1570 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@38717757, pid : 2029, uid : 1001, type : 1
,03-19 12:52:12.707  1020  1033 I AudioService: getStreamVolume 3 index 0
,03-19 12:52:12.707  3462  3462 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-19 12:52:12.707  3347  3403 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/19/12:52:12
,03-19 12:52:12.707  3481  3481 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-19 12:52:12.717  3347  3403 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-19 12:52:12.717  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.717  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.717  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.717  3347  3403 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
03-19 12:52:12.717  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.727  3347  3404 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
,03-19 12:52:12.727  3347  3404 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-19 12:52:12.727  3347  3404 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-19 12:52:12.727  3347  3404 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-19 12:52:12.727  3521  3521 I libpersona: KNOX_SDCARD checking this for 10099
03-19 12:52:12.727  3521  3521 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.727  3521  3521 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.727  3521  3521 E Zygote  : v2
03-19 12:52:12.727  3347  3404 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-19 12:52:12.737  3347  3404 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-19 12:52:12.737  3521  3521 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:12.737  3347  3404 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-19 12:52:12.737  1020  1506 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3521 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:12.737  3347  3404 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
03-19 12:52:12.737  1020  1506 I ActivityManager: Killing 2635:com.android.calendar/u0a131 (adj 15): empty #31
03-19 12:52:12.737  3521  3521 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:12.737  3521  3521 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-19 12:52:12.737  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2398/cgroup.procs: No such file or directory
03-19 12:52:12.747  3312  3392 I Search.GservicesUpdateTask: Updating Gservices keys
03-19 12:52:12.747  1020  1497 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-19 12:52:12.747  3462  3462 I LibraryLoader: Loading: webviewchromium
03-19 12:52:12.757  3462  3462 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7795-7800)
03-19 12:52:12.757  3462  3462 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-19 12:52:12.767  3347  3404 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-19 12:52:12.767  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.767  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.767  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.767  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.777  3462  3462 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6ffcf6b}
,03-19 12:52:12.777  3462  3462 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-19 12:52:12.777  3462  3462 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
03-19 12:52:12.777  3521  3521 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.777  3521  3521 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.787  3538  3538 E Zygote  : MountEmulatedStorage(),
03-19 12:52:12.787  3538  3538 E Zygote  : v2
03-19 12:52:12.787  3538  3538 I libpersona: KNOX_SDCARD checking this for 10055
03-19 12:52:12.787  3538  3538 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:12.787  3538  3538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:12.797  3538  3538 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-19 12:52:12.797  1020  1506 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3538 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-19 12:52:12.797  3538  3538 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:12.797  3312  3393 I Velvet.VelvetFactory: refreshing search history.
,03-19 12:52:12.807  3347  3403 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-19 12:52:12.807  1020  1045 W libprocessgroup: failed to open /acct/uid_10135/pid_2587/cgroup.procs: No such file or directory
03-19 12:52:12.807  1020  1045 W libprocessgroup: failed to open /acct/uid_10139/pid_2570/cgroup.procs: No such file or directory
,03-19 12:52:12.817  3462  3462 I BrowserStartupController: Initializing chromium process, renderers=0
,03-19 12:52:12.817  3462  3462 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:12.817  2029  2029 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-19 12:52:12.827  1020  1045 W libprocessgroup: failed to open /acct/uid_10131/pid_2635/cgroup.procs: No such file or directory
,03-19 12:52:12.827  3538  3538 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.827  3538  3538 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.847  3462  3462 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-19 12:52:12.847  3462  3462 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
,03-19 12:52:12.847  3462  3462 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,03-19 12:52:12.847  3504  3504 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-19 12:52:12.877  3462  3462 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-19 12:52:12.877  3462  3462 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-19 12:52:12.877  3462  3462 I Adreno-EGL: Build Date: 04/06/15 Mon
03-19 12:52:12.877  3462  3462 I Adreno-EGL: Local Branch: 
03-19 12:52:12.877  3462  3462 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-19 12:52:12.877  3462  3462 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-19 12:52:12.877  3462  3462 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-19 12:52:12.907  1341  3180 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-19 12:52:12.917   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-19 12:52:12.917   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-19 12:52:12.917  3213  3213 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-19 12:52:12.917  3504  3504 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-19 12:52:12.917  3504  3504 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
03-19 12:52:12.917   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-19 12:52:12.917   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-19 12:52:12.917  3504  3504 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
03-19 12:52:12.917  3213  3213 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-19 12:52:12.917   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-19 12:52:12.917   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,03-19 12:52:12.927  3213  3213 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-19 12:52:12.927  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.927  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.927  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.927  1020  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.927  3347  3403 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-19 12:52:12.937  1341  3180 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-19 12:52:12.937  3576  3576 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.937  3576  3576 E Zygote  : v2
03-19 12:52:12.937  3576  3576 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:12.937  3576  3576 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.937  3576  3576 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:12.947  3576  3576 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:12.947  3576  3576 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:12.947  1020  1569 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3576 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-19 12:52:12.947  3183  3285 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-19 12:52:12.947   258   452 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-19 12:52:12.947  3347  3403 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
03-19 12:52:12.947   258   449 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-19 12:52:12.977  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:12.977  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:12.977  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-19 12:52:12.997  3538  3538 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-19 12:52:12.997  3576  3576 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.997  3576  3576 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.997  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:12.997  1020  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:12.997  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-19 12:52:13.037  2749  2825 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-19 12:52:13.037  3538  3538 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,03-19 12:52:13.037  3538  3538 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-19 12:52:13.037  3538  3538 D UserAnalysis: Create SecureDbHelper
,03-19 12:52:13.057  3538  3538 D IntelligenceServiceApplication: onCreate()
,03-19 12:52:13.057  3538  3538 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-19 12:52:13.067  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.067  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.067  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.067  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.067  3538  3538 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-19 12:52:13.077  3605  3605 E Zygote  : MountEmulatedStorage(),
,03-19 12:52:13.077  3605  3605 E Zygote  : v2
03-19 12:52:13.077  3605  3605 I libpersona: KNOX_SDCARD checking this for 10056
03-19 12:52:13.077  3605  3605 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:13.077  3605  3605 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-19 12:52:13.077  1020  1494 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3605 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-19 12:52:13.087  1020  1494 I ActivityManager: Killing 2669:com.android.keychain/1000 (adj 15): empty #31
,03-19 12:52:13.087  3605  3605 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:13.087  3605  3605 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.087  3538  3538 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-19 12:52:13.087  3347  3404 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
03-19 12:52:13.087  1020  1570 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.087  1020  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:13.087  1020  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-19 12:52:13.107  3605  3605 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-19 12:52:13.107  3605  3605 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:13.117  1199  1199 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:13.117  1199  1199 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:13.117  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:13.117  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:13.117  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:13.117  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:13.127  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2669/cgroup.procs: No such file or directory,
,03-19 12:52:13.167  3538  3538 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-19 12:52:13.167  3538  3538 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-19 12:52:13.167  3462  3563 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-19 12:52:13.167  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:13.167  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:13.167  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-19 12:52:13.177  3462  3462 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-19 12:52:13.187  1020  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-19 12:52:13.187  3576  3576 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-19 12:52:13.187  3576  3576 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-19 12:52:13.187  3576  3576 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-19 12:52:13.227   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-19 12:52:13.237  1341  3180 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-19 12:52:13.237  1341  3180 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-19 12:52:13.237  3576  3586 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-19 12:52:13.247  1020  1572 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.247  1020  1572 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:13.247  1020  1572 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-19 12:52:13.247  3312  3336 W art     : Suspending all threads took: 22.148ms
,03-19 12:52:13.247  3462  3462 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:13.257  3462  3462 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-19 12:52:13.257  3605  3605 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-19 12:52:13.257  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:13.257  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:13.257  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-19 12:52:13.267  3462  3462 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-19 12:52:13.267  3462  3462 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-19 12:52:13.277  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.277  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.277  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.277  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.277  3462  3462 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-19 12:52:13.287  3638  3638 E Zygote  : MountEmulatedStorage()
,03-19 12:52:13.287  3638  3638 E Zygote  : v2
03-19 12:52:13.287  3638  3638 I libpersona: KNOX_SDCARD checking this for 10058
03-19 12:52:13.287  3638  3638 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:13.287  3638  3638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:13.297  1020  1081 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3638 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-19 12:52:13.297  1020  1081 I ActivityManager: Killing 2713:com.android.chrome/u0a77 (adj 15): empty #31
,03-19 12:52:13.297  3638  3638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-19 12:52:13.297  3638  3638 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.297  3504  3504 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-19 12:52:13.297  3462  3462 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:13.297  3462  3462 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:13.297  3504  3504 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-19 12:52:13.297  3504  3504 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-19 12:52:13.307  1020  1570 I ActivityManager: Killing 2783:com.android.email/u0a141 (adj 15): empty #31
,03-19 12:52:13.317  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.317  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.317  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.317  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.327  3347  3404 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-19 12:52:13.327  3660  3660 E Zygote  : MountEmulatedStorage(),
03-19 12:52:13.327  3660  3660 E Zygote  : v2
03-19 12:52:13.327  3660  3660 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:13.327  3660  3660 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:13.327  3660  3660 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:13.337  3660  3660 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:13.337  3660  3660 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.347  1020  1081 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3660 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-19 12:52:13.347  1020  1081 I ActivityManager: Killing 2539:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
03-19 12:52:13.347  3638  3638 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.347  3638  3638 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.357  3660  3660 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.357   305   305 I art     : Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 20.704ms
,03-19 12:52:13.367  3660  3660 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.377  3462  3676 D OpenGLRenderer: Render dirty regions requested: true
,03-19 12:52:13.377   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 17.151ms
,03-19 12:52:13.377  1020  1081 I ActivityManager: Killing 2889:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-19 12:52:13.387  1020  1570 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-19 12:52:13.387  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-19 12:52:13.387  1020  1570 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-19 12:52:13.387  1020  1570 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-19 12:52:13.387  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-19 12:52:13.387  3462  3462 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-19 12:52:13.387  3462  3462 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-19 12:52:13.397   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.783ms
,03-19 12:52:13.397  3347  3404 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-19 12:52:13.407  1020  2861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:52:13.407  2620  3147 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3147)  
,03-19 12:52:13.407  1020  1497 I ActivityManager: Killing 2911:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-19 12:52:13.417  3347  3404 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-19 12:52:13.457  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2889/cgroup.procs: No such file or directory
,03-19 12:52:13.457  1020  1045 W libprocessgroup: failed to open /acct/uid_10039/pid_2539/cgroup.procs: No such file or directory
03-19 12:52:13.457  1020  1045 W libprocessgroup: failed to open /acct/uid_10077/pid_2713/cgroup.procs: No such file or directory
,03-19 12:52:13.457  1020  1045 W libprocessgroup: failed to open /acct/uid_10141/pid_2783/cgroup.procs: No such file or directory
03-19 12:52:13.457  1020  1045 W libprocessgroup: failed to open /acct/uid_10097/pid_2911/cgroup.procs: No such file or directory
,03-19 12:52:13.477  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:13.477  1020  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:13.477  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-19 12:52:13.487  1020  1081 I ActivityManager: Killing 2987:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-19 12:52:13.487  1020  1081 I ActivityManager: Killing 2943:org.simalliance.openmobileapi.service/1101 (adj 15): empty #32
,03-19 12:52:13.487  3660  3660 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-19 12:52:13.507  3638  3638 I ExternalOEMControlProvider: onCreate
,03-19 12:52:13.517   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-19 12:52:13.527  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.527  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.527  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.527  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.537  3684  3684 E Zygote  : MountEmulatedStorage()
,03-19 12:52:13.537  3684  3684 E Zygote  : v2
03-19 12:52:13.537  3684  3684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:13.537  3684  3684 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:13.537  1020  1033 D InputDispatcher: Focus entered window: 3462
03-19 12:52:13.537  3684  3684 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:13.537  1020  1309 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3684 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:13.537  1020  1309 I ActivityManager: Killing 2299:flipboard.app/u0a96 (adj 15): empty #31
,03-19 12:52:13.537  3684  3684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:13.537  3684  3684 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.537  1020  1497 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:52:13.577  3660  3660 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-19 12:52:13.617  3521  3699 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
03-19 12:52:13.617  3160  3323 I System.out: pool-10-thread-1 calls detatch()
,03-19 12:52:13.617  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:52:13.617  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 12:52:13.627  3462  3462 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-19 12:52:13.627  3462  3676 I OpenGLRenderer: Initialized EGL, version 1.4
,03-19 12:52:13.627  3462  3676 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-19 12:52:13.627  3462  3676 D OpenGLRenderer: Enabling debug mode 0
,03-19 12:52:13.627  3684  3684 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.627  3684  3684 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.647  1020  1571 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:52:13.657  1020  1045 W libprocessgroup: failed to open /acct/uid_1101/pid_2943/cgroup.procs: No such file or directory
03-19 12:52:13.657  1020  1045 W libprocessgroup: failed to open /acct/uid_10153/pid_2987/cgroup.procs: No such file or directory
03-19 12:52:13.657  1020  1045 W libprocessgroup: failed to open /acct/uid_10096/pid_2299/cgroup.procs: No such file or directory
,03-19 12:52:13.657  3521  3700 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-19 12:52:13.657  1020  1793 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:52:13.657  3576  3586 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-19 12:52:13.657  3312  3392 W GAV2    : Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-19 12:52:13.667  3684  3684 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-19 12:52:13.667  3660  3660 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-19 12:52:13.677  3660  3660 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-19 12:52:13.687  1020  1569 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.687  1020  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:13.687  1020  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-19 12:52:13.687  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.687  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:13.687  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-19 12:52:13.687  3213  3635 W MessageQueue: Handler (android.os.Handler) {7088ffb} sending message to a Handler on a dead thread
03-19 12:52:13.687  3213  3635 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {7088ffb} sending message to a Handler on a dead thread
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at ffw.a(SourceFile:327)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at guw.a(SourceFile:120)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at guf.c(SourceFile:26)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at gui.run(SourceFile:297)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:13.687  3213  3635 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 12:52:13.697  1020  1032 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-19 12:52:13.707  1020  3707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:52:13.707  1199  1199 I StatusBar: Icon Only
,03-19 12:52:13.707  1199  1199 D PanelView: There is/are notification(s) 
,03-19 12:52:13.717  1020  1051 I ActivityManager: Displayed Component not be shown by security: +1s346ms
,03-19 12:52:13.717  1020  1051 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-19 12:52:13.717  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{356683b4 u0 com.test.thalitest/.MainActivity t11} time:38765
03-19 12:52:13.717  1020  1051 W ActivityManager: mDVFSHelper.release()
,03-19 12:52:13.717  3684  3684 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-19 12:52:13.717  3684  3684 I ServiceMode: setReferenceIsDumpState : 0
,03-19 12:52:13.717  1020  1046 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-19 12:52:13.727  3462  3462 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@361f7936 time:38776
,03-19 12:52:13.747  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.747  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.747  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.747  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.757  1020  1570 V VibratorService: hasVibrator - useVibetonz: true
,03-19 12:52:13.757  3711  3711 E Zygote  : MountEmulatedStorage()
03-19 12:52:13.757  3711  3711 E Zygote  : v2
03-19 12:52:13.757  3711  3711 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:13.757  3711  3711 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:13.757  3711  3711 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:13.757  3711  3711 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:13.757  1020  1793 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3711 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:13.757  3711  3711 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.767  3312  3520 I ContactAccountLoggerTas: canRun() : Opted Out
,03-19 12:52:13.777  3711  3711 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.787  3711  3711 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.787  2009  2009 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
03-19 12:52:13.787  3312  3392 W GAV2    : Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-19 12:52:13.787  3312  3520 I ContactAccountLoggerTas: canRun() : Opted Out
03-19 12:52:13.787  3312  3392 I ContactAccountLoggerTas: canRun() : Opted Out
,03-19 12:52:13.787  3312  3520 I ContactAccountLoggerTas: canRun() : Opted Out
,03-19 12:52:13.797  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.797  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:13.797  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-19 12:52:13.807  2009  2009 D SecUISvc: Service started flags 0 startId 1
,03-19 12:52:13.807  2009  3728 D SecUISvc: Thread created.
,03-19 12:52:13.817  1020  1507 I art     : Explicit concurrent mark sweep GC freed 25640(1432KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/33MB, paused 12.880ms total 270.235ms
,03-19 12:52:13.817  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.817  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.817  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.817  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.827  3730  3730 E Zygote  : MountEmulatedStorage(),
,03-19 12:52:13.827  3730  3730 E Zygote  : v2
03-19 12:52:13.827  3730  3730 I libpersona: KNOX_SDCARD checking this for 10026
03-19 12:52:13.827  3730  3730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:13.827  3730  3730 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:13.827  1020  1793 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-19 12:52:13.827  1020  1793 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:13.827  1020  1793 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:13.827  1020  1793 D SettingsProvider: selectionArgs: false
03-19 12:52:13.827  1020  1793 D SettingsProvider: selectionArgs: 10058
03-19 12:52:13.827  1020  1793 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:13.827  1020  1793 D SettingsProvider: ret = -1
,03-19 12:52:13.827  3730  3730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:13.837  3730  3730 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.837  1020  1081 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3730 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:52:13.847  3213  3636 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
03-19 12:52:13.847  3213  3636 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-19 12:52:13.847  3213  3636 I System.out: Thread-459(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-19 12:52:13.847  3660  3660 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-19 12:52:13.847  3213  3636 I System.out: Thread-459(ApacheHTTPLog):isSBSettingEnabled false
03-19 12:52:13.847  3213  3636 I System.out: Thread-459(ApacheHTTPLog):isShipBuild true
03-19 12:52:13.847  3213  3636 I System.out: Thread-459(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-19 12:52:13.847  3213  3636 I System.out: Thread-459(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-19 12:52:13.857   276   944 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-19 12:52:13.857   276   944 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-19 12:52:13.857  3730  3730 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.857  3730  3730 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.937  1341  3180 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-19 12:52:13.937  3711  3711 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-19 12:52:13.937  3711  3711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-19 12:52:13.937  1020  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:13.937  1020  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:13.937  1020  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-19 12:52:13.947  3711  3711 D NPS_WSSNPS: [] Service onCreate!!
,03-19 12:52:13.947  3183  3285 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
03-19 12:52:13.947  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.947  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.947  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.947  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.947  3521  3521 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-19 12:52:13.957  3752  3752 E Zygote  : MountEmulatedStorage()
03-19 12:52:13.957  3752  3752 E Zygote  : v2
03-19 12:52:13.957  3752  3752 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:13.957  3752  3752 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:13.957  3752  3752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:13.967  3752  3752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:13.967  1020  1570 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3752 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-19 12:52:13.967  3752  3752 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.967  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.967  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:13.967  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-19 12:52:13.977  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:13.977  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:13.987  3711  3759 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-19 12:52:13.987  3660  3660 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-19 12:52:13.987  3660  3660 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-19 12:52:13.987  3711  3711 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-19 12:52:13.997  3660  3660 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-19 12:52:13.997  3660  3660 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-19 12:52:13.997  3660  3660 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-19 12:52:13.997  3660  3660 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-19 12:52:14.007  3752  3752 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.007  3752  3752 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.007  1862  1862 I SamsungIME: getCurrentCandidateView
,03-19 12:52:14.007  1020  1793 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-19 12:52:14.007   258  1928 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-19 12:52:14.007   258  1042 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-19 12:52:14.007  1020  1569 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-19 12:52:14.007  1020  1569 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:14.007  1020  1569 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:14.007  1020  1569 D SettingsProvider: selectionArgs: false
03-19 12:52:14.007  1020  1569 D SettingsProvider: selectionArgs: 10058
03-19 12:52:14.007  1020  1569 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:14.007  1020  1569 D SettingsProvider: ret = -1
,03-19 12:52:14.017  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:14.027  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-19 12:52:14.027  1020  1569 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-19 12:52:14.037  3711  3711 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-19 12:52:14.047  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:14.067  1020  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.067  1020  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.067  1020  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.077  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.077  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.077  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.097  3711  3776 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-19 12:52:14.097  3711  3776 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-19 12:52:14.097  3711  3776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-19 12:52:14.097  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.097  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:14.097  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-19 12:52:14.107  3711  3711 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-19 12:52:14.117  3312  3393 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-19 12:52:14.117  3394  3394 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-19 12:52:14.127  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.127  1020  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.127  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-19 12:52:14.127  3312  3393 I LibraryLoader: Loading: webviewchromium
,03-19 12:52:14.127  3711  3711 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-19 12:52:14.137  3312  3393 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9175-9180)
03-19 12:52:14.137  3312  3393 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 12:52:14.137  3711  3711 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-19 12:52:14.137  3711  3711 I NPS_WSSNPS: [50.150321] smlBREmailDelete
03-19 12:52:14.137  1020  1571 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.137  1020  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.137  1020  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-19 12:52:14.137  3711  3711 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-19 12:52:14.137  3394  3394 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-19 12:52:14.137  3711  3711 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-19 12:52:14.137  3711  3711 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-19 12:52:14.137  3711  3711 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
,03-19 12:52:14.137  3711  3711 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-19 12:52:14.137  3711  3711 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-19 12:52:14.137  3394  3394 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-19 12:52:14.147  3711  3711 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-19 12:52:14.147  1020  1032 I ActivityManager: Killing 1173:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-19 12:52:14.147  1020  1570 D SettingsProvider: name = access_control_enabled
,03-19 12:52:14.157  3312  3393 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:14.167  3394  3394 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-19 12:52:14.167  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.167  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.167  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.167  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.177  3788  3788 E Zygote  : MountEmulatedStorage()
03-19 12:52:14.177  3788  3788 E Zygote  : v2
03-19 12:52:14.177  3788  3788 I libpersona: KNOX_SDCARD checking this for 10065
03-19 12:52:14.177  3788  3788 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.177  3788  3788 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:14.177  3788  3788 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:14.177  3788  3788 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:14.187  1020  1032 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3788 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:52:14.187  1020  1032 I ActivityManager: Killing 3007:com.sec.usbsettings/1000 (adj 15): empty #31
,03-19 12:52:14.187  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.187  3521  3786 E Gmail   : Error finding the version of the Email provider.....
03-19 12:52:14.187  3521  3786 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-19 12:52:14.187  3521  3786 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-19 12:52:14.187  3521  3786 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-19 12:52:14.187  3521  3786 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-19 12:52:14.187  3521  3786 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:14.187  3521  3786 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:14.187  3521  3786 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:14.187  3521  3786 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:52:14.187  3521  3786 W EmailMigration: We do not support migrating this version of the Email provider.
03-19 12:52:14.187  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.187  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.187  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.207  3799  3799 E Zygote  : MountEmulatedStorage()
03-19 12:52:14.207  3799  3799 E Zygote  : v2
03-19 12:52:14.207  3799  3799 I libpersona: KNOX_SDCARD checking this for 10013
03-19 12:52:14.207  3799  3799 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:14.207  1020  1032 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3799 uid=10013 gids={50013, 9997} abi=armeabi-v7a
03-19 12:52:14.207  1020  1032 I ActivityManager: Killing 2427:com.android.mms/u0a41 (adj 15): empty #31
,03-19 12:52:14.207  3799  3799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:14.217  3799  3799 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:14.217  1020  1570 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.217  1020  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.217  1020  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-19 12:52:14.217  3799  3799 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-19 12:52:14.217  3788  3788 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.217  3788  3788 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.257  3462  3462 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-19 12:52:14.277  3799  3799 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.277  1862  1862 D SamsungIME: Dismiss ExpandCandiate
,03-19 12:52:14.287  3799  3799 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.287  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.287  1020  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.287  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-19 12:52:14.287  1020  1570 D CountryDetector: No listener is left
,03-19 12:52:14.307  1020  1507 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-19 12:52:14.307  1020  1506 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-19 12:52:14.317  1020  1569 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:52:14.317  1020  1494 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-19 12:52:14.317  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:14.327  1020  1045 W libprocessgroup: failed to open /acct/uid_10003/pid_1173/cgroup.procs: No such file or directory
,03-19 12:52:14.337  1020  1309 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.337  1020  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.337  1020  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.337  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3007/cgroup.procs: No such file or directory
03-19 12:52:14.337  1020  1045 W libprocessgroup: failed to open /acct/uid_10041/pid_2427/cgroup.procs: No such file or directory
,03-19 12:52:14.337  1020  1793 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.337  1020  1793 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.337  1020  1793 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-19 12:52:14.337  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:14.347  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:14.347  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.347  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.347  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.347  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.357  3462  3709 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-19 12:52:14.357  3462  3709 I chromium: 
,03-19 12:52:14.367  3828  3828 E Zygote  : MountEmulatedStorage()
,03-19 12:52:14.367  3828  3828 E Zygote  : v2
03-19 12:52:14.367  3828  3828 I libpersona: KNOX_SDCARD checking this for 10102
03-19 12:52:14.367  3828  3828 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.367  3828  3828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:14.367  3828  3828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:14.367  3828  3828 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-19 12:52:14.377  1020  1571 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3828 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-19 12:52:14.377  1020  1497 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:52:14.397  3828  3828 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.397  3828  3828 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.397  3521  3826 I Gmail   : Observing account changes for notifications
,03-19 12:52:14.407  3799  3799 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-19 12:52:14.417  3521  3702 I Gmail   : getAccountsCursor
,03-19 12:52:14.427  1020  3823 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.427  1020  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.427  1020  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-19 12:52:14.437  3788  3788 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-19 12:52:14.467  1674  3827 I GoogleHttpClient: GMS http client unavailable, use old client
,03-19 12:52:14.477  3828  3828 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:52:14.477  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.477  1020  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.477  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
03-19 12:52:14.477  3730  3730 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-19 12:52:14.487  1020  1793 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.487  1020  1793 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.487  1020  1793 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.497  1862  1862 I SamsungIME: getDebugLevel  : 0x4f4c
,03-19 12:52:14.497  1020  1309 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:52:14.497  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:14.507  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:14.507  1020  1793 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.507  1020  1793 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.507  1020  1793 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 12:52:14.517  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.517  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.517  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-19 12:52:14.517  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.517  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.517  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-19 12:52:14.527  3799  3846 V OneTimeService: OneTimeService.onHandleIntent
03-19 12:52:14.527  1020  1309 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.527  1020  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.527  1020  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 12:52:14.557  1020  1032 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:52:14.557  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.557  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.557  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 12:52:14.577  1020  1309 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.577  1020  1309 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:14.577  1020  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-19 12:52:14.577  1762  1762 I Hs20UtilService: Starting #5
,03-19 12:52:14.577  1762  1799 I Hs20UtilService: Message received 5003
03-19 12:52:14.577  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.577  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.577  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.577  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.597  3859  3859 E Zygote  : MountEmulatedStorage()
03-19 12:52:14.597  3859  3859 E Zygote  : v2
03-19 12:52:14.597  3859  3859 I libpersona: KNOX_SDCARD checking this for 10018
03-19 12:52:14.597  3859  3859 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.607  1020  3822 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3859 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,03-19 12:52:14.607  1020  3823 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,03-19 12:52:14.607  3462  3845 D jxcore_app_log: JniHelper::setJavaVM(0xb82d0448), pthread_self() = -1198343192
,03-19 12:52:14.627  1020  1309 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-19 12:52:14.627  3462  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-19 12:52:14.627  3462  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-19 12:52:14.627  3462  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-19 12:52:14.627  3462  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-19 12:52:14.627  3462  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-19 12:52:14.627  3521  3521 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@3933ca96 that was originally bound here
03-19 12:52:14.627  3521  3521 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@3933ca96 that was originally bound here
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:14.627  3521  3521 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:52:14.627  3462  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cb497d added. We now have 1 listener(s)
,03-19 12:52:14.627  1020  1569 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@2e9c63c4
03-19 12:52:14.637  3462  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
03-19 12:52:14.637  3462  3845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
03-19 12:52:14.637  3462  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-19 12:52:14.637  3462  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-19 12:52:14.647  3462  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fbfe940 added. We now have 1 listener(s)
03-19 12:52:14.647  3462  3845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-19 12:52:14.657  3859  3859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:14.667  3859  3859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:14.667  3859  3859 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:14.667  3462  3845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-19 12:52:14.667  3213  3636 I System.out: Thread-459 calls detatch()
03-19 12:52:14.667  3462  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-19 12:52:14.667  3462  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-19 12:52:14.667  3462  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-19 12:52:14.667  3462  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-19 12:52:14.677  3462  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-19 12:52:14.677  3462  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
03-19 12:52:14.687  3859  3859 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:14.687  3859  3859 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:14.697  3462  3845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 12:52:14.697  3462  3845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 12:52:14.697  3462  3845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-19 12:52:14.697  3462  3845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 12:52:14.697  3462  3845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-19 12:52:14.697  3462  3845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-19 12:52:14.697  3462  3845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-19 12:52:14.697  3462  3845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-19 12:52:14.697  3462  3845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-19 12:52:14.697  3462  3845 D io.jxcore.node.ConnectivityMonitor: start: OK
03-19 12:52:14.697  3462  3845 I io.jxcore.node.LifeCycleMonitor: start: OK
03-19 12:52:14.707  3462  3462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-19 12:52:14.707  3462  3462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 12:52:14.717  3521  3815 E SQLiteLog: (283) recovered 30 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-19 12:52:14.727  2658  2735 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-19 12:52:14.767  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.767  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:14.767  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 12:52:14.787  3859  3859 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Mar 19 12:52:14 GMT+01:00 2016
,03-19 12:52:14.797  1020  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.797  1020  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:14.797  1020  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-19 12:52:14.797  3859  3859 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-19 12:52:14.807  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.807  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.807  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.807  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.807  3859  3859 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-19 12:52:14.817   276   944 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-19 12:52:14.817   276   944 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-19 12:52:14.817  3888  3888 E Zygote  : MountEmulatedStorage()
03-19 12:52:14.817  3888  3888 I libpersona: KNOX_SDCARD checking this for 10020
03-19 12:52:14.817  3888  3888 E Zygote  : v2
03-19 12:52:14.817  3888  3888 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.827  3888  3888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:14.827  3888  3888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:14.827  3888  3888 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:14.827  3859  3859 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-19 12:52:14.847  1020  1793 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3888 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a,
,03-19 12:52:14.857  3462  3462 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-19 12:52:14.857  3888  3888 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.857  3888  3888 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.877  1341  3180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-19 12:52:14.887  1341  3180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
03-19 12:52:14.887  3367  3367 I RlzPingService: Setting next ping for 1458993134816
03-19 12:52:14.887  3462  3477 I art     : Background sticky concurrent mark sweep GC freed 24247(1685KB) AllocSpace objects, 8(128KB) LOS objects, 8% free, 7MB/7MB, paused 1.006ms total 104.640ms
,03-19 12:52:14.897  1341  3180 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-19 12:52:14.907  3859  3859 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-19 12:52:14.927  3312  3393 I qtaguid : Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:14.927  3859  3882 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-19 12:52:14.937  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.937  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.937  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.937  1862  1862 I SamsungIME: getDebugLevel  : 0x4f4c
,03-19 12:52:14.947  3859  3882 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
,03-19 12:52:14.967  3183  3285 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-19 12:52:14.967  3730  3730 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-19 12:52:14.987  1020  1572 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.987  1020  1572 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:14.987  1020  1572 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:15.017  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
03-19 12:52:15.017  1020  1020 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-19 12:52:15.027  3730  3730 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-19 12:52:15.027  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.027  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.027  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.027  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:15.027  3730  3730 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-19 12:52:15.047  3916  3916 E Zygote  : MountEmulatedStorage()
03-19 12:52:15.047  1020  1020 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3916 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-19 12:52:15.047  3916  3916 E Zygote  : v2,
03-19 12:52:15.047  3916  3916 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:15.047  3916  3916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:15.047  3916  3916 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:15.047  3916  3916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:15.047  3916  3916 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:15.097  1862  1862 I SamsungIME: KeybaordView init() : load resources
,03-19 12:52:15.117  1674  1693 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-19 12:52:15.117  1674  2224 I art     : Explicit concurrent mark sweep GC freed 3771(165KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 889us total 34.226ms
,03-19 12:52:15.127  3916  3916 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:15.127  3916  3916 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:15.147  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:15.147  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:15.147  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:15.147  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:15.167  3938  3938 E Zygote  : MountEmulatedStorage(),
03-19 12:52:15.167  3938  3938 E Zygote  : v2
03-19 12:52:15.167  3938  3938 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:15.167  3938  3938 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:15.167  1020  1309 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-19 12:52:15.167  1020  1309 I ActivityManager: Killing 2927:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-19 12:52:15.187  3938  3938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-19 12:52:15.187  3938  3938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:15.187  3938  3938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:15.187   305   305 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 22.758ms,
,03-19 12:52:15.207  3521  3815 E File    : fail readDirectory() errno=2
,03-19 12:52:15.207   289   289 E SMD     : DCD OFF,
,03-19 12:52:15.207   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 17.721ms
,03-19 12:52:15.227  3521  3848 I Gmail   : notifyAccountChanged
,03-19 12:52:15.237   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 21.122ms
,03-19 12:52:15.237  3521  3699 I Gmail   : getAccountsCursor
,03-19 12:52:15.267  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:15.277  3938  3938 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:15.277  3938  3938 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:15.277  1980  2965 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-19 12:52:15.277  1980  2965 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-19 12:52:15.277  3521  3848 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-19 12:52:15.277  1980  2965 I System.out: (HTTPLog)-Static: isShipBuild true
03-19 12:52:15.277  1980  2965 I System.out: (HTTPLog)-Thread-219-687660641: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-19 12:52:15.277  1980  2965 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-19 12:52:15.287   276   944 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-19 12:52:15.287   276   944 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-19 12:52:15.297  3859  3859 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-19 12:52:15.337  2620  2620 D FactoryTestApp: [DummyFtClient$onDestroy](2620) Destroy DummyFtClient service
,03-19 12:52:15.337  1862  1862 I SamsungIME: getCurrentKeyboard
03-19 12:52:15.337  1862  1862 I SamsungIME: getTextKeyboard
,03-19 12:52:15.337  2620  2620 D FactoryTestApp: [Support$Values.getString](2620) id=MODEL_COMMUNICATION_MODE, value=gsm
03-19 12:52:15.337  2620  2620 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2620) mConnectionMode = gsm
03-19 12:52:15.337  2620  2620 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2620) RUNNING_FTCLIENT : false
03-19 12:52:15.337  2620  2620 D FactoryTestApp: [DummyFtClient$onDestroy](2620) kill process
03-19 12:52:15.337  2620  2620 I Process : Sending signal. PID: 2620 SIG: 9
,03-19 12:52:15.347  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
03-19 12:52:15.347  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.357  1980  2965 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
03-19 12:52:15.357  1980  2965 I qtaguid : Tagging socket 55 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1980, getuid(): 10011
,03-19 12:52:15.357  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.357  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.367  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.367  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.367  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.367  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.367  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
03-19 12:52:15.367  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.367  3828  3959 I Babel   : MmsConfig: mnc/mcc: 0/0
03-19 12:52:15.367  3828  3959 I Babel   : MmsConfig.loadMmsSettings
03-19 12:52:15.367  3828  3959 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-19 12:52:15.367  3828  3959 I Babel   : MmsConfig.loadFromDatabase
,03-19 12:52:15.367  3521  3848 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-19 12:52:15.377  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.377  3312  3393 I qtaguid : Untagging socket 43
03-19 12:52:15.377  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.377  3312  3393 I qtaguid : Untagging socket 43
03-19 12:52:15.377  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.377  3312  3393 I qtaguid : Untagging socket 43
03-19 12:52:15.377  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.377  3312  3393 I qtaguid : Untagging socket 43
03-19 12:52:15.377  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.377  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.377  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
03-19 12:52:15.377  1020  1309 I ActivityManager: Killing 3030:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
03-19 12:52:15.387  1020  1572 I ActivityManager: Killing 3060:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
03-19 12:52:15.387  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
03-19 12:52:15.417  1020  1045 W libprocessgroup: failed to open /acct/uid_10081/pid_2927/cgroup.procs: No such file or directory
03-19 12:52:15.457  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.397  1020  3823 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:15.457  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
03-19 12:52:15.457  1020  3823 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:15.457  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.457  1020  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-19 12:52:15.457  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
03-19 12:52:15.457  3312  3393 I qtaguid : Untagging socket 43
,03-19 12:52:15.427  3730  3961 D Ads     : Skipping gmscore version check
,03-19 12:52:15.427  3730  3883 D Volley  : [526] g.b: Cache cleared.
,03-19 12:52:15.427  3730  3849 D Volley  : [520] g.b: Cache cleared.
,03-19 12:52:15.477  3828  3959 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-19 12:52:15.477  3828  3959 I Babel   : MmsConfig.loadFromResources
,03-19 12:52:15.477  3828  3959 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-19 12:52:15.477  3828  3959 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-19 12:52:15.477  1020  1081 I ActivityManager: Killing 2749:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,03-19 12:52:15.487  3730  3730 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-19 12:52:15.497  1020  1507 I art     : Explicit concurrent mark sweep GC freed 18302(996KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 5.454ms total 181.870ms
,03-19 12:52:15.497  3730  3730 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-19 12:52:15.497  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:15.497  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.497  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.497  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.497  3730  3730 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-19 12:52:15.447  1862  1862 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-19 12:52:15.517  3963  3963 E Zygote  : MountEmulatedStorage()
,03-19 12:52:15.517  3963  3963 E Zygote  : v2
03-19 12:52:15.517  3963  3963 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:15.517  3963  3963 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:15.517  3963  3963 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-19 12:52:15.517  1020  1081 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3963 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-19 12:52:15.527  3963  3963 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:15.527  3963  3963 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:15.547  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:15.547  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:15.547  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:15.547  1980  2965 I qtaguid : Tagging socket 68 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1980, getuid(): 10011
,03-19 12:52:15.557  1020  1494 I ActivityManager: Process com.sec.factory (pid 2620)(adj 0) has died(42,649)
,03-19 12:52:15.557  3828  3953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-19 12:52:15.567  3828  3842 W art     : Suspending all threads took: 8.792ms
,03-19 12:52:15.607  3963  3963 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:15.607  3963  3963 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:15.607  1020  1045 W libprocessgroup: failed to open /acct/uid_10043/pid_3030/cgroup.procs: No such file or directory
,03-19 12:52:15.617  3938  3938 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-19 12:52:15.627  3521  3848 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-19 12:52:15.627  3521  3848 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-19 12:52:15.637  1020  1572 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:15.637  1020  1572 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:15.637  1020  1572 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-19 12:52:15.637  3828  3828 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-19 12:52:15.637  1020  1494 D SecContentProvider2: uri = 14 selection = getSealedState
,03-19 12:52:15.637  1020  1494 D SecContentProvider2: mCursor = null
,03-19 12:52:15.637  3828  3953 W AudioCapabilities: Unsupported mime audio/evrc
,03-19 12:52:15.647  3963  3963 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-19 12:52:15.657  3828  3953 W AudioCapabilities: Unsupported mime audio/qcelp
,03-19 12:52:15.657  1020  3822 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-19 12:52:15.657  1020  3822 D SecContentProvider2: mCursor = null
,03-19 12:52:15.667  1020  1309 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:15.667  1020  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:15.667  1020  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-19 12:52:15.667  3938  3938 V MTPRx   : sealedState: false
03-19 12:52:15.667  3938  3938 V MTPRx   : sealedUsbMassStorageState: false
,03-19 12:52:15.687  1020  1570 D SettingsProvider: name = mtp_usb_connection_status
,03-19 12:52:15.687  3828  3953 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-19 12:52:15.687  3828  3953 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-19 12:52:15.697  2173  3914 I Icing   : Storage manager: low false usage 2.12MB avail 9.95GB capacity 11.63GB
,03-19 12:52:15.707  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3060/cgroup.procs: No such file or directory
,03-19 12:52:15.707  1020  1045 W libprocessgroup: failed to open /acct/uid_10117/pid_2749/cgroup.procs: No such file or directory
,03-19 12:52:15.707  3730  3730 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-19 12:52:15.717  2173  3974 D FileApkUtils: Optimizing (staging complete)
,03-19 12:52:15.717  2173  3974 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-19 12:52:15.717  2173  3974 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-19 12:52:15.717  1020  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:15.717  1020  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:15.717  1020  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-19 12:52:15.727  2173  3974 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,03-19 12:52:15.727  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:15.727  3963  3963 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-19 12:52:15.737  1020  1033 D SettingsProvider: name = media_player_mode
,03-19 12:52:15.747  1020  1793 D SettingsProvider: name = mtp_usb_conditions_met
,03-19 12:52:15.747  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:15.747  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 12:52:15.747  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-19 12:52:15.757  3828  3842 W art     : Suspending all threads took: 11.700ms
,03-19 12:52:15.757  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.757  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.757  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.757  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:15.767  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:15.767  1020  1572 D SettingsProvider: name = mtp_running_status
,03-19 12:52:15.777  3986  3986 E Zygote  : MountEmulatedStorage()
,03-19 12:52:15.777  3986  3986 E Zygote  : v2
,03-19 12:52:15.777  3986  3986 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:15.777  3986  3986 I libpersona: KNOX_SDCARD not a persona,
,03-19 12:52:15.777  3986  3986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-19 12:52:15.777  1020  1494 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3986 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-19 12:52:15.787  3986  3986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:15.787  3986  3986 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:15.797  3963  3963 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-19 12:52:15.797  3963  3963 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-19 12:52:15.817  3312  3393 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3312, getuid(): 10052
,03-19 12:52:15.817  3312  3520 I ContactAccountLoggerTas: canRun() : Opted Out
,03-19 12:52:15.827  1020  1571 D SettingsProvider: name = media_mount_count
,03-19 12:52:15.827  3462  3877 W jxcore-log: Initializing JXcore engine
03-19 12:52:15.827  3462  3877 W jxcore-log: JXcore engine is ready
,03-19 12:52:15.827  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:15.827  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:15.827  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:15.837  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:15.837  1020  1569 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:15.837  1020  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:15.837  1020  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-19 12:52:15.847  3730  3730 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.,
,03-19 12:52:15.857  1020  1032 D SettingsProvider: name = mtp_sync_alive
,03-19 12:52:15.857  3828  3953 W AudioCapabilities: Unsupported mime audio/x-ms-wma
03-19 12:52:15.857  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:15.877  1020  1507 D SettingsProvider: name = sdcard_launch
,03-19 12:52:15.877  3986  3986 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:15.877  3986  3986 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:15.897  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:15.897  1935  1935 E audit   : type=1400 msg=audit(1458388335.897:205): avc:  denied  { ioctl } for  pid=3877 comm="Thread-482" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-19 12:52:15.897  1935  1935 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:15.897  1935  1935 E audit   : type=1300 msg=audit(1458388335.897:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9304b8f8 items=0 ppid=305 ppcomm=main pid=3877 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-482" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-19 12:52:15.897  1935  1935 E audit   : type=1320 msg=audit(1458388335.897:205): 
,03-19 12:52:15.897  1020  1571 D SettingsProvider: name = boot_time_connected
,03-19 12:52:15.897  3828  3953 W AudioCapabilities: Unsupported mime audio/x-ima
,03-19 12:52:15.907  3462  3877 W jxcore-log: Starting JXcore engine
,03-19 12:52:15.917  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:15.927  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:15.937  1020  1494 D SettingsProvider: name = mtp_open_session
,03-19 12:52:15.947  3963  3963 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-19 12:52:15.947  3963  3963 I F_PHONE : default registerAction()
03-19 12:52:15.947  3963  3963 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-19 12:52:15.947  1020  3823 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:15.947  1020  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:15.947  1020  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:15.967  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:15.977  3347  3403 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-19 12:52:16.007  3828  3953 W AudioCapabilities: Unsupported mime audio/qcelp
,03-19 12:52:16.017  3183  3285 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-19 12:52:16.017  1980  2965 D GCM     : COMPAT: Multi user not supported
,03-19 12:52:16.027  3986  3986 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-19 12:52:16.027  3828  3953 W AudioCapabilities: Unsupported mime audio/evrc
,03-19 12:52:16.037  3576  3576 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-19 12:52:16.037  3576  3576 I PCWCLIENTTRACE_PushUtil: sales region : global
03-19 12:52:16.037  3576  3576 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-19 12:52:16.037  3576  3576 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
,03-19 12:52:16.037  3576  3576 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-19 12:52:16.037  3576  3576 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-19 12:52:16.047  3986  3986 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-19 12:52:16.047  3986  3986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
03-19 12:52:16.047  3462  3877 W jxcore-log: Platform android
03-19 12:52:16.047  3462  3877 W jxcore-log: 
03-19 12:52:16.047  3462  3877 W jxcore-log: Process ARCH arm
03-19 12:52:16.047  3462  3877 W jxcore-log: 
,03-19 12:52:16.057  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:16.057  1020  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:16.057  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-19 12:52:16.067  1483  1483 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-19 12:52:16.087  1980  1980 D ChimeraCfgMgr: Reading stored module config
,03-19 12:52:16.107  1483  1483 D BluetoothBDTestService: onCreate()
,03-19 12:52:16.107  1483  1483 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-19 12:52:16.107  1483  1483 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-19 12:52:16.117  1483  1483 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-19 12:52:16.117  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:16.117  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.117  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.117  1020  1309 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:16.127  3828  3953 W VideoCapabilities: Unsupported mime video/wvc1
,03-19 12:52:16.137  3828  3953 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-19 12:52:16.137  4013  4013 E Zygote  : MountEmulatedStorage(),
03-19 12:52:16.137  4013  4013 E Zygote  : v2
03-19 12:52:16.137  4013  4013 I libpersona: KNOX_SDCARD checking this for 1000
,03-19 12:52:16.137  4013  4013 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:16.137  4013  4013 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:16.137  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-19 12:52:16.137  3916  3962 I AMMetaDataParserService: Resource data:Inside bundle  check
03-19 12:52:16.137  4013  4013 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:16.137  3916  3962 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-19 12:52:16.137  3916  3962 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-19 12:52:16.137  3916  3962 I AMMetaDataParserService: Resource data:2131165186
,03-19 12:52:16.137  4013  4013 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:16.147  3916  3962 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-19 12:52:16.147  3916  3962 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 12:52:16.147  3916  3962 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-19 12:52:16.147  3916  3962 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-19 12:52:16.147  1020  1309 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4013 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-19 12:52:16.147  3576  3576 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-19 12:52:16.147  3347  3403 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-19 12:52:16.157  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-19 12:52:16.157  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-19 12:52:16.157  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-19 12:52:16.157  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-19 12:52:16.167  1020  1571 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:16.167  1020  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:16.167  1020  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-19 12:52:16.167  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-19 12:52:16.167  3916  3962 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-19 12:52:16.167  3916  3962 I AMMetaDataParserService: getResourceTypeNamexml
,03-19 12:52:16.167  3347  3403 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-19 12:52:16.167  3828  3828 V Babel   : babel boot account: SMS
,03-19 12:52:16.167  3828  3828 V Babel   : babel boot account: thalitester@gmail.com
,03-19 12:52:16.177  4013  4013 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:16.177  4013  4013 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:16.177  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.177  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.177  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.177  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:16.177  3916  3962 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-19 12:52:16.187  4030  4030 E Zygote  : MountEmulatedStorage()
,03-19 12:52:16.187  4030  4030 E Zygote  : v2
03-19 12:52:16.187  4030  4030 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:16.187  4030  4030 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:16.187  4030  4030 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:16.197  1020  1506 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4030 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-19 12:52:16.197  1020  1506 I ActivityManager: Killing 1610:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
03-19 12:52:16.197  4030  4030 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:16.197  4030  4030 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:16.207  3916  3962 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-19 12:52:16.227  4030  4030 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:16.227  4030  4030 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:16.227  1020  3822 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1199 (0x0)
,03-19 12:52:16.237  3312  3520 I ContactAccountLoggerTas: canRun() : Opted Out
,03-19 12:52:16.237  3916  3962 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,03-19 12:52:16.247  3576  3576 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-19 12:52:16.247  1980  1980 D WearableService: callingUid 10011, callindPid: 1980
,03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataP,arserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-19 12:52:16.247  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-19 12:52:16.257  3916  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-19 12:52:16.267  3576  3576 I ReactiveServiceManager: Supported : 1
03-19 12:52:16.267  1020  1100 V AlarmManager: waitForAlarm result :4
03-19 12:52:16.267  1020  3823 I ActivityManager: Killing 3082:com.google.android.configupdater/u0a82 (adj 15): empty #31
03-19 12:52:16.277  1020  1793 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-19 12:52:16.277  1020  1793 D QSEECOMAPI: : App is not loaded in QSEE
,03-19 12:52:16.287  1020  1793 D QSEECOMAPI: : Loaded image: APP id = 9
,03-19 12:52:16.297  1980  1980 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-19 12:52:16.297  3828  3953 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-19 12:52:16.297  1020  1793 D QSEECOMAPI: : QSEECom_dealloc_memory ,
03-19 12:52:16.297  1020  1793 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-19 12:52:16.307  1020  1793 E terrier : handleString: Failed to handle string(-4)
03-19 12:52:16.307  1020  1793 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-19 12:52:16.307  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,03-19 12:52:16.307  3916  3962 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-19 12:52:16.307  3916  3962 I AMMetaDataParserService: getResourcePackageName:assistant
03-19 12:52:16.307  3916  3962 I AMMetaDataParserService: Resource data:2131034113
,03-19 12:52:16.307  1020  1100 V AlarmManager: waitForAlarm result :4
,03-19 12:52:16.307  3576  3576 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-19 12:52:16.307  3576  3576 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-19 12:52:16.307  3576  3576 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-19 12:52:16.307  3576  3576 I PCWCLIENTTRACE_PushUtil: sales region : global
03-19 12:52:16.307  3576  3576 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-19 12:52:16.307  3576  3576 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-19 12:52:16.307  3916  3962 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-19 12:52:16.307  3916  3962 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 12:52:16.307  3916  3962 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-19 12:52:16.307  3828  3953 W VideoCapabilities: Unsupported mime video/wvc1
,03-19 12:52:16.317  3916  3962 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-19 12:52:16.317  3916  3962 I AMMetaDataParserService: getResourceTypeNamexml
,03-19 12:52:16.317  4013  4013 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 12:52:16.317  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:16.317  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:16.317  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.317  1020  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:16.327  3462  3877 I jxcore-log: JXcore Cordova bridge is ready!
03-19 12:52:16.327  3462  3877 I jxcore-log: 
03-19 12:52:16.327  3462  3877 W jxcore-log: JXcore engine is started
,03-19 12:52:16.327  3828  3953 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-19 12:52:16.337  3828  3953 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-19 12:52:16.337  3462  3845 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-19 12:52:16.337  3828  3953 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-19 12:52:16.347  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:16.347  1020  1570 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4049 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-19 12:52:16.347  4049  4049 E Zygote  : MountEmulatedStorage()
03-19 12:52:16.347  4049  4049 E Zygote  : v2
03-19 12:52:16.347  4049  4049 I libpersona: KNOX_SDCARD checking this for 10028
03-19 12:52:16.347  4049  4049 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:16.347  4049  4049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-19 12:52:16.347  1020  1570 I ActivityManager: Killing 3160:com.dropbox.android/u0a88 (adj 15): empty #31
03-19 12:52:16.347  3916  3962 I GFX construct_block_size_descriptor_2d second part: took 2.417188ms for 0*0 texture 0
03-19 12:52:16.347  3462  3462 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
03-19 12:52:16.347  4049  4049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:16.347  4049  4049 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-19 12:52:16.357  3916  3962 I GFX generate_partition_tables: took 10.281354ms for 0*0 texture 0
,03-19 12:52:16.357  3916  3962 I GFX raster: took 13.996459ms for 96*96 texture 0
03-19 12:52:16.357  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8323238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82d75f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:16.367  3916  3962 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-19 12:52:16.367  3462  3877 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-19 12:52:16.367  3462  3877 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-19 12:52:16.377  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-19 12:52:16.377  3828  3953 W VideoCapabilities: Unsupported mime video/mp43
,03-19 12:52:16.387  4049  4049 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:16.387  4049  4049 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:16.387  3462  3462 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-19 12:52:16.387  3462  3462 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-19 12:52:16.387  3521  3704 I Gmail   : getAccountsCursor
03-19 12:52:16.397  3828  3953 W VideoCapabilities: Unsupported mime video/sorenson
03-19 12:52:16.397  1020  1569 D FocusedStackFrame: Set to : 0
03-19 12:52:16.397  1020  1569 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 12:52:16.397  1020  1569 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-19 12:52:16.397  1020  1569 D InputDispatcher: Focused application set to: xxxx
03-19 12:52:16.397  1020  1569 D InputDispatcher: Focus left window: 3462
,03-19 12:52:16.397  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:52:16.397  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 12:52:16.407   258  1042 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (151 us)
,03-19 12:52:16.407  3828  3953 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-19 12:52:16.417  1020  1045 W libprocessgroup: failed to open /acct/uid_10068/pid_1610/cgroup.procs: No such file or directory
,03-19 12:52:16.427  3462  3845 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 45ms. Plugin should use CordovaInterface.getThreadPool().
03-19 12:52:16.427  3462  3462 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-19 12:52:16.427  3462  3462 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-19 12:52:16.437  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:16.437  3828  3953 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-19 12:52:16.447  1020  1570 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-19 12:52:16.447  1020  1570 W ActivityManager: mDVFSHelper.acquire()
,03-19 12:52:16.457  1020  1570 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 12:52:16.457  1020  1570 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1,
03-19 12:52:16.457  1020  1570 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-19 12:52:16.467  3521  3702 I Gmail   : getAccountsCursor
,03-19 12:52:16.467  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:16.467  3916  3962 I GFX raster: took 0.834688ms for 96*96 texture 0
03-19 12:52:16.467  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8323238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8670bf0 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:16.477  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:16.497  1508  1508 D Launcher: onRestart, Launcher: 197785415
,03-19 12:52:16.497  1508  1508 D Launcher: onStart, Launcher: 197785415
03-19 12:52:16.497  1508  1508 D Launcher.HomeView: onStart
03-19 12:52:16.497  1508  1508 D Launcher: onResume, Launcher: 197785415
03-19 12:52:16.497  1020  1309 D SettingsProvider: name = kids_home_mode
03-19 12:52:16.497  1020  1309 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:16.497  1020  1309 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:16.497  1020  1309 D SettingsProvider: selectionArgs: false
03-19 12:52:16.497  1020  1309 D SettingsProvider: selectionArgs: 10006
03-19 12:52:16.497  1020  1309 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:16.497  1020  1309 D SettingsProvider: ret = -1
03-19 12:52:16.497  1508  1508 D Launcher.HomeView: onResume
,03-19 12:52:16.497  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-19 12:52:16.507  1508  1508 D MenuAppsGridFragment: onResume
,03-19 12:52:16.507  1020  3823 D ActivityManager: handle home activity for 0
03-19 12:52:16.507  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-19 12:52:16.507  1020  3823 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-19 12:52:16.507  1020  3823 D KnoxTimeoutHandler: post home show event for user 0
03-19 12:52:16.507  1020  1020 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-19 12:52:16.507  1020  3823 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-19 12:52:16.507  1020  3823 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-19 12:52:16.507  1020  1020 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-19 12:52:16.507  1020  3823 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-19 12:52:16.507  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-19 12:52:16.517  1020  1032 D PersonaManagerService: getPersonasForUser(): returning null!
,03-19 12:52:16.517   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=4, Mauncher
,03-19 12:52:16.517  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-19 12:52:16.517  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-19 12:52:16.517  1020  1081 D InputDispatcher: Focus entered window: 1508
,03-19 12:52:16.517  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:52:16.517  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 12:52:16.527  1508  1508 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-19 12:52:16.547  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-19 12:52:16.547  1020  1572 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-19 12:52:16.547  1020  4071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:52:16.557  1199  1199 I StatusBar: Icon Only,
03-19 12:52:16.557  1199  1199 D PanelView: There is/are notification(s) 
,03-19 12:52:16.577  3462  3462 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-19 12:52:16.587  1862  1862 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-19 12:52:16.587  1020  1046 W ProcessCpuTracker: Skipping unknown process pid 4068
,03-19 12:52:16.597  3916  3962 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-19 12:52:16.597  4013  4013 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-19 12:52:16.597  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-19 12:52:16.597  1020  1020 D SensorService: [SO] activate (ident=0xb8afe3a8, enabled=0)
03-19 12:52:16.597  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-19 12:52:16.607  1020  1020 D SensorManager: unregisterListener ::   
03-19 12:52:16.607  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-19 12:52:16.607  1020  1020 D SensorService: [SO] changed settle time [0]
03-19 12:52:16.607  1020  1020 D SensorService: [SO] setDelay [200000000]
03-19 12:52:16.607  1020  1020 D SensorService: [SO] activate (ident=0xb8a5a370, enabled=1)
03-19 12:52:16.607  1020  1020 D SensorService: [SO] AR_init
03-19 12:52:16.607  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-19 12:52:16.617  4013  4073 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458388336625
,03-19 12:52:16.617  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-19 12:52:16.617  4013  4013 I KnoxUsageLogPro: premStatus:2
,03-19 12:52:16.627  4013  4013 I KnoxUsageLogPro: isEulaShown : false
03-19 12:52:16.627  4013  4013 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-19 12:52:16.627  1508  1508 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@bc06120 time:41677
,03-19 12:52:16.637  1020  1051 D PersonaManager: isKioskContainerExistOnDevice
,03-19 12:52:16.637  1020  1569 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:16.647  1020  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:16.647  1020  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-19 12:52:16.647  1020  1051 I ActivityManager: Displayed Component not be shown by security: +198ms
,03-19 12:52:16.657  1020  1045 W libprocessgroup: failed to open /acct/uid_10082/pid_3082/cgroup.procs: No such file or directory
,03-19 12:52:16.657  1020  1045 W libprocessgroup: failed to open /acct/uid_10088/pid_3160/cgroup.procs: No such file or directory
,03-19 12:52:16.667  2173  2173 W InstanceID/Rpc: Found 10011
,03-19 12:52:16.677  1020  1506 I ActivityManager: Killing 3195:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-19 12:52:16.717  1020  1793 W ActivityManager: userId = 0, bbcId = -10000,
03-19 12:52:16.717  1020  1793 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:16.717  1020  1793 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:16.727  4066  4066 D AndroidRuntime: 
03-19 12:52:16.727  4066  4066 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-19 12:52:16.737  4066  4066 D AndroidRuntime: CheckJNI is OFF
,03-19 12:52:16.737  4066  4066 D AndroidRuntime: readGMSProperty: start
03-19 12:52:16.737  4066  4066 D AndroidRuntime: readGMSProperty: already setted!!
03-19 12:52:16.737  4066  4066 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-19 12:52:16.737  4066  4066 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-19 12:52:16.737  4066  4066 D AndroidRuntime: readGMSProperty: end
03-19 12:52:16.737  4066  4066 D AndroidRuntime: addProductProperty: start
,03-19 12:52:16.737  4049  4049 I System.out: Inside onCreate() of WakeupTriggerProvide
03-19 12:52:16.737  4049  4049 I System.out: Inside WakeupProvider
,03-19 12:52:16.757  4013  4073 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 41661
,03-19 12:52:16.777  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.777  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.777  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:16.777  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:16.787  1020  1045 W libprocessgroup: failed to open /acct/uid_10146/pid_3195/cgroup.procs: No such file or directory
,03-19 12:52:16.797  4087  4087 E Zygote  : MountEmulatedStorage()
,03-19 12:52:16.797  4087  4087 E Zygote  : v2
03-19 12:52:16.797  4087  4087 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:16.797  4087  4087 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:16.797  4087  4087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:16.797  4087  4087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:16.797  4087  4087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:16.817  1020  3822 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-19 12:52:16.817  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-19 12:52:16.817  1020  3822 I ActivityManager: Killing 3137:com.sec.dsm.system/1000 (adj 15): empty #31
03-19 12:52:16.817  1020  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-19 12:52:16.817  3916  3962 I GFX construct_block_size_descriptor_2d second part: took 2.708960ms for 0*0 texture 0
,03-19 12:52:16.827  4049  4049 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-19 12:52:16.837  3916  3962 I GFX generate_partition_tables: took 7.899270ms for 0*0 texture 0
,03-19 12:52:16.837  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:16.837  4087  4087 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:16.837  4087  4087 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:16.837  1020  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:16.837  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:16.847  3916  3962 I GFX raster: took 11.608595ms for 96*96 texture 0
03-19 12:52:16.847  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb868d3e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb868deb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:16.847  3916  3962 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-19 12:52:16.857  1020  1309 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:16.857  1020  1309 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:16.857  1020  1309 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:16.897  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-19 12:52:16.897  3916  3962 I GFX raster: took 0.609323ms for 96*96 texture 0
03-19 12:52:16.897  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c9c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8670bf0 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:16.907  4049  4049 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-19 12:52:16.907  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:16.907  1020  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:16.907  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:16.907  4066  4066 E AffinityControl: AffinityControl: registerfunction enter
,03-19 12:52:16.917  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3137/cgroup.procs: No such file or directory
,03-19 12:52:16.917  3916  3962 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-19 12:52:16.927  2173  2173 D ChimeraCfgMgr: Reading stored module config
,03-19 12:52:16.927  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-19 12:52:16.927  3916  3962 I GFX raster: took 0.817188ms for 96*96 texture 0
03-19 12:52:16.927  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb868deb8 counterpartCT=4 counterpartW=96 counterparth=96,
,03-19 12:52:16.927  4087  4087 E KnoxSetupWizardClient: isShipMode : 1
03-19 12:52:16.927  4087  4087 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-19 12:52:16.937  3916  3962 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-19 12:52:16.947  4066  4066 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-19 12:52:16.947  1020  1046 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7,
03-19 12:52:16.947  1020  1046 W ActivityManager: mDVFSHelper.release()
03-19 12:52:16.947  1020  1046 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-19 12:52:16.957  2173  2173 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-19 12:52:16.957  2173  2173 D BootCompletedReceiver: Got an BootCompleted event.
,03-19 12:52:16.967  2173  2173 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-19 12:52:16.977  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:16.977  3916  3962 I GFX raster: took 0.625208ms for 96*96 texture 0
03-19 12:52:16.977  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb868deb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:16.987  3916  3962 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-19 12:52:16.997  2173  4078 W art     : Verification of void com.google.android.gms.checkin.CheckinService.<clinit>() took 129.113ms
,03-19 12:52:16.997  1020  1572 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:16.997  1020  1572 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:16.997  1020  1572 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.017  1020  3823 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.017  1020  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.017  1020  1043 D SensorService: [SO] currT = 42061073000, prevT = 41631778000, diff = 429295000, [-0.479 0.211 9.902]
03-19 12:52:17.017  1020  1043 D SensorService: [SO] -0.479 0.211 9.902
03-19 12:52:17.017  1020  1043 D SensorService: [SO] [100 -> 255]
03-19 12:52:17.017  1020  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.017  3183  3285 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-19 12:52:17.017  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:17.027  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-19 12:52:17.027  3916  3962 I GFX raster: took 0.689271ms for 96*96 texture 0
03-19 12:52:17.027  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb868deb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82d8390 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.027  1020  1081 D PackageManager: START PACKAGE DELETE: observer{867561236}
03-19 12:52:17.027  1020  1081 D PackageManager: pkg{<packageName>}
03-19 12:52:17.027  1020  1081 D PackageManager: user{0}
03-19 12:52:17.027  1020  1081 D PackageManager: caller{2000}
03-19 12:52:17.027  1020  1081 D PackageManager: flags{2}
03-19 12:52:17.027  1020  1081 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-19 12:52:17.027  1020  1081 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-19 12:52:17.027  1020  1081 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-19 12:52:17.027  1020  1081 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-19 12:52:17.027  1020  1081 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-19 12:52:17.037  1980  1980 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:17.037  1020  1061 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-19 12:52:17.037  1020  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-19 12:52:17.037  1020  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-19 12:52:17.037  3916  3962 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-19 12:52:17.047  1020  1061 D ApplicationPolicy: getApplicationUninstallationEnabled
,03-19 12:52:17.047  1020  1061 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-19 12:52:17.057  1020  1793 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:17.057  1020  1793 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.057  1020  1793 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-19 12:52:17.057  1020  1061 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-19 12:52:17.057  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.057  3916  3962 I GFX raster: took 0.665520ms for 96*96 texture 0
03-19 12:52:17.057  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb82d8390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86afd40 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.067  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.067  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.067  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.067  3916  3962 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-19 12:52:17.067  1020  1046 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-19 12:52:17.067  1020  1046 I ActivityManager: Killing 3462:com.test.thalitest/u0a167 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-19 12:52:17.077   258   449 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-19 12:52:17.077   258  1042 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-19 12:52:17.087  4087  4087 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-19 12:52:17.087  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-19 12:52:17.087  3916  3962 I AMMetaDataParserService: Resource data:Inside bundle  check
03-19 12:52:17.087  3916  3962 I AMMetaDataParserService: getResourcePackageName:assistant
03-19 12:52:17.087  3916  3962 I AMMetaDataParserService: Resource data:2131034113
,03-19 12:52:17.097  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a0ce0a7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:42144
,03-19 12:52:17.107  4087  4087 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-19 12:52:17.107  4087  4087 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
03-19 12:52:17.107  4087  4087 D ShortcutReceiver:  shortcut migration not required 
,03-19 12:52:17.167  1020  1061 W PackageSettings: Skipping PackageSetting{18610a69 com.example.hello/10168} due to missing metadata
,03-19 12:52:17.207  3916  3962 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-19 12:52:17.207  3916  3962 I AMMetaDataParserService: getResourceTypeNamexml
,03-19 12:52:17.207  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-19 12:52:17.207  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.207  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:17.207  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.207  3916  3962 I GFX raster: took 0.841616ms for 96*96 texture 0
03-19 12:52:17.207  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8323238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86ac8a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.207  4087  4105 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-19 12:52:17.207  4087  4105 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-19 12:52:17.207  4087  4105 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-19 12:52:17.207  4087  4105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-19 12:52:17.207  4087  4105 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-19 12:52:17.207  4087  4105 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-19 12:52:17.207  4087  4105 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-19 12:52:17.217  4049  4049 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-19 12:52:17.217  4049  4049 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-19 12:52:17.217  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.217  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.217  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.217  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:17.217  3916  3962 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-19 12:52:17.227  4117  4117 E Zygote  : MountEmulatedStorage()
03-19 12:52:17.227  4117  4117 E Zygote  : v2
03-19 12:52:17.227  4117  4117 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:17.227  4117  4117 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:17.237  4117  4117 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:17.237  1020  1032 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4117 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-19 12:52:17.237  1020  1061 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-19 12:52:17.237  4117  4117 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-19 12:52:17.237  4117  4117 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:17.247  4049  4049 D DialogFlow: initQueue()
,03-19 12:52:17.247  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-19 12:52:17.257  1020  1061 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-19 12:52:17.277  4117  4117 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:17.277  4117  4117 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:17.297  1020  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-19 12:52:17.297  1862  1862 E SamsungIME: mOCRHelper is null
,03-19 12:52:17.307  1483  1483 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:52:17.327  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.337  1020  1020 D RCPManagerService: PackageReceiver onReceive()
,03-19 12:52:17.347  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-19 12:52:17.347  3916  3962 I GFX raster: took 1.045262ms for 96*96 texture 0
,03-19 12:52:17.347  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-19 12:52:17.347  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8323238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86ab670 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.357  3916  3962 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-19 12:52:17.377  1980  1980 I art     : Explicit concurrent mark sweep GC freed 21812(1591KB) AllocSpace objects, 32(704KB) LOS objects, 39% free, 9MB/15MB, paused 1.106ms total 79.452ms
,03-19 12:52:17.407  1980  2198 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-19 12:52:17.427  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.437  3916  3962 I GFX raster: took 0.765521ms for 96*96 texture 0
03-19 12:52:17.437  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb868d3e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661c78 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.437  3916  3962 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-19 12:52:17.457  1020  1130 V NetworkStats: removeUidsLocked() for UIDs [10167]
,03-19 12:52:17.457  1020  1130 V NetworkStats: performPollLocked(flags=0x3)
03-19 12:52:17.457  1020  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-19 12:52:17.457  1020  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
,03-19 12:52:17.457  1020  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-19 12:52:17.467  1020  1130 V NetworkStats: performPollLocked() took 9ms
,03-19 12:52:17.467  1020  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-19 12:52:17.477  2173  3914 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-19 12:52:17.487  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.487  3916  3962 I GFX raster: took 0.601770ms for 96*96 texture 0
03-19 12:52:17.487  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c9c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661c78 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.487  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-19 12:52:17.487  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-19 12:52:17.497  1020  3823 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-19 12:52:17.497  1020  3823 D SecContentProvider2: mCursor = null
,03-19 12:52:17.507  3916  3962 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-19 12:52:17.517  4117  4117 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-19 12:52:17.517  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-19 12:52:17.517  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicy: uID is 10167
03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
,03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-19 12:52:17.517  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-19 12:52:17.517  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.517  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.517  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.527  4117  4117 I StatusChecker: onReceive : net.mt.init : DONE
,03-19 12:52:17.527  1468  1468 D RegisteredServicesCache: empty dynamic service
,03-19 12:52:17.537  1020  1045 D EnterpriseDeviceManagerService: Package has changed for user 0
03-19 12:52:17.537  1020  1045 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-19 12:52:17.537  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.537  3916  3962 I GFX raster: took 0.841198ms for 96*96 texture 0
03-19 12:52:17.537  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661c78 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.537  1020  1045 W TextServicesManagerService: no available spell checker services found
,03-19 12:52:17.547  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-19 12:52:17.547  1020  2777 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-19 12:52:17.557  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.557  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.557  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.557  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:17.557  3916  3962 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-19 12:52:17.577  4137  4137 E Zygote  : MountEmulatedStorage(),
03-19 12:52:17.577  4137  4137 E Zygote  : v2
03-19 12:52:17.577  4137  4137 I libpersona: KNOX_SDCARD checking this for 10029
03-19 12:52:17.577  4137  4137 I libpersona: KNOX_SDCARD not a persona,
03-19 12:52:17.577  4137  4137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:17.577  4137  4137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-19 12:52:17.577  4137  4137 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:17.577  1020  1571 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4137 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
03-19 12:52:17.577  1020  1571 I ActivityManager: Killing 3230:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,03-19 12:52:17.587  1020  2777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicy: uID is 10167
03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-19 12:52:17.597  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-19 12:52:17.617  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:17.617  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:17.617  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:17.617  1020  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:17.617  4137  4137 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:17.617  4137  4137 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:17.637  4152  4152 E Zygote  : MountEmulatedStorage()
03-19 12:52:17.637  4152  4152 E Zygote  : v2
03-19 12:52:17.637  4152  4152 I libpersona: KNOX_SDCARD checking this for 10113
03-19 12:52:17.637  4152  4152 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:17.647  1020  1571 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4152 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,03-19 12:52:17.647  1020  1571 I ActivityManager: Killing 3242:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-19 12:52:17.657  4152  4152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:17.657  4152  4152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:17.657  4152  4152 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:17.657  1020  2777 D SSRM:n  : SIOP:: AP = 420
,03-19 12:52:17.667  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.667  3916  3962 I GFX raster: took 0.637083ms for 96*96 texture 0
03-19 12:52:17.667  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661c78 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.677  1980  1980 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-19 12:52:17.687  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.687  1020  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.687  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.687  2173  4078 D GCM     : COMPAT: Multi user not supported
,03-19 12:52:17.687  3916  3962 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-19 12:52:17.697  4152  4152 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:17.697  4152  4152 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:17.697  1020  1571 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.697  1020  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.697  1020  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.707  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.707  3916  3962 I GFX raster: took 0.712343ms for 96*96 texture 0
03-19 12:52:17.707  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb868deb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661c78 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.707  1020  3822 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:17.707  1020  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.707  1020  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.717  3916  3962 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-19 12:52:17.717  1020  1793 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.717  1020  1793 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.717  1020  1793 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.727  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:17.737  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:17.737  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.737  1020  1172 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
,03-19 12:52:17.737  1020  1172 D TaskPersister: removeObsoleteFile: deleting file=11_task_thumbnail.png
,03-19 12:52:17.737  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.747  3916  3962 I GFX raster: took 0.598437ms for 96*96 texture 0
03-19 12:52:17.747  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb82d8390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661c78 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.757  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:17.757  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.757  1020  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.757  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.767  3916  3962 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-19 12:52:17.767  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:17.767  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Inside bundle  check
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:Inside bundle  check
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-19 12:52:17.777  3916 , 3962 I AMMetaDataParserService: getResourcePackageName:assistant
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: Resource data:2131034112
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-19 12:52:17.777  3916  3962 I AMMetaDataParserService: getResourceTypeNamexml
03-19 12:52:17.777  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-19 12:52:17.777  1020  1497 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.777  1020  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.777  1020  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-19 12:52:17.777  3916  3962 I GFX raster: took 0.609740ms for 96*96 texture 0
03-19 12:52:17.777  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c9c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661c78 counterpartCT=4 counterpartW=96 counterparth=96
03-19 12:52:17.787  2173  4171 I CheckinService: Disabling old GoogleServicesFramework version
03-19 12:52:17.787  3916  3962 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
03-19 12:52:17.797  1020  1061 W art     : Suspending all threads took: 5.468ms
03-19 12:52:17.807  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:17.827  1020  1061 I art     : Explicit concurrent mark sweep GC freed 51915(3MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 11.692ms total 424.251ms
,03-19 12:52:17.827  1020  1061 D PackageManager: delete codoeFile: 
,03-19 12:52:17.837  1020  1061 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-19 12:52:17.837  1020  1061 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-19 12:52:17.837  1020  1061 D PackageManager: result of delete: 1{867561236}
,03-19 12:52:17.847  4066  4066 D AndroidRuntime: Shutting down VM
,03-19 12:52:17.857  2173  2173 D SystemUpdateService: onCreate
,03-19 12:52:17.897  2173  2173 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-19 12:52:17.897  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:17.897  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.897  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.897  4152  4152 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-19 12:52:17.907  1020  1061 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-19 12:52:17.907  1020  1061 D PackageManager: userId{-1}
03-19 12:52:17.907  1020  1061 D PackageManager: andCode{true}
,03-19 12:52:17.907  2173  4078 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-19 12:52:17.917  4152  4152 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-19 12:52:17.927  2173  4178 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-19 12:52:17.937  1020  3823 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:17.937  1020  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:17.937  1020  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:17.947  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:17.947  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:17.947  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-19 12:52:17.957  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:17.957  3916  3962 I GFX raster: took 0.600781ms for 96*96 texture 0
03-19 12:52:17.957  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c9c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661c78 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:17.957  4152  4152 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-19 12:52:17.957  3916  3962 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-19 12:52:17.967  1020  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-19 12:52:17.967  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:17.977  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:17.977  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.977  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.977  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.977  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:17.987  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-19 12:52:17.987  2173  4178 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-19 12:52:17.987  1020  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
03-19 12:52:17.987  1020  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:17.987  1020  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 12:52:17.997  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:17.997  4182  4182 E Zygote  : MountEmulatedStorage()
03-19 12:52:17.997  4182  4182 E Zygote  : v2,
03-19 12:52:17.997  4182  4182 I libpersona: KNOX_SDCARD checking this for 10003
03-19 12:52:17.997  4182  4182 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:17.997  4182  4182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:17.997  4182  4182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-19 12:52:17.997  1020  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4182 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-19 12:52:17.997  4182  4182 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-19 12:52:17.997  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.997  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.997  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:17.997  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:18.007  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-19 12:52:18.007  3916  3962 I GFX raster: took 0.737031ms for 96*96 texture 0
03-19 12:52:18.007  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8661c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb831f708 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:18.017  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-19 12:52:18.017  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:18.017  3916  3962 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-19 12:52:18.027  3183  3285 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
03-19 12:52:18.027  4196  4196 E Zygote  : MountEmulatedStorage()
03-19 12:52:18.027  4196  4196 I libpersona: KNOX_SDCARD checking this for 10121
03-19 12:52:18.027  4196  4196 E Zygote  : v2
03-19 12:52:18.027  4196  4196 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:18.027  4196  4196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:18.027  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-19 12:52:18.027  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-19 12:52:18.027  1020  1793 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4196 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-19 12:52:18.027  4196  4196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:18.027  4196  4196 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:18.037  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-19 12:52:18.037  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-19 12:52:18.037  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-19 12:52:18.047  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-19 12:52:18.047  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-19 12:52:18.057  4066  4066 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-19 12:52:18.057  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:18.067  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:18.067  1020  1045 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-19 12:52:18.067  1020  1045 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-19 12:52:18.067   305   305 I art     : Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 806us total 40.529ms
,03-19 12:52:18.077  3916  3962 I GFX raster: took 10.250210ms for 96*96 texture 0
03-19 12:52:18.077  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86515e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:18.077  4182  4182 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:18.077  4182  4182 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:18.077  4196  4196 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:18.077  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:18.077  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:18.077  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:18.077  1020  1793 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:18.077  4196  4196 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:18.087  3576  3587 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
03-19 12:52:18.087  3916  3962 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
03-19 12:52:18.087   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 17.992ms
,03-19 12:52:18.107   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 19.992ms
,03-19 12:52:18.117  4214  4214 E Zygote  : MountEmulatedStorage()
03-19 12:52:18.117  4214  4214 E Zygote  : v2
03-19 12:52:18.117  4214  4214 I libpersona: KNOX_SDCARD checking this for 10030
03-19 12:52:18.117  4214  4214 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:18.117  1020  1793 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4214 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-19 12:52:18.117  1020  1793 I ActivityManager: Killing 3268:com.sec.android.diagmonagent/1000 (adj 15): empty #31
03-19 12:52:18.127  4214  4214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-19 12:52:18.127  4214  4214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-19 12:52:18.127  4214  4214 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-19 12:52:18.157  4214  4214 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:18.167  4214  4214 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:18.167  2173  4173 I CheckinService: Checking schedule, now: 1458388338181 next: 1458867327892
03-19 12:52:18.167  2173  4173 I CheckinService: active receiver: disabled
,03-19 12:52:18.177  4196  4196 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:18.177  4196  4196 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-19 12:52:18.177  4196  4196 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:Inside bundle  check
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: getResourcePackageName:assistant
03-19 12:52:18.177  3916  3962 I AMMetaDataParserService: Resource data:2131034113
03-19 12:52:18.187  1199  1199 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:18.187  1199  1199 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:18.187  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:18.187  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:18.187  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:18.187  1199  1199 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:18.197  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3242/cgroup.procs: No such file or directory
03-19 12:52:18.197  1020  1045 W libprocessgroup: failed to open /acct/uid_10088/pid_3230/cgroup.procs: No such file or directory
03-19 12:52:18.197  3916  3962 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-19 12:52:18.197  3916  3962 I AMMetaDataParserService: getResourceTypeNamexml
03-19 12:52:18.197  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-19 12:52:18.197  3916  3962 I GFX raster: took 0.989740ms for 96*96 texture 0
03-19 12:52:18.197  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb868deb8 counterpartCT=4 counterpartW=96 counterparth=96
03-19 12:52:18.207   289   289 E SMD     : DCD OFF
03-19 12:52:18.207  3916  3962 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-19 12:52:18.207  1508  1508 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
03-19 12:52:18.207  1508  1508 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-19 12:52:18.217  1020  1571 I ActivityManager: Killing 3347:com.policydm/1000 (adj 15): empty #31
03-19 12:52:18.247  2173  4177 I SystemUpdateService: cancelUpdate (empty URL)
03-19 12:52:18.247  2173  4177 I SystemUpdateService: active receiver: disabled
03-19 12:52:18.247  2173  4178 W BaseAppContext: Using Auth Proxy for data requests.
,03-19 12:52:18.337  4196  4196 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-19 12:52:18.347  1020  3823 D SettingsProvider: name = scon_is_running
,03-19 12:52:18.347  1020  3823 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-19 12:52:18.347  1020  3823 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:18.347  1020  3823 D SettingsProvider: selectionArgs: false
,03-19 12:52:18.347  1020  3823 D SettingsProvider: selectionArgs: 10121
,03-19 12:52:18.347  1020  3823 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
,03-19 12:52:18.347  1020  3823 D SettingsProvider: ret = -1
,03-19 12:52:18.357  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-19 12:52:18.357  3916  3962 I GFX raster: took 1.285417ms for 96*96 texture 0
03-19 12:52:18.357  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb868c520 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:18.367  1020  3823 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-19 12:52:18.377  4196  4196 D QuickConnect: Utils.setQCRunningSetting - set : 0
,03-19 12:52:18.377  4196  4196 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-19 12:52:18.377  3916  3962 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-19 12:52:18.397  1199  1199 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:18.407  1020  2861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:52:18.407  4196  4196 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-19 12:52:18.407  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3268/cgroup.procs: No such file or directory
03-19 12:52:18.407  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3347/cgroup.procs: No such file or directory
,03-19 12:52:18.417  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:18.417  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:18.417  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:18.417  1020  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:18.427  4231  4231 E Zygote  : MountEmulatedStorage()
,03-19 12:52:18.437  1020  3822 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4231 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-19 12:52:18.437  4231  4231 E Zygote  : v2
03-19 12:52:18.437  1020  3822 I ActivityManager: Killing 3328:com.sec.esdk.elm/u0a90 (adj 15): empty #31
03-19 12:52:18.437  4231  4231 I libpersona: KNOX_SDCARD checking this for 10127
03-19 12:52:18.437  4231  4231 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:18.437  4231  4231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-19 12:52:18.437  4231  4231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-19 12:52:18.447  4231  4231 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:18.447  2173  4178 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-19 12:52:18.467  4231  4231 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:18.467  4231  4231 D ActivityThread: Added TimaKeyStore provider,
,03-19 12:52:18.487  3916  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-19 12:52:18.497  4214  4214 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-19 12:52:18.497  4214  4214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 12:52:18.497  4214  4214 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-19 12:52:18.497  3916  3962 I GFX raster: took 0.685313ms for 96*96 texture 0
03-19 12:52:18.497  3916  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866c9c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83dbca0 counterpartCT=4 counterpartW=96 counterparth=96
,03-19 12:52:18.507  2173  4178 I AuthZen : Fetching signing key...
,03-19 12:52:18.507  2173  4178 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/keys.db" with flag (131138) and mode_t (0) due to error (30)
,03-19 12:52:18.517  3916  3962 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-19 12:52:18.517  3916  3962 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,03-19 12:52:18.517  4231  4231 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-19 12:52:18.517  4231  4231 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 12:52:18.517  4231  4231 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-19 12:52:18.517  4231  4231 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-19 12:52:18.517  3916  3962 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:18.517  3916  3962 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:52:18.517  3916  3962 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 12:52:18.517  3916  3962 W System.err: 	at andro,id.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 12:52:18.517  3916  3962 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
03-19 12:52:18.517  3916  3962 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-19 12:52:18.517  3916  3962 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:18.517  3916  3962 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 12:52:18.527  2173  4178 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/keys.db'.
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.keyservice.j.a(:com.google.android.gms:140)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.keyservice.g.d(:com.google.android.gms:224)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.keyservice.g.a(:com.google.android.gms:79)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.b.d.b(:com.google.android.gms:219)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:91)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:258)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:209)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:202)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.a.a(:com.google.android.gms:148)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(:com.google.android.gms:30)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:18.527  2173  4178 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: Couldn't open keys.db for writing (will try read-only):
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.keyservice.j.a(:com.google.android.gms:140)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.keyservice.g.d(:com.google.android.gms:224)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.keyservice.g.a(:com.google.android.gms:79)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.b.d.b(:com.google.android.gms:219)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:91)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:258)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:209)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:202)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.a.a(:com.google.android.gms:148)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(:com.google.android.gms:30)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:18.527  2173  4178 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 12:52:18.537  1020  1793 I ActivityManager: Killing 3418:com.sec.factory.camera/1000 (adj 15): empty #31
,03-19 12:52:18.537  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:18.537  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:18.537  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
03-19 12:52:18.537  2173  4178 W SQLiteOpenHelper: Opened keys.db in read-only mode
,03-19 12:52:18.547  1020  1045 W libprocessgroup: failed to open /acct/uid_10090/pid_3328/cgroup.procs: No such file or directory
,03-19 12:52:18.547  4214  4214 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-19 12:52:18.547  4214  4214 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:18.547  4214  4214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 12:52:18.547  2173  3914 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,03-19 12:52:18.547  3312  3681 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-19 12:52:18.557  2173  4178 I AuthZen : Signing key fetched successfully!
,03-19 12:52:18.567  4214  4214 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-19 12:52:18.567  4214  4214 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-19 12:52:18.577  2173  3914 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,03-19 12:52:18.577  2173  4178 W BaseAppContext: Using Auth Proxy for data requests.
,03-19 12:52:18.577  2173  4178 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/keys.db" with flag (131138) and mode_t (0) due to error (30)
,03-19 12:52:18.577  2173  4178 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/keys.db'.
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.keyservice.j.c(:com.google.android.gms:228)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:186)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:153)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:103)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:258)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:209)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:202)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.a.a(:com.google.android.gms:148)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(:com.google.android.gms:30)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:18.577  2173  4178 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: Couldn't open keys.db for writing (will try read-only):
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.data,base.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.keyservice.j.c(:com.google.android.gms:228)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:186)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:153)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:103)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:258)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:209)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:202)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.a.a(:com.google.android.gms:148)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(:com.google.android.gms:30)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-19 12:52:18.577  2173  4178 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 12:52:18.587  2173  4178 W SQLiteOpenHelper: Opened keys.db in read-only mode
03-19 12:52:18.587  4049  4062 W art     : Suspending all threads took: 20.592ms
,03-19 12:52:18.587  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3418/cgroup.procs: No such file or directory
,03-19 12:52:18.597  2173  4178 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/auth.proximity.permit_store" with flag (131138) and mode_t (0) due to error (30)
,03-19 12:52:18.597  2173  4178 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/auth.proximity.permit_store'.,
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 12:52:18.597  2173  4178 E SQLiteDatabase: 
```
